# 📅 Interactive Wall Calendar App

## 🚀 Overview

The **Interactive Wall Calendar App** is a modern, visually rich calendar application inspired by physical wall calendars. It combines aesthetic design with powerful scheduling features, allowing users to manage events, notes, and date ranges in an intuitive way.

---

## ✨ Features

### 🖼️ Visual Experience

* Monthly **hero images (12 default images)**
* User can **upload custom images**
* **Dynamic theming** based on selected image
* Automatic **fallback to default image** if upload fails

---

### 📅 Calendar Functionality

* Monthly calendar view
* **Date range selection (start → end)**
* Support for **multiple ranges**
* Highlighting for:

  * Start date
  * End date
  * In-between dates

---

### 📝 Notes System

* Sticky-notes style **Kanban board layout**
* Notes support:

  * Title
  * Description
  * Single date / date range
* Two ways to create notes:

  * From calendar selection
  * Manual "Add Note"
* Notes are:

  * **Month-specific**
  * Clickable → highlights corresponding dates
* Delete notes using **X button**

---

### 🌡️ Heatmap Mode

* Visualizes event density:

  * More events → darker tone
  * Fewer events → lighter tone
  * No events → no color
* Dynamic scaling based on max events

---

### 🌗 Theme Support

* Light & Dark mode
* Dark mode uses **balanced tones (not overly dark)**
* Consistent UI color hierarchy

---

### 💎 UI/UX Enhancements

* Smooth transitions and animations
* Centered modal with backdrop
* Separate **View vs Edit mode for notes**
* Responsive design (mobile + desktop)

---

## 🧱 Tech Stack

* **React / Next.js**
* **TypeScript**
* **Tailwind CSS**
* LocalStorage (for persistence)

---

## 📁 Project Structure

```
/components
  /Calendar
    /CalDay.tsx
    /Calendar.tsx
    /CalGrid.tsx
    /HeroImage.tsx
    /NoteModal.tsx
    /NotesBoard.tsx
    /SickyNote.tsx

/hooks
    /useNotes.ts
    /useTheme.ts
    /useWindowWidth.ts
/utils
    /calendar.utils.ts
/types
    /calendar.types.ts
/constants
    /calendar.constants.ts
```

* Modular architecture
* Custom hooks for logic separation
* Clean and scalable structure

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/calendar-app.git
cd calendar-app
```

---

### 2. Install dependencies

```bash
npm install
```

---

### 3. Run the development server

```bash
npm run dev
```

---

### 4. Open in browser

```
http://localhost:3000
```

---

## 🛠️ Available Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Run production build
npm run lint     # Run lint checks
```

---

## 📱 Responsiveness

* Fully optimized for:

  * Desktop
  * Tablet
  * Mobile devices

---

## 🎯 Key Highlights

* Strong focus on **UI/UX design**
* Clean **component-based architecture**
* Advanced features like:

  * Dynamic theming
  * Heatmap visualization
  * Multi-range selection

---

## 🚀 Future Improvements

* Drag-to-select range
* Cloud sync / backend support
* Collaboration features
* AI-based event suggestions

---

## 👨‍💻 Author

Developed by *Samman Varshney*

---

## 📌 Note

This project is frontend-focused and uses **localStorage** for persistence. No backend is required.

---
