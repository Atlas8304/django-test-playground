# django-test-playground
### Setup
1. Copy `.env.sample` to `.env`
1. Run `docker-compose up --build`
1. Create superuser `docker-compose exec web python manage.py createsuperuser`
1. Load Initial Data:
	- `docker-compose exec web python manage.py loaddata fixtures/users.json`
	- `docker-compose exec web python manage.py loaddata fixtures/blog.json`