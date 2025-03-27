# Django AWS Deployment

Este projeto faz parte de uma atividade da faculdade, onde foi necessário desenvolver uma aplicação Django e hospedá-la na AWS.

### 🚀 Tecnologias Utilizadas

- 🐍 Python 3.12

- 🌍 Django

- 🛢️ SQLite3

- ☁️ AWS EC2

- 🐳 Docker (opcional)

### 📦 Configuração do Ambiente

🔹 1. **Clonar o Repositório**
```bash
git clone https://github.com/joaogkt/atividadeAWS.git
cd atividadeAWS
```

🔹 2. **Criar e Ativar um Ambiente Virtual**
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```

🔹 3. **Instalar Dependências**
```bash
pip install -r requirements.txt
```

🔹 4. **Aplique as migrações**
```bash
python manage.py migrate
```

🔹 5. **Configuração na AWS**

A aplicação foi hospedada na AWS usando EC2. Os passos incluem:

- Criar uma instância EC2
- Configurar regras de firewall para liberar a segurança na porta 8000

🔹 6. **Executar a Aplicação Localmente**
```bash
python manage.py runserver
```

Acesse http://127.0.0.1:8000/ no navegador.

### 📝 **Notas Finais**

🔒 Certifique-se de configurar corretamente as permissões de segurança no AWS Security Groups

### 👤 Autor

📌 João Gabriel Torres - RGM: 28017188 - [Github](https://github.com/joaogkt)

🔑 Utilize variáveis de ambiente para armazenar credenciais sensíveis

📊 Configurar logs e monitoramento para acompanhar erros e desempenho da aplicação

👤 Autor

📌 Seu Nome - Seu GitHub
