# Online Bookstore MySQL Analysis

A comprehensive MySQL database project for managing and analyzing an online bookstore system. This project includes database schema design, sample data, and advanced SQL queries for business intelligence.

## 📋 Project Overview

This repository contains a complete relational database solution for an online bookstore platform with three main entities: **Books**, **Customers**, and **Orders**. It includes SQL queries ranging from basic data retrieval to advanced analytics for business insights.

## 🗄️ Database Schema

### Tables

**1. Books Table**
- `Book_ID` (Primary Key) - Unique book identifier
- `Title` - Book title
- `Author` - Author name
- `Genre` - Book genre category
- `Published_Year` - Year of publication
- `Price` - Book price
- `Stock` - Current inventory stock

**2. Customers Table**
- `Customer_ID` (Primary Key) - Unique customer identifier
- `Name` - Customer name
- `Email` - Customer email address
- `Phone` - Contact phone number
- `City` - City of residence
- `Country` - Country of residence

**3. Orders Table**
- `Order_ID` (Primary Key) - Unique order identifier
- `Customer_ID` (Foreign Key) - Reference to Customers
- `Book_ID` (Foreign Key) - Reference to Books
- `Order_Date` - Date of order placement
- `Quantity` - Number of books ordered
- `Total_Amount` - Total order amount
