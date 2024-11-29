**KC-CO Cybersecurity Chatbot**<br>
KC-CO's cybersecurity chatbot is designed to assist small businesses with cybersecurity-related inquiries, streamline incident reporting, and promote awareness through educational resources. Built using Dialogflow, it provides an intuitive and efficient way to handle common security concerns.

**Features**<br>
Automated Query Resolution: Answers FAQs on phishing, password security, and malware prevention.
Incident Reporting: Escalates suspicious activities to human experts.
Educational Resources: Offers tips and guides on cybersecurity best practices.
Expandable Framework: Built for future enhancements, including IT support and multilingual capabilities.<br>

**Prerequisites**<br>
Before installing the chatbot, ensure you have the following:

Node.js: Version 16.0 or higher
npm: Package manager for Node.js
Google Cloud Account: Access to Dialogflow
Git: For cloning the repository<br>

**Installation**<br>
1. Clone The Repository<br>
git clone https://github.com/your-username/Umer-developer/UniSQ-FYP.git  
cd kc-co-cybersecurity-chatbot <br>

2. **Install Dependencies**<br>
npm install  
<br>
3. Set up Dialogflow<br>
   Create a Dialogflow Agent<br>
   Go to Dialogflow Console and create a new agent.<br>
    Note down the Project ID.<br>
   Enable Google Cloud APIs<br>
Enable the Dialogflow API and create a service account key file.<br>
Download the key file (JSON format) and place it in the project root directory.<br>
Link the Agent to the Project<br>
Open the Dialogflow console and upload the intents and entities located in the dialogflow/intents and dialogflow/entities folders of this repository.<br>
4.Configure Environment Variables<br>
GOOGLE_APPLICATION_CREDENTIALS=path/to/your/service-account-key.json  
PROJECT_ID=your-dialogflow-project-id  
PORT=3000  

5.Run the Server<br>
Start the chatbot’s server locally:<br>
npm start  <br>
The chatbot will run on http://localhost:3000 <br>
**Configuration** <br>

1.Open the dialogflow/intents folder to edit the default FAQs.<br>
2.Add or modify intents to include new cybersecurity scenarios or queries.<br>
3.After editing, re-upload the intents to Dialogflow through the console.<br>

