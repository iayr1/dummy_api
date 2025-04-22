# Dummy Endpoints Documentation

This document outlines the dummy endpoints defined in `dummy_endpoint.py`. These endpoints simulate real API behavior with hardcoded responses, ideal for development and testing purposes.

## Table of Contents
- [Authentication Endpoints](#authentication-endpoints)
- [Payment Endpoints](#payment-endpoints)
- [Text to Video Endpoints](#text-to-video-endpoints)
- [Image to Video Endpoints](#image-to-video-endpoints)
- [MM Audio Endpoints](#mm-audio-endpoints)
- [Library Endpoints](#library-endpoints)
- [Watermark Endpoints](#watermark-endpoints)
- [Movie Maker Endpoints](#movie-maker-endpoints)
- [Utils Endpoints](#utils-endpoints)
- [Character Score Endpoints](#character-score-endpoints)
- [Referral Endpoints](#referral-endpoints)
- [Main API Endpoints](#main-api-endpoints)

---

## Authentication Endpoints

### 1. User Signup
- **Endpoint**: `POST /signup`
- **Description**: Creates a new user account.
- **Request Body**:
  ```json
  {
    "email": "user@example.com",
    "password": "secure_password",
    "confirm_password": "secure_password"
  }


  
