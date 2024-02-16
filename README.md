# COVID-19 Hospital Bed Management System

This project is a COVID-19 Hospital Bed Management System developed using Flask, SQLAlchemy, and Flask-Login. It helps in managing hospital bed reservations and patient information efficiently during the COVID-19 pandemic.

## Features

- **User Authentication:** Users can sign up, login, and logout securely.
- **User Roles:** Two types of users are supported: normal users and hospital users.
- **Hospital Data Management:** Hospital administrators can add and update hospital information such as available beds.
- **Bed Booking:** Users can book beds based on their requirements (normal, HICU, ICU, or ventilator beds).
- **Patient Details:** Users can view their booked bed details including patient name, contact information, and bed type.
- **Discharge Management:** Hospital administrators can mark patients as discharged, which updates the bed count accordingly.

## Setup and Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Set up a MySQL database named `coviddbms` locally.
4. Update the database connection URI in `app.py` with your local MySQL configuration.
5. Run the Flask application using `python app.py`.

## Usage

- Navigate to `http://localhost:5000/` in your web browser to access the application.
- Sign up as a user or login as an existing user.
- Hospital administrators can log in using the provided credentials.
- Add/update hospital information and manage bed bookings accordingly.
- Users can book beds based on their requirements and view their booking details.
- Hospital administrators can mark patients as discharged when necessary.

## Contributing

Contributions to improve and enhance this project are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
