# CRUD de Tarefas

Projeto com frontend em React Native/Expo e API em Node.js, Express e MongoDB.

## Estrutura

- `frontend/`: aplicativo Expo.
- `backend/`: API REST e conexão com MongoDB.

## Como executar

### Backend

1. Abra um terminal na pasta `backend` e instale as dependências:

   ```bash
   npm install
   ```

2. Crie o arquivo `.env` com base em `.env.example` e informe sua própria `MONGO_URI`. Não publique esse arquivo nem compartilhe sua string de conexão.
3. Inicie a API:

   ```bash
   npm start
   ```

### Frontend

1. Em outro terminal, abra a pasta `frontend` e instale as dependências:

   ```bash
   npm install
   ```

2. Configure `API_URL` em `App.js` para o endereço da API no dispositivo ou navegador.
3. Inicie o app web:

   ```bash
   npm run web
   ```

Consulte os READMEs de cada pasta para os detalhes de configuração.
