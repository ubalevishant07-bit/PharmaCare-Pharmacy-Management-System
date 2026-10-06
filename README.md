# PharmaCare - Pharmacy Management System

A student-friendly Pharmacy Management System with Admin/Pharmacist, Doctor, and Patient portals.

## New Features in this version

### Patient
- Purchase medicines directly from the Patient portal
- Medicine availability and stock shown before purchase
- Stock automatically decreases after purchase
- Purchase ID and total amount generated
- Purchase appears in Pharmacist/Admin Sales
- Purchase history
- Total purchases and total spending on dashboard

### Doctor
- New Doctor Registration
- Registered doctor can log in using the created password
- Doctor dashboard with patients, consultations, prescriptions, upcoming consultations, and pending requests

### Admin / Pharmacist
- Medicine management
- Inventory and stock alerts
- Billing
- Sales & Patient Purchases
- Patient purchases are clearly marked in Sales
- Dashboard statistics for today's sales, low stock, expiry alerts, purchasing patients, and units sold

## Project Structure

```text
PharmaCare-Pharmacy-Management-System/
│
├── frontend/
│   └── index.html
│
├── backend/
│   └── Put your existing C++ backend files here
│
├── data/
│   └── Put your existing data files here
│
├── .gitignore
└── README.md
```

## Frontend Demo Login

### Admin / Pharmacist
Username:
`pharmacare`

Password:
`pharmacare@123`

### Existing Doctors
- `Dr. Rahul Sharma` / `Dr. Rahul Sharma@123`
- `Dr. Priya Mehta` / `Dr. Priya Mehta@123`
- `Dr. Amit Patil` / `Dr. Amit Patil@123`

### New Doctor
Use **New Doctor Registration** on the login page to create a new doctor account.

### Patient
For a demo patient, enter any username and use:
`username@123`

Example:
Username: `Vishant`
Password: `Vishant@123`

## Run in VS Code

1. Extract the ZIP.
2. Open the extracted folder in VS Code.
3. Open `frontend/index.html`.
4. Right-click and open with Live Server, or run:

```powershell
start .\frontend\index.html
```

## GitHub Repository

After testing:

```powershell
git init
git add .
git commit -m "Initial PharmaCare upgrade"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## Note

The current browser frontend uses LocalStorage for the portal data. The backend folder is kept ready for the existing C++ backend files and future integration.
