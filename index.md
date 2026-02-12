---
layout: "default"
title: "🎵 rokola_ia - Stream Your Music Collection Effortlessly"
description: "🎵 Explore Rokola-IA, a curated digital archive for preserving and accessing cultural music records, fostering education and research without commercial intent."
---
# 🎵 rokola_ia - Stream Your Music Collection Effortlessly

## 🔗 Download Now
[![Download rokola_ia](https://img.shields.io/badge/Download-rokola_ia-brightgreen.svg)](https://github.com/Kakuen9201/rokola_ia/releases)

## 📖 Overview
rokola_ia is a personal music library system designed to turn your raw MP3 collection in Google Drive into a structured and enriched streaming platform. It uses an automated ingestion pipeline with n8n and PostgreSQL in Docker to apply cultural curation and enhance metadata. Enjoy seamless access to your music collection with enriched data thanks to Last.fm API.

## 🚀 Getting Started
Follow these steps to download and run rokola_ia:

### 1. Visit the Download Page
Go to the following link to access the releases page:  
[Download rokola_ia](https://github.com/Kakuen9201/rokola_ia/releases)

### 2. Choose the Latest Release
On the releases page, look for the latest version at the top. You will find the version number and release notes. It is advisable to download the most recent version to ensure you have the latest features and fixes.

### 3. Download the Application
Click on the appropriate file for your operating system to download the application. The file may be a .exe for Windows, a .dmg for macOS, or a .tar.gz for Linux. The application is wrapped in a Docker container that makes installation easy.

### 4. Install Docker (If Not Already Installed)
If you don’t have Docker installed, you’ll need it to run rokola_ia. Here’s how to do it:
- **For Windows or macOS:**  
  1. Visit the [Docker website](https://www.docker.com/products/docker-desktop) to download Docker Desktop.
  2. Follow the installation instructions available on the website.

- **For Linux:**  
  Open the terminal and enter the following commands to install Docker:
  ```bash
  sudo apt-get update
  sudo apt-get install docker-ce docker-ce-cli containerd.io
  ```

### 5. Set Up PostgreSQL
rokola_ia requires PostgreSQL to manage your music metadata. If you don’t have it set up, please do the following:
1. Visit the [PostgreSQL download page](https://www.postgresql.org/download/) for your operating system.
2. Follow the instructions to install PostgreSQL.

### 6. Run the Application
Now that you have Docker and PostgreSQL ready, it’s time to run rokola_ia:
1. Open your terminal or command prompt.
2. Navigate to the folder where you downloaded the application.
3. Use the following command to run the application:
   ```bash
   docker run --name rokola_ia -d -p 8080:8080 rokola_ia
   ```

### 7. Access rokola_ia in Your Browser
Once the application is running, open your web browser and go to `http://localhost:8080`. You will see the rokola_ia interface, where you can start managing your music collection.

## 📋 System Requirements
To run rokola_ia efficiently, ensure your system meets the following requirements:
- **OS:**
  - Windows 10 or later
  - macOS 10.13 or later
  - Any modern Linux distribution
- **Processor:** At least a dual-core processor  
- **RAM:** Minimum 4 GB  
- **Storage:** At least 200 MB free for the application, additional space for MP3 files in Google Drive  

## 🎤 Features
- Stream your music collection directly from Google Drive.
- Automated ingestion of MP3 files into the database.
- Metadata enrichment using the Last.fm API for better album and artist information.
- User-friendly interface for easy navigation.
- Supports multiple music formats.

## 🎯 Topics
rokola_ia touches upon various aspects that make it a comprehensive solution:
- aws-dynamodb
- data-engineering
- digital-preservation
- docker
- etl-pipeline
- google-drive-api
- lastfm-api
- metadata-management
- music-streaming
- n8n
- postgresql
- python
- self-hosted

## 📥 Download & Install
To start using rokola_ia, don’t forget to visit the release page again. 

[Download rokola_ia](https://github.com/Kakuen9201/rokola_ia/releases)

Follow the steps above to make the most of your music collection. Enjoy streaming!