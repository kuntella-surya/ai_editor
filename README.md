# 🎨 AI Image Editor

A full-stack AI-powered image editor built with **Next.js**, **Fabric.js**, **Tailwind CSS**, **shadcn/ui**, **Convex**, **Clerk**, and **ImageKit**. The application provides a modern image editing experience with AI-powered tools for generating, editing, and enhancing images.

## ✨ Features

* 🎨 Interactive image editor powered by Fabric.js
* 🖼️ Upload images from your device
* ✂️ Crop, resize, rotate, and flip images
* 📝 Add and customize text
* 🖌️ Freehand drawing
* 🌈 Apply image filters
* 🤖 AI Background Removal
* 🪄 AI Image Generation
* 🧹 AI Object Removal
* 🚀 AI Image Upscaling
* ☁️ Image storage with ImageKit
* 🔐 Secure authentication with Clerk
* ⚡ Real-time backend using Convex
* 📱 Fully responsive UI

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* Tailwind CSS
* shadcn/ui
* Fabric.js

### Backend

* Convex

### Authentication

* Clerk

### Cloud Services

* ImageKit
* Unsplash API

---

## 📁 Folder Structure

```text
app/
components/
context/
convex/
hooks/
lib/
public/
```

---

## ⚙️ Environment Variables

Create a `.env.local` file and add:

```env
# Convex
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLERK_JWT_ISSUER_DOMAIN=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# ImageKit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
IMAGEKIT_PRIVATE_KEY=

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/kuntella-surya/ai-editor.git
```

Navigate to the project

```bash
cd ai-editor
```

Install dependencies

```bash
npm install
```

Start the development server

```bash
npm run dev
```

Open:

```
http://localhost:3000
```

---

## 📌 AI Tools Included

* AI Background Removal
* AI Image Generation
* AI Object Removal
* AI Image Upscaling
* Crop
* Resize
* Rotate
* Flip
* Draw
* Text
* Filters

---

## 🙏 Acknowledgements

This project is based on the excellent AI Image Editor tutorial by **Piyush Agarwal (Roadside Coder)**.

The original project served as the foundation, and this repository includes my own setup, modifications, and improvements for learning and experimentation.

---

## 📄 License

This repository is intended for educational and learning purposes. Please respect the license of the original project if you reuse or redistribute this code.

---

## 👨‍💻 Author

**Kuntella Bhanu Surya Veera Sankar**

GitHub: https://github.com/kuntella-surya
