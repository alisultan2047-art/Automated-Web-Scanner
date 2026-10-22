# Automated Web Scanner

**Project Description**
This project is an automated Python script built for the IBM SkillsBuild Cyber Security BootCamp. It is designed to audit target websites for missing secure HTTP response headers and potential Cross-Origin Resource Sharing (CORS) flaws.

**Dataset Link**
Not applicable. This project does not use a static dataset; it pulls live data directly from target URLs using standard web requests.

**Technologies Used**
- Python
- Google Colab / Jupyter Notebook
- Python `requests` library

**Setup and Run Instructions**
1. Install the required dependencies by running: `pip install -r requirements.txt`
2. Open the `Ali_Sultan_AutomatedWebScanner.ipynb` file in Google Colab or Jupyter Notebook.
3. Run the code cell to execute the scan on the default test website (https://example.com).
4. Review the printed output to see which security headers passed or failed.

**Key Information**
The scanner specifically checks for the presence of Strict-Transport-Security, Content-Security-Policy, X-Frame-Options, and X-Content-Type-Options. It also checks the Access-Control-Allow-Origin header to warn if a website has an overly permissive CORS policy.
