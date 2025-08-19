# FinanceFusion 💰

FinanceFusion is a powerful, AI-driven finance management web application that allows users to track their expenses, incomes, and manage their finances with ease. Built with Next.js, Prisma, and OpenAI's GPT-3.5 Turbo model, this app provides an intelligent chatbot assistant that can answer financial queries and provide personalized advice.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

---

## ✨ Features

- **🤖 AI Chatbot**: Interact with an AI assistant to get insights and answers related to your finances.
- **📈 Expense & Income Tracking**: Keep track of your income and expenses with simple data management.
- **📁 Financial Reports**: Generate monthly reports on income, expenses, and special payments.
- **👤 User Management**: Manage and organize user data securely.
- **🗕️ Calendar Integration**: Set reminders for special payments and recurring expenses.

---

## 🛠️ Technologies Used

- **⚛️ Next.js**: A React framework for building server-side rendered (SSR) web applications.
- **🔀 Prisma**: An ORM for managing the database, ensuring smooth interaction between the backend and the database.
- **🧠 OpenAI GPT-3.5**: Used to power the chatbot assistant and handle natural language processing.
- **💄 MongoDB**: A NoSQL database used for storing and managing user data.
- **🎨 Tailwind CSS**: A utility-first CSS framework used for styling the app.

---

## 🚀 Getting Started

### Prerequisites

- **📦 Node.js**: Install the latest version of Node.js (LTS recommended).
- **💄 MongoDB**: You can use a local MongoDB instance or [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for cloud hosting.
- **🔑 OpenAI API Key**: Sign up for an API key at [OpenAI](https://platform.openai.com/signup).

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/BuddhikaRoshan/FinanceFusion.git
   cd FinanceFusion
   ```

2. Install the required dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Set up your environment variables. Create a `.env.local` file in the root directory with the following:

   ```env
   NEXT_PUBLIC_OPENAI_API_KEY=your-openai-api-key
   DATABASE_URL="mongodb+srv://username:password@cluster.mongodb.net/financefusion?retryWrites=true&w=majority"
   NEXTAUTH_SECRET=your-random-secret-key
   NEXTAUTH_URL=http://localhost:3000
   ```

4. Run Prisma migrations to set up your database schema:

   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. Start the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to start using the application.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

---

## 🌍 Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [Next.js GitHub](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

---

## 🚤 Deployment

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

To deploy manually:

```bash
# Build for production
npm run build

# Start the production server
npm start
```

---

## 👥 Team Members

- Bandara L.P.B.R. (IT22564122)
- Udesha S.M.S. (IT22586902)
- Niwanthika M.A.H. (IT22570758)
- Liyanahetti L.H.R.S.D. (IT22592088)

---

## 🎯 Project Goals

- **🤖 Build a Comprehensive Financial Assistant**: Develop an AI-powered chatbot that answers questions about personal finances and provides insights.
- **💵 Provide Seamless Expense and Income Tracking**: Allow users to easily input and categorize financial entries.
- **📊 Enhance Financial Awareness**: Help users understand their financial situation through key metrics.
- **📝 Create User-Centric Reports**: Generate user-friendly financial summaries.
- **🔒 Ensure Secure Data Management**: Implement industry-standard security practices.
- **🔀 Enable Future Expansion**: Design for easy integration with other financial tools.

---

## 🤝 Contributing

We welcome contributions to FinanceFusion. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your changes.
3. Commit your changes with a descriptive commit message.
4. Push to your forked repository.
5. Open a pull request with a clear description of the changes.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact

For any queries or feedback, feel free to contact:

- **✉️ Email**: buddhikaroshanofficial@gmail.com
- **🐙 GitHub**: [BuddhikaRoshan](https://github.com/BuddhikaRoshan)
- **📁 Project Repository**: [FinanceFusion](https://github.com/BuddhikaRoshan/FinanceFusion)

---

## 🙏 Acknowledgments

- Next.js for providing the framework.
- Prisma for the ORM and database management.
- OpenAI for GPT-3.5, powering the intelligent assistant.
- Tailwind CSS for making styling easy and efficient.

