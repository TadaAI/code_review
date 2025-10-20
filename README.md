# Payroll Data Standardization Challenge

## 🧭 Overview
Our customers send in payroll in various formats, and it is our job to convert them into a standardized format to be entered into their system.  
This saves our customers time by automating the manual data entry they would normally have to do.  
We also give them peace of mind by ensuring accuracy that is greater than what they can achieve manually.

Your task is to create a simplified version of this system with the provided examples.

---

## ✅ Requirements

1. **UI Upload**
   - A user interface where a user can upload a **CSV** or **PDF** containing payroll data.

2. **Data Processing**
   - The system will process the uploaded file and output a standardized JSON format:

     ```json
     [
       {
         "employee_name": "text",
         "pay_type": "text",
         "number_of_hours": "number",
         "rate": "number",
         "total_amount": "number"
       }
     ]
     ```

3. **Missing Data Handling**
   - For any data not available, output `"null"` as the value.

4. **Deployment**
   - Deploy the tool so it is accessible to anyone online.

5. **Enhancements**
   - Add any features that you think will enhance the product.

---
