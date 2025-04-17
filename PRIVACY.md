# **Rocketman Command Center (RCC) Privacy Policy**

_Last updated: March 14, 2025_

## 1. Overview

Rocketman Command Center (“RCC”) is a closed-source, free-to-use (see [LICENSE.md](https://github.com/Rocketman-Tech/rcc/blob/main/LICENSE.md)) macOS utility designed to integrate with Jamf Pro. We care about your privacy and security. This policy explains what data RCC handles, how it is handled, and what safeguards are in place.

## 2. Scope

This policy covers RCC’s handling of data in both local deployments and organizational rollouts. It applies to how RCC behaves on user machines and any interactions it has with your Jamf Pro instance.

## 3. Data Collection and Usage

1. **No Direct User Data Collection by Rocketman Tech**  
   - RCC does **not** transmit any user or device data to any Rocketman Tech servers.  
   - There is no built-in telemetry or analytics sending data to Rocketman Tech.

2. **Jamf Pro Integration**  
   - When configured to do so, RCC calls **only** your organization’s Jamf Pro API.  
   - Data fetched or sent via these API calls (e.g., building IDs, department info, user privileges) is processed locally or within Jamf Pro. No external third-party services are involved.

3. **Local Logging**  
   - RCC creates logs locally on the device where it is installed. These logs record actions taken (e.g., initiating FileVault encryption, updating user privileges) and may contain identifiable information, depending on usage.  
   - When administrators invoke RCC via Jamf Pro, Jamf Pro may also capture relevant logs as part of normal execution.

4. **Log Sharing for Support**  
   - If you request support from Rocketman Tech, we may ask you to share RCC-generated logs to help diagnose issues. These logs might contain identifiable information (e.g., usernames, device info).  
   - We recommend reviewing or anonymizing logs before sharing them with Rocketman Tech, if confidentiality is a concern.

## 4. Security Measures

1. **Minimal Permissions Model**  
   - RCC is designed with the principle of least privilege, limiting access only to what is necessary for its functionality.  
   - Administrators control which features of RCC interact with Jamf Pro.

2. **Secure Storage of Credentials**  
   - Any credentials (e.g., admin passwords for “Break Glass Admin”) are stored locally on the machine (e.g., in the macOS system keychain) and are never sent to Rocketman Tech servers.

3. **No External Connections**  
   - Aside from optional API calls to Jamf Pro (your instance), RCC does not connect to any external services.

## 5. Third-Party Disclosure

- RCC does not share data with any third parties.  
- All data interactions remain within your environment or Jamf Pro infrastructure.

## 6. Compliance and Future Plans

- RCC is built with privacy and security in mind, and we are actively exploring **SOC 2** compliance.  
- We encourage users to operate RCC in a manner consistent with their own organization’s privacy and compliance requirements.

## 7. Changes to This Policy

- We may update this Privacy Policy over time. All updates will be posted in our GitHub repository so you can stay informed.  
- We encourage you to check this page periodically for the latest information.

## 8. Contact Us

For questions, concerns, or feedback about RCC’s privacy practices, please reach out to us:

- **Email:** [support@rocketman.tech](mailto:support@rocketman.tech)  
- **GitHub Issues:** [Submit a request or report an issue](https://github.com/Rocketman-Tech/rcc/issues/new/choose)
