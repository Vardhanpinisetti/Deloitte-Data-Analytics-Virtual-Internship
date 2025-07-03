# Deloitte Data Analytics Virtual Internship
📊 Completed through [Forage](https://www.theforage.com) | July 2025

This repository contains my submissions and work from the **Deloitte Data Analytics Virtual Internship** offered on Forage. The internship provided hands-on experience with real-world business data, allowing me to build analytical dashboards and perform data classification tasks.

### **Tasks Completed**

### Task 1: Telemetry Data Analysis using Tableau
Your task is to analyse the telemetry data collected by Daikibo in a software called Tableau. Here are the steps that you need to take:
1.	Download the free trial of Tableau (link in the Resources).
2.	Install Tableau on your computer and register an account with the same email you used to download the software.
3.	Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
4.	Create a calculated measure field called "Unhealthy" with a value of 10 for every unhealthy status (representing 10 mins of potential down time since the previous message).
5.	Create a bar chart called “Down Time per Factory”.
6.	Create a new sheet with a new bar chart called “Down Time per Device Type”.
7.	Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting a factory in the first chart shows only the down time of the machines in this factory in the second chart).
8.	Select the factory with the most down time (click on its bar), make a screenshot of the dashboard and upload it as a submission for this task.

### **Dashboard Image** (Output): ![Dashboard Image](https://github.com/user-attachments/assets/6f86a9b7-9dd6-4876-83b5-c4343601736b)





### Task 2: Forensic Technology – Equality Score Classification
We have processed all data on employee compensation and generated an Excel file (Equality Table.xlsx, available in the Resources) containing 3 columns:
1.	Factory
2.	Job Role
3.	Equality Score (integer; ranging between -100 and +100; 0 is ideal)
Here is your task:
•	Create a 4th column (Equality class), classifying the equality score into 3 types:
o	Fair (+-10)
o	Unfair (<-10 AND >10)
o	Highly Discriminative (<-20 AND >20)
Examples:
•	10 → Fair
•	-9 → Unfair
•	-30 → Highly Discriminative
Please find the Equality Table you need to edit in the resources below. When you are done, upload the edited version of the file.

## **Formula Used**: 
    =IFS(
    C2<-20, "Highly Discriminative",
    C2>20, "Highly Discriminative",
    C2<-10, "Unfair",
    C2>10, "Unfair",
    C2>=-10, "Fair",
    C2<=10, "Fair")
                
### **Excel Image** (Output):![image](https://github.com/user-attachments/assets/e1c816e3-0c6e-4407-97be-048fb85e8922)


## 🛠 Tools Used
- Tableau
- Microsoft Excel
- Forage Virtual Internship Platform

## 📄 Certificate
file:///C:/Virtual%20Internships/Deloitte%20Data%20Analyst%20Virutual%20Internship/Certificate.pdf


## 🔗 Learn more
Program Link: [Deloitte Data Analytics Virtual Internship](https://www.deloitte.com/au/en/careers/students/virtual-internship.html)


### **Conclusion**
The Deloitte Data Analytics Virtual Internship through Forage was an enriching experience that enhanced my understanding of real-world data analysis in a business context. By working with industry-grade datasets and tools like Tableau and Excel, I developed valuable skills in data visualization, pattern recognition, and analytical thinking. This program not only improved my technical capabilities but also provided insights into how top-tier firms like Deloitte leverage data to drive strategic decisions.

I look forward to applying these skills in future academic and professional opportunities, and I highly recommend this experience to anyone looking to gain practical exposure to data analytics in the corporate world.
