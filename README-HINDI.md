# WhatsApp हिंदी Chatbot (Render Deploy)

## 🧾 ज़रूरी जानकारी:
यह Bot WhatsApp और OpenAI को जोड़ता है ताकि यूज़र के सवालों के जवाब हिंदी में दिए जा सकें।

## ⚙️ कैसे शुरू करें:

### 1. `.env` फाइल बनाएँ
`.env.example` को कॉपी करके `.env` नाम से सेव करें और अपनी API Keys डालें।

### 2. Render पर Deploy करें:
- New Web Service → GitHub या ज़िप अपलोड करें
- Build Command: `npm install`
- Start Command: `node server.js`
- Environment Variables डालें जैसे `.env` में

### 3. Webhook URL डालें:
Meta Developer Console में Webhook URL और VERIFY_TOKEN डालें।

### 4. WhatsApp से टेस्ट करें
टेस्ट नंबर से मैसेज भेजें और Bot को हिंदी में उत्तर देते देखें।

---

**बॉट को हिंदी में जवाब देने के लिए तैयार है!**
