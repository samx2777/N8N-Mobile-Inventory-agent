📊 n8n Automation – AI Chatbot + Airtable Inventory Manager

🚀 Overview

This project contains an n8n workflow that integrates a chatbot powered by Google Gemini 2.5 API with Airtable to manage and update stock/inventory records efficiently.

With this automation, users can simply send a message in the chatbot, and based on the query, the system will:

🔍 Search for stock items in Airtable

✏️ Update rows and columns with new values

📈 Keep inventory records accurate and up-to-date in real time

🛠️ Features

🤖 AI-Powered Input – Uses Gemini 2.5 API to understand natural language commands.

📊 Inventory Search – Quickly looks up products/stocks in Airtable.

✍️ Dynamic Updates – Modifies Airtable rows/columns based on chatbot instructions.

⏱️ Time Saver – No need to manually navigate Airtable – manage everything via chat.

⚡ Scalable – Can be extended to multiple databases or CRMs.

🔗 Tech Stack

n8n
 – Workflow automation

Google Gemini 2.5 API
 – Natural language understanding

Airtable
 – Inventory & stock management

Node.js
 – Runtime for n8n

📂 Workflow Logic

Trigger → User sends a message to the chatbot

Gemini 2.5 API → Analyzes message and extracts intent (search/update/add)

Airtable →

If search → Returns matching stock details

If update → Updates specified row/column

If add → Inserts a new stock item

Response → Chatbot replies with confirmation/result

⚙️ Setup Instructions

Clone this repo:

git clone https://github.com/samx2777/N8N-Mobile-Inventory-agent
cd n8n-automation


Import the workflow JSON into n8n (Import → From File)

Configure credentials:

Gemini API Key

Airtable API Key & Base ID

Activate the workflow

Test by sending a chatbot message like:

"Update stock of Product X to 50"

"Search stock for Laptop model Y"

💡 Use Case Example

E-commerce business: Quickly update product inventory without logging into Airtable.

Warehouse team: Search stock levels via chat.

Retail managers: Keep inventory updated in real-time through a chatbot.

📌 Benefits

Saves manual work ⏱️

Reduces human errors ✅

Makes inventory management as easy as chatting 💬
