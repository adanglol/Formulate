# 🧼 Formulate

> **AI-Powered Data Cleaning, Validation, and Visualization for Schools & Non-Profits using Google AI Studio (Gemini), Google Forms, and Google Sheets.**

---

## 📌 Overview

Schools and non-profits rely heavily on Google Forms for student registrations, event sign-ups, and family intake. However, raw submission data is often rife with errors:
- **Swapped Fields:** Student first/last names placed in parent fields (or vice versa).
- **Invalid Email Domains:** Students submitting commercial emails (`@gmail.com`) instead of district emails (`@*.edu` / `@*.usd`).
- **Malformed Student IDs & Grades:** Incorrect lengths, missing digits, or inconsistent formatting (e.g., "9th", "ninth", "Grade 9").
- **Duplicate Submissions:** Multiple entries submitted by the same student or parent.

**Formulate** leverages **Google AI Studio** and **Gemini** to act as an automated data engine that evaluates form responses, flags errors, categorizes data into clean vs. bad data tabs, and powers real-time quality dashboards.

---

## ✨ Key Features

- **🤖 AI-Driven Validation Engine:** Powered by Gemini (built using Google AI Studio) to perform complex cross-field analysis and fuzzy duplicate detection.
- **🔄 Auto-Routing:** Automatically splits data into **Clean Records** (ready for SIS export) and **Flagged Records** (annotated with specific error codes).
- **📧 Domain & Format Enforcement:** Checks for valid school domain extensions (`.edu`, `.usd`, etc.) and standardizes student IDs and grades.
- **📊 Real-Time Quality Dashboard:** Visualizes overall data health, error frequencies, and site breakdowns using Google Sheets widgets and Looker Studio.

---

## 🛠️ Tech Stack & Integration Architecture