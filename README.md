# Django Login form in Bootstrap 4 modal

Ajax login form rendering and updating in Bootstrap 4 modal is based on blogpost from Derek Morgan.
https://dmorgan.info/posts/django-views-bootstrap-modals/.

## Running Locally

### 1. Setup

```bash
git clone https://github.com/trco/django-bs4-modal-login.git
```

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

### 2. Testing Login modal

```bash
python manage.py runserver
```
#### Login credentials

| User role     | Username     | Password     |
| :-------------|:-------------|:-------------|
| User          | user1234     | demo1234     |
| Admin         | admin1234    | demoadmin    |



After you are logged in as Admin you can create new Users at http://127.0.0.1:8000/admin/.
