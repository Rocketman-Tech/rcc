<img src="https://github.com/user-attachments/assets/6950ad0b-6df8-421f-8764-6e5a62c6cab5" alt="Rocketman CC - Square Icon" width="250">

# Welcome to Rocketman Command Center!

## 🚀 What is RCC?

The **Rocketman Command Center (RCC)** is your streamlined solution for macOS device management, designed to complement and extend the capabilities of Jamf Pro. By replacing traditional bash scripts with a modern, modular approach, RCC simplifies workflows, enhances efficiency, and improves security for administrators and Jamf engineers alike.

### Key Features:
- **Simplify Deployment**: Perform critical tasks like FileVault management, temporary admin access, or user privilege adjustments with a single command.
- **Enhance Automation**: Integrate seamlessly with Jamf Pro, leveraging API-driven workflows for precision and control.
- **Improve Security**: Use best practices like secure token handling and encrypted API credentials for secure operations.
- **Global Configuration Options**: Manage settings via `.plist` files, Jamf parameters, or a combination of both.
- **User-Friendly Prompts**: Create SwiftDialog-based interfaces to collect input directly from end users.

---

## 💡 Get Started

### First Time Setup?
➡️ [Start Here](./First-Time-Setup)

### Ready to Download?  
➡️ [Access the Latest Releases](https://github.com/Rocketman-Tech/rcc/releases)

### Need a little more control?
➡️ [Understand RCC's Global Options](./Understand-RCC's-Global-Options)

---

## 🛠️ Tools Overview

_The RCC toolbox is modular and organized into individual tools, each tailored for specific tasks. Below is a summary of each tool's purpose to help you quickly understand their functionalities._

- **[App Setup Helper](./App-Setup-Helper)**  
  Streamlines enabling Screen Recording permissions for multiple macOS applications through a single prompt.

- **[Break Glass Admin](./Break-Glass-Admin)**  
  Manages a secure backdoor admin account for emergency access to user devices.

- **[Edit User Profile](./Edit-User-Profile)**  
  Allows users to select their building and department, updating this information in Jamf Pro.

- **[FileVault Token Revoker](./FileVault-Token-Revoker)**  
  Removes FileVault secure tokens from specified user accounts to manage encryption access.

- **[Get Backdoor Admin Password From Keychain](./Get-Backdoor-Admin-Password-From-Keychain)**  
  Retrieves the password of a designated backdoor admin account from the system keychain.

- **[List All FileVault Enabled Users](./List-All-FileVault-Enabled-Users)**  
  Displays all user accounts on a macOS device that have FileVault enabled for compliance monitoring.

- **[Rapid Response](./Rapid-Response)**  
  Runs scripts as soon as a config profile deploys—no waiting around for a Jamf check-in.

- **[Rename Computer](./Rename-Computer)**  
  Programmatically renames macOS computers based on a customizable naming scheme.

- **[Reset Jamf Connect Login Screen](./Reset-Jamf-Connect-Login-Screen)**  
  Reverts the login screen from Jamf Connect back to the macOS native login screen for enhanced security.

- **[Secure Token Sharing Tool](./Secure-Token-Sharing-Tool)**  
  Grants secure tokens to users in various ways, facilitating FileVault management.

- **[Self Service Email](./Self-Service-Email)**  
  Generates pre-filled email templates for users to send via their email client or save as plain text.

- **[Temporary Admin](./Temporary-Admin)**  
  Grants users temporary administrative rights while maintaining security controls.

- **[Update User Info](./Update-User-Info)**  
  Identifies and updates the correct username of the logged-in user in Jamf Pro using directory integrations.

- **[Upload Jamf Logs](./Upload-Jamf-Logs)**  
  Uploads specified log files to Jamf Pro, compressing multiple files if necessary to adhere to size limits.

- **[User Privilege Management](./User-Privilege-Management)**  
  Controls user privileges by promoting or demoting user accounts between standard and admin roles.

---

## 💬 Feedback

### Have Feedback or Found a Bug?  
➡️ [Submit an Issue or Request a Feature](https://github.com/Rocketman-Tech/rcc/issues/new/choose)

### Got Ideas or Questions?  
➡️ [Join us in the MacAdmin Slack channel](https://macadmins.slack.com/archives/C08GJ3CTS5B)

---

## 🌟 Inspiration

Our documentation approach takes inspiration from tools like [`npm`](https://docs.npmjs.com/cli/v10/commands/npm), blending professionalism with user-friendly guidance.
