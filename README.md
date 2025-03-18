cd frontend
npm start

cd backend
npm install  # Only if dependencies are missing
nodemon

cd admin
npm install  # Only if dependencies are missing
npm run dev


also add database in  backend/index.js 
// Database connection
mongoose.connect("mongodb+srv://abhi:63.enuvv.mongodb.net/e-commerce");
