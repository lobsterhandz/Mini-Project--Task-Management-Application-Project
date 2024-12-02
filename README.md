# Task Management Application

## Overview
The Task Management Application is a user-friendly tool that allows users to effectively manage tasks and boost productivity. This project utilizes Bootstrap to create a responsive, visually appealing interface. It consists of multiple pages including a home page, task dashboard, task creation page, and user authentication pages.

## Features
- **Home Page**: Welcome users with a Jumbotron, a Carousel showcasing key features, and cards detailing the app's main functionalities.
- **Task Dashboard**: View all your tasks and manage them easily using Bootstrap cards.
- **Task Creation Page**: Add new tasks through a form with Bootstrap styling.
- **Authentication Pages**: Register and login to manage your tasks securely.
- **Responsive Design**: The entire application uses Bootstrap's grid system for a mobile-first, responsive layout.

## Project Structure
```
project/
├── css/
│   └── custom.css       # Custom styles
├── img/
│   ├── featured1.jpg    # Images for carousel
│   ├── featured2.jpg
│   └── featured3.jpg
├── pages/
│   ├── index.html       # Home page
│   ├── dashboard.html   # Task dashboard page
│   ├── create-task.html # Create new task page
│   ├── register.html    # User registration page
│   └── login.html       # User login page
└── README.md            # Project documentation
```

## How to Run the Application
1. Clone the repository to your local machine.
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project folder.
   ```sh
   cd project
   ```
3. Open the `pages/index.html` file in your preferred browser.

## Technologies Used
- **HTML5**: Structure the pages of the application.
- **CSS3**: Styling of the application, including custom styles in `custom.css`.
- **Bootstrap 5**: Used for responsive layout, forms, navigation, buttons, and more.
- **JavaScript (Bootstrap JS)**: Added interactivity for the carousel and navigation.

## Pages Description
1. **Home Page (`index.html`)**:
   - Includes a Jumbotron to welcome users and a "Get Started" button leading to the Task Dashboard.
   - A Bootstrap carousel displays key features of the application.
   - Cards explain the app's main functionalities: managing tasks, tracking progress, and collaborating.

2. **Task Dashboard (`dashboard.html`)**:
   - Provides a list of tasks organized using Bootstrap cards.
   - The tasks can be edited or deleted (future versions may include backend integration).

3. **Task Creation Page (`create-task.html`)**:
   - Allows users to add a new task with details such as title, description, and due date.

4. **Register (`register.html`) and Login (`login.html`) Pages**:
   - Bootstrap forms for user registration and authentication.
   - Form validation for ensuring input correctness.

## Customization
- **CSS Customization**: You can modify `css/custom.css` to add or override styles according to your needs.
- **Images**: Replace the images in the `img` directory to customize the carousel with your own images.
- **Content**: Update the text content in the HTML files to fit your specific use case.

## Future Enhancements
- **Backend Integration**: Add a server-side component (e.g., Node.js, Django) to persist user data and tasks.
- **Database Support**: Integrate with a database like MySQL to store tasks, users, and more.
- **Authentication**: Secure login and register functionality with proper backend handling.

## Contributing
Feel free to fork the project and submit pull requests. Any suggestions or improvements are highly welcome.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contact
For any questions or support, feel free to reach out:
- **Email**: support@example.com
- **GitHub**: [YourGitHubProfile](https://github.com/YourGitHubProfile)

