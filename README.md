Репозиторий создан для видео , которая опубликовано на дзене.
Инсталяция роли ansible-galaxy install -r requirements.yml -p ./roles/
Запуск плейбука ansible-playbook -k -K -i inventory main.yml
Переменные для конфигуриования инвентари файла 
harbortest ansible_host=10.1.1.208 ansible_user=siadmin ansible_password= ansible_become=true ansible_become_password=
