# INYA-AI-SUBMISSION-RURAL-SURVEY-BOT

# 🌾 Rural Buddy: Rural Survey & FAQ Bot  

## 📌 Overview  
**Rural Buddy** is an **AI-powered conversational assistant** designed for rural engagement.  
It works across **Voice, Chat, and SMS** in **English, Hindi, and regional languages**.  

The bot has two main objectives:  
1. **Conduct respectful surveys** about local representatives (MLA/MP) and public services.  
2. **Provide FAQs** on government schemes, health facilities, commodity prices, and pincode lookups.  

✅ Ensures **political neutrality**  
✅ Protects **user privacy & consent**  
✅ Supports **multilingual simple phrasing with light code-switching**  

---

## 🎯 Features  
- 🗳️ **Survey Flow** – Collect MLA/MP names, 1–5 satisfaction scores, opinions, sentiment tagging.  
- 📚 **FAQ Flow** – Answer queries on schemes, health facilities, pincodes, commodity prices.  
- 🌍 **Multilingual** – English, Hindi & one regional language.  
- 🔄 **Mock Data Fallback** – JSON datasets when APIs are unavailable.  
- ⚖️ **Neutral & Safe** – No political bias, respectful data handling.  

---

## 🏗️ Architecture  
- **Opening:** Greeting → Language selection → Consent → Survey or FAQ choice.  
- **Survey Branch:** MLA/MP info → Satisfaction score → Opinion text → Timestamp + location + sentiment.  
- **FAQ Branch:** Intent detection → Scheme info, PHC location, prices, pincodes.  
- **Fallback:** Use mock JSON datasets when APIs fail, labeled as approximate.  

---

## 🔗 Prototype Links  
Try the live prototypes here:  

- 🎙️ **[Voice Agent](https://app.inya.ai/demo/94c544fd-4119-4664-94a9-148a11bdfc8e)**  
- 💬 **[Web Agent](https://app.inya.ai/chat-demo/a132a240-b25e-4c45-8b3e-b82bf201ca79)**  

⚠️ *Note: Please fill the pre-call variables before using. It will not affect responses or questions.*  

---

## 📂 Data Sources & APIs  
- 🏥 [National Health Facility Registry](https://facility.abdm.gov.in) – PHC/CHC/Hospital search  
- 🏥 [All India Health Centres – OGD](https://data.gov.in/catalog/all-india-health-centres-directory) – Backup health data  
- 🌾 [Agmarknet](https://agmarknet.gov.in) – Wholesale mandi prices  
- 🛒 [Consumer Affairs Price Monitoring](https://fcainfoweb.nic.in) – Retail prices  
- 📮 [Postal API](https://api.postalpincode.in) – Pincode lookup  
- 👥 [Lok Sabha Members](
