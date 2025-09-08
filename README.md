
## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Bantrothudivya/contactform.git
   cd contactform

   python -m venv venv
venv\Scripts\activate   # On Windows

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py runserver
