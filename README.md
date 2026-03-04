# Application Customers Data Analysis

---

## 📈 Dashboard Preview
<img width="1871" height="1028" alt="Appication Data View" src="https://github.com/user-attachments/assets/c84322a5-ec0f-4e65-9718-9de3f309e09f" />

---

## 📌 Project Overview
This project focuses on transforming raw, "messy" customer data into a clean, structured, and insightful dataset. The primary goal was to understand customer behavior and demographics to drive better decision-making within our application.

---

## 🛠 Tools & Technologies
* **Excel:** Used for data visualization and building the final Dashboard.
* **Power Query:** Used for complex data cleaning and transformation processes.

---

## 🧹 Data Cleaning Process
The raw data contained 16 columns and required significant preprocessing to ensure accuracy:
* **De-duplication:** Removed duplicate entries based on the `INDEX` column.
* **Name Normalization:** Cleaned customer names by removing titles (Mr., Mrs., Dr.) and suffixes (DDS, etc.), focusing only on the First and Last name (e.g., "Dr. Amgad Hussien DDS" -> "Amgad Hussien").
* **Handling Missing Values:** Filled empty fields in Job Titles and Work Locations with "Unknown" to maintain data integrity during analysis.
* **Email Standardization:** Standardized disparate email formats and missing domains into a consistent format (e.g., `username@example.com`).
* **Phone Number Formatting:** Cleaned phone numbers by removing country codes, symbols, and special characters, converting them into the `(XXX) XXX-XXXX` format. Missing/invalid numbers were set to `(000) 000-0000`.
* **Address Strategy:** Implemented a hierarchical fallback strategy for missing address fields, ensuring that available information from the City, State, or Country levels was utilized effectively.

---

## 📊 Analysis & Insights
The project aimed to visualize key customer insights, including:
* **Customer Segmentation:** Identifying the distribution of different customer categories.
* **Engagement:** Tracking the volume of customers who have successfully registered/logged into the application.
* **Correlation Analysis:** Used a **Scatter Plot** to visualize the relationship between **Age and Income**, helping to identify high-value customer segments.
* **Geographic Distribution:** Analyzing customer presence across different countries and regions.

---

## 🚀 Conclusion
This project demonstrates the ability to perform end-to-end data preparation, transforming unusable raw data into actionable insights for business growth.

---

## 🔓 Usage & License
Feel free to use this dataset for practice, analysis, or any other educational purposes. The data is open for everyone to explore and learn from.

## 📧 Contact Me
If you have any questions or want to discuss this project, feel free to reach out directly:

* **WhatsApp:** [Message me on WhatsApp](https://wa.me/201553918594)
* **Primary Email:** [amgadhussien.da@gmail.com](mailto:amgadhussien.da@gmail.com)
* **Secondary Email:** [qwertr307@gmail.com](mailto:qwertr307@gmail.com)
* **Phone:** [+20 155 391 8594](tel:+201553918594)
