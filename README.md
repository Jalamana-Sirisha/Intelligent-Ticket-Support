# 🧠 AI Ticket Resolution System 3.0  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)  
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)  
![Repository Size](https://img.shields.io/github/repo-size/Jalamana-Sirisha/Intelligent-Ticket-Support)  
![Last Commit](https://img.shields.io/github/last-commit/Jalamana-Sirisha/Intelligent-Ticket-Support)  
![Dashboard](assets/dashboard.png)


---

## 📖 Introduction  

The **AI Ticket Resolution System** is an advanced automation platform powered by **Natural Language Processing (NLP)** and **Transformer-based deep learning models**.  
It intelligently classifies, analyzes, and resolves customer support tickets with minimal human intervention.  

By leveraging intelligent automation and machine learning insights, the system helps organizations:  
- **Reduce manual triage time**  
- **Accelerate response speed**  
- **Ensure consistent, high-quality customer support**  

The project also includes:  
- An interactive **Streamlit dashboard** for real-time analytics and visualization  
- Seamless **Slack integration** for instant notifications and team collaboration  
- A **modular design** for easy scalability and customization  

This solution represents a major step toward **AI-driven service operations**, empowering teams to make faster and smarter decisions.



---

## ✨ Key Features  

- 🚀 Automated classification of customer support tickets  
- 💡 Intelligent resolution suggestions using Transformer models  
- 📊 Visual analytics dashboard for performance tracking  
- ⚡ Real-time updates and smooth UI rendering  
- 🤖 Slack integration for instant backend communication  
- 🌐 Multilingual support (10+ languages)  
- 🧩 Knowledge base embedding and content gap analysis  

---

## ⚙️ Installation  

1. **Clone the Repository**

       git clone https://github.com/Jalamana-Sirisha/Smart-Ticket-Classifier.git
       cd Smart-Ticket-Classifier
   
2. **Create and Activate a Virtual Environment**

       python3 -m venv venv
       source venv/bin/activate     # For Linux/Mac
       venv\Scripts\activate        # For Windows

3. **Install Dependencies**
    
       pip install -r requirements.txt
    
4. **Prepare Dataset**
Use the provided **cleaned_ticket_data.csv**,
Or replace it with your own dataset and update file paths in the scripts.

5. **(Optional) Train the Model**

       python trainer.py

7. **Run the Application By running**

       python app.py

9. **Open the other terminal and Run to open the GUI Dashboard**

       streamlit run gui_dashboard.py

**Uplaod the ticket and Enjoy the saved time!**

---
For Slack Integration 
---
1. Paste the slack **channel ID** in app.py SLACK_CHANNEL_ID = "C0XXXXXXX"
   
2. Open terminal (in virtual env) paste your slack token (export SLACK_BOT_TOKEN=YOUR TOKEN)

3. Run app.py & gui_dashboard.py

---
Example Workflow
---

1. A new support ticket is received.

2. data_connector.py processes and cleans it.

3. categorizer.py uses the trained model to predict the category.

4. The result appears in the GUI or CLI With **Real Time Solution Recommendation**.

5. Analytics and reports are generated automatically.

6. Slack messaged can be seen from notification pannel. 

---
Tech Stack
---

**Language**: Python

**Libraries**: Transformers, Pandas, NumPy, Matplotlib etc.

**Frameworks**: PyTorch

**Visualization**: Streamlit

**Data**: CSV-based datasets and embeddings

---
Why Use This Project
---

**Efficiency** — Automates ticket routing

**Scalability** — Handles large datasets easily

**Accuracy** — Uses Transformer-based contextual understanding

**Insights** — Detects knowledge gaps and tracks model performance

---
## 📞 Contact & Support  

For any **questions**, **bug reports**, or **feature suggestions**, please open an issue on this GitHub repository.  
We truly appreciate your feedback and contributions that help make this project even better.  

👤 **Author:** *Jalamana Sirisha (Group - 4)*  
📧 **Email:** [sirishajalamana@gmail.com](mailto:sirishajalamana@gmail.com)  
🌐 **GitHub:** [https://github.com/Jalamana-Sirisha](https://github.com/Jalamana-Sirisha)  
🔗 **LinkedIn:** [https://www.linkedin.com/in/jalamana-sirisha-46307131a](https://www.linkedin.com/in/jalamana-sirisha-46307131a)  

💬 *Feel free to connect for collaboration, suggestions, or project discussions.*
