# CS 360 Inventory Management App – 3D Printing Filament

**Author:** Timothy Johnson  
**Course:** CS 499  
**Date:** September 2025  

## Overview
This Android app is an **Inventory Management tool** designed to help users track 3D printing filament spools. It was originally created as a class project and later enhanced for professional-quality usability, functionality, and design.

## Features
- **Add, Edit, Delete, and View Filaments**  
  Each filament includes details such as color, quantity, and date added.

- **User-Friendly UI**  
  - Switched from a grid layout to a list layout for better readability  
  - Custom icons for filament spools  
  - Rainbow-colored title for visual appeal  
  - Dark theme with adjusted font sizes, spacing, and alignment  

- **Data Management**  
  - Full CRUD operations with **SQLite**  
  - Input validation to prevent invalid entries  
  - User feedback messages for success or failure  

- **Algorithms & Data Structures**  
  - `FilamentManager` class with a **HashMap** for fast lookups  
  - Sorting filaments by color, weight, or type  

- **Database Enhancements**  
  - SQLite integration for storing spools, colors, and storage locations  
  - Export inventory to CSV or JSON  
  - Basic password protection for admin actions  

## Screenshots
![Old Version](images/old1.png)  
*Old login screen*  

![New Version](images/new1.png)  
*Enhanced login screen*  

![Old Inventory](images/old2.png)  
*Original inventory view*  

![New Inventory](images/new2.png)  
*Updated inventory view with list layout*  
