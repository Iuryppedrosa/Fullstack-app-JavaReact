# User Management App
![ListUsers](https://private-user-images.githubusercontent.com/89420889/322011202-654a24a5-275e-4bbe-a2df-43878197bf6c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMDg2NzcsIm5iZiI6MTcxMzMwODM3NywicGF0aCI6Ii84OTQyMDg4OS8zMjIwMTEyMDItNjU0YTI0YTUtMjc1ZS00YmJlLWEyZGYtNDM4NzgxOTdiZjZjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE2VDIyNTkzN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg2YjE5MTEwYTFmMjllZWUyN2FkNWUzMWQzZTg0N2VkZjEwMWJlNGVkZGQxYzYwM2IyYzVmNGQ0MmE1Yjk5ZTMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0._T0qwQ-P340KkmEb-w2ywrQvTd0QEdqiKOndirz7OEA)

![EdiUsers](https://private-user-images.githubusercontent.com/89420889/322011212-f41ec614-e82f-47a6-bb2e-928f48e0c5ec.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMDg2NzcsIm5iZiI6MTcxMzMwODM3NywicGF0aCI6Ii84OTQyMDg4OS8zMjIwMTEyMTItZjQxZWM2MTQtZTgyZi00N2E2LWJiMmUtOTI4ZjQ4ZTBjNWVjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE2VDIyNTkzN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWQ5ZThlMDk4NWZjN2E5MzA2Y2EyMDUzZjc4OGUxZDAwN2Q5NjQzZjc3MDRlZjc1MGM1NmY1YmUzYmRlNDY4NWYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.iNFtJa4uvM-Zx85Al6T9hhJy-Z6EIk4ru_ZPuEme-_U)


A user-friendly application built with React for the frontend, Java Spring for the backend, and MySQL for data storage. Easily manage users by adding, editing, viewing, or deleting their profiles.

## Features

- **Add User:** Quickly add users by entering their email, name, and username.
- **Edit User:** Modify user details effortlessly.
- ![CodeFolders](https://private-user-images.githubusercontent.com/89420889/322011217-87e7526c-3a2a-4cba-a8e4-c4aae5c9c642.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMDg2NzcsIm5iZiI6MTcxMzMwODM3NywicGF0aCI6Ii84OTQyMDg4OS8zMjIwMTEyMTctODdlNzUyNmMtM2EyYS00Y2JhLWE4ZTQtYzRhYWU1YzljNjQyLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE2VDIyNTkzN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTZjNDY1MWEzNDJiNzA2OTU5YmFlODVkMGU4ZTE4OTllN2E0N2M5OTZhYjg5ZTZjYzIxZTI1MDI2M2ZmZTlhYWYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.8B5wC4WrI228AR5O92347JbUx6rr8dI7gkieS3Tw9tg)
- **View User:** View user profiles in detail.
- **Delete User:** Remove users from the database with a single click.

## Installation

### Prerequisites

Ensure you have Node.js and Java installed on your machine before proceeding.

### Steps

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/user-management-app.git
## Navigate to the project directory and install dependencies:
cd user-management-app/frontend && npm install
cd ../backend && ./mvnw install

3. Start the React development server:
npm start

4. Start the Spring Boot application:
./mvnw spring-boot:run 

5. The application will be running on http://localhost:3000 for the frontend and http://localhost:8080 for the backend.

## Usage
The intuitive interface allows you to:
Add Users: Click the ‘Add User’ button and fill in their email, name, and username.
View Users: Explore user profiles in detail.
Edit Users: Modify user information.
Delete Users: Remove users from the database.

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
License
MIT

Feel free to replace the placeholders with actual links, descriptions, and specific instructions relevant to your project. If you have any additional features or customizations, make sure to include them in the README as well! 😊
![outraimagem](https://private-user-images.githubusercontent.com/89420889/322011215-6566a5b9-e162-4694-8696-3105a53d1786.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MTMzMDg2NzcsIm5iZiI6MTcxMzMwODM3NywicGF0aCI6Ii84OTQyMDg4OS8zMjIwMTEyMTUtNjU2NmE1YjktZTE2Mi00Njk0LTg2OTYtMzEwNWE1M2QxNzg2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA0MTYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNDE2VDIyNTkzN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTI2YzhkYjg5ODRmMjRlMTczMTAwMTVhYTJlZGM3OTE5Y2Q0YTg2M2RlZTllMTBkYjc3MTYzNzY3MmVkZGViZDMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.g7yJy6TXpSSHZFNW4OF4AWWjoOVveldGEp_nFLe9Nf0)
## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
