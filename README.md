# CRUD App for Author and Article

This is a full-stack **CRUD web application** built using **Spring Boot**, designed to manage **Articles and Authors**. The system allows users to create, read, update, and delete articles and associate them with authors. It also integrates features such as **email notifications**, **cloud image storage using Cloudinary**, and a **scheduled task** to auto-publish articles.

---

## 🚀 Features

- **CRUD Operations** for Articles and Authors
- **Email Notifications** upon:
  - Article creation
  - Article update
  - Article deletion
- **Cloudinary Integration** for uploading and storing article banner images
- **Spring Scheduler** that:
  - Runs every day at **12:00 AM**
  - Checks if the article's `publishDate` matches the current date
  - If status is `DRAFT`, it auto-updates the status to `PUBLISH`
- **Global Exception Handler** to catch and handle runtime errors gracefully
- Logging with SLF4J for tracking application events and exceptions

---

## 🛠️ Tech Stack

- **Backend:** Spring Boot, Spring MVC, Spring Data JPA
- **Templating Engine:** JSP
- **Database:** MySQL
- **Image Storage:** Cloudinary
- **Email Service:** JavaMailSender
- **Logging:** SLF4J
- **Scheduler:** Spring @Scheduled annotation

---

## 📸 Screenshots

![Screenshot (1540)](https://github.com/user-attachments/assets/95c41c17-c301-4afc-b8dd-89f92bb422da)

![Screenshot (1541)](https://github.com/user-attachments/assets/7b5c8d69-a6cb-4d4d-98cb-bd9250007197)
![Screenshot (1542)](https://github.com/user-attachments/assets/7360d2ca-90fd-49cd-881c-783ee84d7493)

---

## 📂 Project Structure

