
# Check Reader App

This is a full-stack application to upload check images, extract MICR data and amount using AI (Tesseract OCR), and display the result in a web UI.

## 🛠 Tech Stack
- Frontend: ReactJS + TailwindCSS
- Backend: Spring Boot (Java)
- OCR Engine: Tesseract OCR

## 🚀 How to Run

### Prerequisites
- Java 17+ and Maven
- Node.js (v18+)
- Tesseract OCR installed (https://github.com/tesseract-ocr/tesseract)

### Backend
```bash
cd backend
mvn clean install
mvn spring-boot:run
```

### Frontend
```bash
cd frontend
npm install
npm start
```

Upload a sample check image and view extracted data in the result table.

## 📂 Sample Image Location
Place sample check images in `backend/sample-checks/` for testing.

