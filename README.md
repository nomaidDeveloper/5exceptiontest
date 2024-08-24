# Item Management Application

A full-stack application with a React frontend and a Node.js/Express backend, using MySQL and Sequelize for database management.

## Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-repository.git
cd your-repository
```

### 2. Backend Setup

```bash
cd backend
npm install
```

- Create a MySQL database.
- Create a `.env` file in `backend`:

    ```env
    DB_NAME=your_database_name
    DB_USER=your_database_user
    DB_PASSWORD=your_database_password
    DB_HOST=localhost
    DB_DIALECT=mysql
    ```

- Start the backend server:

    ```bash
    npm run dev
    ```

### 3. Frontend Setup

```bash
cd ../frontend
npm install
```


- Start the frontend:

    ```bash
    npm start
    ```

## API Endpoints

- **POST /items:** Create items.
- **GET /items:** Retrieve paginated items with optional filters.

