##Monthly Financial Planner Pro

![alt text](https://github.com/F13ND5/Monthly-Planner-Pro/blob/dev/Monthly%20Financial%20Planner%20Pro%20logo.png)

Monthly Financial Planner Pro is a comprehensive web application designed to help users efficiently manage their monthly finances. It features advanced tools such as income and expense tracking, automated future planning, real-time synchronization, and financial data integration using Plaid and OpenBanking APIs.

---

## 🚀 Key Features

1. **Dynamic Financial Table:**
- Automatically generates rows for the next 6 months based on the current date.
Inline editing for income and expenses with real-time savings and budget difference calculations.
- Dropdowns for selecting income/expense categories.

2. **Advanced Data Visualizations:**
- Interactive line charts to track income vs. expense trends.
- Pie charts for a detailed breakdown of expenses by category.

3. **Integration with Plaid/OpenBanking APIs:**
- Fetch and sync live bank transaction data for enhanced financial planning.

4. **Localization and Multilingual Support:**
- Powered by ngx-translate for seamless support across multiple languages.

5. **Authentication and Security:**
- Secure user data with JWT-based authentication.

6. **Export and Import Options:**
- Export financial data as Excel or PDF.
- Import pre-filled financial data for quick onboarding.

---

## 🛠️ Tech Stack

**Frontend:**
- Angular
- Angular Material
- NgRx (for state management)
- RxJS

**Backend:**
- Python (Django Framework)
- PostgreSQL

**APIs and Integrations:**
- Plaid API
- OpenBanking APIs

**Data Visualization:**
- Chart.js

**Localization:**
- ngx-translate

**Deployment:**
- Hosted on Heroku

---

## ⚙️ Setup

**Backend (Django):**

1. Clone the repository:
```bash
git clone https://github.com/F13ND5/monthly-financial-planner.git  
```

2. Navigate to the backend directory:
```bash
cd backend  
```

3. Install dependencies:
```bash
pip install -r requirements.txt  
```

4. Apply database migrations:
```bash
python manage.py migrate  
```

5. Start the development server:
```bash
python manage.py runserver  
```

**Frontend (Angular):**

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

3. Run the Angular app:
```bash
ng serve
```

---

## 📦 Deployment on Heroku

1. Create a Heroku app and link your repository:
```bash
heroku create  
git push heroku main
```

2. Configure environment variables:
- Set up PostgreSQL database URL and Plaid/OpenBanking API credentials.
- Ensure Django settings and Angular API endpoints match production settings.

3. Deploy the app:
```bash
heroku deploy
```

---

## 🌟 Contributing

**We welcome contributions! If you'd like to improve this project:**

1. Fork the repository.

2. Create a feature branch:
```bash
git checkout -b feature-name  
```

3. Commit your changes:
```bash
git commit -m "Add your message here"  
```

4. Push to the branch:
```bash
git push origin feature-name  
```

5. Open a Pull Request.

---

## 📝 License
This project is licensed under the **MIT License**. See the [LICENSE]() file for more details.

---

## 🌟 Acknowledgments
- Thanks to the developers of Angular, Django, and Chart.js for providing the tools that made this project possible.
- Special appreciation to the teams behind Plaid and OpenBanking APIs for enabling seamless data integration.
