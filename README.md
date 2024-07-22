# Barba Brutal

Barba Brutal é uma aplicação criada para gerenciar agendamentos de serviços em uma barbearia. O projeto é composto por três partes principais: frontend, mobile e backend, desenvolvidas com Turborepo, utilizando Yarn como gerenciador de pacotes.

## Estrutura do Projeto

- **Frontend**: Desenvolvido com Next.js
- **Mobile**: Desenvolvido com React Native e Expo
- **Backend**: Desenvolvido com Nest.js

## Pré-requisitos

- Node.js (v14 ou superior)
- Yarn (v1.x)
- Expo CLI (para desenvolvimento mobile)

## Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/douglasrangel-stack/barba-brutal.git
    cd barba-brutal
    ```

2. Instale as dependências:
    ```sh
    yarn install
    ```


## Scripts

Para iniciar os aplicativos, use os seguintes comandos:

### Global

Para iniciar o servidor de desenvolvimento de todas as aplicações juntas:
```sh
yarn dev
```

### Frontend

Para iniciar o servidor de desenvolvimento do Next.js:
```sh
cd apps/frontend
yarn dev
```

### Mobile

Para iniciar o aplicativo mobile com Expo:
```sh
cd apps/mobile
expo start
```

### Backend

Para iniciar o servidor do Nest.js:
```sh
cd apps/backend
yarn start:dev
```

## Estrutura de Pastas

```
barba-brutal/
├── apps/
│   ├── frontend/   # Aplicação frontend (Next.js)
│   ├── mobile/     # Aplicação mobile (React Native com Expo)
│   └── backend/    # Aplicação backend (Nest.js)
├── packages/       # Pacotes compartilhados (se aplicável)
├── turbo.json      # Configuração do Turborepo
├── package.json    # Dependências principais
└── yarn.lock       # Arquivo de bloqueio do Yarn
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.