JAYASURIYAA N M | QA Engineer Portfolio
Objective: Showcasing end-to-end manual testing, defect reporting, and root-cause analysis across production and simulated e-commerce environments.

Project 1: Live Production Feature Parity & UX Analysis
Target Application: Flipkart (Live Production Environment)

Testing Focus: Usability Testing, Cross-Platform Feature Parity, Support Systems.

Defect Logged: SCRUM-9

Defect Summary: Web Chatbot provides mobile-app instructions for Language Settings; Feature entirely missing on Desktop Web.

Severity: Low (Does not break core purchasing loop).

Priority: Medium (Impacts regional user experience and support deflection).

Execution Details:

Identified a critical architectural discrepancy where the desktop web application lacked the regional language switcher available on the mobile application.

Interrogated the production support chatbot to verify fallback logic. Discovered the bot blindly provided mobile-specific instructions (e.g., "Tap on Choose Language") to desktop users, creating a frustrating UX loop.

Business Impact Analyzed: Documented how this specific flaw degrades user trust for non-English speakers and formulated an enhancement ticket for the Product Team to review.
<img width="1600" height="900" alt="project 1" src="https://github.com/user-attachments/assets/3fd56e0f-ec0e-4408-8a47-28da86e79243" />
Project 2: E-Commerce Sandbox Regression Testing
Target Application: SauceDemo (Dedicated QA Testing Environment)

Testing Focus: Critical Path Testing, Functional UI Testing, Payment Gateway Validation.

Defect Logged: SCRUM-10

Defect Summary: Fatal Checkout Blockade - "Last Name" mandatory field rejects input and prevents payment processing.

Severity: Critical / Sev-1 (Completely blocks the transaction logic).

Priority: Highest (Direct and immediate loss of revenue).

Execution Details:

Executed multiple simulated attacks on a highly volatile e-commerce build.

Discovered a critical failure in the checkout flow where the mandatory "Last Name" input field corrupted keystrokes and instantly cleared user data.

Because the payment gateway requires this field to proceed, this single functional bug completely blocked the checkout process, resulting in a 100% cart abandonment rate.

Captured and attached a 17-second screen recording to provide undeniable visual evidence of the data corruption to the development team, drastically reducing their debugging time.
<img width="637" height="302" alt="Project_2_screenshot" src="https://github.com/user-attachments/assets/dffb4fd9-90a3-430b-ba4a-582a2ee00011" />


https://github.com/user-attachments/assets/e3045f1b-aa6f-4188-8341-a97e20c4075d

