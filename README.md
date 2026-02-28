# Dhanalakshmi lorry body building Employee Management System

## 📌 Project Overview

This is a small internal company web application built using **Flask
(Python)**.\
The system allows administrators to manage employees, track work hours,
calculate earnings, and record withdrawals.

### 🎯 Objectives

-   Add / Edit / Delete employees
-   Track daily working hours
-   Calculate daily earnings
-   Record withdrawal payments
-   Search employee details
-   Secure admin login system

Usage:\
- 1--2 internal users\
- Accessed 4--5 times per day\
- Small company internal tool

------------------------------------------------------------------------

# 🧱 Technology Stack

## 🖥 Backend & Frontend

-   Flask (Python)
-   HTML, CSS, Bootstrap
-   Jinja2 Templates

## 🗄 Database

-   Supabase (Managed PostgreSQL)
-   Built-in Authentication
-   Free tier suitable for small usage

## ☁ Hosting

-   Google Cloud Run (Serverless deployment)
-   HTTPS enabled by default

## 🔐 Authentication

-   Supabase Auth (Email + Password)
-   Secure password hashing handled by Supabase

## 🚀 DevOps & Collaboration

-   GitHub (Version Control)
-   GitHub Actions (CI/CD)
-   Docker (Containerization)

------------------------------------------------------------------------

# 👥 Team Roles

## 🎨 Frontend Developer

-   UI design
-   Dashboard layout
-   Employee forms
-   Search page
-   Responsive design

## 👨‍💻 Backend Developer

-   Flask application structure
-   Supabase integration
-   CRUD operations
-   Business logic
-   Authentication handling

## 🚀 DevOps Engineer

-   Docker configuration
-   Cloud Run deployment
-   Environment variables setup
-   CI/CD pipeline configuration

## 📋 Project Manager

-   GitHub repository management
-   Issue tracking
-   Code review coordination
-   Branch protection
-   Sprint planning

------------------------------------------------------------------------

# 🗄 Database Structure

## Employees

-   id
-   name
-   position
-   hourly_rate
-   created_at

## Work Logs

-   id
-   employee_id (Foreign Key)
-   date
-   hours_worked
-   money_earned

## Withdrawals

-   id
-   employee_id (Foreign Key)
-   date
-   amount

------------------------------------------------------------------------

# 🏗 System Architecture

User (Admin) ↓ Flask App (Cloud Run) ↓ Supabase (PostgreSQL + Auth)

------------------------------------------------------------------------

# 💰 Estimated Monthly Cost

  Service             Estimated Cost
  ------------------- ----------------------
  Supabase            \$0 (Free Tier)
  Cloud Run           \$0--\$5
  Domain (Optional)   \~\$10/year
  **Total**           \~\$0--\$5 per month

------------------------------------------------------------------------

# 🔐 Security Considerations

-   Do not store passwords manually
-   Use environment variables for API keys
-   Enable HTTPS
-   Protect main branch in GitHub
-   Perform regular database backups

------------------------------------------------------------------------

# 📦 Git Workflow

Branches: - main (production) - develop - feature/\*

Workflow: 1. Create issue 2. Create feature branch 3. Submit pull
request to develop 4. Review & test 5. Merge to main

------------------------------------------------------------------------

# 🚀 Final Summary

This system provides: - Secure employee management - Attendance and
earnings tracking - Withdrawal recording - Search functionality -
Low-cost cloud deployment - Scalable architecture for future growth

Designed for simplicity, affordability, and professional deployment.
