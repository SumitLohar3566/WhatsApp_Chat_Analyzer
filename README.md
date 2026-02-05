# WhatsApp Chat Analyze

An interactive Streamlit-based application that provides deep analysis of WhatsApp chat data, including message statistics, sentiment, media insights, emoji analysis, busiest users, timelines, and more.

-  Project Preview
<img width="1913" height="802" alt="Screenshot 2025-11-30 102140" src="https://github.com/user-attachments/assets/2ce66a47-3b51-4abd-8235-d7a44c6814c2" />
<img width="1905" height="809" alt="Screenshot 2025-11-30 102156" src="https://github.com/user-attachments/assets/75919454-12da-4198-89eb-ecc3172b0baa" />

- Features

✔ 1. Basic Chat Statistics

Total Messages

Total Words

Media Shared

Links Shared

Deleted Messages

✔ 2. User-based Insights

Most Active Users

Percentage Participation Chart

User-specific Message Stats

✔ 3. Emoji & Text Analysis

Emoji count table

Emoji distribution pie chart

Most used words

Word Frequency Bar Graph

✔ 4. Chat Timelines

Daily Timeline

Monthly Timeline

Weekly Activity

Monthly Activity Map

Weekly Heatmap

✔ 5. Chat Type Detection

Automatically detects whether the uploaded chat is:

Android (2022 format)

iPhone format

✔ 6. Beautiful Visualizations

Matplotlib

Seaborn heatmaps

Streamlit UI

Dynamic charts

- Tech Stack
Technology	Purpose
Python	Core logic
Pandas	Data processing
Matplotlib	Charts
Seaborn	Heatmaps
Emoji / urlextract	NLP & parsing
Streamlit	UI/Frontend
📂 Folder Structure
WhatsApp-Chat-Analyzer/
│── app.py
│── requirements.txt
│── README.md

- Installation & Setup
1. Clone the Repository
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer

2. Install Dependencies
pip install -r requirements.txt

3. Run the Application
streamlit run app.py

-- How to Export WhatsApp Chat
Android (Without Media):
Open Chat → More → Export Chat → Without Media

iPhone:
Open Chat → Contact Info → Export Chat → Without Media

Upload the exported .txt file into the app.

# Screenshots
<img width="1293" height="302" alt="Screenshot 2025-11-30 103251" src="https://github.com/user-attachments/assets/36905177-320d-46a4-83fa-b26ac4c403b3" />
<img width="1377" height="692" alt="Screenshot 2025-11-30 103330" src="https://github.com/user-attachments/assets/e82a4be1-c886-4235-870c-7c6c2c83f3ef" />
<img width="1404" height="734" alt="Screenshot 2025-11-30 103343" src="https://github.com/user-attachments/assets/ddc3b204-bd4c-4e54-8050-f73aaeb744b6" />
<img width="1454" height="656" alt="Screenshot 2025-11-30 103401" src="https://github.com/user-attachments/assets/d73a14c7-142b-4c13-9ab3-adfeb47e0b2c" />
<img width="1454" height="695" alt="Screenshot 2025-11-30 103413" src="https://github.com/user-attachments/assets/668c45f1-04d1-4283-aec8-7b1c346313da" />

# Future Enhancements

- Sentiment Analysis (Positive / Negative / Neutral)

- Toxic Message Detection

- WhatsApp Group Network Graph

- Auto Emoji Word Cloud

- Topic Modeling (LDA)

- Dark Theme UI

- Contact Developer: Sumit Lohar - Email:sumitlohar063@gmail.com - GitHub: https://github.com/SumitLohar3566 - LinkedIn:(https://www.linkedin.com/in/sumit-lohar-498341317/)
