# AI-Powered Career Assistant

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

## Support
For further assistance, contact the development team via Teams or submit a ticket using the internal support portal.

## License
This project is licensed under the [MIT License](LICENSE).

---
*Empower your workforce with actionable career insights — with AI-Powered Career Assistant.*

