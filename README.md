# 🛡️ IncomeShield AI  
### AI-Powered Parametric Insurance for Gig Workers  

---

## 📌 Problem Statement

India’s gig delivery workers (Zomato, Swiggy, Zepto, Amazon) lose **20–30% of their weekly income** due to uncontrollable external disruptions like heavy rain, extreme heat, pollution, and curfews.

Currently, there is **no system to protect their income**, forcing them to bear the full financial loss.

---

## 💡 Inspiration

The idea came from observing how delivery partners struggle during bad weather conditions. While customers stay safe at home, gig workers lose their earnings without any support system.

We wanted to build a solution where:
> “Even if a worker cannot work due to external conditions, their income remains protected.”

---

## ⚙️ What it does

IncomeShield AI is an **AI-powered parametric insurance platform** that:

- 📊 Calculates **weekly premiums dynamically**
- 🌦 Monitors environmental disruptions in real-time  
- ⚡ Automatically triggers payouts  
- 🛡 Prevents fraud using intelligent detection systems  

### 🔥 Core Logic

$$
Payout = Environmental\ Trigger + Verified\ Income\ Drop
$$

---

## 🛠 How we built it

We designed a modular system combining frontend, backend, and AI models.

### 💻 Tech Stack

- Frontend: React + Tailwind CSS  
- Backend: Spring Boot  
- Database: MySQL  
- AI/ML: Python (Scikit-learn)  
- Cache: Redis  
- APIs: Weather API (OpenWeather / Mock)

---

### 🤖 AI Components

#### 1. Risk Prediction Model
- Predicts probability of income loss  
- Uses weather data + historical earnings  
- Outputs risk level → determines premium  

#### 2. Fraud Detection Model
- Uses **Isolation Forest (Anomaly Detection)**  
- Detects:
  - GPS spoofing  
  - Fake inactivity  
  - Repeated suspicious claims  
  - Coordinated fraud patterns  

---

## 🛡️ Adversarial Defense & Anti-Spoofing Strategy

### 🚨 Problem

Fraudsters can spoof GPS location to fake claims during disruptions.

---

### 🔍 Multi-Signal Verification

Instead of relying only on GPS, we analyze:

- 📍 Movement patterns  
- 📱 App activity (order interactions)  
- 📊 Accelerometer data  
- 📶 Network signal variation  
- 📦 Delivery logs  

---

### 📊 Trust Score System

Each user is assigned a trust score:

$$
TrustScore = f(activity + movement + history + device\ signals)
$$

- High score → instant payout  
- Low score → flagged for verification  

---

### 🧠 Group Fraud Detection

We detect coordinated fraud by identifying clusters of users showing identical behavior patterns (e.g., Telegram scam groups).

---

### ⚖️ Fairness System

To avoid penalizing genuine users:

- Claims are **not rejected instantly**  
- Flagged users go through **soft verification**:
  - Selfie check  
  - Activity validation  

---

## 💰 Weekly Premium Model

Premium is calculated based on:

- Weekly earnings  
- Weather risk  
- Location demand  
- Historical data  

### 📊 Example

| Weekly Income | Risk Level | Premium |
|--------------|-----------|--------|
| ₹5000        | Medium    | ₹100   |

👉 Premium range: **2% – 5% of weekly income**

---

## ⚡ Parametric Trigger System

Payout is triggered only when BOTH conditions are met:

### ✅ Environmental Trigger
- Rainfall > 50mm  
- Temperature > 42°C  
- AQI > 300  
- Curfew  

### ✅ Income Drop Trigger
- Delivery activity drops by 40%  

---

## 🔄 Workflow

1. User onboarding  
2. Weekly premium calculation  
3. Policy activation  
4. Real-time monitoring  
5. Trigger detection  
6. Income verification  
7. Fraud detection  
8. Instant payout  

---

## 🖥 Platform Choice

**Web Application**

### Why?

- Easy access on all devices  
- Faster development  
- Better analytics dashboard  

---

## 📊 Analytics Dashboard

- 📈 Expected vs Actual Income  
- ⚠️ Risk Levels  
- 💸 Premium details  
- 🛡 Fraud alerts  
- 🌦 Active disruptions  

---

## ⚠️ Challenges we ran into

- Designing a fair system balancing automation and user trust  
- Handling GPS spoofing fraud  
- Creating a weekly pricing model instead of traditional insurance  
- Simulating real-world APIs  

---

## 🏆 Accomplishments that we're proud of

- Built a complete AI-based insurance concept  
- Designed a strong fraud-resistant system  
- Created a real-world applicable solution for gig workers  

---

## 📚 What we learned

- Real-world application of parametric insurance  
- Importance of fraud detection in fintech systems  
- Building AI-driven decision-making systems  
- Designing solutions for real-world economic problems  

---

## 🔮 What's next for IncomeShield AI

- Behavior-based premium reduction  
- Advanced AI pricing models  
- Multi-city scalability  
- Integration with real delivery platforms  

---

## 🧰 Built With

React, Tailwind CSS, Spring Boot, MySQL, Python, Scikit-learn, Redis  

---

## 🚀 Try It Out Link

Coming Soon  

---

## 💻 GitHub Repository

(Add your repository link here)

---

## 🎥 Demo Video Link

(Add your video link here)

---
