# Brainware University Attendance System

A modern, web-based attendance management system designed specifically for Brainware University. This system provides an efficient way to manage student attendance across different sections and subjects.

## 🚀 Features

### For Administrators
- User management (add/delete users)
- Section management (add/delete sections)
- Student management (add/delete students with unique student codes)
- Subject management (add/delete subjects)
- Complete data overview dashboard

### For Teachers
- Mark attendance for specific dates
- View attendance history
- Export attendance data to CSV
- Visual analytics and reports
- Track attendance rates and patterns

### For Students
- View personal attendance records
- Check attendance percentage by subject
- Real-time attendance status

## 💻 Technologies Used

- **Frontend Framework**: HTML5, TailwindCSS
- **Programming Language**: JavaScript (ES6+)
- **Data Visualization**: Chart.js
- **Storage**: Browser LocalStorage
- **UI Components**: Custom TailwindCSS components
- **Icons/Styling**: TailwindCSS utility classes

## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Open the project folder:
   ```bash
   cd brainware-attendance-system
   ```

3. Since this is a static website, you can open it using any web server. For example, using Python:
   ```bash
   # For Python 3.x
   python -m http.server 8000
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## 📱 How to Use

### Initial Setup (Admin)
1. Create an admin account using the signup form
2. Log in as admin
3. Add sections (e.g., "CS 2023 Batch")
4. Add subjects for each section
5. Add students with unique student codes

### For Teachers
1. Log in using teacher credentials
2. Select the date, section, and subject
3. Mark attendance for students
4. View attendance history
5. Export attendance data when needed
6. Check analytics dashboard for insights

### For Students
1. Log in using student credentials
2. View attendance records
3. Check attendance percentage by subject

## 🔐 Security Features

- Role-based access control
- Unique student codes
- Password-protected accounts
- Session management
- Data validation and sanitization

## 📊 Data Management

### Data Structure
- Students: name, code, section
- Sections: name, associated subjects
- Subjects: name, associated section
- Attendance: date, section, subject, present students

### Data Operations
- Create, Read, Update, Delete (CRUD) operations
- Data export functionality
- Attendance analytics
- Historical data tracking

## ⚠️ Important Notes

1. **Local Storage**: 
   - Data is stored in browser's localStorage
   - Clear browser data will reset the system
   - For production, implement proper backend storage

2. **Browser Compatibility**:
   - Works best on modern browsers
   - Requires JavaScript enabled
   - Responsive design for all devices

## 🔄 Future Improvements

1. **Backend Integration**:
   - Implement proper database storage
   - Add API endpoints
   - Enable multi-device sync

2. **Additional Features**:
   - Email notifications
   - Automated attendance reports
   - Mobile app integration
   - Biometric attendance
   - Leave management

3. **Security Enhancements**:
   - Implement proper authentication
   - Add password hashing
   - Enable 2FA
   - Add audit logs

## 👥 User Roles

### Administrator
- Full system access
- User management
- System configuration
- Data management

### Teacher
- Attendance management
- Report generation
- Analytics access
- Student data view

### Student
- Personal attendance view
- Subject-wise reports
- Attendance statistics

## 💡 Best Practices

1. **Regular Backups**:
   - Export attendance data regularly
   - Keep backup of student records

2. **Data Entry**:
   - Verify student codes before entry
   - Double-check attendance marks
   - Use proper naming conventions

3. **System Usage**:
   - Regular password updates
   - Log out after each session
   - Verify data before deletion

## 📞 Support

For any queries or support, please contact:
- System Administrator
- Technical Support Team
- Department Coordinator

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Developed with ❤️ for Brainware University 