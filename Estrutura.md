# Estrutura do Projeto (Centel App)

A arquitetura do projeto foi desenhada visando modularidade, clareza e separação de responsabilidades. 
O sistema é dividido nas seguintes camadas principais dentro de `src/app/`:

centel-app/
├── src/
│   ├── app/
│   │   ├── core/                  # Serviços globais e essenciais.
│   │   ├── enums/                 # Valores constantes e padronizados do sistema.
│   │   ├── features/              # Funcionalidades principais (Telas).
│   │   ├── models/                # Interfaces e tipagens de dados.
│   │   ├── shared/                # Elementos visuais reutilizáveis.
│   │   ├── utils/                 # Funções utilitárias puras.
│   │
│   └── environments/              # Configurações de ambiente.