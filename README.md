# 🚘 ANPR (Automatic Number Plate Recognition) System using Django

This project is a complete Automatic Number Plate Recognition (ANPR) system built using **Python**, **Django**, **OpenCV**, and **EasyOCR**. It captures frames from uploaded videos, extracts vehicle number plates using OCR, and stores both the image and text in a database. An Excel report is generated with the extracted data and saved in the `media/` folder.

---
## 🙋‍♂️ Author

**Binanjay Dwibedee**   
[GitHub](https://github.com/BinanjayDwibedee/ANPR-Automatic-Number-Plate-Recognition) | [LinkedIn](https://www.linkedin.com/in/binanjaydwibedee/)


## 🛠 Features

- 🎥 Upload video for processing
- 📸 Extract frames (every 30th frame) using OpenCV
- 🔍 Detect and read number plates using EasyOCR
- 🗃 Save captured images and extracted text in a database
- 📄 Generate Excel report with images and number plate text
- 🌐 Simple web interface with Django

---

## 🚀 Technologies Used

- Python 3.12
- Django 5.x
- OpenCV
- EasyOCR
- Pillow
- openpyxl

---





## 📸 Demo screenshot/video

![Image](https://github.com/user-attachments/assets/d5f993c6-23d4-4c80-891c-6090e0f8a957)
![image](https://github.com/user-attachments/assets/d1807537-6cea-4079-858a-eb8d9902bfb6)


https://github.com/user-attachments/assets/836d8b50-86e3-4c83-98d6-9411b3fa1b44



https://github.com/user-attachments/assets/5ac9decd-f920-4de7-ad79-c5226ac65370



## 📁 Project Structure

![image](https://github.com/user-attachments/assets/4e4d1802-5678-4bc9-8897-ae53c0f770d2)

anpr_project/
├── anpr_project/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
├── detector/
│ ├── templates/
│ ├── static/
│ ├── views.py
│ ├── models.py
│ ├── urls.py
│ └── forms.py
├── media/
│ └── (uploaded frames & Excel report)
├── manage.py
└── README.md
##⚙️ Setup Instructions

```bash
# Clone repo
git clone https://github.com/yourusername/anpr_project.git
cd anpr_project

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install requirements
pip install -r requirements.txt

# Run database migrations
python manage.py makemigrations
python manage.py migrate

# Start server
python manage.py runserver 0.0.0.0:8000



## 📜 License


MIT License

Copyright (c) 2025 Binanjay Dwibedee

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


