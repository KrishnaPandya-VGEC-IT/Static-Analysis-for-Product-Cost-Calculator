# Static-Analysis-for-Product-Cost-Calculator
This repo contains project that focuses on performing Static Analysis on Product Cost Calculator.

Here are some project keypoints:

-	The tool I have used for static code analysis is pmd-eclipse- plugin 4.40.0
-	In the results by PMD The code contains two Data flow anomalies on lines 21 and 22 respectively.


Project Setup:

-	pmd-eclipse plugin is a very useful plugin when it comes to code analysis. The tool is available on the eclipse marketplace.

-	After clicking the install button, and restarting the IDE, we can directly right-click on the project -> PMD -> Check code to analyze the code.

-	The tool provides the Violations overview, violations outline, and detailed descriptions.

-	It categorizes violations in 5 types: Warning, Important, Urgent, critical, and blocker (from less severe to more severe)

-	Under detailed outline, it shows the type of violation, line, the time when it was founded (in execution), Rule it violates, and Error message.
