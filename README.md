# residential-issue-reporting-portal-public-bridge


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/residential-issue-portal.git
   cd residential-issue-portal
2. Create & activate virtual environment

python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

3. Install dependancies

pip install -r requirements.txt

4. Apply migrations & Create SuperUser

   python manage.py migrate
   python manage.py createsuperuser

5. To Run Server

   python manage.py runserver

6. Open the Web app in browser:

    http://127.0.0.1:8000/
