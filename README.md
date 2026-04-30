# Web Scraping with Python
📌 __Project Overview__

This project demonstrates practical Python programming using Jupyter Notebooks on Google Colab. It focuses on web scraping and data cleaning using popular Python libraries.

The workflow includes extracting data from a web page, processing it into a structured format, and exporting it for further use.

---
🎯 Objectives

The main objectives of this assignment were: <br>
- Practice Python coding using Jupyter Notebooks on Google Colab
- Use `requests` and `BeautifulSoup` to extract data from a web page
- Parse and clean the extracted data
- Store structured data in a Pandas DataFrame
- Export the final dataset to a `.csv` file

---
🛠️ Tools and Libraries Used
- Python
- Google Colab
- requests - for sending HTTP requests
- BeautifulSoup (bs4) - for parsing HTML content
- pandas - for data manipulation

---
📂 Project Workflow
1. **Setup Environment**
   - Import required libraries
   - configure Google Colab notebook
2. **Data Extraction**
   - Send an HTTP request to the target webpage using `requests`
   - Retrieve HTML content
3. **Parsing HTML**
   - Use `BeautifulSoup` to navigate and extract relevant elements
4. **Data Cleaning**
   - Remove unwanted characters and formatting
   - Handle missing or inconsistent data
5. Data Structuring
   - Store cleaned data into a Pandas DataFrame
6. Export Data
   - Save the DataFrame as a `.csv` file for external use
  
---
📊 Output
- A structured dataset in CSV format containing the extracted and cleaned data

--- 
▶️ How to Run the Project
1. Open the notebook in Google Colab
2. Install required libraries (if not already available):
```
pip install requests beautifulsoup4 pandas
```
3. Run each cell sequentially
4. Download the generated `.csv` file

---
📁 File Structure
```
project/
|-- notebook.ipynb
|-- output.csv
|-- README.md
```
💡 Key Learnings
- Basics of web scraping using Python
- HTML parsing and navigation
- Data cleaning techniques
- Working with Pandas DataFrames
- Exporting data for real-world applications

---
⚠️ Disclaimer

This project is for educational purposes only. Ensure that web scraping complies with the website's terms of service and robots.txt policies.
