# Building Doctor - Premium Tutorial Website

A premium tutorial website for "Building Doctor", a building treatment company. Built with HTML, Tailwind CSS, and vanilla JavaScript.

## Project Structure

- `index.html`: Main homepage with hero section and tutorial cards.
- `tutorial[1-7].html`: Individual video tutorial pages.
- `/images`: Contains website images (e.g., `home-pic1.jpeg`).
- `/videos`: Contains video tutorials (`vid1.mp4` - `vid7.mp4`).
- `/downloads`: Contains PDF resources.

## Setup Instructions

1.  Clone the repository.
2.  Ensure all assets are in their respective folders:
    -   Content images in `/images`
    -   Video files in `/videos`
    -   PDFs in `/downloads`
3.  Open `index.html` in your browser or use a local server (e.g., Live Server in VS Code).

## Deployment

 This site is ready for deployment on Vercel.
 
 ## Deployment Guide
 
 ### Option 1: Vercel (Recommended)
 
 1.  Push your code to a GitHub repository.
 2.  Go to [Vercel](https://vercel.com) and sign up/log in.
 3.  Click **"Add New..."** > **"Project"**.
 4.  Import your GitHub repository: `your-repo-name`.
 5.  **Build Settings**: Leave everything as default.
     -   Framework Preset: `Other`
     -   Build Command: (Leave empty)
     -   Output Directory: (Leave empty)
 6.  Click **Deploy**.
 
 ### Option 2: Netlify
 
 1.  Push your code to GitHub.
 2.  Go to [Netlify](https://netlify.com) and sign up/log in.
 3.  Click **"Add new site"** > **"Import an existing project"**.
 4.  Connect to GitHub and select your repository.
 5.  **Build Settings**: Leave everything as default.
     -   Base directory: (Leave empty)
     -   Build command: (Leave empty)
     -   Publish directory: (Leave empty or `.` if required)
 6.  Click **Deploy site**.
 
 ## Github Push Guide
 
 If you haven't pushed your code to GitHub yet, follow these steps:
 
 1.  Create a **new repository** on GitHub (do not initialize with README, .gitignore, or License).
 2.  Run the following commands in your project terminal:
 
 ```bash
 git branch -M main
 git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
 git push -u origin main
 ```
 
 Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your actual GitHub details.
