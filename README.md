# AULAML
# Repositório para as atividades da disciplina Inteligência Artificial.

Professor José Walmir Gonçalves Duque

Set-ExecutionPolicy Unrestricted

cd "C:\AULAML"

python -m venv venv

venv\scripts\activate

pip install pandas

pip install notebook

pip freeze > requirements.txt

pip install pandas seaborn

pip install -r requirements.txt

O ChatGPT disse:
# AULAML

Este repositório contém instruções completas para configurar o ambiente Front-end, Back-end e AI utilizados nas aulas de Machine Learning.

---

## 🔹 Front-end

📌 **Crie um arquivo `.env` na raiz do front-end com:**

```env
VITE_API_URL=http://localhost:8080
```

▶️ Executando o Front-end
cd nutrition-project/src

npm install
npm run dev

🔹 Back-end
▶️ Executando o Back-end
# Instale o Maven globalmente
# Conecte ao Postgres na porta 5432 (pgAdmin ou SQLTools no VSCode)
# Configure o arquivo application.properties com os dados da sua conexão.
mvn spring-boot:run

🔹 AI (Machine Learning / RAG / Python)
▶️ Criar ambiente virtual
# Requer Python 3.10
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv/Scripts/activate       # Windows

▶️ Instalar dependências
pip install -r requirements.txt


📌 Crie um arquivo .env para a AI com:

GEMINI_API_KEY=<SuaChave>
GOOGLE_AI_VERTEX=FALSE

▶️ Executar a API de IA
uvicorn app:app --reload --port 8001
