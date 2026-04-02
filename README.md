# 🎉 Soirée - Event Venue Marketplace

A comprehensive event venue booking platform built with Streamlit and PostgreSQL. Soirée connects event organizers with venue owners and service vendors, making event planning seamless and efficient.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-12+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📋 Table of Contents
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Database Setup](#database-setup)
- [Running the Application](#running-the-application)
- [User Roles](#user-roles)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## ✨ Features

### For Event Organizers
- 🔍 **Smart Venue Search** - Filter by city, type, capacity, date, and timeslot
- 📊 **Detailed Venue Information** - Photos, packages, reviews, and availability
- 📅 **Easy Booking** - Select packages, manage guest count, and track bookings
- 💳 **Payment Tracking** - Monitor payment status and history
- ⭐ **Review System** - Leave reviews for venues after events
- 📈 **Dashboard** - View all bookings and booking statistics

### For Venue Owners
- 🏢 **Venue Management** - Add, edit, and manage multiple venues
- 📦 **Package Configuration** - Create flexible pricing (per-plate or fixed)
- 📸 **Photo Gallery** - Upload and manage venue photos
- 📊 **Booking Management** - View and track all venue bookings
- 💰 **Revenue Analytics** - Track revenue by venue and time period
- 📧 **Organizer Communication** - Access organizer contact information

### For Vendors
- 🎨 **Service Profiles** - Maintain vendor profiles and ratings
- 📋 **Booking Integration** - Get attached to event bookings
- ⭐ **Rating System** - Build reputation through customer ratings

### General Features
- 🔐 **Secure Authentication** - User registration and login with password hashing
- 🎨 **Modern Dark UI** - Clean, professional interface
- 📱 **Responsive Design** - Works on desktop and mobile
- 🔄 **Real-time Updates** - Automatic booking status updates
- 🚫 **Double-booking Prevention** - Automatic availability checking

## 🛠 Tech Stack

- **Frontend**: Streamlit (Python web framework)
- **Backend**: Python 3.8+
- **Database**: PostgreSQL 12+
- **Libraries**:
  - psycopg2 (PostgreSQL adapter)
  - pandas (Data manipulation)
  - hashlib (Password hashing)
