# 🚑 RapidAid — Emergency QR Card Generator

**“If someone collapses in public, their phone becomes useless—locked, silent, inaccessible. RapidAid changes that.”**

RapidAid turns any smartphone lock screen into a **life-saving medical ID**, showing essential details even when the phone is locked. It generates a beautifully designed emergency wallpaper containing medical information, responder instructions, and vCard-enabled emergency contacts. One scan of the QR code reveals everything in a clean, structured, universally readable format—**even if the user cannot speak for themselves.**

---

## 🌟 Why RapidAid Matters (Story + Impact)

During emergencies, **seconds matter**. When someone is unconscious or disoriented, responders have no access to their medical history, allergies, or emergency contacts. Phones stay locked, apps require permission, and precious time is lost.

**RapidAid solves this by bringing critical information to the surface.**

Your lock screen becomes a **silent first responder**:
- Shows essential medical details at a glance  
- Can be scanned instantly  
- Works on every phone, every OS  
- No installation, no unlock, no app, no backend  

A single scan reveals user-friendly, structured emergency information with the ability to **import contacts directly** using vCards.

---

## 🌐 Live Demo  
👉 **https://YOUR-USERNAME.github.io/rapidaid/**  
(Replace with actual deployed GitHub Pages URL)

---

# ✨ Features

### 🩺 **1. Emergency Card Wallpaper Generator**
- Generates a **1080×1920 portrait wallpaper** for any smartphone lock screen.  
- Clean, readable, modern layout (Option 2 spacing).  
- Fully offline — works entirely in the browser.

### 🎨 **2. Custom Wallpaper Options**
- Preloaded aesthetic portrait wallpapers  
- Upload wallpaper from phone gallery  
- Card styles:
  - **Solid**
  - **Translucent**
  - **Glass / Frosted blur (iOS-style)**  
- Adjustable transparency slider

### 🧩 **3. Auto Text Contrast**
The tool detects background color and automatically adjusts text color for best visibility — with manual overrides if needed.

### 📝 **4. Multi-format QR Payload (Human + Machine readable)**
QR code contains:

---

### **A. Human-Readable Block**
Example:

RapidAid Emergency Info
Name: Priya Sharma
Blood Group: O+
Age: 24
Allergies: Penicillin
Medications: Insulin
Instructions: Carry epipen

Emergency Contacts:
	1.	John – +91XXXX
	2.	Sister – +91XXXX

  This ensures **any QR scanner**, even the simplest ones, displays clean, readable information.

---

### **B. JSON Block**
Included under:

—JSON—
{
“name”: “…”,
“contacts”: [
{
“label”: “John Doe”,
“phone”: “+91XXXX”,
“vcard”: “BEGIN:VCARD\nVERSION:3.0\nFN:John Doe\nTEL:+91XXXX\nEND:VCARD”
}
]
}

This helps advanced QR apps parse data programmatically.

---

### **C. vCard Block**
Each emergency contact has a standalone vCard:

—VCARDS—
BEGIN:VCARD
VERSION:3.0
FN:John Doe
TEL:+91XXXX
END:VCARD

This ensures:
- iPhones can directly "Add to Contacts"  
- Android scanners support direct import  
- Universal compatibility  

---

# 🧪 How to Use

1. Fill out your medical & emergency info  
2. Choose a background template color  
3. Choose text color (auto or manual)  
4. Select wallpaper (or upload your own)  
5. Choose card style: Solid / Translucent / Glass  
6. Adjust transparency  
7. Click **Generate**  
8. Click **Download PNG**  
9. Set as lock-screen wallpaper

---

# 🛡 Privacy

- No data leaves your device  
- No network requests  
- All processing happens locally in the browser  
- Safe for medical/emergency info  

---


# 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open a PR.

---

# 📄 License

This project is **MIT Licensed** — free to use, modify, and distribute.

---

# ❤️ Credits

Created with care to help people carry vital emergency information  
directly on their lock-screen in a beautifully designed, accessible format.
