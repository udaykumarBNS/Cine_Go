# 🎬 Movie Tickets Booking App

A Flask-based web application for booking movie tickets, managing venues/shows (admin), and browsing upcoming shows (user).

## 🚀 Features

### **User Side**
- ✅ Sign up / Login (Role-based: User vs Admin)
- ✅ Browse shows by venue/location
- ✅ Book tickets (with seat availability check)
- ✅ View booking history

### **Admin Side**
- ✅ Add/Edit/Delete Theatres
- ✅ Add/Edit/Delete Shows
- ✅ View summary analytics (capacity charts)

## 🛠️ Tech Stack
- **Backend**: Python (Flask, Flask-SQLAlchemy, Flask-RESTful)
- **Frontend**: Bootstrap 5, HTML/CSS
- **Database**: SQLite (with migrations via Flask-Migrate)
- **Visualization**: Matplotlib (for admin charts)

## ⚙️ Setup

### Prerequisites
- Python 3.8+
- Pipenv (recommended)

### Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/udaykumarBNS/Cine_Go.git
   cd Cine_Go