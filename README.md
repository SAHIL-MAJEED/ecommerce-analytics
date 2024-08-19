# 🛒 E-commerce Analytics Dashboard

This project is a full-stack web application for visualizing e-commerce data from a Shopify store. It connects to a MongoDB database, retrieves data via a REST API, and displays it using charts on the frontend.

## 🌟 Features
1. **Total Sales Over Time**: Analyze total sales grouped by day, month, quarter, and year.
2. **Sales Growth Rate Over Time**: See the growth of sales as a percentage.
3. **New Customers Added Over Time**: Track when new customers are added.
4. **Repeat Customers Analysis**: Identify customers who made multiple purchases.
5. **Geographical Distribution of Customers**: Visualize customer locations on a map.
6. **Customer Lifetime Value by Cohorts**: Track customer value grouped by the month of their first purchase.

## 🛠 Tech Stack
### Backend
- **Node.js** with **Express.js**: For creating REST APIs.
- **MongoDB** with **Mongoose**: For data storage and management.
- **CORS**: For allowing cross-origin requests from the frontend.

### Frontend
- **React.js**: For building the user interface.
- **Chart.js** and **React-Chartjs-2**: For creating visual charts.
- **Axios**: For making HTTP requests to the backend.

## 🚀 Getting Started

### Prerequisites
Ensure that you have the following installed:
- [Node.js](https://nodejs.org/) (which includes npm)
- [Git](https://git-scm.com/) (for cloning the repository)
- [MongoDB Compass](https://www.mongodb.com/products/compass) (optional, to explore the database)

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd ecommerce-analytics
. Frontend Setup
Open a new terminal and navigate to the frontend directory:

cd frontend
Install dependencie
npm install
Start the frontend development server:
npm start
The app will open automatically in your browser at http://localhost:3000.

4. Connecting to MongoDB
The backend is already set up to connect to a sample MongoDB cluster. The connection string is:
mongodb+srv://db_user_read:LdmrVA5EDEv4z3Wr@cluster0.n10ox.mongodb.net/RQ_Analytics?
