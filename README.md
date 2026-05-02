# 📸 FrameIt — Polaroid Image Editor

FrameIt is a lightweight web application for generating customizable Polaroid-style images. It provides real-time editing capabilities, allowing users to upload photos, apply visual filters, add captions, and export high-quality styled images directly from the browser.

---

## 🖼️ Preview
<img width="795" height="896" alt="Screenshot 2026-05-02 222812" src="https://github.com/user-attachments/assets/837f5e58-6562-4326-98b8-d9f1fb3ac38a" />
<img width="729" height="915" alt="Screenshot 2026-05-02 222825" src="https://github.com/user-attachments/assets/5665896a-68f2-4246-a442-f55d98846042" />


---

## 🚀 Key Features

- Image upload with instant preview  
- Custom captions with selectable typography  
- Optional date labeling for contextual metadata  
- Fine-grained image adjustments:
  - Blur
  - Brightness
  - Contrast
  - Saturation
  - Grayscale  
- Predefined visual presets:
  - Normal
  - Vintage
  - Black & White
  - Lomo  
- Frame and layout customization:
  - Frame color
  - Background color
  - Shadow intensity
  - Rotation (tilt)  
- Real-time UI updates with no page reloads  
- Export functionality:
  - Styled Polaroid (PNG)
  - Original uploaded image  

---

## 🛠️ Technology Stack

| Layer        | Technology            |
|-------------|----------------------|
| Frontend    | HTML5, CSS3          |
| Logic       | Vanilla JavaScript   |
| Rendering   | html2canvas          |

---

## ⚙️ Architecture Overview

- **FileReader API** is used to load images client-side  
- **CSS filters** handle all visual transformations  
- **DOM manipulation** ensures real-time UI updates  
- **html2canvas** captures the styled component and converts it into a downloadable image  

---

## ▶️ Getting Started

### Clone the repository
```bash
git clone https://github.com/your-username/frameit.git
---
```

Author
keerthi
