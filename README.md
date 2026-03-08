# OWASP ZAP Web Spidering Lab

## Objective

The objective of this lab is to demonstrate how web spidering works using OWASP ZAP to discover hidden pages, directories, and application endpoints in a web application.

## Tool Used

- OWASP ZAP
- Kali Linux
- Web Browser

## What is Web Spidering?

Web spidering is the process of automatically crawling a web application to discover all available pages, links, and resources.

Security professionals use spidering to:

- Map the structure of a web application
- Identify hidden endpoints
- Discover attack surfaces

## Lab Steps

1. Open OWASP ZAP
2. Configure the browser to use ZAP as a proxy
3. Navigate to the target web application
4. In OWASP ZAP select the target URL
5. Run **Spider Scan**
6. ZAP begins crawling the website and collecting URLs
7. Review discovered endpoints in the **Sites** panel

## Results

The spider scan successfully mapped the structure of the target web application and discovered multiple pages and resources that could be further analyzed for vulnerabilities.

## Screenshots

Screenshots of the spidering process are stored in the screenshots folder.

## What I Learned

- How web spidering works in security testing
- How OWASP ZAP maps web applications
- How security testers discover hidden endpoints

## References

OWASP ZAP Official Documentation
