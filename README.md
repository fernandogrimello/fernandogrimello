# Olá, eu sou Luiz Fernando Grimello 👋

**Desenvolvedor Web Full Stack**  
📍 Brasília – DF &nbsp;|&nbsp; 📧 fernandogrimello@gmail.com

Desenvolvedor Web Full Stack com vivência no ciclo completo de desenvolvimento de software — da modelagem do banco de dados à entrega de interfaces modernas, responsivas e acessíveis. Atuo com **Node.js, React, TypeScript e SQL**, aplicando boas práticas de código, testes automatizados (unitários e E2E) e deploy em nuvem. Tenho experiência em projetos reais que envolvem autenticação segura com JWT, comunicação em tempo real com Socket.IO, integração com APIs externas, arquitetura SaaS e desenvolvimento mobile com React Native. Perfil orientado à qualidade de entrega, aprendizado contínuo e colaboração em equipe. Atualmente cursando **Desenvolvimento de Sistemas no SENAC** (conclusão prevista: jul/2026).

---

##  Projetos em Destaque

###  AppFreela
> Plataforma fullstack de marketplace que conecta contratantes a profissionais autônomos.

🔗 [Demo ao vivo](https://appfreela.onrender.com/) · [Documentação técnica](https://github.com/fernandogrimello/appfreela-showcase)
> Código-fonte privado a pedido da instituição de ensino (projeto de TCC).

- Autenticação com JWT e controle de acesso por perfil (contratante / profissional / admin)
- Sistema completo de agendamentos com fluxo de estados (pendente → confirmado → concluído)
- Chat em tempo real entre usuários
- Avaliações, reputação e sistema de favoritos
- Notificações e lembretes automáticos via cron job
- Geolocalização de profissionais
- Deploy na nuvem: **Render + TiDB Cloud**
- Cobertura de testes com **Jest** (testes unitários) e **Playwright** (testes E2E)

**Stack:** Node.js · Express · JavaScript · MySQL · JWT · Cloudinary · HTML5 · CSS3

---

###  Sistema SaaS — Em desenvolvimento (privado)
> Plataforma SaaS com arquitetura em tempo real, voltada para gestão de filas dinâmicas.

- Painéis interativos por tipo de usuário
- Comunicação em tempo real com Socket.io
- Banco de dados PostgreSQL hospedado no Neon (São Paulo)
- Frontend em React + Vite + Tailwind CSS

**Stack:** Node.js · Express · Socket.io · React · Vite · Tailwind CSS · PostgreSQL · Prisma ORM

---

###  RouletApp — Sistema de Karaokê (privado)
> SaaS de gestão de filas de karaokê para bares e casas noturnas.

- Arquitetura de Guest + Visit para check-ins recorrentes de clientes
- Suporte multi-estabelecimento e multi-sala com URLs dinâmicas por slug
- Autenticação JWT com seis níveis de permissão
- Fluxo de "roleta" do KJ: sorteio → confirmação de quem cantou / ausência
- Eventos em tempo real via Socket.IO segmentados por sala
- Página de recepção com validação de CPF/telefone
- Painel do proprietário com resumos financeiros e gestão de equipe

**Stack:** React · Vite · Tailwind CSS · Node.js · Express · Socket.IO · Prisma · PostgreSQL

---

###  Forno Fácil
> Aplicativo mobile para controle de forno elétrico via NFC, voltado para idosos (modelo B2B vendido junto ao forno).

🔗 [Documentação e demonstração](https://github.com/fernandogrimello/forno-facil-showcase)
> Código-fonte privado — produto com modelo de negócio comercial.

- App em React Native + Expo, com interface simplificada e acessível
- Controle do forno via NFC, com firmware ESP32 (WiFi, MQTT, NFC e relé) desenvolvido em paralelo
- Sistema de som com feedback de voz/áudio (expo-av)
- Animações para guiar o usuário durante o uso
- Projeto de hardware: diagramas de fiação e lista de componentes

**Stack:** React Native · Expo · ESP32 (WiFi/MQTT/NFC) · expo-av

---

##  Testes & Qualidade de Software

Aplico testes automatizados como parte do fluxo de desenvolvimento, cobrindo desde unidades isoladas de código até fluxos completos do usuário no navegador.

- **Testes Unitários** — desenvolvidos com **Jest**, cobrindo controllers, services e regras de negócio do backend.
- **Testes End-to-End (E2E)** — desenvolvidos com **Playwright**, simulando fluxos reais de usuário (login, cadastro, agendamentos, notificações, módulo administrativo).
- **Testes E2E / Automação de navegador** — experiência também com **Selenium** para automação e testes em diferentes navegadores.
- Suítes organizadas por módulo (login, dashboard, notificações, administração), com execução individual e em lote.

![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

---

##  Tecnologias

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Mobile
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socketdotio&logoColor=white)

### Banco de Dados
![MySQL](https://img.shields.io/badge/MySQL-003B57?style=for-the-badge&logo=mysql&logoColor=white)
![TiDB Cloud](https://img.shields.io/badge/TiDB_Cloud-FF7C2E?style=for-the-badge&logo=tidb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

### Testes
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

### Design & Ferramentas
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

### Cloud
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)

---

##  Formação & Certificações

-  **Desenvolvimento de Sistemas** — SENAC Brasília *(jan/2025 – jul/2026)*
-  **AWS Cloud Essentials Knowledge Badge** — Amazon Web Services *(2025)*
-  **AWS Foundations: Getting Started** — Amazon Web Services *(2025)*
-  **JavaScript ES6+** — Cisco Networking Academy *(2025)*
-  **CSS3 — Flexbox, Grid e Responsividade** — Cisco Networking Academy *(2025)*
-  **HTML5 — Fundamentos e Boas Práticas** — Cisco Networking Academy *(2025)*
-  **Operating Systems Basics** — Cisco Networking Academy *(2025)*

---

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luiz-fernando-grimello-6568b4358)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fernandogrimello@gmail.com)
