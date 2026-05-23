# fb-ai-chatbot

Facebook Messenger AI chatbot for **Wetopian Market BD**, powered by Claude (Anthropic). Handles customer service inquiries for an e-commerce store selling women's sharees, home decor, eco products, and electronics.

## Stack

- Node.js / Express
- Facebook Messenger Webhook (Graph API v19)
- Anthropic Claude (`claude-haiku-4-5`)

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Set environment variables:
   ```
   ANTHROPIC_API_KEY=your_key
   FB_PAGE_TOKEN=your_page_token
   FB_VERIFY_TOKEN=your_verify_token
   PORT=3000
   ```

3. Start the server:
   ```bash
   npm start
   ```

## Webhook

- `GET /webhook` — Facebook verification
- `POST /webhook` — Incoming messages
- `GET /` — Health check
