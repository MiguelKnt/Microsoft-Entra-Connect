# Integrating On-Premises Active Directory with Microsoft Entra ID

## Overview
In this project, I successfully integrated an **on-premises Active Directory (AD)** with **Microsoft Entra ID** (formerly Azure AD) using **Entra Connect**. The primary goal was to enable hybrid identity synchronization, providing secure access to cloud resources while retaining control over user management within the on-premises Active Directory.

## Project Objectives
- 🔄 Set up **Microsoft Entra Connect** to synchronize on-premises Active Directory with Microsoft Entra ID.
- 🔐 Enable **Hybrid Identity**, ensuring users can securely authenticate across both on-premises and cloud environments.

## Technologies Used
- 🌐 **Microsoft Entra ID** (formerly Azure AD)
- 💻 **On-Premises Active Directory** (Windows Server)
- ⚙️ **Microsoft Entra Connect**
- ☁️ **Azure Portal**

## Setup & Configuration

### Prepare On-Premises Active Directory
- 🖥️ Ensured that the on-prem AD environment was fully configured with accessible domain controllers.
- ✅ Verified that the User Principal Name (UPN) suffixes were compatible with Entra ID for synchronization.

### Install Entra Connect
- 📥 Downloaded and installed **Microsoft Entra Connect** on the designated server.
- ⚙️ Chose the appropriate synchronization method to sync user data from on-prem AD to Entra ID.

### Configure Synchronization
- 🔄 Ran the initial synchronization process to connect on-prem AD with Microsoft Entra ID and began syncing user attributes.
- 🛠️ I Ensured successful synchronization and resolved any errors that occurred during the process.

## Results & Key Takeaways
- 🔑 Successfully established **Hybrid Identity** to allow users in the on-premises Active Directory to authenticate via Microsoft Entra ID.
- 🌐 Ensured users could access cloud resources with their on-premises credentials, simplifying the user experience.

