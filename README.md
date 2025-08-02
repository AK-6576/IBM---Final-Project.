# IBM---Final-Project.
Capstone project for Edunet - IBM Internship.

Topic - Digital Financial Literacy AI Agent
An AI-powered assistant designed to help users understand and navigate digital finance in a safe and secure manner. Built using IBM Watsonx.ai and Retrieval-Augmented Generation (RAG).
Provides multilingual support and trustworthy guidance on UPI, interest rates, stock market, personal finance, investing , loan safety, fraud prevention, online scams and more.

Problem Statement - Many individuals, especially from rural or digitally underserved areas, lack financial literacy. They struggle with understanding UPI, online scams, interest rates, or personal budgeting. This can lead to fraud, poor money management, or digital exclusion.

Solution - An AI agent trained using IBM Watsonx.ai that delivers reliable, document-based answers about digital finance. With multilingual support and document retrieval (RAG), it ensures users receive grounded, easy-to-understand financial guidance.

Technologies Used:
IBM Watsonx.ai Studio
IBM Granite Foundation Model (LLM)
Vector Index for Retrieval-Augmented Generation
PDF documents from RBI/NPCI & other related sourses
NLP (Natural Language Processing)
IBM Cloud Object Storage

IBM Cloud Services Used:
Watsonx.ai Studio
IBM Granite Model
Watsonx Vector Index
IBM Cloud Lite Account
IBM Cloud IAM
IBM Cloud Object Storage

Users:
General public seeking financial clarity
Rural and semi-urban citizens
Students and young professionals
First-time UPI and digital banking users
NGOs and government outreach programs
Customer service centers
Self-Help Groups / Women’s Collectives
Educators / Institutions

Factors:
Uses RAG to fetch answers from real RBI/NPCI or uploaded PDFs
Built entirely on IBM Cloud using Watsonx tools
Handles unrelated questions with polite redirection
Future-ready with multilingual support
Educates users on scams, interest rates, budgeting, stock market, UPI, and more
Provides safe and personalized financial guidance

Features & Components:
Document-based Q&A via Vector Index
Powered by IBM Granite LLM for natural language understanding
Built-in NLP support
Responds gracefully to off-topic/irrelated questions
Covers real financial concerns (scams, loans, savings, UPI, etc.)

Working:
User inputs a query (e.g., “How to avoid UPI fraud?”)
IBM Granite LLM processes the language
Vector Index retrieves trusted content from uploaded financial PDFs
Agent responds with a grounded, natural-language answer

Execution:
Log in to IBM Cloud Lite: https://cloud.ibm.com
Launch Watsonx.ai Studio
Create a new AI Agent
Upload financial PDFs to a Vector Index
Choose Tools for web search (Google,Wikipedia,DuckDuckGo etc..)
Configure agent instructions and topics (restricting AI from answering off-topic questions politely)
Test in the preview panel
Deploy via web snippet, Streamlit, or custom web UI

Scope:
WhatsApp or mobile app integration
Speech-to-text input for voice-driven queries
Automatic monthly report generation
Region-specific financial policy updates
Multilingual expansion with Watson Language Translator
Ease of life.
