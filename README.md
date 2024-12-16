# NestJS Users API

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/samuelikz/nestjs_users.svg)](https://github.com/samuelikz/nestjs_users/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/samuelikz/nestjs_users.svg)](https://github.com/samuelikz/nestjs_users/issues)

## 📝 Descrição do Projeto

Este é um projeto de API de Gerenciamento de Usuários desenvolvido com NestJS, oferecendo operações CRUD completas e autenticação segura. A aplicação foi projetada para ser escalável, eficiente e seguir as melhores práticas de desenvolvimento de software.

## 🚀 Funcionalidades Principais

- Registro de novos usuários
- Autenticação com JWT (JSON Web Token)
- Atualização de perfil de usuário
- Listagem e detalhamento de usuários
- Exclusão de usuários
- Validação robusta de dados
- Documentação de API com Swagger

## 🛠️ Tecnologias Utilizadas

- **Backend**
  - NestJS
  - TypeScript
  - TypeORM
  - PostgreSQL
  - JWT para autenticação
  - Swagger para documentação de API
  - Class Validator para validações

- **Ferramentas de Desenvolvimento**
  - Docker
  - Jest (testes)
  - ESLint
  - Prettier

## 📋 Pré-requisitos

- Node.js (v16 ou superior)
- Docker (opcional, para containerização)
- PostgreSQL

## 🔧 Instalação

### Clone o Repositório
```bash
git clone https://github.com/samuelikz/nestjs_users.git
cd nestjs_users
```

### Instale as Dependências
```bash
npm install
```

### Configuração do Ambiente
1. Crie um arquivo `.env` na raiz do projeto
2. Adicione as seguintes variáveis:
```
DATABASE_URL=postgresql://usuario:senha@localhost:5432/nome_do_banco
JWT_SECRET=sua_chave_secreta_aqui
PORT=3000
```

### Execute as Migrações
```bash
npm run migration:run
```

### Inicie o Servidor
```bash
npm run start:dev
```

## 🐳 Docker

### Construir Imagem
```bash
docker build -t nestjs-users .
```

### Executar Container
```bash
docker run -p 3000:3000 nestjs-users
```

## 🧪 Testes

### Executar Testes Unitários
```bash
npm run test
```

### Executar Testes de Cobertura
```bash
npm run test:cov
```

## 📖 Documentação da API

Após iniciar o servidor, acesse a documentação do Swagger:
`http://localhost:3000/api`

## 🚀 Deploy

Plataformas recomendadas:
- Heroku
- DigitalOcean
- AWS
- Railway
- Vercel

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

## ⚖️ Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

Samuel - [LinkedIn](https://www.linkedin.com/in/samuel-nunes-da-silva-057899133/)

Link do Projeto: [https://github.com/samuelikz/nestjs_users](https://github.com/samuelikz/nestjs_users)

---

**Desenvolvido com ❤️ por Samuel Silva**
