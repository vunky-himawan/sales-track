# This repository is used to learn RESTFul API using Laravel.

# Sales Track

Sales Track adalah aplikasi manajemen penjualan yang memungkinkan admin (owner) dan karyawan untuk mencatat, melihat, dan menganalisis data penjualan mereka. Aplikasi ini dibangun menggunakan Laravel untuk backend API, Alpine.js untuk interaktivitas sisi klien, dan Chart.js untuk visualisasi data.

### Features:

1. **Authentication**: Users must login to access the app.
2. **Dashboard**: The dashboard view displays a summary of sales statistics, such as total monthly sales, top sales, etc.
3. **Sales Management**:
    - **Add Sales Data**: Admins and employees can add new sales data, including information such as sales date, products sold, quantity, and price.
    - **View Sales List**: Admins and employees can view a list of all sales data that has been entered. Admins have the option to edit and delete sales data, while employees can only view the data.
4. **Data Visualization**:
    - **Monthly Sales Graph**: The visualization graph displays monthly sales trends in the form of a line graph or bar graph, making it easy to see the progress of sales over time.
    - **Sold Products Chart**: This graph displays the percentage of products sold, helping admins and employees to see which products customers are most interested in.
5. **Search and Filter**: Admins and employees can search for sales data based on certain criteria, such as dates or specific products, as well as apply filters to customize the data display.
6. **Responsive and User Friendly**: The user interface is designed to be responsive and easy to use, both on desktop and mobile devices.

### Technology Used

1. **Laravel**: PHP framework for API backend.
2. **Alpine.js**: JavaScript framework for lightweight client-side interaction.
3. **Chart.js**: JavaScript library for creating charts and data visualizations.
4. **Tailwind CSS**: CSS framework for building responsive user interfaces.
5. **MySQL**: Relational database for storing and managing data.

### User

1. **Admin (Owner)**: Has full access to all features of the app. They are responsible for managing sales data and other users.
2. **Employee**: Have limited access. They can add sales data and view sales reports, but do not have the right to edit or delete sales data.

### Installation Steps

1. Clone this repository to your local:

```bash
git clone https://github.com/vunky-himawan/sales-dashboard.git
```

2. Go to the project directory:

```bash
cd sales-dashboard
```

3. Install dependencies using Composer:

```bash
composer install
```

4. Copy the .env.example file to .env:

```bash
cp .env.example .env
```

5. Generate the application key:

```bash
php artisan key:generate
```

6. Configure the database in the .env file.
7. Run the migration to create the database schema:

```bash
php artisan migrate
```

8. Run the local server:

```bash
php artisan serve
```

The application is now accessible at http://localhost:8000.
