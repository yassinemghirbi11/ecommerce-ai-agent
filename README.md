# 🤖 n8n AI Product Assistant

An intelligent **AI-powered customer assistant** built with n8n that can understand **text messages and product images**, then automatically respond with relevant product information.

---

## 🚀 Features

* 🧠 AI-powered responses (LLM integration)
* 🖼️ Image recognition (clients send product photos)
* 💬 Text understanding (natural language queries)
* 🛍️ Product information retrieval
* ⚡ Automated replies (Messenger / WhatsApp / API)
* 🔄 Fully automated workflow using n8n

---

## 🧩 How It Works

1. The customer sends:

   * A product image 📸 or
   * A text message 💬

2. The system processes the input:

   * Analyzes the image (Image Recognition)
   * Understands the text (AI / NLP)

3. Product search:

   * Database / Google Sheets / API

4. Response:

   * Product name
   * Price
   * Description
   * Availability

---

## 🏗️ Workflow Architecture

Webhook / Trigger
⬇️
AI Agent (Text + Image Understanding)
⬇️
Product Lookup (Database / API)
⬇️
Response Generator
⬇️
Send Message (Facebook / WhatsApp)

---

## 🛠️ Technologies Used

* **n8n** – Workflow automation
* **OpenAI / LLM APIs** – AI responses
* **Image Recognition API** (e.g. Vision AI)
* **HTTP Requests** – External integrations
* **Webhook** – Receive client messages

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/n8n-ai-product-assistant.git
cd n8n-ai-product-assistant
```

### 2. Import workflow into n8n

* Open n8n
* Click **Import Workflow**
* Upload the `.json` file

### 3. Configure environment variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_key_here
VISION_API_KEY=your_key_here
FB_PAGE_TOKEN=your_token_here
```

---

## 🔐 Security

⚠️ Never expose:

* API keys
* Tokens
* Credentials

Use environment variables instead.

---

## 📸 Use Case Example

User: *sends a photo of shoes* 👟
→ AI detects product
→ Searches database
→ Replies:

> "This is Nike Air Max 270, price: $120, available in stock."

---

## 🎯 Use Cases

* E-commerce automation
* Facebook Messenger bots
* WhatsApp business automation
* Customer support AI
* Product recommendation systems

---

## 📌 Future Improvements

* 🔍 Better image recognition accuracy
* 🌍 Multi-language support
* 🧾 Order creation automation
* 💳 Payment integration

---

## 👨‍💻 Author

Built by **Yassine** 🚀

---

## ⭐ Support

If you like this project:

* ⭐ Star the repo
* 🍴 Fork it
* 🧠 Improve it

---
