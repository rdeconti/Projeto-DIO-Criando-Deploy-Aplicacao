# Projeto-DIO-Criando-Deploy-Aplicacao

:spiral_calendar: Atualizado em 26 de Junho de 2025 :heart:

<img align="right" alt="GIF" height="160px" src="https://github.com/rdeconti/rdeconti-resources/blob/main/Digital%20Innovation%20One%20-%20Logotipo.png" />

Este projeto foi proposto pela Digital Innovation One  
- Link do código original: https://github.com/denilsonbonatti/k8s-projeto1-app-base  
- Professor: José Luiz Abreu Cardoso Junior  
- Aulas: [DIO](https://web.dio.me/lab/criando-um-deploy-de-uma-aplicacao/learning/9343edc6-01b7-44cf-a8bd-9741ee0d6a7c?back=/track/tonnie-java-and-ai-europe)

## Descrição
- Neste projeto será realizado um deploy de uma aplicação completa com frontend, backend e database mysql. No desenvolvimento do projeto serão criadas as imagens dos containeres e serviços necessários no kubernetes para que a aplicação esteja pronta para produção.

---

## Estrutura do Projeto

```
Projeto-DIO-Criando-Deploy-Aplicacao/
│
├── BACKEND/
│   └── ...código do backend...
│
├── FRONTEND/
│   └── ...código do frontend...
│
└── README.md
```

---

## BACKEND

### Descrição
O diretório `BACKEND` contém a API responsável pelo processamento dos dados da aplicação.  
Tecnologias utilizadas:
- Node.js (ou outra stack, conforme seu projeto)
- Express (ou framework equivalente)
- Conexão com banco de dados MySQL

### Como executar o backend

1. Acesse a pasta do backend:
    ```sh
    cd BACKEND
    ```
2. Instale as dependências:
    ```sh
    npm install
    ```
3. Configure as variáveis de ambiente (exemplo: `.env`):
    ```
    DB_HOST=localhost
    DB_USER=root
    DB_PASS=sua_senha
    DB_NAME=nome_do_banco
    ```
4. Inicie o servidor:
    ```sh
    npm start
    ```
5. O backend estará disponível em `http://localhost:3000` (ou porta configurada).

---

## FRONTEND

### Descrição
O diretório `FRONTEND` contém a interface web da aplicação.  
Tecnologias utilizadas:
- React (ou outra stack, conforme seu projeto)
- Consumo da API backend

### Como executar o frontend

1. Acesse a pasta do frontend:
    ```sh
    cd FRONTEND
    ```
2. Instale as dependências:
    ```sh
    npm install
    ```
3. Inicie a aplicação:
    ```sh
    npm start
    ```
4. O frontend estará disponível em `http://localhost:3001` (ou porta configurada).

---

## Observações

- Certifique-se de que o backend esteja rodando antes de iniciar o frontend.
- Para ambiente de produção, utilize os arquivos de configuração do Kubernetes presentes no projeto.

---

## Licença
    - MIT License