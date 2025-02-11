# API Escola


## ⚙ Configuração do Ambiente Virtual (venv)

Para garantir um ambiente de desenvolvimento limpo e isolado, é recomendável usar um ambiente virtual do Python. Siga as etapas abaixo para configurar e ativar o ambiente virtual:

1. **Abra o terminal e navegue até o diretório raiz do projeto.**
2. **Crie um novo ambiente virtual dentro do diretório do projeto:**

   ```bash
   python -m venv venv
   ```

3. **Ative o ambiente virtual:**

   - No Windows:

     ```bash
     venv\Scripts\activate
     ```

   - No macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

4. **Agora você está no ambiente virtual, onde pode instalar as dependências necessárias para o funcionamento do projeto.**

## Instalando Dependências

Certifique-se de que o ambiente virtual está ativado antes de prosseguir. Execute o seguinte comando para instalar todas as dependências listadas no arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Migrações do Banco de Dados

Antes de iniciar a aplicação, é necessário aplicar as migrações ao banco de dados. Certifique-se de estar no diretório raiz do projeto e com o ambiente virtual ativado. Em seguida, execute os seguintes comandos:

```bash
python manage.py makemigrations
python manage.py migrate
```

## Executando o Servidor de Desenvolvimento

Após aplicar as migrações, você pode iniciar o servidor de desenvolvimento do Django. Execute o seguinte comando:

```bash
python manage.py runserver
```

O servidor estará disponível em `http://127.0.0.1:8000/`. Você pode acessar esse endereço no seu navegador para interagir com a aplicação.

## 📚 Estrutura do Projeto

A estrutura básica do projeto é a seguinte:

```
drf-escola-curso-01/
├── escola/
│   ├── migrations/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── setup/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── .gitignore
├── manage.py
└── requirements.txt
```

- **escola/**: Contém a aplicação principal, incluindo modelos, visualizações, serializadores e URLs.
- **setup/**: Contém as configurações do projeto Django.
- **manage.py**: Script de utilidade que permite interagir com o projeto de várias maneiras.

## 🤝 Contribuição

Se você deseja contribuir para este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request. Toda contribuição é bem-vinda!

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="![WhatsApp Image 2023-01-31 at 10 52 47 (1)](https://github.com/user-attachments/assets/430109f9-1127-4cf3-a823-c29d32ecea76)"
    />
    <p>&nbsp&nbsp&nbspDayane Teodoro<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/Dayanebiaerafa">
    GitHub</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/dayaneteodoro/
felipe-exe">LinkedIn</a>
&nbsp;|&nbsp;
    <a href="https://www.instagram.com/dayane_cie/">
    Instagram</a>
&nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p>


💞 Feito com amor por Dayane Teodoro⁉ 


