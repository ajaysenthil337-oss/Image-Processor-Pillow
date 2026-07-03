# 🖼️ Professional Image Processor

A full-featured, production-ready image processing web application built with **Python Flask** and **Pillow (PIL)**. Features a modern, responsive SaaS-style interface with dark/light theme support.

---

## ✨ Features

| Feature | Description |
|---|---|
| **Upload** | Drag & drop or file picker — supports JPG, JPEG, PNG (up to 16 MB) |
| **Resize** | Custom width & height with high-quality Lanczos resampling |
| **Rotate** | 0°–360° rotation with expandable canvas |
| **Grayscale** | One-click colour to grayscale conversion |
| **Flip Horizontal** | Mirror the image along the vertical axis |
| **Flip Vertical** | Mirror the image along the horizontal axis |
| **Blur** | Gaussian blur with adjustable radius (0–50) |
| **Sharpen** | Adjustable sharpness factor (0–10) |
| **Brightness** | Adjustable brightness factor (0–5) |
| **Crop** | Pixel-precise cropping with left / top / right / bottom inputs |
| **Preview** | Side-by-side original vs. processed comparison |
| **Download** | One-click download of the processed image |
| **Dark / Light Theme** | Toggle with localStorage persistence |

---

## 🛠️ Technologies Used

- **Backend:** Python 3, Flask
- **Image Processing:** Pillow (PIL)
- **Frontend:** HTML5, CSS3 (custom properties, glassmorphism, animations), Vanilla JavaScript
- **Icons:** Lucide Icons (CDN)
- **Typography:** Inter (Google Fonts)

---

## 📂 Folder Structure

```
ImageProcessor/
│
├── app.py                  # Flask application & API routes
├── requirements.txt        # Python dependencies
├── README.md               # Project documentation
│
├── templates/
│   └── index.html          # Main HTML template
│
└── static/
    ├── css/
    │   └── style.css       # Design system & all styles
    ├── js/
    │   └── app.js          # Frontend application logic
    ├── uploads/            # Uploaded images (auto-created)
    └── processed/          # Processed images (auto-created)
```

---

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Steps

1. **Clone / Download the project**
   ```bash
   cd ImageProcessor
   ```

2. **Create a virtual environment (recommended)**
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS / Linux
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Run Instructions

```bash
python app.py
```

The server starts at **http://10.71.243.211:5000**. Open this URL in your browser.

---

## 📸 Screenshots

> _Add screenshots of the running application here._

| View | Screenshot |
|---|---|
|<img width="1918" height="1093" alt="image" src="https://github.com/user-attachments/assets/f62bfae7-ae8f-4831-aef6-f41ebb808777" />
<img width="1915" height="1083" alt="image" src="https://github.com/user-attachments/assets/622d5d97-62ed-4066-8856-55cc01dc3cca" />
<img width="1915" height="1087" alt="image" src="https://github.com/user-attachments/assets/e1300efe-86ed-41dc-99f3-a1fd0c62fefa" />
<img width="1917" height="1080" alt="image" src="https://github.com/user-attachments/assets/0023ef2d-f9a3-4ec5-896c-3192558949c0" />




---

## 🔮 Future Scope

- **Batch Processing** — Process multiple images at once
- **History Panel** — View and re-download previous processed images
- **Filters & Effects** — Sepia, emboss, edge detection, contour
- **Watermarking** — Add text or image watermarks
- **Format Conversion** — Convert between JPG, PNG, WEBP, BMP
- **AI Features** — Background removal, super-resolution upscaling
- **User Accounts** — Authentication & personal image library
- **Cloud Storage** — Save images to AWS S3 / Google Cloud Storage
- **REST API** — Expose processing endpoints for external integrations

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">
  Built with ❤️ using Flask & Pillow
</p>
