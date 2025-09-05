✈️ SmartTrip Planner – AI-Powered Day Itinerary Generator
🌟 Introduction

SmartTrip Planner is an AI-driven chatbot that helps travelers design personalized one-day itineraries.
By combining Multi-Agent workflows, LangGraph, and Groq’s LLaMA 3.3-70B, the app tailors schedules to user preferences like sightseeing, shopping, temples, or beaches.

This project showcases how AI Agents + RAG + LLMs can automate travel planning while keeping the user in control.

💡 Highlights

🏙️ City-aware plans → Suggests activities relevant to the chosen city

🗺️ Interest-driven schedules → Temples, malls, markets, beaches, etc.

⏰ Time-based slots → Clear morning, afternoon, and evening plans

🤖 Agent workflow → Modular input, processing, and generation steps

🎨 Interactive web app → Built with Gradio for smooth user experience

⚡ Powered by Groq → Blazing-fast itinerary generation with LLaMA 3.3-70B

🛠️ Technology Stack

Python 3.10+

LangChain & LangGraph → Agent workflows & state handling

Groq API → High-speed text generation

Gradio → User interface

🔑 Core Workflow

User Input → City & Interests

Planner Agent → Collects and validates input

Itinerary Agent → Calls LLaMA 3.3-70B to generate a plan

Output → A structured, bulleted day itinerary

Workflow Graph:

Start → Get City → Get Interests → Generate Itinerary → End

🖼️ Example

Input

City: Chennai

Interests: Vadapalani Temple, T Nagar, Mall, Marina Beach

Output

8:00 AM - Visit Vadapalani Temple  
10:00 AM - Shopping at T. Nagar  
12:30 PM - Lunch & mall visit (Phoenix MarketCity / Express Avenue)  
3:30 PM - Relax at Marina Beach  
6:00 PM - Dinner at a local restaurant  

📂 Repository Layout
├── app.py             # Main code (CLI + Gradio UI)
├── requirements.txt   # Dependencies
├── README.md          # Documentation

🚀 Quick Start

1️⃣ Clone repo & install dependencies

git clone https://github.com/your-username/smarttrip-planner.git
cd smarttrip-planner
pip install -r requirements.txt


2️⃣ Add your Groq API key inside app.py

llm = ChatGroq(
    temperature=0,
    groq_api_key="YOUR_API_KEY",
    model_name="llama-3.3-70b-versatile"
)


3️⃣ Launch the app

python app.py


Access the Gradio UI from the local URL provided.

🔮 Roadmap

🌐 Multi-day itinerary planning

🏨 Hotel & restaurant recommendations

📌 Google Maps integration for route optimization

📤 Export to PDF or mobile app

🤝 Contribution

We welcome contributions!

Fork the repo

Create a feature branch

Submit a pull request 🚀

📜 License

Released under the MIT License.

👉 This version is different in tone & structure:

New title: SmartTrip Planner – AI-Powered Day Itinerary Generator

Different section names (Introduction, Highlights, Roadmap)

More concise storytelling style
