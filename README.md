# Nutrition Analysis DBMS

A nutrition analysis and meal planning application built using **Flask, MySQL, and React**. The project demonstrates database design, SQL programming, nutrition tracking, recipe management, meal planning, feedback management, and user weight/BMI tracking.

## 📌 Project Overview

The Nutrition Analysis system is designed to manage nutrition-related information through a structured relational database and a Flask-based backend.

The database stores users, recipes, ingredients, nutritional information, meal plans, diet logs, feedback, and weight history. SQL triggers, functions, and stored procedures are used to implement database-level operations and automation.

## 🏗️ Architecture

```text
React Frontend
      │
      │ HTTP / REST API
      ▼
Flask Backend
      │
      │ SQLAlchemy / PyMySQL
      ▼
MySQL Database
      │
      ├── Users
      ├── Recipes
      ├── Ingredients
      ├── Nutrition
      ├── Meal Plans
      ├── Diet Logs
      ├── Feedback
      └── Weight History
