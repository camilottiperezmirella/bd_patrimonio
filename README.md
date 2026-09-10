# bd_patrimonio

API para cadastro e gerenciamento de patrimônios, armazenando item, local, data de registro, valor e código do patrimônio.
Instalação e execução
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_PROJETO>
npm install
npm start

A API estará disponível em
http://localhost:3000

Tecnologias
Node.js
[Framework utilizado]
JSON
[Banco de dados, se houver]

Rotas
Método	  Rota	        Função
GET	/patrimonios	Lista patrimônios
GET	/patrimonios/:id	Consulta patrimônio
POST	/patrimonios	Cadastra patrimônio
PUT	/patrimonios/:id	Atualiza patrimônio
DELETE	/patrimonios/:id	Exclui patrimônio

Exemplo de requisição
POST /patrimonios
Content-Type: application/json
{
  "item": "Notebook Dell",
  "local": "Laboratório 01",
  "dataRegistro": "2026-09-10",
  "valor": 3500.00,
  "patrimonio": "PAT-00125"
}

Exemplo de resposta
{
  "item": "Notebook Dell",
  "local": "Laboratório 01",
  "dataRegistro": "2026-09-10",
  "valor": 3500.00,
  "patrimonio": "PAT-00125"
}
Exemplos de patrimônios
PAT-00125 — Notebook Dell — R$ 3.500,00
PAT-00123 — Celular Iphone — R$ 4.500,00
PAT-00555 — Tablet Samsung — R$ 1.500,00
PAT-00856 — Alexa Smart Speaker — R$ 500,00
