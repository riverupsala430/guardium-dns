# 🛡️ guardium-dns - Simple tools to manage home internet

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/riverupsala430/guardium-dns)

Guardium DNS gives you control over your home internet. It helps you manage what sites your family members access. This application works with the Technitium DNS server. It provides a dashboard to see internet traffic. You can also connect it to your ASUS router to block specific devices from the internet or set up advanced filter rules.

## 📋 What this tool does

Many families want to restrict access to certain websites. Guardium DNS makes this task easy. You can block harmful or distracting content across every device in your home. It uses DNS technology to filter requests before they reach your screens.

Key capabilities include:

*   DNS filtering for a safer online experience.
*   Dashboard to view connected devices and traffic.
*   ASUS router integration for hardware-level control.
*   Kill switch for specific devices found by MAC address.
*   Support for secure traffic like DNS-over-HTTPS.

## ⚙️ System requirements

Your computer must meet these basic needs to run the software:

1. Windows 10 or Windows 11.
2. At least 4 gigabytes of RAM.
3. Technitium DNS server installed on your network.
4. An active network connection.

## 📥 How to setup your software

Follow these steps to install the tool on your Windows computer.

1. Visit [this page to download](https://github.com/riverupsala430/guardium-dns) the latest version.
2. Look for the file marked as the latest release.
3. Save the file to a folder on your computer.
4. Double-click the file to start the installation.
5. Follow the screen prompts to finish the process.
6. Open the program from your desktop shortcut.

## 🖥️ Using the dashboard

The dashboard provides a map of your network activity. You see a list of every device currently online. Each device entry shows its name and current status. 

To create a filter, select the device from the list. Choose the category of sites you want to block. Click save to apply these changes. The software pushes these rules to your DNS provider immediately.

## 🔗 Connecting to your router

Integration with your ASUS router provides deeper control. This connection allows the software to interact directly with your home network hardware.

1. Open the settings menu inside the application.
2. Select the Router tab.
3. Enter the IP address of your ASUS router.
4. Type your router administrator username and password.
5. Click test connection to verify the link.
6. Enable the MAC filter feature to use the kill switch.

The kill switch stops traffic for a device instantly. This feature stays active until you turn it off within the dashboard.

## 🌐 Advanced features

The software supports secure protocols to protect your privacy. DNS-over-HTTPS hides your search history from your internet service provider. You can toggle this setting in the General tab of the application.

Transparent DNS Director ensures all devices on your network follow your rules. It forces every device to use your chosen DNS settings, even if they have manual settings configured.

## 🛠️ Troubleshooting common issues

If the application fails to connect to your DNS server, check these items:

*   Verify the Technitium DNS server is running.
*   Check that your computer sits on the same local network as the DNS server.
*   Ensure your firewall allows traffic on port 5380.
*   Restart the application if the dashboard remains blank after ten seconds.

If you lose control of your router, you can disable the connection in the settings menu. Removing the integration restores your router to its original state.

## 🛡️ Maintaining your home network

Good security habits improve your results with Guardium DNS. Update your DNS lists once a week to keep filters relevant. Check the dashboard logs occasionally to see if any devices attempt to reach blocked sites. This information helps you decide if you need to adjust your blocklist.

Keep your Windows system updated. New updates often address network security gaps that could affect your control software. If you encounter errors, check the logs folder for specific messages. These logs explain why a connection failed or why a rule did not apply.

This tool acts as a layer of protection. Use it alongside other security measures like strong account passwords and secure router configurations to build a robust home network.