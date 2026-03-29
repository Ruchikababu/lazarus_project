# 💊 Project Lazarus - AI Prescription Analyzer

An intelligent AI-powered system that analyzes prescription data, detects potential risks, and provides interactive insights using Machine Learning, voice alerts, and dashboards.

---

## 🚀 Features

* 🤖 **AI-Based Risk Detection** (Machine Learning model)
* 📊 **Interactive Dashboard** (Bar & Pie charts)
* 🎤 **Voice Input + Voice Alerts**
* 💊 **Automatic Data Decoding**
* 📂 **Works with ANY CSV file**
* 🧠 **Smart Column Detection**
* 💬 **Built-in Chatbot (Text + Voice)**

---

## 🛠️ Tech Stack

* Python
* Streamlit
* Pandas
* Scikit-learn
* Matplotlib
* Pyttsx3 (Text-to-Speech)
* SpeechRecognition

---

## 📂 Project Structure

```
Lazarus_Project/
│
├── app.py
├── data/
│   └── sample_prescription.csv
├── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/lazarus-project.git
cd lazarus-project
```

Install dependencies:

```bash
pip install streamlit pandas matplotlib scikit-learn pyttsx3 SpeechRecognition pyaudio
```

If PyAudio fails:

```bash
pip install pipwin
pipwin install pyaudio
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 📊 How It Works

1. Upload any CSV file
2. Select a column (if not auto-detected)
3. System decodes and analyzes data
4. AI model predicts risk level
5. Dashboard shows results
6. Voice system gives alerts

---

## 📄 Sample CSV Format

```
patient_id,medicine,notes
101,bcd,normal dose
102,efg,overdose warning
103,hij,duplicate entry
```

---

## 🧠 AI Model

* Uses TF-IDF Vectorization
* Logistic Regression for classification
* Predicts:

  * ✅ Safe
  * ⚠️ Risk Detected

---

## 🔊 Voice Features

* Speak results using text-to-speech
* Voice input using microphone
* Interactive AI chatbot

---

## 🔥 Future Enhancements

* Deep Learning (LSTM / BERT)
* Cloud Deployment
* Mobile App Integration
* Real Hospital Data Integration
* Authentication System

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Developed by **Rajasri R**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
