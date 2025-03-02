
### **Project Overview: Analyzing Healthcare Utilization and Health Factors**  

#### **Problem Statement:**  
This project aims to analyze healthcare utilization by:  
1. Determining the average number of illnesses concerning age in years.  
2. Visualizing the average percentage of members with private health insurance, categorized by gender.  
3. Finding the total number of people based on their count of illnesses using a count plot.  

#### **Project Description:**  
The project began with data preprocessing, where the dataset was imported into Jupyter Notebook for cleaning and visualization. No duplicate entries were found in the dataset. A new column was added to represent age in years for better clarity.  

To analyze illness trends, the `value_counts()` function was used to calculate the frequency of illnesses. Data visualizations were then created using different plots:  
- A **count plot** to display the distribution of illnesses.  
- A **pie chart** to show the proportion of members with private health insurance, categorized by gender.  
- A **bar chart** to examine illness trends across different age groups.  

These visualizations provided insights into illness distribution and health insurance coverage, contributing to a better understanding of healthcare utilization.  

#### **End Users:**  
- Healthcare Professionals (Doctors, Nurses)  
- Health Insurance Providers  
- Public Health Researchers  
- Healthcare Economists  
- Policy Makers  

#### **Technology Used:**  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **IDE:** VS Code with Jupyter Notebook  
- **Operating System:** Windows 10  

#### **Results:**  
1. **Bar Chart:**  
   - The age group **27 years** has the lowest illness rate, while **72 years** has the highest.  

2. **Pie Chart:**  
   - **53.0% of females** and **58.6% of males** do not have private health insurance, while **47.0% of females** and **41.4% of males** do.  

3. **Count Plot:**  
   - Distribution of illness counts among people:  
     - **Illness 1:** 1,638 people  
     - **Illness 0:** 1,554 people  
     - **Illness 2:** 946 people  
     - **Illness 3:** 542 people  
     - **Illness 4:** 274 people  
     - **Illness 5:** 236 people  

This project successfully provides insights into healthcare utilization trends, helping stakeholders make data-driven decisions for policy development and resource allocation.
