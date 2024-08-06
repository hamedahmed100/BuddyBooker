# BuddyBooker

BuddyBooker is a web application designed to make scheduling appointments between two people simple and intuitive. Whether it's for a meeting, a catch-up with a friend, or a collaboration between colleagues, BuddyBooker has you covered!

## Features

- **Simple Appointment Setup**: Easily create and manage appointments between two users.
- **Calendar View**: Visualize all your scheduled appointments in a user-friendly calendar.
- **Notifications**: Get notified about upcoming appointments.
- **Responsive Design**: Accessible on both desktop and mobile devices.
- **User Authentication**: Secure login and registration system.
- **Customizable Themes**: Choose between different themes to suit your style.

## Installation

### Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine.
- Angular CLI installed globally: 
  ```bash
  npm install -g @angular/cli
  ```

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/hamedahmed100/buddybooker.git
    cd buddybooker
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Run the application:**

    ```bash
    ng serve
    ```

    Open your browser and navigate to `http://localhost:4200/`.

## Usage

1. **Sign Up / Login:** 
   Create an account or log in with your credentials.
   
2. **Create an Appointment:** 
   Click on "New Appointment", select a date, time, and invite a buddy.
   
3. **View Appointments:** 
   Navigate to the "My Calendar" page to see all your scheduled appointments.

4. **Edit or Cancel Appointments:**
   Click on an existing appointment to edit or cancel it.

## Technologies

- **Frontend**: Angular, TypeScript, HTML5, CSS3, SCSS
- **Backend**: (to be decided - e.g., Node.js/Express, Firebase)
- **Database**: (to be decided - e.g., MongoDB, Firebase Firestore)
- **Authentication**: (to be decided - e.g., JWT, Firebase Authentication)
- **Calendar Integration**: FullCalendar.js or Angular Calendar

## Folder Structure

```
buddybooker/
│
├── src/
│   ├── app/
│   │   ├── components/       # Reusable components
│   │   ├── services/         # Services for API calls and data handling
│   │   ├── models/           # Data models
│   │   ├── pages/            # Pages of the app (Home, Login, Calendar, etc.)
│   │   ├── app.module.ts     # Main module file
│   │   ├── app.component.ts  # Main component file
│   └── assets/               # Static assets (images, styles, etc.)
│
├── angular.json              # Angular CLI configuration
├── package.json              # Node.js dependencies and scripts
├── README.md                 # Project documentation
└── tsconfig.json             # TypeScript configuration
```

## Contributing

Contributions are always welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Created by [Your Name](https://github.com/yourusername) - feel free to contact me!

---

Feel free to modify the content as per your project's specifics, such as the backend technology stack, demo link, and your contact information.
