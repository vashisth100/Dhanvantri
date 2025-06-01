# 🧠 Prescription Scanner App

An AI-powered medical app that:
- 📷 Scans handwritten prescriptions
- 🧠 Uses OCR + NLP to extract medicine names
- 🛒 Auto-books medicines for purchase
- 💳 Generates UPI QR code for instant payment

---

## 📌 Features

- Prescription image upload via mobile
- OCR to recognize handwritten text (Tesseract/TrOCR)
- Named Entity Recognition (NER) to extract drug names
- Medicine list generation + price total
- UPI QR Code payment integration

---

## 📁 Project Structure

prescription-scanner-app/
├── frontend/ # React Native or Flutter mobile app
├── backend/ # API server with OCR + NER integration
├── model/ # ML training code and models
├── data/ # Prescription images and annotations
└── docs/ # Planning, wireframes, Gantt charts


---

## 🚀 Tech Stack

| Part | Tech |
|------|------|
| Frontend | React Native / Flutter |
| Backend | FastAPI / Node.js |
| OCR | Tesseract, TrOCR (HuggingFace) |
| NLP | SpaCy or Transformers for NER |
| UPI | Razorpay / BHIM API |

---

## 📅 Roadmap

- [x] Project setup & folder structure
- [ ] Collect + label prescription image data
- [ ] Train OCR + NER models
- [ ] Create backend APIs for scan + UPI
- [ ] Build mobile UI and integrate everything

---

## 📜 License

MIT © 2025 [vashishth100]

---

## 🤝 Contributing

PRs welcome. Feel free to fork and raise issues.

