# AI-Powered Emergency Medical Services (EMS) System

## 📌 Abstract

The field of Emergency Medical Services (EMS) has undergone a technological transformation aimed at improving response times, diagnostic accuracy, and patient outcomes. Traditional emergency care methods rely heavily on manual assessments by paramedics and verbal or handwritten reports, often leading to delayed communication, errors in interpreting vital signs, and inconsistent patient evaluations.

To address these challenges, we propose an **AI-powered EMS framework** that enhances real-time coordination between ambulance teams and hospitals. Developed using **Python** and **Tkinter**, the system includes two core modules:

- **Ambulance-side application**: Captures patient data.
- **Hospital-side server**: Securely receives and analyzes the data through a socket connection.

Machine learning algorithms are employed for real-time predictive analytics to assess patient conditions efficiently.

## 🤖 Machine Learning Models Used

Three classification models were tested for performance and reliability:

| Model               | Accuracy | Precision | Recall | F1-Score |
|--------------------|----------|-----------|--------|----------|
| Decision Tree       | 94.86%   | 94.87%    | 94.83% | 94.85%   |
| Gaussian Naive Bayes (GNB) | 85.98%   | -         | -      | 85.94%   |
| K-Nearest Neighbors (KNN) | 100%     | 100%      | 100%   | 100%     |

- **Decision Tree**: Highly accurate and explainable, suited for complex cases.
- **GNB**: Balanced and fast, suitable for probabilistic predictions.
- **KNN**: Outstanding performance, ideal for accurate emergency diagnostics.

## ⚙️ Technologies Used

- **Language**: Python
- **GUI**: Tkinter
- **Communication**: Python Sockets (Client-Server architecture)
- **ML Libraries**: scikit-learn, pandas, NumPy

## 🚑 Key Features

- Real-time data sharing between ambulance and hospital
- Automated patient condition prediction
- Reduces human error in emergency decision-making
- Secure and efficient communication pipeline
- GUI-based applications for ease of use by medical personnel

## 🚀 Future Improvements

- Integration with real-time GPS and mapping systems
- Deployment on mobile devices or tablets for field use
- Use of deep learning models for enhanced predictive power
- Integration with hospital Electronic Health Record (EHR) systems

## 📁 Project Structure

```
EMS-AI-System/
├── ambulance_app/        # GUI client for paramedics
├── hospital_server/      # Server-side analyzer and dashboard
├── models/               # Trained ML models
├── data/                 # Patient data and datasets
└── README.md
```

## 📄 License

This project is for academic and research purposes. Licensing and use in production environments require appropriate authorization.
[Published Paper](https://eudoxuspress.com/index.php/pub/article/view/2270/1518) 
---

*This intelligent, explainable system modernizes EMS by minimizing human error and improving decision-making speed, marking a significant step forward in the evolution of emergency healthcare.*
