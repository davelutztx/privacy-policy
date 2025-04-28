# Privacy Policy
**Effective Date:** April 28, 2025  
**App Name:** Lutzapp LinkedIn Assistant  
**Hosted at:** https://davelutztx.github.io/privacy-policy/

---

## 1. Introduction
Welcome to **Lutzapp LinkedIn Assistant** ("we", "us", or "our"). This privacy policy explains how we collect, use, disclose, and protect information when you use our application and services. We are committed to safeguarding your privacy and ensuring transparency about how your data is handled.

## 2. Information We Collect
We only collect and process the following data in order to provide the core functionality:

- **LinkedIn Data**:  
  - Post content, timestamp, and metadata fetched via your LinkedIn account’s authorized API access.  
  - Basic profile information (name, profile URL) to identify the correct user feed.

We do **not** collect any additional personal data, such as your private messages, credentials, or other unrelated account information.

## 3. How We Use Your Information
We use the collected information strictly to:

1. **Authenticate & Fetch:** Connect to LinkedIn’s API to retrieve your CEO’s latest posts.  
2. **Generate Commentary:** Send the post text to OpenAI to create concise, engaging commentary.  
3. **Publish/Repost:** Post the combined original content and AI commentary back to your designated channels (LinkedIn, Slack, etc.).

## 4. Data Sharing & Disclosure
We do not sell or rent your personal data to third parties. We may share your data only in the following ways:

- **LinkedIn API**: To fetch posts and publish content, we share only the minimal required fields under your OAuth consent.  
- **OpenAI API**: To generate commentary, we transmit only the text of the CEO’s posts.

All API interactions occur over encrypted HTTPS connections. No other third parties have access to your data.

## 5. Data Retention
- **Workflow Metadata** (`lastPostId`) is retained indefinitely in your n8n instance until you manually clear or reset the workflow credentials.  
- **AI-generated content** is stored only long enough to complete the repost and is not archived long-term unless your n8n configuration explicitly writes logs or database records.

## 6. Security
We implement reasonable technical and organizational measures to protect your data:

- All credentials (LinkedIn, OpenAI, scraping APIs) are stored securely in n8n’s built-in credentials manager.  
- OAuth tokens are automatically refreshed and never exposed in logs.  
- Access to your n8n instance should be secured behind HTTPS and strong authentication (e.g., VPN, secure reverse proxy).

## 7. Third-Party Services
Our workflow relies on the following external services:

- **LinkedIn API** (OAuth2) for fetching and posting content.  

Please review their respective privacy policies for details on how they handle data.

## 8. Your Rights
Since this is a personal/internal app, you control:

- **Access & Deletion:** You may clear your n8n credentials or remove the workflow at any time.  
- **Revoking Permissions:** You can revoke the app’s access in your LinkedIn account settings under **Data Privacy → Third-party applications**.

## 9. Changes to This Privacy Policy
We may update this policy from time to time. The **Effective Date** above will indicate when the policy was last revised. Major changes will be highlighted in this document.

## 10. Contact Information
For questions or concerns about this privacy policy, please file an issue or discussion in the GitHub repo:  
**https://github.com/davelutztx/privacy-policy**

