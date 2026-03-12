# MLU_Hackathon
# 🛡️ Digital Arrest Shield  
### Real-Time Detection and Prevention of Digital Arrest Scams

Digital Arrest Shield is an **AI-powered cybersecurity system** designed to detect and warn users about **Digital Arrest scams** in real time. The system analyzes suspicious messages, call transcripts, or chat content using **Natural Language Processing (NLP)** and **machine learning** to identify scam patterns and alert users before they become victims.

---

# 📌 Problem Statement

In recent years, cybercriminals have been exploiting individuals through a rapidly growing fraud known as **Digital Arrest Scam**. In this scam, attackers impersonate officials from law enforcement agencies such as the **Central Bureau of Investigation (CBI)**, **Enforcement Directorate (ED)**, **Narcotics Control Bureau (NCB)**, police departments, or the **Reserve Bank of India (RBI)**.

Victims are contacted through phone calls, video calls, or messaging platforms and falsely accused of serious crimes such as:

- Money laundering  
- Drug trafficking  
- Cyber fraud  
- Terror financing  
- Suspicious financial transactions  

Fraudsters claim the victim is under a **“Digital Arrest Warrant”** and must remain under constant digital surveillance to avoid immediate arrest.

To manipulate victims, scammers:

- Display fake legal documents (FIRs, arrest warrants, court orders)
- Threaten jail time or freezing of bank accounts
- Isolate victims from friends and family
- Demand immediate money transfers to “resolve the case”

Many victims lose **large sums of money** before realizing the fraud.

Currently, there is **no real-time technological system** that can detect and warn users about these scams while the interaction is happening.

---

# 🎯 Objective

The objective of this project is to build **Digital Arrest Shield**, a system that:

- Detects **digital arrest scam patterns** in real time
- Analyzes **messages, chat content, or call transcripts**
- Identifies suspicious **keywords and linguistic patterns**
- Provides **instant alerts to users**
- Recommends safe actions such as **disconnecting the call or reporting the incident**

The goal is to **prevent financial loss and protect citizens from psychological manipulation** used in these scams.

---

# ⚙️ Features

✔ Real-time scam message detection  
✔ NLP-based text analysis  
✔ Scam keyword detection  
✔ Threat and urgency pattern detection  
✔ Instant risk alert system  
✔ Evidence logging for reporting cybercrime  

---

# 🧠 Technologies Used

| Technology | Purpose |
|------------|--------|
| Python | Core programming language |
| Flask | Backend web framework |
| Scikit-Learn | Machine learning model |
| NLTK | Natural language processing |
| HTML / CSS / JavaScript | Frontend interface |
| Git & GitHub | Version control and collaboration |

---

# 🏗️ System Architecture
User Input (Message / Call Transcript)
|
v
Text Preprocessing
|
v
NLP Feature Extraction
|
v
Machine Learning Model
|
v
Scam Detection Engine
|
v
Risk Alert System


---

# 📂 Project Structure


digital-arrest-shield
│
├── dataset
│ └── scam_messages.csv
│
├── model
│ └── train_model.py
│
├── app
│ ├── app.py
│ └── templates
│ └── index.html
│
├── utils
│ └── preprocessing.py
│
├── requirements.txt
└── README.md
