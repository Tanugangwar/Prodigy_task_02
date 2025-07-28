# Prodigy InfoTech Internship - Task 02

## 🧩 Task: Pixel Manipulation for Image Encryption

This Python project allows users to **encrypt** and **decrypt** images using pixel manipulation techniques. Each pixel's RGB value is altered using a simple mathematical operation with a provided key.

---

## ⚙️ Features
- Encrypts images using RGB value shifting
- Decrypts back using inverse shift
- Works on PNG, JPG, BMP formats
- CLI-based input for file and key

---

## 📁 Files Included
- `pixel_encryptor.py` – Main Python code
- `README.md` – Documentation
- `LICENSE` – Open-source license
- `.gitignore` – Ignored files for Git

---

## ▶️ How to Run

1. Install required library:
   ```bash
   pip install pillow
   
2.Run the script:
```bash
python pixel_encryptor.py

3.Provide input:
Choose (e)ncrypt or (d)ecrypt: e
Enter the path to the image: sample.png
Enter encryption key (integer): 50

🔐 How It Works:
-For encryption: each RGB pixel (r, g, b) becomes ((r+key)%256, (g+key)%256, (b+key)%256)
-For decryption: subtract the key instead

👩‍💻 Author
Tanu Gangwar
B.Tech CSE, Galgotias University
Prodigy InfoTech Internship – Task 02
