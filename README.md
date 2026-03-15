# MediTrack: Pharmacy Management System

MediTrack is a professional pharmacy management application developed in Python. It provides a comprehensive solution for managing inventory, tracking orders, and handling customer and hospital interactions for pharmacies.

## 🚀 Features

- **Inventory Management**: Track medicines, surgical products, ayurvedic treatments, and general items.
- **Stock Monitoring**: Real-time updates on stock availability and expiration dates.
- **User Roles**: Separate interfaces and functionalities for individual customers and hospital representatives.
- **Order Processing**: Integrated cart system for placing orders with multiple payment options.
- **Prescription Verification**: Specialized handling for prescription-only medicines.
- **Profile Management**: Users can create accounts and update their personal or hospital details.
- **Reporting**: Comprehensive database system for tracking sales and inventory history.

## 🛠️ Technical Stack

- **Frontend**: Python Tkinter (GUI)
- **Backend**: Python
- **Database**: MySQL

## 📋 Prerequisites

- Python 3.x
- MySQL Server

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone <repository-url>
cd MediTrack
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Database Configuration
1. Open your MySQL terminal or workbench.
2. Execute the SQL script located at `database/schema.sql` to create the `pharmacy` database and required tables.
3. Update the database connection settings in `src/main.py`:
   ```python
   db = mysql.connector.connect(
       host="localhost",
       user="root",
       passwd="YOUR_PASSWORD",
       database="pharmacy"
   )
   ```

## 🏃 How to Run
Navigate to the root directory and run:
```bash
python src/main.py
```

## 📂 Project Structure

- `src/`: Contains the application source code.
  - `main.py`: The entry point of the application.
  - `assets/`: Images and icons used in the GUI.
- `database/`: Database schema and initialization scripts.
- `docs/`: Project documentation, including ER diagrams and reports.
- `requirements.txt`: List of Python dependencies.

## 📄 Documentation
Detailed project reports and diagrams can be found in the `docs/` directory:
- [Database System Report](./docs/Database%20System%20Report.docx)
- [Pharmacy Management System PDF](./docs/Pharmacy%20Management%20System.pdf)
- [ER Diagram](./docs/ER.png)

## ⚖️ License
This project is licensed under the MIT License - see the LICENSE file for details.
