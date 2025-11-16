# cf_ai_phone

This is an event finder and reminder scheduler built on Cloudflare Workers AI.

It uses Llama 3.3 on Workers AI and Durable Objects to persist the chat state. Try opening the url from different browsers; the chat messages are persisted in Durable Object memory. 

This project is based on the example from https://github.com/cloudflare/agents-starter/.

To run the project locally:

```sh
cd autumn-shape-697e
npm start
```
Navigate to http://localhost:5173/