# Django-igti
Repositório para a primeira aula interativa - IGTI - com o framework Django

## Roteiro utilizado na aula: 
- Criar módulo serie
	python manage.py startapp serie
- Adicionar módulo 'serie' no settings do projeto principal
- Registrar URL no projeto principal
- Criar arquivo serie/urls.py e redirecionar para view
- Criar método para cadastrar
- Testar nova rota com o 'hello world!'
- Criar template para o módulo 'serie'
- Testar view módulo 'serie'
- Alterar menu.html
- Criar Model 'serie'
- Registrar Model 'serie' no serie/admin.py
- Criar a migration
	python manage.py makemigrations serie
- Executar a migration
	python manage.py migrate
- Criar Form 'serie'
- Alterar o serie.html e testar o projeto
- Alterar o método cadastrar da view para renderizar o form e os dados
- Criar método para deletar
- Registrar url para deletar
- Criar página update.html
- Criar método para update
- Registrar url para update
