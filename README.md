````markdown
# 📊 Auralytics – Personal Finance Analytics Dashboard

**Auralytics** is a modern personal finance analytics web app that helps users track and analyze their financial accounts and transactions with powerful visualizations and a clean, responsive UI.

---

## 🚀 Features

- 🔐 **Secure Authentication** – User-specific financial data via login flow  
- 💰 **Account Overview** – Displays account balances and summaries  
- 📊 **Transaction Analytics** – Graphs and charts to visualize expenses  
- 🧾 **Advanced Transaction Table** – Filter, paginate, and categorize transactions  
- 📅 **Date-Based Insights** – View financial trends over time  
- ⚡ **Responsive UI** – Smooth experience across desktop and mobile

---

## 🧱 Tech Stack

| Tech             | Purpose                                 |
|------------------|-----------------------------------------|
| **Next.js**       | Full-stack React framework              |
| **Tailwind CSS**  | Utility-first CSS for styling           |
| **Prisma ORM**    | Type-safe DB schema & migration tool    |
| **PostgreSQL**    | Relational database                     |
| **Lucide Icons**  | Beautiful and lightweight icons         |
| **ShadCN/UI**     | Prebuilt accessible UI components       |

---

## 🛠️ Installation Guide

### 📌 Prerequisites

- [Node.js](https://nodejs.org/) (v18 or newer)
- [PostgreSQL](https://www.postgresql.org/) database installed and running
- [Git](https://git-scm.com/)

---

### ✅ Step 1: Clone the Repository

```bash
git clone https://github.com/varma-101/auralytics.git
cd auralytics
````

---

### ✅ Step 2: Install Dependencies

```bash
npm install
# or
yarn install
```

---

### ✅ Step 3: Set Up Environment Variables

```

---

### ✅ Step 4: Initialize the Database

Run the following commands to generate the Prisma client and run migrations:

```bash
npx prisma generate
npx prisma migrate dev --name init
```

---

### ✅ Step 5: Start the Development Server

```bash
npm run dev
# or
yarn dev
```

The app will be running at:
🔗 `http://localhost:3000`

---


## 🚀 Deployment

You can deploy this app on **Vercel**, **Render**, or **Netlify**. Make sure to:

* Set environment variables in the platform’s dashboard
* Use a production PostgreSQL database

---

## 🤝 Contributing

Pull requests are welcome! Here's how to contribute:

```bash
# Fork the repo
git checkout -b feature/YourFeature
git commit -m "Add your feature"
git push origin feature/YourFeature
```

