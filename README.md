# Gaming Zone
(Gaming Zone)[https://projectgamingzone.netlify.app/] foi uma atividade prática desenvolvida como parte do curso FullStack de Codificação Front-End do SENAI.

---

## 🧱 Tecnologias Utilizadas

- **HTML5**: estrutura das páginas
- **CSS3 + Bootstrap 5**: estilização e responsividade
- **JavaScript**: lógica de login e interações
- **jQuery**: efeitos dinâmicos (cadastro e rolagem suave)

---

## 🏠 Página Home (`index.html`)

### Componentes principais:

- **Navbar responsiva** com links:
  - Promoções
  - Console
  - Jogos
  - Login (com link para `login.html`)
- **Carrossel de banners** com imagens e descrições
- **Seção "Mais Vendidos"** com 3 cards de produtos (imagem, descrição e botão de compra)
- **Rodapé estilizado**

### Estilização personalizada:

No `estilo.css`, foram aplicadas regras de centralização, tamanhos de imagem, espaçamento, cores e responsividade.

---

## 🔐 Página de Login (`login.html`)

### Componentes:

- **Navbar** (idêntica à da Home)
- **Formulário de Login** com validação:
  - Usuário: `admin`
  - Senha: `123456`
- **Botão "Voltar ao Topo"** com rolagem suave
- **Seção de Cadastro** que aparece ao clicar em "Não é cadastrado ainda? Cadastre-se"

---

## 🚀 Futuras Funcionalidades para Prática

Este projeto foi desenvolvido como acompanhamento de um curso, e agora serve como base para explorar e praticar novas habilidades. Abaixo estão algumas funcionalidades que podem ser implementadas futuramente para continuar evoluindo com o projeto, tanto no front quanto no back-end:

### 🔐 Autenticação de Usuários
- Implementar sistema de login e registro (ex: Firebase, Auth0, ou API própria).
- Diferenciar usuários autenticados e não autenticados, permitindo por exemplo salvar favoritos ou deixar comentários apenas para usuários logados.

### 🧾 Sistema de Avaliações ou Comentários
- Permitir que os usuários deixem comentários ou avaliações sobre os jogos.
- Ideal para praticar operações de CRUD e integração com um backend.

### ❤️ Favoritos ou Lista de Desejos
- Adicionar funcionalidade para marcar jogos como favoritos.
- Criar uma seção "Minha Lista" personalizada para cada usuário.

### 🕹️ Página de Detalhes para Cada Jogo
- Criar uma página individual com mais informações sobre cada jogo (ex: descrição, trailer, screenshots).
- Treina rotas dinâmicas e estrutura de dados mais complexa.

### 🎮 Integração com APIs de Jogos
- Substituir dados estáticos por dados reais utilizando APIs como:
  - [RAWG Video Games Database](https://rawg.io/apidocs)
  - [IGDB](https://api-docs.igdb.com/)
- Trabalha fetch/axios, estados de loading, tratamento de erros, entre outros.

### 🗂️ Filtros e Busca Avançada
- Criar filtros por gênero, nota, plataforma etc.
- Implementar uma barra de busca funcional com debounce para melhorar a performance.

### 🎨 Painel Admin
- Criar uma área protegida para que apenas administradores possam adicionar, editar ou excluir jogos.
- Bom para treinar permissões e formulários complexos.

### 📱 Responsividade e PWA
- Aprimorar a experiência mobile.
- Transformar o projeto em um **Progressive Web App** (instalável no celular), utilizando manifest.json e Service Workers.

### 🧠 Recomendações Inteligentes
- Sugerir jogos similares com base no histórico do usuário (favoritos, visualizações).
- Começar com uma lógica simples baseada em gênero e depois avançar para algo mais inteligente.

### 📈 Analytics Simples
- Adicionar estatísticas como jogos mais visitados, mais favoritados, etc.
- Pode-se usar Google Analytics ou construir uma dashboard própria com gráficos (Chart.js, Recharts).

---

### 📌 Qual o Próximo Passo?
Essas ideias podem ser organizadas e priorizadas conforme os objetivos de aprendizado:
- **Front-end:** focar em UI, responsividade, animações, roteamento e integração com APIs.
- **Back-end:** explorar banco de dados, autenticação, permissões e lógica de recomendação.
- **Fullstack:** juntar as duas pontas, criar experiências completas e seguras.
- **UX/UI Design:** melhorar a experiência do usuário, acessibilidade e identidade visual.

A ideia é seguir evoluindo o projeto de forma prática e contínua. 😄🎯

