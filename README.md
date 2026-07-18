# ⚔️ TCG Templar

> Um jogo de cartas colecionáveis para web, com abertura de pacotes, coleção, criação de decks, heróis, batalhas e troca de cartas entre jogadores.

![Status](https://img.shields.io/badge/status-Em%20Desenvolvimento-orange)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![Supabase](https://img.shields.io/badge/Supabase-Database-3ECF8E?logo=supabase)
![Vercel](https://img.shields.io/badge/Vercel-Deployed-black?logo=vercel)

---

## 🌐 Acesse o projeto

- 🎮 **TCG Templar:** https://tcg-templar.vercel.app/
- 🔐 **Cadastro pela TemplarChoice:** https://templarchoice.vercel.app/

> Para entrar no jogo, é necessário possuir uma conta cadastrada na TemplarChoice.

---

## 📖 Sobre o projeto

O **TCG Templar** é um projeto pessoal desenvolvido para criar uma experiência completa de jogo de cartas colecionáveis no navegador.

O jogador pode abrir pacotes temáticos, aumentar sua coleção, montar decks, desbloquear heróis, disputar batalhas e trocar cartas com outros jogadores.

O projeto também funciona como um laboratório prático para autenticação, banco de dados, gerenciamento de estado, regras de jogo e integração entre aplicações utilizando React, Supabase e Vercel.

A interface foi recentemente redesenhada para oferecer uma experiência mais moderna, minimalista, organizada e confortável tanto no desktop quanto no mobile.

---

# ✨ Funcionalidades

## 👤 Conta e perfil

- Login integrado à TemplarChoice
- Persistência de sessão
- Perfil do jogador
- Sistema de experiência e níveis
- Lista de amizades

## 🎴 Cartas e coleção

- Coleção completa de cartas
- Diferentes raridades
- Visualização detalhada das cartas
- Identificação de cartas bloqueadas
- Organização visual da coleção

## 🎁 Pacotes

- Seleção de pacotes temáticos
- Abertura animada
- Pacotes gratuitos diários
- Probabilidades de raridade
- Exibição das cartas recebidas

## 🧩 Construção de decks

- Criação e edição de decks
- Seleção de cartas da coleção
- Visualização das cartas adicionadas
- Seleção de deck antes da batalha
- Seleção de herói para cada deck

## 🦸 Heróis

- Loja de heróis
- Compra e desbloqueio
- Seleção de herói para o deck

## ⚔️ Batalhas

- Batalhas contra CPU
- Seleção de modos de jogo
- Sistema de energia por turno
- Campo de batalha interativo
- Estratégia baseada em cartas, heróis e composição de deck

## 🔄 Troca de cartas

- Tela exclusiva para trocas
- Seleção das cartas oferecidas
- Seleção das cartas solicitadas
- Envio de propostas para outros jogadores
- Acompanhamento de trocas pendentes
- Aceitação ou recusa de propostas
- Notificações sobre o status das trocas

---

# 🖼️ Novo visual

## Login

![Tela de login](./screenshots/tela%20de%20login.png)

---

## Tela inicial

![Tela inicial](./screenshots/tela%20inicial%201.png)

![Continuação da tela inicial](./screenshots/tela%20inicial%202.png)

---

## Seleção de pacotes

![Seleção de booster](./screenshots/sele%C3%A7%C3%A3o%20de%20booster.png)

---

## Abertura de pacote

![Cartas recebidas ao abrir o pacote](./screenshots/cartas%20ao%20abrir%20o%20pacote.png)

---

## Coleção de cartas

![Coleção de cartas](./screenshots/cole%C3%A7%C3%A3o%20das%20cartas.png)

---

## Construção de deck

![Construção do deck](./screenshots/constru%C3%A7%C3%A3o%20do%20deck.png)

---

## Seleção de deck

![Seleção de deck](./screenshots/sele%C3%A7%C3%A3o%20de%20deck.png)

---

## Loja de heróis

![Loja de heróis](./screenshots/loja%20de%20herois.png)

---

## Modos de batalha

![Seleção de modo de batalha](./screenshots/sele%C3%A7%C3%A3o%20de%20modo%20de%20batalha.png)

---

## Campo de batalha

![Campo de batalha](./screenshots/campo%20de%20batalha.png)

---

## Troca de cartas

![Troca de cartas](./screenshots/troca%20de%20cartas.png)

---

# 🛠 Tecnologias

## Front-end

- React
- JavaScript
- CSS
- Vite

## Back-end e banco de dados

- Supabase
- PostgreSQL
- Supabase Auth

## Deploy

- Vercel

## Ferramentas

- Git
- GitHub
- Figma
- VS Code

---

# 🏗 Arquitetura

```text
Usuário
   │
   ├── TemplarChoice
   │      └── Cadastro e autenticação
   │
   └── TCG Templar
          ├── React
          ├── Supabase Auth
          ├── PostgreSQL
          └── Vercel
```

---

# 🚀 Roadmap

## ✅ Concluído

- [x] Sistema de autenticação
- [x] Perfil do jogador
- [x] Sistema de experiência e níveis
- [x] Abertura de pacotes
- [x] Coleção de cartas
- [x] Construção de decks
- [x] Loja e seleção de heróis
- [x] Batalhas contra CPU
- [x] Sistema de energia por turno
- [x] Sistema de amizades
- [x] Troca de cartas entre jogadores
- [x] Notificações de trocas
- [x] Redesign das principais telas
- [x] Melhorias no layout mobile
- [x] Deploy na Vercel

## 🚧 Em desenvolvimento

- [ ] Melhorias no balanceamento das cartas
- [ ] Aprimoramentos na inteligência da CPU
- [ ] Novas animações e efeitos visuais
- [ ] Estatísticas do jogador
- [ ] Histórico de batalhas
- [ ] Novas coleções, cartas e heróis

## 🔮 Futuro

- [ ] PvP online
- [ ] Matchmaking
- [ ] Sistema de ranking
- [ ] Temporadas e recompensas
- [ ] Missões diárias e semanais
- [ ] Conquistas
- [ ] Eventos especiais
- [ ] Guildas
- [ ] Aplicativo mobile ou PWA

---

# 🎯 Objetivos técnicos

Este projeto foi criado para praticar e consolidar conhecimentos em:

- Arquitetura front-end
- Gerenciamento de estado
- Autenticação entre aplicações
- Modelagem e persistência de dados
- Regras e lógica de jogos
- Controle de inventário e coleção
- Sistemas de troca entre usuários
- Responsividade e experiência mobile
- Deploy e manutenção de aplicações web

---

# 📈 Status

O **TCG Templar** continua em desenvolvimento. Novas funcionalidades, cartas, melhorias visuais e ajustes de balanceamento são adicionados progressivamente.

---

# 👨‍💻 Autor

**Emanuel Penna**

- [LinkedIn](https://www.linkedin.com/in/emanuel-penna)
- [GitHub](https://github.com/EmanuelFHX)
- [Portfólio](https://portfolio-emanuel-penna.vercel.app/)

---

# 📄 Aviso

Este repositório é destinado à apresentação pública e ao portfólio do projeto.

O código-fonte principal do **TCG Templar** permanece privado.
