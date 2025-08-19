
# Portfolio app (models, serializers, tests)

Arquivos prontos para colar em um projeto Django com DRF.

## Instalação
1. Adicione `'rest_framework'` e `'portfolio'` em `INSTALLED_APPS`.
2. Rode migrações:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
3. Rode os testes:
   ```bash
   python manage.py test portfolio -v 2
   ```

Modelos: Tag, Technology, Project, ProjectLink, Experience, Education  
Serializers: correspondentes + `ProjectSerializer` com `links` aninhados.
