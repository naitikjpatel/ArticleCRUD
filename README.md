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

> Add screenshots of `article-form`, `article-list`, and `article-view` if available.

---

## 📂 Project Structure

