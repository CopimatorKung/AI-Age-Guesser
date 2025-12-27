# 👤 AI Age & Emotion Guesser (Project 4)

แอปพลิเคชันวิเคราะห์ใบหน้าอัจฉริยะที่ใช้พลังของ **Gemini 2.5 Flash-Lite** ในการทายอายุและอารมณ์ผ่านกล้องเว็บแคมแบบ Real-time พัฒนาด้วย Python และ Streamlit

## 🌟 Features
* **Live Camera Integration**: ถ่ายภาพหน้าตัวเองผ่านเบราว์เซอร์ได้ทันที
* **Multimodal AI Analysis**: ใช้ Gemini 2.5 Flash-Lite วิเคราะห์ทั้งภาพและข้อความพร้อมกัน
* **Real-time Feedback**: ทายอายุ อารมณ์ และลักษณะเด่นของใบหน้าพร้อมคำแนะนำกวนๆ

## 🛠️ Tech Stack
* **Frontend**: Streamlit
* **AI Model**: Google Gemini 2.5 Flash-Lite
* **Libraries**: `google-genai`, `Pillow`, `python-dotenv`

## 🚀 How to Run

1. **Clone Repository**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/AI-Age-Guesser.git](https://github.com/YOUR_USERNAME/AI-Age-Guesser.git)
   cd AI-Age-Guesser
2. **Setup Virtual Environment**
   ```bash
   python -m venv venv
   venv\Scripts\activate
3. **Clone Repository**
   ```bash
   pip install -r requirements.txt
4. **Environment Setup**
   ```bash
   GEMINI_API_KEY=your_api_key_here
5. **Running Websites**
   ```bash
   streamlit run main.py
