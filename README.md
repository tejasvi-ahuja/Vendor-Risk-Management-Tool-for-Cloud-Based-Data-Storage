# Vendor Risk Management Tool for Cloud-Based Data Storage

## Overview

This project provides a comprehensive set of tools for assessing and managing the risks associated with third-party vendors who store or process your organization's data on their cloud infrastructure. The solution consists of two main Excel files:

1. **Vendor Risk Assessment Questionnaire** – A detailed set of questions that should be asked of third-party vendors who host your data in cloud environments. The questionnaire is designed to evaluate their security, compliance, and risk management practices.
2. **Risk Calculation Tool** – A tool that uses the answers from the Vendor Risk Assessment Questionnaire to calculate and assess the overall risk of working with each vendor. It considers factors such as risk likelihood, impact, risk appetite, and mitigation strategies, and presents a comprehensive summary dashboard.

The goal of this project is to provide organizations with a streamlined way to evaluate the security, compliance, and risk posture of any vendor hosting data in cloud environments, whether on public cloud platforms (e.g., AWS, Azure, Google Cloud) or private cloud infrastructures.

## Files

### 1. Vendor Risk Assessment Questionnaire

This Excel file contains a comprehensive list of questions across several domains. It helps evaluate how vendors manage and protect data stored on their cloud infrastructure.

**Domains Covered:**
- **Application & Interface Security**
    - Example Question: *Do you provide tenants with documentation on how you maintain segregation of duties within your cloud service offering?*
- **Audit Assurance & Compliance**
    - Example Question: *Do you review your Information Security Management Program (ISMP) at least once a year?*
- **Change Control & Configuration Management**
    - Example Question: *Are there controls in place to prevent unauthorized access to your application, program, or object source code, and ensure it is restricted to authorized personnel only?*
- **Data & Information Security Lifecycle Management**
    - Example Question: *Do you encrypt tenant data at rest within your environment?*
- **Encryption & Key Management**
    - Example Question: *Do you have documented ownership for each stage of the lifecycle of encryption keys?*
- **Governance & Risk Management**
    - Example Question: *Do you conduct risk assessments associated with data governance requirements at least once a year?*
- **Human Resources**
    - Example Question: *Is a formal disciplinary or sanction policy established for employees who have violated security policies and procedures?*
- **Identity & Access Management**
    - Example Question: *Do you provide documentation that describes your access control policies and how you manage user access to tenant data?*
- **Infrastructure & Virtualization**
    - Example Question: *Do you have documented information security baselines for every component of your infrastructure (e.g., hypervisors, operating systems, routers, DNS servers, etc.)?*
- **Mobile Security**
    - Example Question: *Do you enforce security policies on mobile devices accessing your cloud services?*
- **E-Discovery**
    - Example Question: *Are you capable of supporting litigation holds for a specific tenant without freezing data from other tenants?*
- **Supply Chain Management**
    - Example Question: *Do you ensure your suppliers and service providers adhere to your information security policies?*
- **Threat & Vulnerability Management**
    - Example Question: *Do you continuously monitor and assess vulnerabilities within your cloud environment?*
- **Business Continuity**
    - Example Question: *Do you provide a tenant-triggered failover option for disaster recovery?*

### 2. Risk Calculation Tool

The Risk Calculation Tool is an Excel file that uses responses from the **Vendor Risk Assessment Questionnaire** to calculate the overall risk associated with a vendor. The tool evaluates risk likelihood, potential business impact, risk appetite, and suggests mitigation strategies for each domain. The output is a detailed risk profile and a visual summary dashboard.

**Key Features of the Risk Calculation Tool:**
- **Risk Likelihood**: Estimates the likelihood of a risk event happening based on the vendor’s responses.
- **Impact Definition**: Assesses the potential business impact of a risk event occurring.
- **Risk Appetite**: Customizable to reflect your organization’s tolerance for risk.
- **Mitigation Description**: Provides recommended actions for mitigating each identified risk.
- **Risk Score**: Calculates an overall risk score to help prioritize vendors based on risk.
- **Summary Dashboard**: A visual dashboard summarizing the vendor’s overall risk, likelihood, impact, and mitigation status.

## How to Use

1. **Complete the Vendor Risk Assessment Questionnaire**:
   - Fill in the questionnaire with the responses from your vendor. This helps you assess how the vendor handles various aspects of data security, governance, compliance, and more.
   
2. **Input Data into the Risk Calculation Tool**:
   - Transfer the vendor’s responses from the **Vendor Risk Assessment Questionnaire** into the **Risk Calculation Tool**. The tool will automatically calculate the associated risks and scores.

3. **Review the Risk Profile**:
   - The tool will generate a risk profile that includes:
     - **Likelihood** and **Impact** ratings for each risk domain.
     - **Risk Appetite** settings based on your organization's thresholds.
     - A **Risk Score** to help you prioritize the vendor.
     - **Mitigation Actions** to reduce or eliminate identified risks.
     - A **Summary Dashboard** for a quick visual overview of the vendor’s risk.

4. **Make Informed Decisions**:
   - Based on the generated risk profile, evaluate if the vendor meets your organization’s security and compliance requirements. Use the risk mitigation actions to help manage any potential gaps.

## Getting Started

1. Clone or download this repository.
2. Open the **Vendor Risk Assessment Questionnaire** file and fill in the vendor’s answers to the questions.
3. Open the **Risk Calculation Tool** file and input the responses from the questionnaire.
4. Review the **Risk Profile** and **Summary Dashboard** to assess the overall risk of the vendor.


