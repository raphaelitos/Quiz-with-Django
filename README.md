# Django Quiz App

Este é um projeto básico de quiz desenvolvido com Django e Vue.js. O aplicativo permite que os usuários participem de um quiz e recebam feedback sobre suas respostas.

## Configuração do Ambiente de Desenvolvimento

**Clone o Repositório:**
    ```bash
    git clone https://github.com/seu-usuario/django-quiz-app.git
    cd django-quiz-app
    ```

**Crie e Ative o Ambiente Virtual:**
    ```bash
    python -m venv venv
    # No Windows:
    venv\Scripts\activate
    # No macOS e Linux:
    source venv/bin/activate
    ```


**Execute as Migrações e o Servidor de Desenvolvimento:**
    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

O aplicativo estará disponível em [http://localhost:8000/](http://localhost:8000/).

## Dependências

Certifique-se de ter as seguintes dependências instaladas no seu ambiente de desenvolvimento:

- Django (e as "django-extensions")
- Vue.js
- Bootstrap
  
Instale as dependências Python usando `pip` e as dependências JavaScript usando `npm`.
