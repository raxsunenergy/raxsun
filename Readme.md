# 🌞 RaxSun Solar System Installation - Company Website

Welcome to the official website project for **RxSun Solar System Installation**. This website aims to showcase the company's services in solar energy solutions, providing customers with the best in solar panel installation for homes, industries, and more.

## 🌟 Features
- Responsive and modern design
- Information about solar energy solutions
- Services provided by RxSun, including residential, commercial, and industrial installations
- Contact forms for customer inquiries
- Blog section for solar tips, news, and innovations
- SEO-friendly structure

---

## 🚀 Technologies Used

- **HTML5/CSS3**: For structuring and styling the website.
- **JavaScript**: Dynamic content and interactivity.
- **ReactJS**: Frontend framework for building reusable UI components.
- **Bootstrap**: Responsive design framework.
- **Node.js**: Backend support for API and server-side logic.
- **Express.js**: For handling server requests and routing.
- **MongoDB**: Database to store user data, inquiries, and service details.

---

## 🛠️ Project Setup

### Prerequisites

- **Node.js**: Make sure Node.js is installed on your machine. You can download it from [Node.js](https://nodejs.org/).
- **MongoDB**: Ensure you have MongoDB installed or use a cloud MongoDB service like MongoDB Atlas.

### Installation Steps

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/raxsun-website.git
    cd raxsun-website
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

3. **Set up environment variables**: Create a `.env` file in the root directory and add the following:
    ```bash
    MONGO_URI=<your_mongo_db_connection_string>
    PORT=5000
    ```

4. **Run the development server**:
    ```bash
    npm start
    ```
   The app will be running on `http://localhost:5000`.

---

## 📁 Project Structure

```bash
├── public/              # Static files (HTML, CSS, JS)
├── src/                 # React components
│   ├── components/      # Reusable UI components
│   ├── pages/           # Website pages (Home, About, Services)
│   ├── api/             # API service for backend calls
│   └── assets/          # Images, logos, and media
├── server/              # Backend (Node.js + Express)
│   ├── models/          # MongoDB models
│   ├── routes/          # API endpoints
│   └── controllers/     # Business logic
├── .env                 # Environment variables
└── README.md            # Project documentation
