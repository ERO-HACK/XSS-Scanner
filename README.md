# 🚀 **XSS Scanner Tool - Usage & Installation Guide**


📝 **Description:**
This tool automates the scanning of web applications for Cross-Site Scripting (XSS) vulnerabilities. 
It injects multiple payloads into URL parameters, sends requests, and analyzes the response to detect 
if the payload caused an XSS. Results show possible vulnerabilities with URLs and allow saving reports.

-----------------------------------------------
▶️ **How to Use:**
Run the scanner script with your target URL.  
Replace the parameter value you want to test with the keyword `XSS`.  
Example command:  
`python main.py --url https://example.com/search?q=XSS.`  
`python main.py -u https://example.com/search?q=XSS.`

-----------------------------------------------
💡 The tool will:  
✅ Inject payloads into the specified parameter  
✅ Send HTTP requests to the target URL  
✅ Analyze responses for XSS execution  
✅ Display progress and possible vulnerabilities  
✅ Prompt you to save vulnerable payload URLs in a report file 

-----------------------------------------------
🛠️ **Author:**  
shayan  
To get this tool, use the @erotools_bot.

-----------------------------------------------
![xxxx](https://github.com/user-attachments/assets/b4e2e20f-aaf6-4e0b-9435-163c9ae76bd8)

