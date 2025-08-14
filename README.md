# getMeAJob

## 📌 Overview
**getMeAJob** is a Selenium IDE automation project designed to **scrape and apply to student job listings** from sites such as [schonherz.hu](https://www.schonherz.hu) based on **predefined criteria**.

The automation opens job listing pages, checks for an **"Apply"** button, and:
- Clicks **Apply** if the job matches your criteria and you haven’t applied yet.
- Skips the listing if:
  - You already applied.
  - The apply button is missing.
  - The listing doesn't match your filters.

The `.side` project files allow you to easily import and run the automation in your browser with [Selenium IDE](https://www.selenium.dev/selenium-ide/).

---

## 🚀 Features
- **Targeted Job Search:** Focuses on student job boards such as schonherz.hu.
- **Auto Apply:** Automatically applies to jobs when possible.
- **Duplicate Prevention:** Skips jobs you have already applied to.
- **Criteria-Based Filtering:** Only applies to positions matching your personal preferences.
- **Hands-Free Workflow:** Runs through multiple listings without manual clicks.

---

## 🛠 Requirements
- **Selenium IDE** browser extension:
  - [Firefox Add-on](https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/)
- Firefox
- `.side` project files from this repository

---

## ⚙️ Usage
1. **Install Selenium IDE** in your browser.
2. **Import the `.side` file**:
   - Open Selenium IDE
   - Go to `File → Open Project`
   - Select your desired `.side` file
3. **Adjust the search/filter criteria** inside Selenium IDE if needed.
4. **Run the test suite**:
   - The script will open the job site, go through listings, and:
     - Apply when the button is present and criteria match.
     - Skip if already applied or button not found.
5. **Check your job portal account** to see which applications were submitted.

---

## 📌 Customization
You can:
- Modify the criteria for applying.
- Schedule automatic runs with [Selenium-side-runner](https://www.selenium.dev/selenium-ide/docs/en/introduction/command-line-runner) for daily job hunts.

---

## 📄 License
This project is licensed under the MIT License — you are free to use, modify, and share it.

---

## 💡 Disclaimer
This project is for **personal use only**. Please respect the terms of service of each job portal before running automated scripts.
