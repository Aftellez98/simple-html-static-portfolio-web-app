# Simple Static Web App

## Overview

This application is a test project aimed at exploring the capabilities of HTML and demonstrating how to create a very simple static web app for a portfolio. The entire application is composed of a single `index.html` file, showcasing the basics of HTML structure and content.

## Features

- **Single Page Application**: The entire app is contained within a single `index.html` file.
- **Static Content**: Displays static content suitable for a portfolio.
- **Easy Deployment**: Designed for easy deployment on Amazon S3.

## Getting Started

To set up and run this app, follow the steps below:

1. **Clone the Repository** (if applicable):
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Open the HTML File**:
   - Open `index.html` in any web browser to view the web app.

## Deployment on Amazon S3

To deploy this static web app on Amazon S3, follow these steps:

1. **Create an S3 Bucket**:
   - Go to the AWS S3 Console.
   - Click on "Create bucket".
   - Enter a unique bucket name and choose a region.
   - Set the bucket to be publicly accessible (for a public portfolio).

2. **Upload `index.html`**:
   - Click on the created bucket.
   - Click on "Upload" and select your `index.html` file.
   - Set the permissions to allow public access.

3. **Configure Static Website Hosting**:
   - Go to the "Properties" tab of your bucket.
   - Enable "Static website hosting".
   - Set the index document to `index.html`.

4. **Access Your Web App**:
   - After configuration, you will be provided with a URL to access your static web app.

## Conclusion

This project serves as a simple demonstration of how HTML can be utilized to create a basic portfolio web app. By
