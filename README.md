AI Video Editor

Overview

AI Video Editor is a web application that provides powerful AI-driven tools for video editing. Users can upload videos and apply a range of features such as trimming, merging audio, applying filters, and generating subtitles, all powered by artificial intelligence.

Features

Trim Video: Crop videos to the desired length.

Merge Audio: Combine audio files with video seamlessly.

Apply Filters: Enhance your videos with AI-powered filters.

Generate Subtitles: Automatically generate accurate subtitles using AI.

Technologies Used

Front-End

HTML: Structure and layout of the web pages.

CSS: Styling and responsive design.

JavaScript: Dynamic content and interactivity.

Back-End

Java Spring Boot: Handles file uploads, processes video editing requests, and integrates AI functionalities.

Installation

Prerequisites

Java Development Kit (JDK)

Node.js (optional for serving front-end)

Spring Boot CLI

Steps

Clone the repository:

git clone https://github.com/username/ai-video-editor.git
cd ai-video-editor

Set up the back-end:

Navigate to the backend directory.

Run the Spring Boot application:

./mvnw spring-boot:run

The back-end server will start at http://localhost:8080.

Serve the front-end:

Open index.html in a browser or serve it using a local web server (e.g., Live Server in VS Code).

Usage

Open the application in your web browser.

Upload a video file using the Upload Your Video section.

Select the desired editing tool from the Editing Tools section.

The edited video will be processed and available for download.

API Endpoints

POST /process

Processes the uploaded video with the specified action.

Request Parameters:

file: The video file to process (multipart form-data).

action: The editing action to perform (trim, merge, filter, subtitles).

Response:

200 OK: Operation succeeded.

400 Bad Request: Invalid input or parameters.

Contributing

Fork the repository.

Create a new branch for your feature:

git checkout -b feature-name

Commit your changes and push to your fork.

Create a pull request.

License

This project is licensed under the MIT License.

Contact

For support or inquiries, contact us at: support@aivideoeditor.com

