# Google Dialogflow (GDF) cheat sheet
Course: HEIG-VD CLD 2024/25  
Authors: Alex Berberat, Aude Laydu, Maxime Lestiboudois, Nathan Parisod  
Date:  09.06.2025

## Why Google Dialogflow ?
GDF would be particularly useful for a Swiss SME that wants to automate customer service interactions, such as answering frequently asked questions, making apointments, registering orders,...  
It allows the companies to have a 24/7 support in multiple language and reduce the cost of hiring real people.  

GDF acts as an middleman between the customers and the companies.  
It reveives natural language input such as text or voice, processes the intent and retruns the answer in the form of text or voice or it can also trigger an action.  


## Benefits and limitations
### Benegits
- Easy to set up.
- Easy to intgrate.
- Can understand multiple languages.

### Limitations
- Vendor lock-in.
- Less control than open-source alternatives.
- Data privacy.


## Cost structure
### Measured components are : 
- Nbr of requests (text or voice)
- The version of GDF chosen. (ES or CX)
- Storage.
- Additional charges for non google integrations.  

For a small Swiss SME with ~4000 requests per month we would have.
- First 1000 requests for free.
- Remaining 3000 costs: ~0.002/requests = $6/month
- Optional Google Cloud services: ~$0-10/month


## How to get started
### Prerequisites
- Google Cloud Platform account.
- Basic knowledge of APIs and intent-based chatbot.

### Steps to prepare
1. Create a Google Cloud project.
2. Enable Dialogflow API.
3. Create a Dialogflow agent.
4. Define intents and entities.
5. Set up integrations (web, messaging). 

### Hello-world example
1. Create an intent with training phrases like "Hi", "Hello".
2. Set a response to smth like "Hello! How can I help you?".
3. Test in GDF simulator.


## Common commands/operations/configurations/usage patterns
- Creating intents and entities to handle user inputs.
- Set-up fulfillment to connect to backend logic.
- Intergating with external platforms (website, Messaging app, ...)
- Using contexts to handle long converstations.
- Give training phrases of what users might say.
- Create different variants for a response to make the conversation feel more natural.
