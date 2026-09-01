# HEALTH-CARE-THRIVE-HACKATHON
FollowUp AI 🏥 is an explainable healthcare prototype that predicts which patients are most likely to miss follow-up appointments. It provides transparent risk scores, clear explanations, and a priority queue so staff can intervene early. Built with React and TypeScript, it turns prediction into prevention.
# FollowUp AI 🏥

### Patient Follow-up Risk Predictor

> **Predict. Explain. Prioritize. Intervene.**

FollowUp AI is an explainable healthcare platform that predicts which patients are most likely to miss their next follow-up appointment and helps hospital staff take preventive action.

## 🚨 Problem

Hospitals manage thousands of follow-up appointments, making it difficult to identify patients who may miss their next visit.

A missed follow-up can result in incomplete treatment and delayed care.

**FollowUp AI answers:**

> *Who is most likely to miss their next appointment, and why?*

## 💡 Solution

The system analyzes:

* Previous appointment history
* Missed appointments
* Age
* Distance from hospital
* Treatment duration
* Appointment frequency

Patients receive a **0–100 risk score**:

🟢 **Low:** 0–29
🟡 **Medium:** 30–59
🔴 **High:** 60–100

Patients are automatically ranked in a **Priority Queue** so staff can focus on those who need intervention most.

## 🧠 Explainable Risk

Every prediction includes the reasons behind the score.

Example:

**87 — HIGH RISK**

* 4 missed appointments
* Low attendance history
* 31 km from hospital
* Long treatment duration
* Frequent appointments

This ensures staff receive **actionable explanations instead of a black-box score**.

## ⚙️ Features

* 📊 Risk dashboard
* 🎯 Patient priority queue
* 🧠 Explainable predictions
* 👥 Patient management
* 📅 Appointment history
* 📞 Intervention tracking
* 📈 Analytics
* 🧪 Risk simulator
* 📤 CSV export
* 💾 Persistent demo data

## 🧮 Risk Model

The prototype uses a transparent weighted scoring system:

| Factor                | Weight |
| --------------------- | -----: |
| Missed appointments   |    40% |
| Attendance history    |    15% |
| Distance              |    15% |
| Treatment duration    |    10% |
| Appointment frequency |    10% |
| Age                   |    10% |

The scoring engine can later be replaced with a trained ML classifier using historical attendance data.

## 🛠️ Tech Stack

**React • TypeScript • Tailwind CSS • Recharts • Lucide Icons • LocalStorage**

## 🔮 Future Scope

* Machine-learning prediction
* EHR integration
* Automated SMS/WhatsApp reminders
* Personalized interventions
* Real-time analytics
* Fairness and model monitoring

## ⚠️ Disclaimer

This is a healthcare prototype for educational/hackathon purposes. It does not diagnose medical conditions or replace professional clinical judgment. All demo patient data is fictional.

---

### **FollowUp AI**

**Turning prediction into prevention.**

Live web link:
[Live Web Link](https://priorityshield.lovable.app)    
## 🎥 Demo Video

[▶️ Watch ThreatQueue Demo](https://drive.google.com/file/d/1dkcbWvmMOJ3_Dyuv1D-LRi284VZApl56/view?usp=sharing)
