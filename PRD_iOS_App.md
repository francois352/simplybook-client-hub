# Product Requirements Document: Neurofeedback Client Hub (iOS App)

**Working Title:** Neurofeedback Client Hub
**Author:** Manus AI
**Version:** 1.0
**Date:** November 11, 2025

---

## 1. Introduction

This document outlines the product requirements for the **Neurofeedback Client Hub**, an iOS application that will serve as a branded client portal for Neurofeedback Luxembourg, integrating with the SimplyBook.me API.

### 1.1. Project Vision

To provide a seamless, professional, and integrated experience for clients to manage their appointments and interact with Neurofeedback Luxembourg, enhancing client satisfaction and retention.

### 1.2. Target Audience

- **Primary:** All current and future clients of Neurofeedback Luxembourg.

---

## 2. Core Features

| ID | Feature | Priority | Description |
| :-- | :--- | :--- | :--- |
| F01 | **Appointment Management** | Must-have | View upcoming and past appointments, book new sessions, and cancel/reschedule existing ones via the SimplyBook.me API. |
| F02 | **Secure Authentication** | Must-have | Secure client login using the SimplyBook.me client login API. |
| F03 | **Push Notifications** | Must-have | Reminders for upcoming appointments (24 hours and 1 hour before). |
| F04 | **Practitioner Profiles** | Should-have | A view to see information about the practitioners at Neurofeedback Luxembourg. |
| F05 | **Resource Link** | Must-have | A simple, in-app link to the main website's resource page. |

---

## 3. Technical Specifications

- **Platform:** iOS (iPhone & iPad)
- **Language:** Swift
- **UI Framework:** SwiftUI
- **API:** SimplyBook.me REST API
- **Dependencies:** Alamofire for networking.

---

## 4. GDPR & Data Privacy

- The app will not store any personal data on the device. All data will be fetched from and sent to the SimplyBook.me API in real-time.
- The app's privacy policy will clearly state that all data is managed by SimplyBook.me and will link to their privacy policy.
