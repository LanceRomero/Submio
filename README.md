# SubmiTrack

**SubmiTrack** is an AI-assisted file submission tracker that automates the process of collecting, verifying, and organizing file uploads in a shared Google Drive folder. Designed for educators, team managers, and organizers, SubmiTrack matches uploaded files against a list of expected names and file formats, then displays real-time submission progress in a web-based dashboard with optional Excel export.

---

## ✨ Features

- 🔗 Accepts a shared Google Drive folder link
- 📋 Upload or input a list of expected submitters
- 🔍 Matches uploaded files by name and format
- 📊 Real-time, color-coded dashboard (Green = submitted, Red = missing, Yellow = wrong format)
- 📁 Auto-renames uploaded files for consistency
- 👁️ File previews (PDFs, Google Docs)
- 📤 Export submission status to Excel
- 🔐 OAuth authentication for private Drive folders (optional)

---

## 🔧 Tech Stack

| Layer        | Technology                             |
|--------------|----------------------------------------|
| Frontend     | React.js / Tailwind CSS                |
| Backend      | Python (FastAPI or Flask)              |
| File Handling| Google Drive API, openpyxl, pandas     |
| Auth         | Google OAuth 2.0                       |
| (Optional) DB| Firebase / Supabase                    |

---

## 📌 Setup Instructions (Coming Soon)

> Full setup instructions, including OAuth credentials, will be provided in future commits.

For now, here's the basic idea:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/submitrack.git
   cd submitrack
