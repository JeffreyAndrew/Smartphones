
$  docker-compose  -f docker-compose-dev.yml up -d --build

docker-compose -f docker-compose-dev.yml run users python manage.py recreate_db
