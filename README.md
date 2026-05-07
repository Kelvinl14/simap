## Sistema Integrado de Mapeamento de Pessoas com Deficiência

---

# 📌 Descrição do Projeto

O **SIMAP-PCD** é uma plataforma digital desenvolvida para auxiliar órgãos públicos no cadastro, monitoramento e mapeamento georreferenciado de Pessoas com Deficiência (PCDs).

O sistema centraliza informações relevantes sobre a população PCD, permitindo que gestores públicos tomem decisões mais eficientes e baseadas em dados, promovendo inclusão social, acessibilidade e melhor distribuição de recursos públicos.

---

# ❗ Problema

A gestão pública enfrenta dificuldades relacionadas à ausência de dados centralizados, atualizados e organizados sobre Pessoas com Deficiência.

Essa limitação causa problemas como:

* Falta de mapeamento geográfico das necessidades;
* Dificuldade na criação de políticas públicas eficientes;
* Distribuição inadequada de recursos;
* Processos burocráticos e descentralizados;
* Baixa integração entre secretarias e serviços públicos.

Além disso, muitos sistemas existentes não possuem acessibilidade adequada e não seguem padrões modernos de inclusão digital.

---

# 🎯 Objetivo da Solução

Desenvolver uma plataforma acessível e integrada para:

* Realizar o cadastro unificado de PCDs;
* Mapear geograficamente a população cadastrada;
* Gerar relatórios e indicadores estratégicos;
* Auxiliar na tomada de decisão da gestão pública;
* Facilitar o acesso da população PCD aos serviços públicos;
* Garantir conformidade com LGPD e diretrizes de acessibilidade (WCAG).

---

# 👨‍💻 Integrantes da Equipe

* Alan Viera da Silva
* Diego
* Everson Borges Motta
* Guilherme Lima
* Kauã 
* Kelvyn Leôncio Andrade Lima

---

# 🛠️ Tecnologias Escolhidas

## Frontend Web

* React.js
* Next.js
* TailwindCSS

## Backend

* Node.js
* Express.js

## Banco de Dados

* PostgreSQL
* PostGIS (dados geográficos)

## APIs e Serviços Externos

* Gov.br (autenticação)
* APIs de Mapas (Google Maps/OpenStreetMap)

## Ferramentas

* Git & GitHub
* Figma
* Docker
* Postman

---

# 🎨 Protótipo

🔗 Link do protótipo Figma:
https://www.figma.com/proto/nCNr7XyspTLLxMduhbgAtY/Simap-interface?node-id=1-2&p=f&t=8wIy1kj4Bnv4WOJR-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=1%3A2&show-proto-sidebar=1

---

# 🧩 Diagramas C4

## 🔷 C1 – Diagrama de Contexto

O diagrama de contexto apresenta:

* Usuários principais:

  * Pessoas com Deficiência
  * Gestores públicos

* Sistemas externos:

  * Gov.br
  * Serviço de mapas
  * Serviço de notificações

* Sistema central:

  * SIMAP-PCD

📌 Objetivo:
Demonstrar como o sistema interage com usuários e serviços externos.

---

## 🔷 C2 – Diagrama de Contêineres

O diagrama de contêineres apresenta:

### Frontend

* Aplicação Web (React)
* Aplicativo Mobile (Flutter)

### Backend

* API REST em Node.js

### Banco de Dados

* PostgreSQL/PostGIS

### Serviços externos

* Gov.br
* APIs de mapas
* Serviços de notificação

📌 Objetivo:
Demonstrar a arquitetura interna da solução e a comunicação entre os componentes.

---

# 🚀 Instruções de Execução

## Pré-requisitos

* Node.js
* PostgreSQL
* Git

---

## Clonar o repositório

```bash
git clone https://github.com/seu-repositorio/simap-pcd.git
```

---

## Backend

```bash
cd src/backend

npm install

npm run dev
```

## Frontend Web

```bash
cd src/frontend

npm install

npm start
```

# 📚 Organização do Repositório

```id="2kdr0c"
/simap
 ├── diagramas/
 ├── prototipo/
 ├── src/
 ├── docs/
 ├── README.md
 └── infra/
```

---

# 📄 Licença

Este projeto possui finalidade acadêmica e de pesquisa.
