# Assets Management System

This project is a Django-based web application for managing organizational assets and their allocation to employees. It provides features for tracking assets, allocating them to staff, and generating reports.

## Features

- Asset registration and management
- Employee management
- Asset allocation and tracking
- Allocated assets report with pagination
- Export report to Excel
- Print report functionality

## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/P-Munyua/Assets.git
   cd Assets
   ```

2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Apply migrations:**
   ```sh
   python manage.py migrate
   ```

4. **Run the development server:**
   ```sh
   python manage.py runserver
   ```

## Usage

- Access the web interface at `http://localhost:8000/`
- Use the navigation to manage assets and employees
- View and export allocation reports from the reports section

## Folder Structure

- `asset/` - Main Django app for asset management
- `templates/asset/` - HTML templates
- `static/` - Static files (CSS, JS)
- `requirements.txt` - Python dependencies

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under
