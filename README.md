# 🎴 Cards Commander - Informações Gerais
---

## 📂 Estrutura do Projeto

```bash
├── src/                          # Código-fonte principal
│   ├── controller/               # Controladores da API
│   ├── middleware/               # Middlewares de autenticação e validação
│   ├── schema/                   # Esquemas de dados para validação
│   ├── service/                  # Lógica de negócios e serviços
│   └── test/                     # Testes automatizados para a API
├── cardsCommander.cards.json      # Armazenamento de cards
├── README.md                      # Documentação principal do projeto
├── jest.config.js                 # Configuração do Jest para testes
└── package.json                   # Gerenciamento de dependências
```

- **Controladores (`controller`)**: Arquivos responsáveis por definir como as rotas da API são tratadas.  
- **Middlewares (`middleware`)**: Módulos intermediários que verificam autenticação, autorização e outras lógicas antes de processar as requisições.
- **Esquemas (`schema`)**: Definem a estrutura e validação dos dados que a API manipula.
- **Serviços (`service`)**: Lógica de negócios que faz a ponte entre os controladores e a persistência de dados.
- **Testes (`test`)**: Conjunto de testes para garantir a integridade da API e suas funcionalidades.

---
## 🚀 Recursos Principais

- **📦 Armazenamento de Cards:**  
  Todos os cards estão salvos no arquivo:  
  [`cardsCommander.cards.json`](./cardsCommander.cards.json) 📂  

- **🌐 Rotas da API:**  
  As rotas estão definidas em [`routes.ts`](./routes.ts).  
  Para obter os 100 cards disponíveis, utilize a rota:  
  ```bash
  GET /cards
  ```  

- **🔐 Autenticação & Autorização:**  
  O sistema de autenticação e autorização garante que **apenas** usuários autenticados e autorizados possam criar ou editar seus baralhos. Segurança em primeiro lugar! 🛡️

## 🧪 Testes

- **Verificação de Regras de Negócio & Endpoints:**  
  Temos uma suíte de testes completa para garantir o funcionamento da API, incluindo a verificação de regras de negócio e validação dos endpoints. Para rodar os testes:  
  ```bash
  npm test
  ```  
  *(Dica: você pode usar `npm run test:verbose` para obter um relatório mais detalhado dos testes!)*
  

## 📚 Documentação Adicional
Para informações mais detalhadas, visite a [Documentação Completa](./docs/README.md) ou confira o [Guia de Contribuição](./CONTRIBUTING.md). 
