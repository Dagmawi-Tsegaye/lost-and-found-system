Addis Ababa University (AAU) - Lost and Found System
This is a portfolio project designed to solve the common problem of managing lost and found items on a large university campus. It provides a centralized, digital platform for the Addis Ababa University (AAU) community to report, search for, and securely reclaim lost belongings. Please note, this is a personal project and is not officially affiliated with or used by Addis Ababa University.

Live Demo: https://lost-and-found-system-chi.vercel.app/home.html

About The Project
The traditional method of handling lost items at AAU is often informal and unreliable, leading to frustration and permanent loss of property. This project introduces a structured and efficient digital solution. Built with a user-centered design approach, the system allows students and staff to manage lost and found items transparently, fostering a stronger sense of community and responsibility.

Key Features
Seamless Item Reporting: Users can easily submit detailed reports for both lost and found items, including categories, descriptions, locations, and photo uploads.

Advanced Search & Filtering: A robust search functionality allows users to quickly find items based on keywords, categories, and location.

Secure Claim Process: A private verification system ensures items are returned to their rightful owners. Finders can ask claimants for non-public details about an item before revealing contact information.

Moderator-Focused Admin Role: The administrator role is designed for moderation and dispute resolution, without the ability to edit user-generated content, thereby ensuring the integrity of all posts.

Accountability Log: The system tracks when an item is successfully returned and records the claimant's information (submitted by the finder) for accountability.

Responsive Design: The UI was designed in Figma and built with a mobile-first approach, ensuring full functionality on desktops, tablets, and smartphones.

Technology Stack
Frontend: HTML5, CSS3, Vanilla JavaScript

Backend-as-a-Service (BaaS): Supabase

Database: Supabase DB (PostgreSQL)

Authentication: Supabase Auth

Design: Figma

Deployment: Vercel

Project Development Insights
The development process involved solving key challenges to ensure the system was both secure and user-friendly.

Admin Role Integrity: A key design decision was to redefine the traditional admin role. To protect data integrity and user trust, admins cannot edit or delete user posts. Instead, their role is focused on moderating content, resolving user disputes, and managing the overall health of the system.

User Experience Refinement: Based on initial designs and feedback, the user interface and navigation were significantly refined. A unified navigation bar was implemented, and the item reporting process was streamlined to be as intuitive as possible, reducing friction for users.

Getting Started
To get a local copy up and running for development:

Clone the repository:

Bash

git clone https://github.com/Dagmawi-Tsegaye/lost-and-found-system.git
Open the home.html file in your browser. (Note: A live internet connection is required for Supabase integration to work).

Contact
Dagmawi Tsegaye Feleke - dagmawi.tsegaye.feleke@gmail.com

Project Link: https://github.com/Dagmawi-Tsegaye/lost-and-found-system

Acknowledgments
Dr. Eyob: For his guidance and constructive criticism throughout the project's development.

Classmates and Friends: For their helpful suggestions and assistance with testing.
