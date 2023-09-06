# Website Summary Generator

![Screenshot from 2023-09-06 22-00-49](https://github.com/GautamGulati28/reactjs-website-summarizer/assets/101964337/c08226a3-bf81-4ab6-9fde-29306c0456c6)


## Overview

Website Summary Generator is a web application built using React (with Vite), Redux, and Tailwind CSS. It leverages the Rapid API to extract and display a summary for any given website. This project aims to provide users with a quick and concise overview of web content by analyzing the text and extracting key information.

## Features

- **Website URL Input**: Users can enter the URL of any website they want to summarize.
- **Website Summary**: The application extracts relevant information from the provided URL and presents it in a structured format.
- **Responsive Design**: The user interface is designed to work seamlessly on both desktop and mobile devices.

## Technologies Used

- **React with Vite**: The project is built on the React framework using Vite for fast development and optimized builds.
- **Redux**: Redux is used for state management, ensuring a predictable and centralized state.
- **Tailwind CSS**: Tailwind CSS is used for styling the application, allowing for rapid development and customization.
- **Rapid API**: Rapid API is used to fetch and analyze the content of the provided website.

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/GautamGulati28/reactjs-website-summarizer
   ```

2. Navigate to the project directory:

3. Install the project dependencies:

   ```
   npm install
   ```

4. Obtain your Rapid API key and configure it in the project. You can do this by creating a `.env` file in the project root directory and adding your API key as follows:

   ```
   VITE_RAPID_API_ARTICLE_KEY=your-api-key
   ```

5. Start the development server:

   ```
   npm run dev
   ```

6. Open your web browser and visit `http://localhost:5173/` to use the Website Summary Generator.

## Usage

1. Enter the URL of the website you want to summarize in the provided input field.

2. Click the "Generate Summary" button.

3. The application will fetch and analyze the content from the provided website and display a summary.

4. You can reset the input field and generate summaries for other websites as needed.
