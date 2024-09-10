# 🕸️ **Web Scraping Workshop** 🕸️

Welcome to the **Web Scraping with Python Workshop**! 🎉 In this workshop, you'll learn how to extract valuable data from websites using Python's **BeautifulSoup** and **Selenium**. By the end, you’ll have hands-on experience with scraping, and you’ll complete a mini project to apply what you’ve learned.

## 🗂️ **Workshop Overview**

- **Jupyter Notebooks** for interactive learning
- **BeautifulSoup** to scrape HTML
- **Selenium** for interacting with dynamic websites
- **Mini Project**: Apply your knowledge on a real-world scraping task
- **Sample HTML Files**: Practice with provided files

---

## 💻 **Getting Started**

### 1. **Prerequisites**

Before you begin, ensure you have the following installed:

- **Anaconda**: Download [here](https://www.anaconda.com/products/distribution)
- **Jupyter Notebook**: Installed with Anaconda
- **Google Chrome**: For Selenium automation


---

### 2. **Installation Instructions**

1. **Create a Virtual Environment** (optional but recommended)
   ```bash
   conda create -n web_scraping python=3.9
   conda activate web_scraping
   ```

2. **Install Required Libraries**:
   ```bash
   pip install beautifulsoup4 selenium pandas matplotlib
   ```

3. **Run Jupyter Notebooks**:
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open the provided **Jupyter Notebooks** to follow along with the workshop.

---

## 🗒️ **Workshop Modules**

### 📖 1. **BeautifulSoup Basics**
- **Notebook**: `WebScraping_Book1.ipynb`
- Learn how to parse static HTML pages.
- Topics covered:
  - **Parsing HTML/XML**
  - **Searching and extracting data** using `find`, `find_all`, and `select`
  - **Handling malformed HTML**
  
  **Sample HTML**: `Test_HTML_1.html` and `Test_HTML_2.html  provided in the `Sample_Files` folder.

### ⚙️ 2. **Selenium Basics**
- **Notebook**: `Webscraping_Book2.ipynb`
- Learn how to interact with dynamic content and JavaScript-heavy websites.
- Topics covered:
  - **Navigating websites** with Selenium
  - **Interacting with forms, buttons, and other elements**
  - **Automating user actions** like clicks and text entry
  
  **Sample HTML**:`Test_HTML_3.html` provided in the `Sample_Files` folder.

### 🎯 3. **Mini Project**
- **Notebook**: `Webscraping_Book3_Test.ipynb`
- Apply both BeautifulSoup and Selenium to scrape real-world data.
- Task: Extract information from a website, automate some interactions, and clean up the data using Python.

  **Hint**: Use both **static scraping (BeautifulSoup)** and **dynamic scraping (Selenium)** where necessary. 🧑‍💻

---

## 🚀 **How to Use the Sample Files**

- **Sample HTML Files**: These are static files for you to practice scraping using BeautifulSoup/Selenium. Start with simple parsing, and try extracting elements by tags, attributes, or class names.
  - Example: `Test_HTML_1.html`

- **Notebook Examples**: Each notebook contains step-by-step instructions and code snippets that will help you learn the tools. Run the cells and modify the code to experiment with different scenarios.

---

## 🎉 **Workshop Project**

For the mini-project, we have chosen a publicly accessible website (https://www.hochschulkompass.de/) and gather specific data:
1. **Task**: Extract university details (name, location, number of students, etc.) from an education portal using **Selenium** and **BeautifulSoup**.
2. **Submission**: Create a notebook summarizing your scraping process, clean data, and visualizations.
3. **Presentation**: Share your findings and challenges with the group.
4. **Master File with Solution**: After the workshop, we will upload a master file that contains a complete solution for the mini-project. You can compare your approach with the solution and identify areas of improvement.

---

## 🔧 **Tips and Troubleshooting**

- **Jupyter Notebook not running?**
  - Try restarting your Anaconda environment.
  - Make sure you’re using the correct Python version (`python --version`).

- **Selenium Errors?**
  - Ensure that the **ChromeDriver** version matches your **Google Chrome** version.
  - Update ChromeDriver if necessary.

- **BeautifulSoup Issues?**
  - Be cautious with malformed HTML; you might need to use `lxml` as the parser to handle tricky HTML structures.

---

## 🎯 **Workshop Goals**

By the end of this workshop, you will:
- Be comfortable using **BeautifulSoup** for parsing static HTML.
- Know how to handle **JavaScript-heavy** websites with **Selenium**.
- Understand the basics of web scraping ethics and how to scrape responsibly.
- Be able to complete a **real-world scraping project** on your own.

---

## 🌟 **Have Fun!**

Web scraping is all about **experimentation** and **iteration**. It may not work perfectly on the first try, but keep experimenting! Scraping is a great tool for social scientists to gather and analyze data from the web.

Feel free to ask questions and **enjoy the journey**! 🎉

---

### 📧 **Contact and Support**
If you run into any issues, feel free to reach out:
- **Instructors**: Saijal Shahania & Dr. David Broneske
- **Email**: shahania@dzhw.eu, broneske@dzhw.eu

Happy scraping! 😊

---


