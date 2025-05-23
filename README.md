# Spotify Explorer

Este é o projeto Spotify Explorer, uma aplicação web que permite explorar dados musicais da API do Spotify utilizando apenas Client ID e Client Secret, sem necessidade de login do usuário final.

## Estrutura do Projeto

Esta versão do projeto está otimizada para deploy direto no Vercel, com o frontend na raiz do projeto.

## Funcionalidades

- Autenticação via Client Credentials do Spotify
- Exploração de gêneros musicais
- Listagem de artistas por gênero
- Visualização de álbuns por artista
- Listagem de músicas com detalhes
- Filtros avançados para atributos musicais:
  - BPM (tempo)
  - Energia
  - Valência (felicidade)
  - Dançabilidade
  - Acústica
  - Instrumental
  - Popularidade
  - Duração
- Ordenação por diversos critérios
- Visualizações gráficas de atributos musicais
- Modo escuro
- Interface responsiva

## Deploy no Vercel

1. Faça login na sua conta do [Vercel](https://vercel.com/)
2. Clique em "Add New" e selecione "Project"
3. Conecte sua conta do GitHub e selecione o repositório
4. Mantenha todas as configurações padrão (não altere o Root Directory)
5. Configure as variáveis de ambiente:
   - `VITE_API_URL`: https://spotify-explorer-backend.onrender.com/api
   - `VITE_NODE_ENV`: production
6. Clique em "Deploy"

## Backend

O backend deve ser implantado separadamente no Render.com. Os arquivos do backend estão disponíveis em um repositório separado.

## Uso

1. Obtenha suas credenciais do Spotify:
   - Acesse [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/)
   - Crie um novo aplicativo
   - Obtenha o Client ID e Client Secret
2. Insira as credenciais no formulário de login
3. Explore gêneros, artistas, álbuns e músicas
4. Utilize os filtros avançados para refinar sua busca
5. Visualize detalhes e atributos das músicas

## Desenvolvimento Local

1. Instale as dependências:
```bash
npm install
```

2. Crie um arquivo `.env` baseado no `.env.example`

3. Inicie o servidor de desenvolvimento:
```bash
npm run dev
```

## Licença

MIT
