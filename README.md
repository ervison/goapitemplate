# goapitemplate





/project-root
│
├── /cmd                  # Entrypoints da aplicação
│   └── /api              # Pasta com o código principal da API
├── /internal             # Código interno da aplicação que não deve ser exportado
│   ├── /server           # Configuração do servidor
│   ├── /handlers         # Handlers de API (controladores)
│   ├── /services         # Lógica de negócio
│   ├── /repositories     # Interação com o banco de dados (DAO/Repository Pattern)
│   ├── /models           # Definição dos modelos/estruturas de dados
│   ├── /middlewares      # Middlewares da aplicação
│   ├── /routes           # Definição das rotas
│   └── /config           # Configurações globais (e.g., leitura de env)
│
└── /pkg                  # Pacotes reutilizáveis e exportáveis
