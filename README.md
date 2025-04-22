# 🎬 Cine Go - Movie Ticket Booking System

**Cine Go** is a web-based movie ticket booking application inspired by platforms like BookMyShow. It allows users to browse movies, view showtimes, and book tickets online. Admins can manage movies, theaters, and schedules.

## 🚀 Features

### 👤 User Functionality
- User registration and login
- Browse movies and showtimes
- Book tickets and view bookings
- User-friendly interface with responsive design

### 🔧 Admin Functionality
- Secure admin login
- Add/Edit/Delete movies and shows
- Manage theaters and seat availability
- View all bookings

## 🛠️ Tech Stack

| Layer         | Technology Used      |
|---------------|----------------------|
| Backend       | Python, Flask        |
| Database      | SQLite, SQLAlchemy   |
| Frontend      | HTML, CSS, Bootstrap |
| Templating    | Jinja2               |
| IDE           | Visual Studio Code   |

## 🗃️ Database Schema

- **User Table**: `id`, `name`, `email`, `password`
- **Movie Table**: `id`, `title`, `genre`, `duration`, `description`
- **Theater Table**: `id`, `name`, `location`
- **Show Table**: `id`, `movie_id`, `theater_id`, `show_time`
- **Booking Table**: `id`, `user_id`, `show_id`, `seats_booked`

## 🧪 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/cine-go.git
   cd cine-go
   ```

2. **Create and Activate Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask App**
   ```bash
   python app.py
   ```

5. **Visit in Browser**
   ```
   http://localhost:5000
   ```

## 📁 Folder Structure

```
cine-go/
│
├── static/             # CSS, images
├── templates/          # Jinja2 templates
├── app.py              # Main Flask app
├── models.py           # SQLAlchemy models
├── requirements.txt    # Python dependencies
└── README.md
```
