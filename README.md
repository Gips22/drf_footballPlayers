Проект с использованием DRF.
2 модели: футбольные игроки и клубы. 

По ходу реализации проекта, использовались различные типы views. В комментариях указаны предыдущие варианты. Финальный вариант с использованием нескольких представлений для обработки urls вместо компактного общего view  с router для нескольких path необходим для возможности использовать кастомные permissions, пагинацию и аутентификацию под каждую отдельную view.

Использовался python3.10

А также:

asgiref==3.5.2
certifi==2022.9.24
cffi==1.15.1
charset-normalizer==2.1.1
coreapi==2.3.3
coreschema==0.0.4
cryptography==38.0.3
defusedxml==0.7.1
Django==4.1.3
django-rename-app==0.1.3
django-templated-mail==1.1.1
djangorestframework==3.14.0
djangorestframework-simplejwt==4.8.0
djoser==2.1.0
idna==3.4
itypes==1.2.0
Jinja2==3.1.2
MarkupSafe==2.1.1
oauthlib==3.2.2
psycopg2-binary==2.9.5
pycparser==2.21
PyJWT==2.6.0
python3-openid==3.2.0
pytz==2022.6
requests==2.28.1
requests-oauthlib==1.3.1
six==1.16.0
social-auth-app-django==4.0.0
social-auth-core==4.3.0
sqlparse==0.4.3
uritemplate==4.1.1
urllib3==1.26.13