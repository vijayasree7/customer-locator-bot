# Customer Locator Bot – Automation Anywhere A360 (Community Edition)

## 📌 Overview
The **Customer Locator Bot** is built in **Automation Anywhere A360 (Community Edition)**.  
It navigates to a website, extracts customer data, logs execution details, and saves the data into an Excel file.  
This is a practical example of combining **browser automation**, **data extraction**, and **file handling**.

---

## ⚙️ Bot Logic
1. **Start**  
2. **Log File Creation** → Creates a log file to capture bot execution details  
3. **Open Browser** → Launches browser and navigates to the site 
4. **Read Data from Browser** → Extracts customer data from the webpage  
5. **Excel File Creation** → Creates an Excel file for storing extracted data  
6. **Bot Execution** → Implements business logic and writes results  
7. **End**  

---

## 🖼️ Screenshot

Workflow:
![Customer Locator Workflow](customer_locator_workflow.png)

Example:  
![Customer Locator Log](customer_locator_log.png)

---

## 🔄 How to Recreate This Bot
1. Log in to **Automation Anywhere A360 (Community Edition)**.  
2. Go to **My Bots → Create a new Bot**.  
3. Import `CustomerLocator_Main.json`.  
4. Place the input file `data.xlsx` in the correct path (or update the file path inside the bot).  
5. Run the bot → check the generated `execution.log` and `data.xlsx` for results.  

---

## 🗂️ Repository Structure
customer-locator-bot/

|- README.md

|- CustomerLocator_Main.json       # Bot definition

|- data.xlsx                       # Sample Excel file

|- execution.log                   # Sample log file

|- customer_locator_workflow.png   # Workflow screenshot
|- customer_locator_log.png        # Output screenshot

---

## 📖 Metadata
- **Author:** Vijaya Sree Janjanam  
- **Created:** 05-Sep-2025  
- **Bot Type:** Automation Anywhere A360  

---

![Automation Anywhere](https://img.shields.io/badge/Automation%20Anywhere-A360-orange)
![Bot Type](https://img.shields.io/badge/Customer%20Locator%20Bot-blue)

---

## 🚀 Next Steps
-  Visit my next repositories for other bot automation solutions.

--- 
