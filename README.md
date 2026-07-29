# StyleDrop AI - Customer Support Automation 🚀

An automated, no-code AI customer support pipeline built with **Make.com**, **Google Gemini AI**, and **Gmail**.

---

## 📌 Project Overview

StyleDrop AI replaces manual customer support handling with an automated processing pipeline. When a customer submits an inquiry through Google Forms, the system processes the feedback in real-time, generates an empathetic, context-aware AI response using Google Gemini AI, and routes the draft along with its category to a Gmail inbox for review—reducing response times from hours to under 15 minutes.

### Key Highlights
* **Zero Manual Effort:** Automatically reads incoming inquiries and dispatches polished replies.
* **Context-Aware AI:** Leverages Google Gemini AI to generate polite, brand-aligned responses tailored to customer context.
* **Rapid Response:** Cuts customer support delivery time down to minutes.

---

## ⚙️ How It Works

`[ Google Form Inquiry ]` ➔ `[ Google Sheet Log ]` ➔ `[ Make.com Trigger ]` ➔ `[ Google Gemini AI ]` ➔ `[ Gmail Inbox Review ]`

1. **Intake:** A customer submits a complaint or inquiry via Google Forms.
2. **Logging:** The form submission is automatically logged as a new row in Google Sheets.
3. **Trigger:** Make.com detects the new row instantly.
4. **AI Processing:** Make.com sends the complaint context to Google Gemini AI to categorize the complaint (**Delivery**, **Refund**, or **Product Quality**) and draft an accurate, polite reply.
5. **Dispatch:** Make.com sends both the categorization tag and the draft reply directly to a Gmail inbox for human review.

---

## 🖼️ Workflow Architecture

![StyleDrop Workflow Screenshot](workflow-screenshot.png)
---

## 🛠️ Tools & Technologies

* **Automation Platform:** [Make.com](https://make.com)
* **AI Model:** Google Gemini AI
* **Data Logging:** Google Sheets
* **Email Service:** Gmail

---

## 👤 Author & Credits

* **Project Lead:** Rahmat Inuwa
* **Location:** Nigeria / Minna
* **Program:** Deep_Tech / WESOnline Mentorship Program
* **Contact:** rahmatameerah@gmail.com
