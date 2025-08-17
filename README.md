# 🤖 Blog Generation LLM App

A Streamlit-based web application that generates **AI-powered blogs** using the **LLaMA 2 model**.  
Users can provide a topic, select the number of words, and choose the target audience style.  
The app then generates a professional blog post tailored to the chosen parameters.

---

## 🚀 Features
- 📝 Generate blogs on any topic
- 🎯 Customize number of words
- 👥 Choose writing style:
  - Researchers
  - Data Scientists
  - Common People
- 🖥️ Simple and interactive **Streamlit** web UI
- 🧠 Powered by **LLaMA 2 (via CTransformers + LangChain)**

---

## 🏗️ Project Structure

```plaintext
Blog-Generation-LLm-App/
│── Models/              # Pretrained model files (ignored from Git)
│── venv/               
│── app.py              # Main entry script for running the app
│── requirements.txt     # Python dependencies
│── .gitignore           # Git ignore file
│── README.md            # Project documentation
```

---

## 📦 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sivakumar793/Blog-Generation-LLm-App.git
   cd Blog-Generation-LLm-App
2. Create a virtual environment (recommended):
```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate      # Windows
```
3. Install dependencies:
   ```bash
   pip install -r requirements.tx
   ```
⚙️ Model Setup
```bash
   Models/
    └── llama-2-7b-chat.ggmlv3.q8_0.bin
```
▶️ Usage

Run the Streamlit app:
```bash
   streamlit run app.py
```
🖼️ App Workflow

Enter a blog topic

Select the number of words

Choose the target audience style

Click Generate

🎉 Get an AI-generated blog instantly!

📖 Example Prompt
```bash
Topic: Artificial Intelligence in Healthcare

Words: 200

Style: Researchers

✅ The app will generate a 200-word research-style blog on AI in healthcare.
```
📌 Requirements

Python 3.9+

Streamlit

LangChain

CTransformers

(Already included in requirements.txt)

🤝 Contributing

Feel free to fork this repo, open issues, and submit pull requests to improve the project.

📜 License

This project is licensed under the MIT License.

👤 Author
Siva Kumar M
https://github.com/Sivakumar793


