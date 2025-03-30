# CareerWise - AI Powered Career Assistant 
Link to the Demo Website - http://copilotstudio.microsoft.com/environments/Default-8d1a69ec-03b5-4345-ae21-dad112f5fb4f/bots/cr0f0_careerWiseBot/canvas?__version__=2&enableFileAttachment=true

![Logo](https://github.com/user-attachments/assets/cecac6f2-6db5-4efc-a131-52cb16e0fd89)

## Quackathon - Stevens Institute Of Technology

## Team Name
Team Bermuda

## Project Members
Sanika Mhadgut

Abhishek Kumar

Ankit Chaurasia


## Overview
The AI-Powered Career Assistant is a smart conversational AI system designed to help employees make informed career decisions by providing actionable insights from complex payroll and market data. The system leverages Microsoft Copilot Studio, integrating with various data sources to offer personalized career guidance.

## Features
1. **Conversational AI**: Natural conversations with employees to answer career-related questions.
2. **Human Capital Management**: Dedicated HR bot for employee support.
3. **Data Integration**: Connects to sources like Glassdoor, ADP, and Reddit for market insights.
4. **Employee Data Access**: Reads from employee CSV and company documents.
5. **Earning Potential Insights**: Analyzes data to generate earning insights.
6. **Personalized Career Roadmaps**: Provides tailored career growth recommendations.
7. **Data Correction Requests**: Facilitates employee data correction via Adaptive Cards in Microsoft Teams.
8. **Teams Integration**: Notifications and messages through Microsoft Teams.
9. **Application Monitoring**: Integrated with Azure Application Insights.
10. **Website Deployment**: Hosted on the company’s website.
11. **Multilingual Support**: Supports multiple languages.
12. **Exportable Reports**: Generates PDF or PPT reports for mentorship discussions.
13. **Mentor Matching**: Connects employees with mentors based on goals.
14. **Analytics Dashboard**: Provides visual analytics via an embedded tab in Copilot.
15. **Power Automate Flows**: Automates workflows for streamlined operations.
16. **Secure Authentication**: Powered by Microsoft Azure AD.

## Architecture
```
      Employee                  Glassdoor, ADP, Reddit APIs
          |                                 |            
  Microsoft Teams    <---->   Copilot Studio <---->    Power Automate
          |                                 |            
  Employee Data CSV                Azure Application Insights
          |                                 |            
     Company Website          Microsoft Azure AD (Authentication)
```

## Topic Triggers and Use Cases
### **Employee Analytics**
- **Employee Lookup & Verification**: Confirm employee status using employee data CSV.
- **Payroll & Compensation**: Retrieve latest salary or bonus information.
- **Attendance & Leave Management**: Track overtime hours and attendance records.
- **Career Growth**: Provide career growth options and insights.

### **Employee FAQ**
- **For New Users**: Guide on ADP account setup.
- **For Current Employees**: Help with tax withholding updates.
- **For Exiting Employees**: Provide 401(k) information.

### **HR Analytics**
- **Employee Compensation Analysis**: Compare net pay across departments.
- **Department and Role Insights**: Identify departments with the highest salaries.
- **Employee-Specific Queries**: Provide detailed compensation breakdowns.
- **General Insights and Trends**: Analyze relationships between overtime hours and pay.
- **Budget Management**: Recommend strategies to optimize department expenses.

## Technologies Used
- **Languages**: JSON
- **Frameworks**: Microsoft Power Platform, Adaptive Cards
- **Platforms**: Microsoft Copilot Studio, Microsoft Teams
- **Cloud Services**: Azure Application Insights
- **Databases**: Excel, CSV Files
- **APIs**: Glassdoor API, ADP API, Reddit API
- **Automation**: Power Automate
- **Authentication**: Microsoft Azure AD

## Setup Instructions
1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    ```
2. **Configure APIs**:
    - Register with Glassdoor, ADP, and Reddit APIs for access keys.
    - Update API keys in the configuration file.
3. **Connect Data Sources**:
    - Upload employee data CSV and HR data CSV.
4. **Deploy on Microsoft Copilot Studio**:
    - Import the solution package to your Copilot Studio workspace.
5. **Enable Teams Integration**:
    - Connect the bot to Microsoft Teams.
6. **Monitor with Azure**:
    - Configure Azure Application Insights for monitoring and logging.
7. **Authentication**:
    - Enable Microsoft Azure AD for secure login.

## Usage
- Open Microsoft Teams and search for the AI Career Assistant bot.
- Ask career-related questions like:
  - *"Can you confirm if Gina Cook is still employed here?"*
  - *"I am Sheila Holmes, can you show me my latest bonus details?"*
- Use Adaptive Cards for data correction requests.
- Access visual reports from the analytics tab.

## Demo:


![WhatsApp Image 2025-03-30 at 09 37 48](https://github.com/user-attachments/assets/46610bb7-6e2a-4187-b976-a0af1794c5f1)
<img width="467" alt="Screenshot 2025-03-30 at 10 36 01 AM" src="https://github.com/user-attachments/assets/d833d689-f4a4-4acc-b9dc-6d55222f9ce6" />
<img width="1470" alt="Image14" src="https://github.com/user-attachments/assets/ab070bab-0643-4ddd-9b3f-0709de49117f" />
<img width="1470" alt="Screenshot 2025-03-30 at 10 32 07 AM" src="https://github.com/user-attachments/assets/39a2c198-b40e-4046-b8e1-4888c9ca41ed" />
<img width="350" alt="Screenshot 2025-03-30 at 1 14 52 PM" src="https://github.com/user-attachments/assets/24605aa1-854c-41b7-a7d0-5ad3dc940fee" />

<img width="356" alt="Screenshot 2025-03-30 at 1 16 21 PM" src="https://github.com/user-attachments/assets/8be6fb29-7663-4a03-a3e3-af46cb309fd9" />
<img width="354" alt="Screenshot 2025-03-30 at 1 17 47 PM" src="https://github.com/user-attachments/assets/acd5ba54-bea5-44df-961e-adc584625749" />
<img width="1470" alt="Screenshot 2025-03-30 at 12 50 26 PM" src="https://github.com/user-attachments/assets/9ed37ae5-5970-487d-9c70-9b7e267a35a1" />
<img width="353" alt="Screenshot 2025-03-30 at 1 24 29 PM" src="https://github.com/user-attachments/assets/092f13c4-e887-4b1e-b6de-bfe0ae56b77a" />

<img width="1468" alt="Screenshot 2025-03-30 at 10 31 29 AM" src="https://github.com/user-attachments/assets/557790dd-a9d9-4fa6-941d-9a872dded135" />
<img width="1468" alt="Screenshot 2025-03-30 at 10 31 07 AM" src="https://github.com/user-attachments/assets/339f9ac1-beb4-4fcf-8659-7d7b049975c6" />
<img width="1271" alt="Screenshot 2025-03-30 at 10 29 22 AM" src="https://github.com/user-attachments/assets/33582a2f-13a8-4479-bc81-4f0600da37db" />
<img width="1391" alt="Screenshot 2025-03-30 at 10 28 35 AM" src="https://github.com/user-attachments/assets/fc22c70c-8425-4855-b1f9-6321a1a856fa" />
<img width="1008" alt="Screenshot 2025-03-30 at 10 28 10 AM" src="https://github.com/user-attachments/assets/8cd7aaae-d221-470f-9afe-8f3910b15d16" />
<img width="1470" alt="Screenshot 2025-03-30 at 10 27 47 AM" src="https://github.com/user-attachments/assets/89bff117-d247-47e7-af6f-3e60c39263d5" />
<img width="172" alt="Screenshot 2025-03-30 at 10 27 05 AM" src="https://github.com/user-attachments/assets/be9578ad-13ec-46a9-91bf-4b26db743ac8" />
<img width="175" alt="Screenshot 2025-03-30 at 10 26 55 AM" src="https://github.com/user-attachments/assets/2adc32c1-3ff3-4cfc-9a6c-36cdbe58e94a" />
<img width="174" alt="Screenshot 2025-03-30 at 10 26 43 AM" src="https://github.com/user-attachments/assets/c022e8ef-49e0-4d6d-ade7-1f530b6a8f7f" />
<img width="1060" alt="Screenshot 2025-03-30 at 10 26 21 AM" src="https://github.com/user-attachments/assets/a251cae3-104f-40b8-a26c-b24cb1939d7e" />
<img width="254" alt="Screenshot 2025-03-30 at 10 05 01 AM" src="https://github.com/user-attachments/assets/1ad23b24-94d1-46c9-92a1-5e16f05850e2" />




## Support
For further assistance, contact the development team via Teams or submit a ticket using the internal support portal.

## License
This project is licensed under the [MIT License](LICENSE).

---
*Empower your workforce with actionable career insights — with AI-Powered Career Assistant.*

