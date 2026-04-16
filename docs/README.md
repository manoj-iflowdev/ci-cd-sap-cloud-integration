This Integration Package [Continuous Integration and Delivery for SAP Cloud Integration](https://github.com/nesun3/ci-cd-sap-cloud-integration/tree/main/build#download-the-zip-file-of-the-integration-package-and-import-it-to-your-tenant) contains integration flows to illustrate the design to implement the Continuous Integration (CI) and Continuous Delivery/Deployment (CD) pipelines for SAP Cloud Integration Projects. This enables you to create your own CI/CD pipelines without relying on native Git, a prerequisite for most CI/CD tools, or requiring additional specialized knowledge.

The Integration Package contains 4 integration flows built in such a way that you only need to replace a few configuration parameters specific to your environment and organization/project. The rest of the logic remains as is, making it simple and easy to get started.

Further, you can use this package as a starting template to create your own CI/CD pipelines tailored to your organization/project needs and customize them further.

> This package uses the public ODATA APIs of the SAP Integration Suite and public GitHub REST API under the hood to create CI/CD pipelines.

| Integration Flow Name | Descriptions |
|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sync Integration Contents to GitHub | Sync all or specific integration contents (only packages, iflows, value mappings) from the SAP Cloud Integration tenant to GitHub Repository to store and see the full history of changes |
| Sync Integration Contents to GitHub - Delta | Check the SAP Cloud Integration tenant for a new version of your integration contents (only packages, iflows) and if a new version exists, sync the changed integration contents to GitHub Repository and keep track of the latest changes. |
| Transport Integration Contents | Export the latest version of all or specific integration artifacts (either packages or iflows or value mappings) from the Source tenant and either import or update the artifact on the Target tenant without using any external tool. |
| Upload Integration Contents from GitHub | Download the latest version of either an integration flow artifact or resources of an integration flow artifact from GitHub repository and either update or create the artifacts on the tenant. |

# Prerequisites
Ensure that you have these [prerequisites](https://github.com/nesun3/ci-cd-sap-cloud-integration/blob/main/.config/README.md) in place before proceeding with the interface configuration.

# Configuration
> If the prerequisites are fulfilled, you'll be ready to configure the external parameters of the integration flow!

Follow the configuration guide for each interface in the table below, which contains links to their respective configuration guides.

| Integration Flow Name | Config Guide Link |
|---------------------------------------------|-------------------|
| Sync Integration Contents to GitHub | [Link](https://github.com/nesun3/ci-cd-sap-cloud-integration/tree/main/.config/Sync%20Integration%20Contents%20to%20GitHub#external-parmeter-configuration-on-sap-cloud-integration) |
| Sync Integration Contents to GitHub - Delta | [Link](https://github.com/nesun3/ci-cd-sap-cloud-integration/tree/main/.config/Sync%20Integration%20Contents%20to%20GitHub%20-%20Delta#external-parmeter-configuration-on-sap-cloud-integration) |
| Transport Integration Contents | [Link](https://github.com/nesun3/ci-cd-sap-cloud-integration/tree/main/.config/Transport%20Integration%20Contents#external-parmeter-configuration-on-sap-cloud-integration) |
| Upload Integration Contents from GitHub | [Link](https://github.com/nesun3/ci-cd-sap-cloud-integration/tree/main/.config/Upload%20Integration%20Contents%20from%20GitHub#external-parmeter-configuration-on-sap-cloud-integration) |

# Step-by-Step Walkthrough
| Integration Flow Name | Walkthrough/Demo Link |
|---------------------------------------------|-----------------------|
| Sync Integration Contents to GitHub | [Link](https://youtu.be/IKupHcvvHwI) |
| Sync Integration Contents to GitHub - Delta | [Link](https://youtu.be/X_Vz7-pr7X4) |
| Transport Integration Contents | [Link](https://youtu.be/SUVq4Y_CZuk) |
| Upload Integration Contents from GitHub | [Link](https://youtu.be/427mmiJBXTk) |

# Maintainer
This project is maintained by Manoj Gali, a Senior SAP CPI Consultant with over 5 years of experience in SAP integration technologies. Manoj specializes in SAP CPI, PI/PO, and hybrid integration landscapes, with deep technical expertise in Groovy Scripting, XSLT, and User-Defined Functions (UDFs). He focuses on designing, developing, and optimizing scalable integration solutions to ensure secure, high-performance data exchange across enterprise environments.

For questions or contributions regarding this integration package, please reach out via:
- Email: manoj.gali695@gmail.com