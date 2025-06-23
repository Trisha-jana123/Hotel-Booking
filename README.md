# 🏨 Hotel Booking Platform

A full-featured hotel booking web application built with **Django**, **SQLite**, and **Bootstrap**. This project allows users to register, search for hotels, book rooms, and manage their reservations through a clean and responsive UI.

## 🚀 Features

- ✅ User authentication (Sign up, Login, Logout)
- 🔍 Real-time hotel and room search
- 🗓️ Room booking and reservation management
- 📄 Booking history and user dashboard
- 📱 Responsive frontend using Bootstrap
- 🛡️ Session handling and basic security features

## 🛠️ Tech Stack

- **Backend**: Django (Python)
- **Frontend**: HTML5, CSS3, Bootstrap
- **Database**: SQLite
- **Templating Engine**: Django Templates

## 🧑‍💻 How to Run Locally

```bash
git clone https://github.com/yourusername/hotel-booking-platform.git
cd hotel-booking-platform
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` to access the app.

## 📸 Screenshots

### 🔐 Welcome / Login Page
![Welcome](images/welcome.png)

### 🏨 Hotel Listings Page
![Hotel List](images/hotel-list.png)

### 🛏️ Hotel Detail & Room Options
![Hotel Detail](images/hotel-detail.png)

### 🧾 Booking Form Page
![Booking Form](images/booking-form.png)

## 📝 Future Improvements

- Payment gateway integration
- Admin panel for hotel/room management
- Email booking confirmations
- Booking cancellation/modification logic

## 📂 Folder Structure

```
hotel_booking_platform/
├── bookings/            # App for booking logic
├── users/               # User authentication and profile
├── templates/           # HTML templates
├── static/              # CSS, JS, and image files
├── db.sqlite3           # Database file
└── manage.py
```

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📄 License

This project is open source and available under the MIT License.
