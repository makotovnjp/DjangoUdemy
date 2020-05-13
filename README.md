# DjangoUdemy
DjangoUdemy

# 手順
1. cd project_practice

1. First time to create project
    - sudo docker-compose run app sh -c "django-admin.py startproject app ."
    
1. From second time 
    - sudo docker-compose run app 
    
# Dockerなしでの手順
1. django-admin.py startproject app .

2. python manage.py startapp core

# テスト手順
1. Test Command
    - python manage.py test && flake8

