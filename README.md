# Grazioso-Salvare-Rescue-Dashboard
# Grazioso Salvare Animal Rescue Dashboard

## Project Overview

For this project, I worked on developing a database-driven dashboard for Grazioso Salvare, an organization that identifies and trains rescue dogs for different types of search-and-rescue operations. The goal was to create a system that allows users to filter and review animal shelter data to identify dogs that meet specific rescue training requirements.

The project involved using MongoDB to manage animal shelter records, developing a Python CRUD module to interact with the database, and connecting that module to a dashboard designed to display relevant information.

## 1. How do you write programs that are maintainable, readable, and adaptable?

When writing programs, I try to keep my code organized, use meaningful variable names, and separate different responsibilities into smaller components. This makes the code easier to understand, troubleshoot, and update when changes are needed.

One example was the Python CRUD module I developed in Project One. Instead of writing database queries directly into every part of the dashboard, I created a reusable module to handle database operations. This allowed the dashboard to interact with MongoDB without having to repeat the connection and query logic throughout the application.

One advantage of this approach is that changes to the database connection or CRUD functionality can be made in one location instead of modifying multiple sections of code. It also makes debugging easier because I can test the database operations separately from the dashboard interface.

In the future, I could use a similar CRUD module in other applications that need to store, retrieve, update, or delete information, such as inventory management systems, scheduling applications, or other data-driven programs.

## 2. How do you approach a problem as a computer scientist?

When approaching a problem, I begin by identifying what the client needs and breaking those requirements into smaller tasks. For Grazioso Salvare, the main objective was to help the organization identify shelter animals that matched specific search-and-rescue criteria.

I needed to understand how the animal shelter data was organized, determine which database queries would return the appropriate records, and connect those results to the dashboard.

This project was different from some of my previous assignments because I had to think about how several components worked together rather than focusing only on one program. The database, Python CRUD module, and dashboard each had a separate responsibility, but they all needed to communicate correctly for the application to work.

I approached the project by working through the requirements step by step, testing database queries, reviewing errors, and making corrections as I progressed.

In future projects, I would continue using this approach by first reviewing the client's requirements, examining the available data, planning the database structure, and testing individual components before integrating them into a larger application.

## 3. What do computer scientists do, and why does it matter?

Computer scientists use programming, data analysis, and problem-solving to develop technology that helps people and organizations work more efficiently. Their work can involve designing software, managing databases, improving existing systems, and finding ways to turn complex information into useful solutions.

For Grazioso Salvare, the dashboard was designed to make it easier to identify dogs that meet specific rescue training requirements. Instead of manually reviewing large amounts of animal shelter information, users could filter the data and focus on animals that matched the criteria for different rescue operations.

This type of application can help organizations save time, reduce the amount of manual work required, and make more informed decisions based on available data.

Working on this project helped me better understand how computer science connects technical development with real-world needs. It also showed me how important it is to design applications that are not only functional but also useful to the people who rely on them.
