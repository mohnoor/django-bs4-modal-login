# Django Login form in Bootstrap 4 modal

Ajax login form rendering and updating in Bootstrap 4 modal is based on blogpost from Derek Morgan.
https://dmorgan.info/posts/django-views-bootstrap-modals/.

## Running Locally

```bash
git clone https://github.com/trco/django-bs4-modal-login.git
```

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

```bash
python manage.py createsuperuser
```
Follow the instructons for creating a superuser.

```bash
python manage.py runserver
```
Login with selected Username and Password in previous step.
