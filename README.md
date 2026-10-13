# VayuDrishti — Weather Intelligence Platform

A software platform developed for the **Smart India Hackathon (SIH)** to collect, analyze, and verify weather-related reports and provide useful insights about weather events across India.

## 🌦️ Overview

VayuDrishti aims to bring weather reports from multiple sources into one platform. It focuses on organizing public weather information, validating submitted reports, and presenting weather intelligence through a dashboard.

## ✨ Key Features

- **Weather Report Collection:** Supports weather reports from configured data sources.
- **Report Verification:** Includes verification modules for report credibility and location validation.
- **Duplicate Detection:** Helps identify potentially duplicated reports.
- **Location Validation:** Checks location-related information associated with reports.
- **Weather Data Ingestion:** Supports ingestion of weather information from configured sources.
- **Weather Dashboard:** A frontend interface for presenting weather information and insights.
- **Media Support:** Supports report submissions with optional photo or video files through the backend API.

## 🛠️ Technology Stack

**Frontend**
- React
- TypeScript
- Vite
- CSS

**Backend**
- Node.js
- Express (where configured)
- JavaScript

**Data and Analysis**
- Weather datasets
- Configured weather data sources
- Report verification and scoring modules

## 📁 Project Structure

```text
sih-weather-platform/
├── backend/       # Backend services and verification modules
├── public/        # Static assets
├── src/           # Frontend application
├── index.html
├── package.json
├── server.js
├── vite.config.ts
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed on your computer
- Git (optional, for cloning the repository)

### 1. Clone the repository

```bash
git clone https://github.com/Disha761/sih-weather-platform.git
cd sih-weather-platform
```

### 2. Install frontend dependencies

```bash
npm install
```

### 3. Install backend dependencies

```bash
cd backend
npm install
cd ..
```

### 4. Configure environment variables

Create a `.env` file inside the `backend/` directory if required by your configuration. Do not commit API keys, passwords, or other secrets to GitHub.

### 5. Run the application

Start the backend using the root script if available:

```bash
npm run start:backend
```

Alternatively, follow the backend scripts configured in `backend/package.json`.

Start the frontend in a separate terminal:

```bash
npm run dev
```

Open the local URL shown by Vite in your terminal.

> Note: The exact commands and required environment variables depend on the scripts and configuration in the repository.

## 📡 Report Submission API

The backend documentation describes a report submission endpoint:

`POST /api/reports`

It accepts multipart form data containing report details such as title, description, event category, city, state, coordinates, event time, and optional media files.

## 🎯 Project Goal

The goal of VayuDrishti is to support better organization and verification of weather-related reports, helping users explore weather events and relevant information through a unified platform.

## 👩‍💻 Developed For

**Smart India Hackathon (SIH)**

Developed by **Disha Joshi** and team.

## 📌 Project Status

Under development. Features and data-source integrations may evolve as development progresses.
