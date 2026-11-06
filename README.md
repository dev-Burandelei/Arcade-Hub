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

*Desenvolvido como projeto pessoal para explorar desenvolvimento web, programação de jogos e integração com APIs.*
