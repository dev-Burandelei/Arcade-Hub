# 🎮 Arcade Hub

### Uma plataforma web inspirada nos clássicos fliperamas, reunindo jogos, experiências interativas e conteúdo acadêmico.

<p align="center">
  <a href="https://node-project-xi-dun.vercel.app/">
    <strong>🚀 Acessar aplicação</strong>
  </a>
  ·
  <a href="https://github.com/dev-Burandelei/node_project">
    <strong>📂 Código-fonte</strong>
  </a>
</p>

---

## 📖 Sobre o projeto

O **Arcade Hub** é uma plataforma web que reúne jogos desenvolvidos para navegador, conteúdos acadêmicos e integração com serviços externos em uma experiência interativa inspirada nos fliperamas clássicos.

O projeto surgiu como uma oportunidade de explorar conceitos de desenvolvimento web, programação de jogos, gerenciamento de estados e integração com APIs de terceiros.

Além da experiência visual, a aplicação busca aplicar conceitos de organização modular, separação de responsabilidades e desenvolvimento de funcionalidades interativas utilizando JavaScript.

## ✨ Funcionalidades

- 🎮 **Biblioteca de jogos:** interface para explorar e acessar diferentes experiências interativas.
- 🏓 **Pong:** implementação do clássico jogo de arcade utilizando JavaScript e HTML Canvas.
- 🌐 **Multiplayer:** modalidade de jogo online, conforme funcionalidades disponíveis na aplicação.
- 📚 **Conteúdo acadêmico:** seção dedicada à disponibilização de conteúdos educacionais.
- 🎧 **Integração com Spotify:** conexão com serviços de música por meio da API e do Web Playback SDK.
- 🎨 **Identidade visual retrô:** interface inspirada nos fliperamas clássicos, com elementos neon e interações animadas.

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação no projeto |
|---|---|
| HTML5 | Estrutura das páginas |
| CSS3 | Estilização, responsividade e animações |
| JavaScript | Lógica e interatividade |
| Canvas API | Renderização dos jogos |
| Spotify Web API | Integração com serviços do Spotify |
| Spotify Web Playback SDK | Reprodução de músicas |
| Git e GitHub | Versionamento e gerenciamento do código |
| Vercel | Hospedagem e publicação da aplicação |

## 🏗️ Arquitetura e organização

A aplicação utiliza uma organização modular para separar componentes relacionados aos jogos, gerenciamento de estados, entidades e sistemas.

O motor de jogos utiliza uma arquitetura baseada em estados, permitindo organizar os diferentes momentos da execução, como inicialização, gameplay e encerramento.

A renderização é controlada por `requestAnimationFrame`, enquanto os eventos de teclado são utilizados para capturar as interações dos jogadores.

## 🧠 Desafios técnicos e soluções

Durante o desenvolvimento do Arcade Hub, alguns desafios exigiram decisões específicas de arquitetura e implementação para garantir uma experiência interativa e eficiente.

### 🌐 Multiplayer em tempo real com WebSocket

A implementação do modo multiplayer utilizou WebSocket para estabelecer uma comunicação bidirecional entre os jogadores e o servidor.

A solução permite:
- Estabelecer uma conexão persistente entre cliente e servidor.
- Sincronizar informações e estados da partida em tempo real.
- Coordenar as interações dos jogadores por meio de um loop de jogo.
- Reduzir a dependência de requisições HTTP periódicas para atualização da partida.

Essa abordagem possibilitou desenvolver uma experiência multiplayer com comunicação contínua e atualizações em tempo real.

### 🎨 Renderização otimizada com CSS

A interface foi desenvolvida utilizando recursos nativos de HTML e CSS, priorizando uma renderização leve e evitando processamento desnecessário de elementos visuais.

Entre as decisões adotadas estão:
- Utilização de CSS para construção e atualização dos elementos visuais.
- Redução da necessidade de processamento gráfico adicional via JavaScript.
- Organização dos estilos para facilitar manutenção e evolução da interface.
- Priorização de uma experiência fluida, minimizando possíveis quedas na taxa de quadros (*frame drops*).

### 🎧 Integração com a API do Spotify

A integração com o Spotify envolveu a comunicação com serviços externos e a implementação de autenticação utilizando OAuth Authorization Code com PKCE.

