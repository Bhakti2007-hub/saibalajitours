# 🚗 Sai Balaji Tours and Travels  
### Your trusted travel partner – Book cars easily and instantly online.

---

## 📝 1. Project Title and Tagline  
**Sai Balaji Tours and Travels**  
Your trusted travel partner – providing comfortable, safe, and affordable rides with instant online booking.

---

## 🌐 2. Project Overview  

**Sai Balaji Tours and Travels** is a complete **online car booking platform** built using **HTML, CSS, and JavaScript**.  
It allows users to explore available cars, check prices, book rides, and receive instant confirmations via **Email** and **WhatsApp**.  

This website provides a simple and modern interface with live GPS-based pickup detection and real-time booking validation.

---

## ✨ 3. Features  

✅ Modern & Responsive UI  
🚘 Car selection and booking form  
📍 Live GPS-based pickup location  
📅 Date & time-based slot checking  
💬 WhatsApp confirmation message  
📧 EmailJS-based email confirmation  
🗺️ Google Maps integration  
💾 LocalStorage for saved bookings  
🧠 Automatic duplicate booking detection  
🌙 Light and dark mode (optional)  
📱 Fully mobile-friendly interface  

---

## 🧰 4. Tech Stack  

| **Category**               | **Technology / Tool**               | **Purpose / Description**                                      |
| -------------------------- | ----------------------------------- | -------------------------------------------------------------- |
| 🖥️ **Frontend**           | **HTML5**                           | Structure and layout of all web pages                          |
| 🎨 **Styling**             | **CSS3**                            | Website design, layout styling, and responsiveness             |
| ⚙️ **Scripting**           | **JavaScript (Vanilla JS)**         | Handles interactivity, booking form logic, and dynamic updates |
| ✉️ **Email Integration**   | **EmailJS API**                     | Sends automated booking confirmation emails to users           |
| 💬 **Messaging**           | **WhatsApp API**                    | Sends booking details directly to admin’s WhatsApp number      |
| 📍 **Geolocation**         | **OpenStreetMap API**               | Detects and autofills user's live pickup location              |
| 🗺️ **Map Display**        | **Google Maps Embed**               | Displays the Shirdi office location in the Contact section     |
| 💾 **Storage**             | **LocalStorage (Browser)**          | Temporarily stores booking data to prevent duplicate slots     |
| 🧠 **Conflict Management** | **Custom JS Logic**                 | Validates if the selected date/time slot is already booked     |
| 🧱 **UI Design Tools**     | **Canva, Figma (optional)**         | Used for banners, image editing, and interface layout          |
| 🚀 **Hosting Platform**    | **GitHub Pages / Netlify / Vercel** | Deploys the live website online for public access              |
| 🧩 **Code Editor**         | **Visual Studio Code (VS Code)**    | Used for development, editing, and debugging                   |
| 🧾 **Version Control**     | **Git & GitHub**                    | For project versioning, commits, and collaboration             |


---

## 📁 5. Project Structure  
SaiBalajiTours/
│
├── index.html
├── images/
│ ├── car1.jpg
│ ├── car2.jpg
│ ├── car3.jpg
│ └── swift-1.jpg
└── README.md


---

## 💡 6. How It Works  

1️⃣ User visits homepage → views available cars  
2️⃣ Clicks **Book Now** → fills the booking form  
3️⃣ Website fetches **live location** and **date/time**  
4️⃣ On submit → data is sent to **EmailJS** and **WhatsApp API**  
5️⃣ Confirms booking and saves record locally to prevent duplicate slots  

---

## ⚙️ 7. Setup / Installation  

**Step 1:** Clone the repository  
```bash
git clone https://github.com/<your-username>/SaiBalajiTours.git
cd SaiBalajiTours
Step 2: Open index.html in any web browser

Step 3: Setup EmailJS

Go to https://www.emailjs.com/

Create a new service and email template

Get your Service ID, Template ID, and Public Key


