# CytoSight: AI-Powered ALL Detection

## Project info

CytoSight is a web-based, proof-of-concept computer-aided diagnosis (CAD) system designed to automate the detection of Acute Lymphoblastic Leukaemia (ALL) from blood smear images. This project leverages a state-of-the-art deep learning model to provide rapid and accurate classifications, presented through a modern and intuitive user interface.

**URL**: https://github.com/kwansinnn/cytosight.git

## Key Features

Dual-Model Ensemble: Utilizes two specialized ConvNeXt V2 models—one for single-cell and one for multi-cell images—ensembled for a robust final prediction.

User Authentication: Secure user registration and login handled by Supabase.

Interactive Dashboard: A user-friendly interface for uploading images, viewing analysis results, and managing your profile.

Analysis History & Reporting: Persistently stores analysis results and allows for the generation of custom reports.

Collaboration Tools: A dedicated space for teams to create discussion threads around specific cases.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

## What technologies are used for this project?

### Frontend

Framework: React with TypeScript

Build Tool: Vite

Styling: Tailwind CSS & shadcn/ui

Backend-as-a-Service: Supabase

### Backend (Model Training)

Framework: PyTorch

Language: Python

Environment: Google Colab

Core Model: ConvNeXt V2
