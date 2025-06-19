# Submio

**Submio** is an AI-assisted file submission tracker that automates the process of collecting, verifying, and organizing file uploads in a shared Google Drive folder. Designed for educators, managers, and event organizers, Submio matches uploaded files against a list of expected names and formats, and presents submission progress in a real-time dashboard with Excel export support.

---

## ✨ Features

- 🔗 Accepts a shared Google Drive folder link
- 📋 Upload or input a list of required submitters
- 🔍 Matches uploaded files by name and format
- 📊 Live, color-coded dashboard (Green = submitted, Red = missing, Yellow = wrong format)
- 📁 Auto-renames files for consistency
- 👁️ File previews for supported formats (e.g., PDF, Google Docs)
- 📤 Generates downloadable Excel reports
- 🔐 Optional Google OAuth for accessing private folders

---

## 🔧 Tech Stack

| Layer        | Technology                             |
|--------------|----------------------------------------|
| Frontend     | React.js / Tailwind CSS                |
| Backend      | Python (FastAPI or Flask)              |
| File Handling| Google Drive API, openpyxl, pandas     |
| Auth         | Google OAuth 2.0                       |
| Optional DB  | Firebase / Supabase                    |
