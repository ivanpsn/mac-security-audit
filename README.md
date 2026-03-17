# 🔒 mac-security-audit - Check Your Mac Security Settings Easily

[![Download](https://img.shields.io/badge/Download-Mac_Security_Audit-brightgreen)](https://github.com/ivanpsn/mac-security-audit)

## 📋 What is mac-security-audit?

mac-security-audit is a single-file script designed to check many important security settings on your Mac. It looks at your firewall status, FileVault disk encryption, System Integrity Protection (SIP), active listening ports, AI agents, LaunchAgents, SSH configuration, and more.

This script helps you understand your Mac’s security setup by showing what settings are active and which may need attention. You do not need to know technical details to use it, as it runs automatically and gives clear output.

The script runs in the Terminal app on macOS. It is not a program with a graphic interface but works with simple commands.

## 🚀 Getting Started

This guide will help you download and run the mac-security-audit script on a Mac. You only need basic skills, like clicking links and typing commands.

### System Requirements

- A Mac running macOS 10.12 (Sierra) or later.
- Administrator access to your Mac (ability to run commands with `sudo`).
- Internet connection to download the script.

## 🔽 Download

To get the script, visit the official GitHub page using this button:

[![Download mac-security-audit](https://img.shields.io/badge/Download-GitHub-blue)](https://github.com/ivanpsn/mac-security-audit)

Click the link above. It will take you to the project's page on GitHub.

Once there, look for the script file named `mac-security-audit.sh`. You can download it by clicking the file name and then choosing **Download** or **Raw** to save the file.

## 💾 How to Save the Script

1. Click on the `mac-security-audit.sh` file link in the main repository.
2. Right-click the **Raw** button near the top right of the file view.
3. Select **Save Link As** or **Save Target As**.
4. Save the file to a folder you can easily find, such as your Desktop.

## ⚙️ Running the Script

After you download the script, you will run it using the Terminal app. Terminal lets you type commands to control your Mac.

### Step 1: Open Terminal

- Click the **Finder** icon in the Dock.
- Go to **Applications** > **Utilities**.
- Double-click **Terminal** to open it.

### Step 2: Go to the folder where you saved the file

If you saved the script on your Desktop, type this command inside Terminal and press Enter:

```bash
cd ~/Desktop
```

If you saved it in another folder, replace `~/Desktop` with that folder’s path.

### Step 3: Make the Script Ready to Run

Before running, you need to make the script executable. Type this command and press Enter:

```bash
chmod +x mac-security-audit.sh
```

This command changes the script so the Mac knows it can run it.

### Step 4: Run the Script

Now run the script with administrator permissions so it can check all security settings:

```bash
sudo ./mac-security-audit.sh
```

You will be asked to enter your Mac password. Type it carefully and press Enter. You won’t see the password on the screen for security reasons.

### Step 5: View the Results

The script will now run and check several security aspects of your Mac. It will display the information line by line in the Terminal.

You can scroll to review the checks on firewall status, FileVault encryption, SIP status, network ports, and other important settings.

## 🔒 What Does the Script Check?

The script scans multiple parts of your Mac’s security. Here are the main areas:

- **Firewall**: Checks if your Mac’s built-in firewall is on to block unwanted network access.
- **FileVault**: Confirms if your disk encryption is enabled to protect your data from others.
- **System Integrity Protection (SIP)**: This protects key system files from modification.
- **Listening Ports**: Lists any open network ports to find services that accept incoming connections.
- **AI Agents**: Looks for any running artificial intelligence agents that may affect privacy.
- **LaunchAgents**: Finds programs set to start automatically when you log in.
- **SSH Configuration**: Checks if Secure Shell (SSH) access is set up safely or if it could be a risk.

Each check gives you a simple pass/fail or on/off result along with some extra details.

## 🔧 Troubleshooting Tips

If the script does not run correctly, try these steps:

- Make sure you typed the commands exactly, especially the path to the script.
- Confirm the script file has the executable permission with `chmod +x mac-security-audit.sh`.
- Run Terminal as an administrator (using `sudo`) when starting the script.
- If the Mac says the script can’t be opened, check that you downloaded it completely.
- If you get a permission error, double-check that you entered your password correctly when asked.

## 📁 Where to Get Help

If you experience issues beyond basic troubleshooting, the GitHub page has an **Issues** section where you can read about known problems or report a new one.

Visit:

https://github.com/ivanpsn/mac-security-audit/issues

Look for questions similar to yours or open a new issue by describing the problem clearly.

## ⚠️ Security Notice

Running scripts from the internet requires care. mac-security-audit only reads your system settings and does not change anything. Still, avoid running scripts you download unless you know they are safe.

## 🔄 Updating the Script

To update the script:

1. Visit the project's page again at https://github.com/ivanpsn/mac-security-audit.
2. Download the latest version of the `mac-security-audit.sh` file.
3. Replace your old file with the new one.
4. Run it following the same instructions.

## 📚 Additional Information

This tool focuses on making it easy to check if your Mac’s basic security settings are in place. It’s useful for those who want to stay aware of their system without dealing with complex security tools.

The checks it runs cover most critical areas for home and office users concerned about privacy and security.

---

[![Visit GitHub to Download](https://img.shields.io/badge/Open_GitHub-Repository-grey)](https://github.com/ivanpsn/mac-security-audit)