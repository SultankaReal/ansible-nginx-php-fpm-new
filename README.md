# Цель: дополнить роль из проекта ansible-nginx-php-fpm: пусть DocumentRoot будет в директории /opt/nginx/ansible, использовать handler для перечитывания конфигурации nginx.

## Создана роль в /etc/ansible/roles (/roles/main.yml в проекте)

## Создан playbook в /etc/ansible/playbooks (/playbooks/nginx_php_fpm.yml в проекте)

## nginx.conf - конфигурационный файл nginx 

## Изменен DocumentRoot в nginx.conf и в main.yml

## handler создан в /etc/ansible/playbooks (/playbooks/nginx_php_fpm.yml в проекте) для перечитывания конфигурации nginx

# Применение:
ansible-playbook /etc/ansible/playbooks/nginx_php_fpm.yml
