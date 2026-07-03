# AI-Pharmacy-WhatsApp-Assistant
An AI-powered WhatsApp chatbot that instantly checks medicine availability, answers customer queries, and automates medicine reservations using Google Sheets + n8n + Groq.

🎥 Watch the Full Loom Demo:
🔗 [https://www.loom.com/share/f2c88f1426b5400e9bc2db2dab7cfcb2]

🚀 Overview

Pharmacies receive hundreds of repetitive WhatsApp messages every week:

"Do you have Panadol?"
"How much does it cost?"
"Can you reserve this medicine?"
"What are your opening hours?"

Many customers travel long distances only to discover that the required medicine is out of stock.

This AI automation solves that problem by providing instant WhatsApp responses using live inventory data stored in Google Sheets.

Instead of manually replying to every customer, the pharmacy owner simply updates their inventory sheet, and the AI handles the rest.

🎯 Business Problem
Before Automation

❌ Customers travel to the pharmacy only to find medicines unavailable.

❌ Staff repeatedly answer the same questions.

❌ Medicine reservations are tracked manually.

❌ Slow customer service during busy hours.

❌ No 24/7 customer support.

✅ Solution

This project automates the entire customer communication process through WhatsApp.

Customers can:

Check medicine availability
View prices
Ask pharmacy FAQs
Reserve medicines
Receive instant AI-powered replies

The pharmacy only needs to maintain a Google Sheet for inventory, while the AI automatically uses the latest data.

✨ Features
🤖 AI-powered WhatsApp Assistant
💊 Real-time Medicine Availability
📋 Google Sheets Inventory Integration
❓ FAQ Automation
📝 Medicine Reservation System
🧠 Conversation Memory
⚡ Instant Responses
📱 WhatsApp Business Integration
🔄 No-Code Workflow using n8n
🏗️ Tech Stack
n8n
Groq API (LLM)
WhatsApp Cloud API
Google Sheets API
AI Agent
Simple Memory
REST APIs
📂 Workflow Architecture
Customer
      │
      ▼
WhatsApp Business
      │
      ▼
n8n Workflow
      │
      ▼
AI Agent (Groq)
      │
 ┌────┼────────────┐
 │    │            │
 ▼    ▼            ▼
FAQ Inventory   Orders
(Google Sheets)
      │
      ▼
AI Response
      │
      ▼
Customer
📊 Google Sheets Used
📦 Inventory Sheet

Stores:

Medicine Name
Stock
Price
Availability
❓ FAQ Sheet

Stores common questions like:

Store Hours
Delivery
Payment Methods
Contact Information
📝 Orders Sheet

Automatically records:

Customer Name
Phone Number
Medicine
Quantity
Date & Time
📸 Project Demo
Medicine Availability

Customer:

Do you have Panadol?

AI:

✅ Yes! Panadol 500mg is available.

Price: Rs.180

Stock: 120

FAQ

Customer:

What time do you open?

AI:

We are open Monday to Saturday from 9 AM to 9 PM.

Medicine Reservation

Customer:

Reserve 2 boxes of Panadol.

AI:

Your reservation has been successfully recorded.

💼 Business Impact

✅ Reduces repetitive customer support.

✅ Improves customer satisfaction.

✅ Saves staff time.

✅ Prevents unnecessary customer travel.

✅ Enables 24/7 automated assistance.

✅ Uses Google Sheets—no complex software required.


👩‍💻 About Me

Sadia Ali

AI Automation Developer | n8n | LLM Automation | Workflow Automation

GitHub: https://github.com/Sadia0076
LinkedIn: https://www.linkedin.com/in/sadia-ali-ce/
⭐ If you found this project helpful, consider giving it a Star!
