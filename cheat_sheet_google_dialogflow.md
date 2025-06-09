# Google DialogFlow Cheat Sheet

**Course:** HEIG-VD CLD 2024/25  
**Authors:** Alex Berberat, Aude Laydu, Maxime Lestiboudois, Nathan Parisod  
**Date:** 09.06.2025

---

## Why Google DialogFlow?

Google DialogFlow is particularly useful for a Swiss SME that wants to automate customer service interactions, such as answering frequently asked questions, making appointments, or registering orders.  
It allows companies to offer 24/7 multilingual support and reduce the cost of hiring human staff.  

Google DialogFlow acts as a middleman between customers and companies.  
It receives natural language input (text or voice), processes the intent, and returns a response (text or voice), or can trigger an action.

---

## Benefits and Limitations

### Benefits

- Easy to set up.  
- Easy to integrate.  
- Supports multiple languages.  

### Limitations

- Vendor lock-in.  
- Less control compared to open-source alternatives.  
- Concerns about data privacy.  

---

## Cost Structure

### Costs depend on

- Number of requests (text or voice)  
- Version of Google DialogFlow (ES or CX)  
- Storage  
- Additional charges for non-Google integrations  

For a small Swiss SME with `~60'000 requests/month`:

- First `1000/day` requests: `free`  
- Remaining `59'000` requests: `~$0.002/request` = `(60'000 - (30 * 1000)) * 0,002` =~ `$60/month`
- Optional but useful Google Cloud services such as hosting fees: `~$0–10/month`
- Estimated total: `~$60-70/month`

---

## How to Get Started

### Prerequisites

- Google Cloud Platform (GCP) account
- Basic knowledge of APIs and intent-based ChatBots  

### Setup Steps

1. Create a Google Cloud project  
2. Enable the DialogFlow API  
3. Create a DialogFlow agent  
4. Define intents and entities  
5. Set up integrations (web, messaging, etc.)  

### Hello World Example

1. Create an intent with training phrases like "Hi", "Hello"  
2. Set a response like "Hello! How can I help you?"  
3. Test it in the Google DialogFlow simulator  

---

## Common Commands / Operations / Usage Patterns

- Create intents and entities to handle user inputs  
- Set up fulfillment to connect to backend logic  
- Integrate with external platforms (website, messaging apps, etc.)  
- Use contexts to handle long conversations  
- Provide training phrases based on user input variations  
- Create multiple response variants for more natural conversations  
