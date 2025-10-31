# 🚀 Quick Start Guide - Art Class Attendance System

## First Time Setup

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Run the Application
```bash
python artclassatt.py
```

The application will:
- Create the database automatically
- Start in maximized window mode
- Open on the Dashboard tab

## 📋 Daily Workflow

### Morning Routine
1. **Open Dashboard** - Check today's statistics
2. **Go to Attendance Tab** - Mark students as they arrive
3. **Quick Entry**: Type roll number → Press Enter

### Adding New Students
1. **Go to Students Tab**
2. **Fill in the form** (left panel):
   - Roll Number (unique)
   - Name
   - Phone (10 digits)
   - Email
   - Course Fees
   - Fees Paid
   - Dates (DD/MM/YYYY format)
3. **Click "Add Student"**

### Marking Attendance
**Method 1: Attendance Tab (Recommended)**
1. Go to "✓ Attendance" tab
2. Enter roll number
3. Press Enter or click "Mark Present"
4. See live update in the list below

**Method 2: Students Tab**
1. Go to "👥 Students" tab
2. Use "Quick Attendance" section
3. Enter roll number and press Enter

### Recording Fee Payments
**Method 1: Fees Tab**
1. Go to "💰 Fees" tab
2. Double-click on student with pending fees
3. Enter payment details
4. Click "Record Payment"

**Method 2: Students Tab**
1. Go to "👥 Students" tab
2. Click "View Students"
3. Select a student from the list
4. Click "Fees Management"
5. Enter payment and submit

## 🎯 Common Tasks

### Search for a Student
1. Go to Students tab
2. Type in search box (Roll No/Name/Phone)
3. Click "Search" or press Enter
4. Click "🔄 Refresh" to see all students again

### Generate Reports
1. Go to "📈 Reports" tab
2. Choose report type:
   - **Monthly Report**: Attendance statistics
   - **Expiring Courses**: Students ending soon
   - **Financial Report**: Fees analysis
3. Click "Generate Report"

### Export Data
**Students List:**
1. Students tab → "📤 Export to CSV"

**Payment History:**
1. Open Fees Management for a student
2. Click "View All Payments"
3. Click "Export to CSV"

**Monthly Report:**
1. Generate Monthly Report
2. Click "Export to CSV"

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+A` | View Today's Attendance |
| `Ctrl+R` | Generate Monthly Report |
| `Ctrl+F` | Focus Search Bar |
| `Enter` | Submit current form |

## 💡 Pro Tips

### 1. **Use Tabs Efficiently**
- Dashboard: Quick overview
- Students: Add/manage students
- Attendance: Daily marking
- Reports: Analysis
- Fees: Payment tracking

### 2. **Quick Attendance Marking**
- Keep Attendance tab open during class
- Just type roll number and press Enter
- No need to click buttons

### 3. **Double-Click Features**
- Double-click student → View profile
- Double-click in fees list → Open payment

### 4. **Status Bar**
- Bottom left: Last action performed
- Bottom right: Current date/time

### 5. **Color Codes**
- 🟢 Green: Active/Paid/Success
- 🟡 Yellow: Warning/Expiring soon
- 🔴 Red: Expired/Pending/Error

## 🔧 Troubleshooting

### Student Already Exists
- Each roll number must be unique
- Use search to find existing student

### Attendance Already Marked
- Can only mark once per day
- Check "Today's Attendance" to verify

### Date Format Error
- Use DD/MM/YYYY format
- Example: 15/10/2025

### Email Not Sending
- Email is disabled by default
- Configure in code if needed
- Payments still work without email

## 📊 Understanding the Dashboard

### Statistics Cards
1. **Total Students**: All registered students
2. **Today's Attendance**: Students present today
3. **Active Courses**: Courses not yet ended
4. **Pending Fees**: Total amount due

### Recent Activity
- Shows last 10 attendance records
- Updates automatically
- Most recent at top

## 💰 Payment Methods

Available options:
- Cash
- Credit Card
- Bank Transfer
- UPI
- Cheque

Select appropriate method when recording payment.

## 📅 Date Formats

**Input Format**: DD/MM/YYYY
- Example: 25/12/2025

**Display Format**: YYYY-MM-DD
- Stored in database
- Shown in reports

## 🎨 Taking Screenshots

For your README, capture:
1. **Dashboard** - Full window showing all stats
2. **Student List** - With some data populated
3. **Attendance Tab** - Showing today's list
4. **Fees Management** - Payment interface
5. **Financial Report** - Complete analysis

## 📞 Support

For issues or questions:
1. Check this guide first
2. Review ENHANCEMENTS.md for features
3. Check README.md for detailed info

---

**Happy Managing! 🎨**
