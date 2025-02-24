# Matomo Analytics Setup for jmcoded.site

## Introduction
This document outlines the steps taken to implement Matomo analytics on the website `http://jmcoded.site` using the "Matomo Analytics - Ethical Stats. Powerful Insights" WordPress plugin. The goal is to track website traffic and gain insights into user behavior.

## Prerequisites
* A Matomo Cloud account (or self-hosted Matomo installation).
* WordPress website `http://jmcoded.site`.
* Administrator access to the WordPress dashboard.

## Steps Taken

1.  **Logged into Matomo Cloud:**
    * Logged into my Matomo Cloud account at `https://jmcoded.matomo.cloud`.
    * **Screenshot:**
        ![Matomo Cloud Dashboard](https://github.com/user-attachments/assets/6f6a31de-beb0-4081-b885-15e725f3da8b)
        * The screenshot shows the main Matomo dashboard after successful login, displaying the initial overview of website activity.
2.  **Found Site ID and Matomo URL:**
    * After logging in, I knew I needed to find the Site ID and Matomo URL. So, I clicked on "Manage Websites" in the left-hand menu.
    * I then located my website (`http://jmcoded.site`) in the list.
    * There, I found the Site ID (1) and the Matomo URL (`https://jmcoded.matomo.cloud`).
    * **Screenshot:**
        ![Manage Websites Page](https://github.com/user-attachments/assets/857b0419-cf1f-40ce-89a3-f8f3532c6c8a)
        * This screenshot shows the "Manage Websites" page where I found the Site ID and Matomo URL for my website.
3.  **Installed the Matomo Analytics WordPress Plugin:**
    * I then logged into my WordPress dashboard. I needed to add the plugin, so I navigated to 'Plugins' -> 'Add New'.
    * I searched for 'Matomo Analytics - Ethical Stats. Powerful Insights' and clicked 'Install Now' and then 'Activate'.
    * **Screenshot:**
        ![Installed Plugins Page](https://github.com/user-attachments/assets/ebd083ac-b871-40aa-ae97-3407f39eb575)
        * The screenshot shows the 'Installed Plugins' page with the Matomo Analytics plugin successfully activated, as indicated by the "Deactivate" button.
4.  **Configured the Plugin:**
    * After activating the plugin, I navigated to the 'Matomo Analytics' -> 'Settings' page.
    * Since I am using Matomo cloud, I changed the tracking mode to 'Manual'.
    * I then constructed the tracking code using the Site ID and Matomo URL, and pasted it into the provided text area.
    * **Screenshot:**
        ![Matomo Plugin Settings](https://github.com/user-attachments/assets/70d2235f-0b12-4db6-9eca-f3f8f81bbcd9)
        * The screenshot shows the plugin's settings page with the manually pasted tracking code.
5.  **Verified the Installation:**
    * To ensure the tracking was working, I opened a new browser tab and visited my website, `http://jmcoded.site`.
    * Immediately after, I went back to my Matomo dashboard and opened the 'Real-time' report.
    * I was pleased to see my visit being tracked in real-time, confirming that the installation was successful.
    * **Screenshot:**
        ![Matomo Real-time Report](https://github.com/user-attachments/assets/ac83c6f2-736b-4287-b949-7187a02b2e21)
        * The screenshot displays the 'Real-time' report with my visit recorded.

## Benefits of Matomo Analytics

* **Privacy-Focused:** Matomo prioritizes user privacy and data ownership.
* **Detailed Insights:** Provides comprehensive website traffic data and user behavior analysis.
* **Customizable Reports:** Allows for creating custom reports tailored to specific needs.
* **Real-time Tracking:** Offers real-time insights into website activity.
* **Open Source:** Provides transparency and community support.
* **GDPR Compliance:** Helps with GDPR compliance by giving control over data.
* **Data Ownership:** You control your data, not a third party.


## Conclusion
Matomo analytics is now successfully implemented on `http://jmcoded.site`. This will provide valuable insights into website traffic and user behavior, enabling data-driven decisions for website optimization.

## Additional Details

* Date and Time of Setup: February 24, 2024, 1:00 AM WAT
* Browser Used: Chrome
* Operating System: Windows 10
