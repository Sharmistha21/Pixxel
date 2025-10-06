
#AI Photo Editor

An AI-powered web photo editor built with Next.js, Fabric.js, and Convex — enabling users to upload, edit, enhance, and transform images in real-time using smart AI tools.
Designed for creators, designers, and developers who want Photoshop-like control in the browser, powered by cloud storage and on-device rendering.

🚀 Features
✨ AI-Powered Enhancements — Auto-improve lighting, colors, and sharpness.

🧠 Object Removal & Background Erase — Intelligent inpainting to clean up images.

🎨 Fabric.js Canvas Editor — Draw, crop, resize, rotate, add filters, and layers.

☁️ Image Upload & CDN — Integrated with ImageKit for real-time optimization and delivery.

🔒 Authentication — Secure user login via Clerk.

🗂️ Cloud Database — Manage project data and edits using Convex as a serverless backend.

💾 Save & Share — Export final edits or save projects to your personal workspace.

⚡ Optimized for Performance — Lazy loading, dynamic imports, and responsive UI with Tailwind + Shadcn UI.

🏗️ Tech Stack
Category	Technology
Frontend	Next.js 14, React 18, Tailwind CSS, Shadcn UI
Canvas Engine	Fabric.js
AI / Image Processing	ImageKit, OpenAI / Replicate (optional for background removal)
Backend	Convex (Serverless Functions + Database)
Auth	Clerk

#Usage Guide

Upload an Image — Drag and drop or import from your gallery.

Edit — Use crop, resize, filters, draw, or text tools from the toolbar.

Apply AI Tools — Click “Enhance” or “Remove Background.”

Save/Export — Download or save your project to your account.
Deployment	Vercel
Storage	ImageKit CDN
