# Product Requirements Document: Neurofeedback Client Hub (Web & Mobile)

**Working Title:** Neurofeedback Client Hub
**Author:** Manus AI
**Version:** 2.0
**Date:** November 11, 2025

---

## 1. Introduction

This document outlines the revised product requirements for the **Neurofeedback Client Hub**, a cross-platform application (Web, iOS, Android) that provides a branded, integrated experience for Neurofeedback Luxembourg clients, built on the SimplyBook.me API.

### 1.1. Project Vision

To create a seamless, professional, and value-added portal for clients to manage their appointments, access exclusive content, and communicate securely with practitioners, thereby enhancing client satisfaction and retention.

---

## 2. Core Features

| ID | Feature | Priority | Description |
| :-- | :--- | :--- | :--- |
| F01 | **Appointment Management** | Must-have | View, book, and manage appointments via the SimplyBook.me API. |
| F02 | **Secure Messaging** | Should-have | A secure, GDPR-compliant chat feature for clients to communicate with their assigned practitioner. |
| F03 | **Resource Library** | Must-have | Access to an exclusive library of educational content (articles, videos) available only to active clients. |
| F04 | **Push & Email Notifications** | Must-have | Automated reminders for appointments and new messages. |
| F05 | **Practitioner Profiles** | Must-have | Detailed profiles for each practitioner, including bio, specialties, and a link to their schedule. |

---

## 3. Technical Specifications

- **Platforms:** Web, iOS, Android
- **Web Framework:** Next.js (React)
- **Mobile Framework:** React Native
- **Backend:** A Node.js backend on elest.io to handle secure messaging, notifications, and business logic, acting as a proxy to the SimplyBook.me API.
- **Database:** PostgreSQL for storing messages and user-specific data.

---

## 4. Obvious Improvements Incorporated

1.  **Cross-Platform:** The app will be available on web, iOS, and Android, providing a consistent experience on any device.
2.  **Secure Messaging:** The addition of a secure, GDPR-compliant messaging feature provides a significant value-add beyond the standard SimplyBook.me interface and addresses a key business need.
3.  **Exclusive Content:** Offering a client-only resource library increases the value of being a Neurofeedback Luxembourg client and encourages app usage.
4.  **Robust Backend:** A dedicated backend allows for more complex features (like secure messaging) and provides a layer of abstraction and security in front of the SimplyBook.me API.
