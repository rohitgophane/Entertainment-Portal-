Entertainment Portal – Detailed Documentation

The Entertainment Portal is a web-based application built using Spring Boot, Spring MVC, JPA/Hibernate, MySQL, and JSP. This project provides essential user functionalities like authentication, profile management, post creation, and multimedia content exploration.
It is designed as a beginner-friendly yet professional-level full-stack Java project.

📌 Project Overview

This project showcases how to build a complete Java-based MVC web application with:

Backend: Spring Boot

Frontend: JSP

Database: MySQL

ORM: Hibernate/JPA

Build Tool: Maven

It demonstrates real-world features such as login, signup, CRUD operations, session handling, profile updates, and integration with an external API (Spotify).

🔥 Features (In Detailed Form)
1. User Authentication

New users can sign up with details.

Existing users can log in using email + password.

Secure password validation.

Session management ensures only logged-in users can access restricted pages.

2. Profile Management

Each user has a profile page.

Users can edit personal information.

Stores and retrieves profile data from MySQL using JPA.

3. Post Management

Users can create posts related to entertainment content.

Posts include:

Title

Description

Media type (Movies, Music, Series, etc.)

Posts are saved in the database via JPA Repository.

4. Home Dashboard

Displays content based on user activity.

Links to login, signup, profile, and post features.

5. Basic Spotify Integration

Spotify API controller exists for future implementation.

Demonstrates API calling structure.

6. JSP Frontend

Simple UI built using JSP, CSS, HTML.

Dynamic content rendering using JSTL and Spring Model.

🧱 Technologies Used (Detailed)
Backend Technologies

Spring Boot (Core framework)

Spring Web MVC

Spring Data JPA (Database Layer)

Hibernate ORM

MySQL Database

Frontend Technologies

JSP pages

HTML5 + CSS3

JSTL / Expression Language (EL)

Build & Tools

Maven

Java 17 (or supported version)

Eclipse / IntelliJ

Tomcat (embedded in Spring Boot)