O desenvolvimento contemplou:
- Autenticação e autorização de usuários.
- Comunicação com a Spotify Web API.
- Integração com o Spotify Web Playback SDK.
- Utilização dos recursos disponibilizados pelo serviço para incorporar funcionalidades musicais à plataforma.

O principal desafio foi integrar um serviço externo à experiência da aplicação, respeitando os requisitos de autenticação e comunicação definidos pela plataforma.

## 🚀 Como executar o projeto

### Pré-requisitos

- Navegador atualizado.
- Git instalado.
- Extensão Live Server do Visual Studio Code ou outro servidor HTTP local.

### Instalação

Clone o repositório:

```bash
git clone https://github.com/dev-Burandelei/node_project.git
```

Entre na pasta:

```bash
cd node_project
```

Abra o projeto utilizando o Live Server ou outro servidor HTTP local.

Acesse o endereço disponibilizado pelo servidor no navegador.

## 🔐 Integração com Spotify

A integração utiliza o fluxo de autenticação OAuth Authorization Code com PKCE.

Para configurar a integração:

1. Crie uma aplicação no [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
2. Configure a URI de redirecionamento.
3. Informe as configurações necessárias no projeto.
4. Realize a autenticação para utilizar os recursos disponibilizados pela integração.

**Observação:** alguns recursos do Spotify podem depender de permissões, disponibilidade da API e requisitos da conta do usuário.

## 📸 Demonstração

<img width="1917" height="862" alt="image" src="https://github.com/user-attachments/assets/6f3e3cdd-4acd-4c96-9854-92869eb71c4f" />
<img width="1917" height="852" alt="image" src="https://github.com/user-attachments/assets/d3f6c5be-d51b-4486-8b41-3ae7766810d0" />
<img width="1917" height="857" alt="image" src="https://github.com/user-attachments/assets/3ac5aca9-367d-4385-ab4a-af92758f807a" />



## 🗺️ Melhorias futuras

- [ ] Aprimorar a experiência em dispositivos móveis.
- [ ] Expandir a biblioteca de jogos.
- [ ] Melhorar a conectividade do modo multiplayer.
- [ ] Implementar testes automatizados.
- [ ] Aprimorar o tratamento de erros e o gerenciamento de autenticação.
- [ ] Expandir a documentação técnica e da arquitetura.

## 👨‍💻 Autor

**Vanderlei Andrade**

Bacharel em Ciência da Computação pela Universidade Federal de São Carlos (UFSCar).

Interesses em Desenvolvimento de Software, Ciência de Dados, Machine Learning e Inteligência Artificial Generativa.

- [GitHub](https://github.com/dev-Burandelei)
- [LinkedIn](www.linkedin.com/in/vanderlei-assis)

---


# 🎮 Arcade Hub

### A web platform inspired by classic arcades, bringing together games, interactive experiences, and educational content.

<p align="center">
  <a href="https://node-project-xi-dun.vercel.app/">
    <strong>🚀 Live Demo</strong>
  </a>
  ·
  <a href="https://github.com/dev-Burandelei/node_project">
    <strong>📂 Source Code</strong>
  </a>
</p>

---

## 📖 About the Project

**Arcade Hub** is a web platform that brings together browser-based games, educational content, and third-party service integrations into an interactive experience inspired by classic arcade machines.

The project was developed as an opportunity to explore web development, game programming, state management, and third-party API integration.

Beyond its visual experience, the application applies concepts of modular architecture, separation of concerns, and interactive feature development using JavaScript.

## ✨ Features

- 🎮 **Game Library:** Interface for exploring and accessing different interactive experiences.
- 🏓 **Pong:** Implementation of the classic arcade game using JavaScript and HTML Canvas.
- 🌐 **Multiplayer:** Online multiplayer functionality with real-time communication.
- 📚 **Educational Content:** Dedicated section for educational materials.
- 🎧 **Spotify Integration:** Music integration through the Spotify API and Web Playback SDK.
- 🎨 **Retro Visual Identity:** Interface inspired by classic arcades, featuring neon elements and animated interactions.

## 🛠️ Technologies

| Technology | Application |
|---|---|
| HTML5 | Page structure |
| CSS3 | Styling, responsive layouts, and animations |
| JavaScript | Application logic and interactivity |
| Canvas API | Game rendering |
| WebSocket | Real-time multiplayer communication |
| Spotify Web API | Spotify service integration |
| Spotify Web Playback SDK | Music playback |
| Git & GitHub | Version control and source code management |
| Vercel | Application hosting and deployment |

## 🏗️ Architecture and Organization

The application follows a modular structure to separate game components, state management, entities, and systems.

The game engine uses a state-based architecture to organize different execution stages, such as initialization, gameplay, and termination.

Rendering is handled through browser-native technologies, while keyboard events capture player interactions and control game behavior.

## 🧠 Technical Challenges and Solutions

During the development of Arcade Hub, several technical challenges required specific architectural and implementation decisions to ensure an interactive and efficient user experience.

### 🌐 Real-Time Multiplayer with WebSocket

The multiplayer functionality was implemented using WebSocket to establish bidirectional communication between players and the server.

This approach enables:

- Maintaining persistent connections between clients and the server.
- Synchronizing game information and player states in real time.
- Coordinating player interactions through a game loop.
- Reducing reliance on periodic HTTP requests for game updates.

This implementation enabled continuous communication and real-time game state updates, providing the foundation for an interactive multiplayer experience.

### 🎨 CSS-Based Rendering Optimization

The interface was developed using native HTML and CSS features, prioritizing lightweight rendering and minimizing unnecessary visual processing.

Key implementation decisions include:

- Using CSS to build and update visual elements.
- Reducing the need for additional graphical processing through JavaScript.
- Organizing stylesheets to improve maintainability and scalability.
- Prioritizing a smooth user experience while minimizing potential frame drops.

### 🎧 Spotify API Integration

Spotify integration involved communicating with external services and implementing authentication through the OAuth Authorization Code with PKCE flow.

The implementation includes:

- User authentication and authorization.
- Communication with the Spotify Web API.
- Integration with the Spotify Web Playback SDK.
- Use of Spotify services to incorporate music features into the platform.

The main challenge was integrating an external service into the application while complying with the platform's authentication and communication requirements.

## 🚀 Getting Started

### Prerequisites

- A modern web browser.
- Git installed.
- Visual Studio Code with the Live Server extension or another local HTTP server.

### Installation

Clone the repository:

```bash
git clone https://github.com/dev-Burandelei/node_project.git
```

Navigate to the project directory:

```bash
cd node_project
```

Launch the project using Live Server or another local HTTP server.

Open the local URL provided by your development server in your browser.

## 🔐 Spotify Integration

The Spotify integration uses the OAuth Authorization Code with PKCE authentication flow.

To configure the integration:

1. Create an application in the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
2. Configure the redirect URI.
3. Provide the required application configuration.
4. Authenticate to access the available Spotify features.

**Note:** Some Spotify features may depend on API permissions, service availability, and user account requirements.

## 📸 Screenshots

<p align="center">
  <img width="95%" src="https://github.com/user-attachments/assets/6f3e3cdd-4acd-4c96-9854-92869eb71c4f" alt="Arcade Hub interface screenshot 1" />
  <img width="95%" src="https://github.com/user-attachments/assets/d3f6c5be-d51b-4486-8b41-3ae7766810d0" alt="Arcade Hub interface screenshot 2" />
  <img width="95%" src="https://github.com/user-attachments/assets/3ac5aca9-367d-4385-ab4a-af92758f807a" alt="Arcade Hub interface screenshot 3" />
</p>

## 🗺️ Future Improvements

- [ ] Improve the experience on mobile devices.
- [ ] Expand the game library.
- [ ] Improve multiplayer connectivity.
- [ ] Implement automated tests.
- [ ] Improve error handling and authentication management.
- [ ] Expand technical and architectural documentation.

## 👨‍💻 Author

**Vanderlei Andrade**

B.Sc. in Computer Science from the Federal University of São Carlos (UFSCar), Brazil.

Interests in Software Development, Data Science, Machine Learning, and Generative Artificial Intelligence.

- [GitHub](https://github.com/dev-Burandelei)
- [LinkedIn](https://www.linkedin.com/in/vanderlei-assis)

---

*Developed as a personal project to explore web development, game programming, and API integration.*

*Desenvolvido como projeto pessoal para explorar desenvolvimento web, programação de jogos e integração com APIs.*
