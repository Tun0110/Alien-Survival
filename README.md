# Alien Survival — Última Fronteira

## Rodar no computador
1. Instale Node.js.
2. Extraia o ZIP e abra a pasta no VS Code.
3. No terminal, rode `npm install`.
4. Copie `.env.example` para `.env` e defina uma senha forte para `ADMIN_SENHA` e uma chave longa para `SESSION_SECRET`.
5. Rode `npm start` e abra http://localhost:3000.

A conta administrativa é criada na primeira inicialização com os dados do `.env`. Não publique `.env` no GitHub. O arquivo `data.json` é criado automaticamente e está no `.gitignore`. Esse JSON serve para testes locais; para hospedagem pública, use banco persistente (por exemplo PostgreSQL) e armazenamento de sessão próprio para produção. As senhas são armazenadas com hash bcrypt.

Controles: W/A/S/D para mover; E/G/J/L/P/N para atacar. No celular, use os botões na tela.
