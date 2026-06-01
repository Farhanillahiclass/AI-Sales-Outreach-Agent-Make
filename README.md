# 🤖 Autonomous AI Sales Outreach & Lead Qualification Agent

An advanced, production-ready AI Automation workflow built on **Make.com** using native **Make AI Agents**. This system acts as a 24/7 Virtual Sales Representative that autonomously qualifies inbound leads, performs deep company research, and drafts hyper-personalized responses.

---

## 🚀 Features

* 📧 **Automated Lead Ingestion:** Continuously watches your Gmail inbox for new unread messages.
* 🔍 **Deep Company Research:** Automatically extracts the sender's domain and uses AI Web Search to gather company Size, industry, and potential pain points.
* 📊 **Lead Scoring & Qualification:** Categorizes leads into **HIGH, MEDIUM, or LOW** priority based on custom objective frameworks.
* 📅 **Smart Calendar Sync:** Checks your Google Calendar for free slots and automatically proposes 2-3 specific meeting times if the lead is highly qualified.
* ✍️ **Ghostwritten Drafts:** Creates beautifully formatted HTML email replies directly inside your Gmail Drafts folder.
* 💬 **Team Collaboration:** Sends instant notifications to your Slack workspace when a high-quality lead is processed.

---

## 👤 Author
Developed with ❤️ by **Farhan**.

## 🛠️ Tech Stack & Tools Used

* **Platform:** [Make.com](https://www.make.com/)
* **AI Engine:** Make AI Agent (GPT-4o / GPT-4-turbo)
* **Trigger:** Gmail (Watch Emails)
* **Research:** Make AI Web Search
* **Calendar:** Google Calendar (Get Free/Busy Information)
* **Communication:** Slack (Send a Message) & Gmail (Create a Draft)

---

## 📦 How to Install and Use

### Prerequisites
1. A **Make.com** account.
2. API Access / Connections for Gmail, Google Calendar, and Slack.

### Setup Steps
1. Download the `sales_outreach_agent_blueprint.json` file from this repository.
2. Go to your **Make.com** dashboard and click **Create a new scenario**.
3. Click the three dots `...` (More) menu at the bottom and select **Import Blueprint**. Upload the downloaded `.json` file.
4. Update the connections for each module:
    * **Gmail Module:** Connect your business email account.
    * **Make AI Agent Module:** Select your active AI Provider/Model and map the input variables (`sender_email`, `subject`, `body`, etc.).
    * **Google Calendar & Slack Modules:** Link your respective workspace accounts.
5. Save the scenario and switch the scheduling button to **ON**.

---

## 📝 Customization

You can open the **Make AI Agent** module to modify the `System Prompt` (Instructions). Update the context section to reflect your own company description, target audience, pricing plans, or specific services offered.

---

## 📄 License
This project is open-source and available under the MIT License.
