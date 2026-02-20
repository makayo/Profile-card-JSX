# 🪪 Profile Card JSX Component

This project contains a simple React component called **UserProfile**, which displays a user's name, email, and a profile photo. It also includes a `mailto:` link so users can send an email directly.

---

## 🚀 How to Run

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Start the Development Server

```bash
npm start
```

### 3️⃣ Open in Browser

Visit:

```
http://localhost:3000
```

---

## 🧩 Component Props

The `UserProfile` component:

- Accepts two props: `name` and `email`
- Displays a title ("User Profile")
- Shows a profile image
- Displays the user's name and email
- Provides a clickable email link using `mailto:`

The profile image is stored locally inside an `images` folder and is imported into the component file.
This ensures the image is bundled correctly during development and production builds.

---

```plaintext
src/
 ├── components/
 │    ├── UserProfile.jsx
 │    └── images/
 │         └── matrix_possum.jpg
 ├── App.js
 └── index.js
```
---

## 🚀 How to Run

### 1️⃣ Install Dependencies

```bash
npm install
```

### 2️⃣ Start the Development Server

```bash
npm start
```

### 3️⃣ Open in Browser

Visit:

```
http://localhost:3000
```

---

## 🧩 Component Props

The component accepts the following props:

- **name** — The user's full name  
- **email** — The user's email address  

### 📌 Example Usage

```jsx
<UserProfile name="Jane Doe" email="jane@example.com" />
```

---

## 🧪 Test Cases

### ✅ Normal Test Cases

- `name="Jane Doe"`, `email="jane@example.com"`
- `name="Michael Smith"`, `email="m.smith@company.org"`
- `name="Alicia P. Rivera"`, `email="arivera@gmail.com"`

### ⚠️ Edge Test Cases

- `name=""`, `email="no.name@example.com"`
- `name="Ghost User"`, `email=""`
- `name="Dr. #$%&*!"`, `email="weird@example.com"`

---
