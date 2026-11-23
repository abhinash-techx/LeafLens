# 🌿 LeafLens – AI-Based Plant Disease Detection and Analysis System

LeafLens is an AI-powered web application designed to analyze plant leaf images and provide information about possible plant diseases using a Vision AI model.

The system allows users to upload plant images and receive AI-generated analysis through a simple and user-friendly interface.

## 🚀 Project Overview

Plant diseases can affect crop quality and agricultural productivity. Identifying possible diseases at an early stage can help users understand plant health conditions.

LeafLens uses a Vision AI model through the Groq API to analyze uploaded plant images and return structured results.

**The project integrates an existing AI vision model; it does not train a model from scratch.**

## ✨ Key Features

- 📷 Plant leaf image upload
- 🔍 AI-based plant image analysis
- 🌱 Possible plant disease identification
- 📊 Structured JSON response
- 🖥️ Simple and responsive user interface
- ⚡ FastAPI-based REST API
- 🖼️ Image validation and processing
- 📁 Supports JPG, JPEG, PNG and WEBP formats
- 🔐 API key management using environment variables
- ☁️ Cloud deployment support

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Fetch API
- FormData

### Backend
- Python
- FastAPI
- Uvicorn
- Requests
- Python-dotenv
- Pillow (PIL)

### AI Integration
- Groq API
- Qwen Vision Model (`qwen/qwen3.8-27b`)

### Deployment and Version Control
- GitHub – Source Code Management
- Netlify – Frontend Hosting
- Render – Backend Hosting

## 🏗️ System Architecture

```text
          USER
            |
            v
      LEAFLENS WEBSITE
     (
