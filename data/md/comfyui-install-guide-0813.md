title: "Installing ComfyUI: A Beginner's Guide"
description: "A step-by-step tutorial to install ComfyUI, a modern UI library, on your local machine."
date: "2024-08-13"

# Installing ComfyUI: A Beginner's Guide

This guide will lead you through the process of installing ComfyUI on your local machine. Whether you're a web development novice or a seasoned pro, these instructions will help you get ComfyUI up and running in no time.

## Prerequisites

- Node.js (version 14 or later)
- npm (usually comes with Node.js)
- Git
- A GitHub account (optional, for contributing to the project)

## Step 1: Clone the Repository

Open your terminal or command prompt.

Navigate to the directory where you want to store your project.

Run the following command:

```bash
git clone https://github.com/comfyui/comfyui.git
cd comfyui
```

## Step 2: Install Dependencies
In the project directory, run:

```bash
npm install
This command will install all necessary dependencies for ComfyUI.
```

## Step 3: Set Up Environment Variables
In the root of your project, create a file named .env.

Open this file and add the following line (customize as needed):

```plaintext
REACT_APP_CUSTOM_VAR=your_custom_value
```

## Step 4: Run the Development Server
To start the development server, run:

```bash
npm start
Open http://localhost:3000 in your browser. You should see the ComfyUI homepage.
```

## Step 5: Build the Project
If the development server runs without errors, build the project for production:

```bash
npm run build
```

## Step 6: Test the Build
Run the production build locally:

```bash
npm run serve
```
This will serve the production build on a local server, and you can verify everything is working as expected.



## Step 7: Deploy to GitHub Pages (Optional)
If you have a GitHub account and want to deploy your project:

Build the project as described in Step 5.
Deploy it to GitHub Pages using the following command:
```bash
npm run deploy
```

## Step 8: Usage
Once ComfyUI is installed, you can start using it in your React projects. Import components and use them as needed.

Troubleshooting
If you encounter any issues:

Double-check that all environment variables are correctly set.
Look at the console in your browser for any error messages.
Ensure your Node.js and npm versions are up to date.
Congratulations! You've successfully installed ComfyUI. Enjoy building modern UIs with ease!

For more help, refer to the ComfyUI documentation or join the community on GitHub.