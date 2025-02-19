# Expense Tracker Website

This project is an **Expense Tracker Website** built using **Next.js**, **Drizzle ORM**, **PostgreSQL**, and **Tailwind CSS**. The application allows users to create budgets, add expenses, and visualize their spending with a bar chart.

## Features

### **Budget Management**
- Users can create budgets for different expense categories.

### **Expense Tracking**
- Add expenses to each budget and track them effectively.

### **Filtering**
- View all expenses or filter by specific budgets.

### **Data Visualization**
- A bar chart provides a visual representation of expenses within each budget.

### **Responsive Design**
- The application is fully responsive, ensuring a seamless experience across various devices and screen sizes.

## Technologies Used

- **Next.js**: React framework for building server-side rendered applications.
- **Drizzle ORM**: TypeScript ORM for PostgreSQL, providing a type-safe data access layer.
- **PostgreSQL**: Relational database for storing application data.
- **Tailwind CSS**: Utility-first CSS framework for designing responsive user interfaces.

## Getting Started

To run this project locally, follow these steps:

### **Prerequisites**

Ensure you have the following installed on your system:

- **Node.js**
- **npm** or **yarn**
- **PostgreSQL**

### **Installation**

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Satyam-Mishra-1/Expense-tracker.git
   cd expense-tracker
   ```

2. **Install dependencies:**
   ```sh
   npm install  # or yarn install
   ```

3. **Set up environment variables:**
   - Create a `.env.local` file in the root directory.
   - Add the following environment variables:
     ```sh
     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
     CLERK_SECRET_KEY=your_clerk_secret_key
     NEXT_PUBLIC_CLERK_SIGN_IN_URL=your_clerk_sign_in_url
     NEXT_PUBLIC_CLERK_SIGN_UP_URL=your_clerk_sign_up_url
     NEXT_PUBLIC_DATABASE_URL=your_database_url
     ```

4. **Run database migrations:**
   ```sh
   npm run db:push
   npm run db:studio
   ```

5. **Start the development server:**
   ```sh
   npm run dev  # or yarn dev
   ```

6. **Open your browser and navigate to:**
   ```sh
   http://localhost:3000
   ```

## Usage

- **Create budgets** for various expenses.
- **Add expenses** to each budget.
- **Filter expenses** by specific budgets or view all expenses.
- **Use the bar chart** to visualize expenses within each budget.

## Acknowledgements

- [Next.js Documentation](https://nextjs.org/docs)
- [Drizzle ORM Documentation](https://orm.drizzle.team/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)

