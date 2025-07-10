### 🌐 PT-BR
#### [EN-US](https://github.com/ArthurFakhouri/Brev.ly/blob/main/READMEEN.md)

<h4 align="center"> 
	:heavy_check_mark: 🚀 NLW-Agents 🚀 :heavy_check_mark:
</h4>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8F-demonstração">Demonstração</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## 🈸 Projeto
NLW-Agents é um projeto que é baseado no projeto LetMeAsk ocorrido no evento da Rocketseat. Nesse projeto é possível executar a criação de uma sala e em cada sala é possível fazer a gravação de voz e todo esse áudio será transcrito
e utilizado para responder possíveis perguntas feitas em uma sala.

<b>Funcionalidades:</b>
- [✅]  Deve ser possível obter as salas
- [✅]  Deve ser possível a criação de uma sala
- [✅]  Deve ser possível obter as perguntas em uma sala
- [✅]  Deve ser possível a criação de uma pergunta
- [✅]  Deve ser possível raelizar o upload de um arquivo de áudio.

## 🔧 Como executar
### Server
Vá para a pasta em que você clonou o projeto, abra o terminal e execute os comandos para rodar o servidor:
```bash
01 - cd server
02 - npm i -g pnpm (Instalação do pnpm globalmente)
03 - pnpm i
04 - Configure as variáveis de ambiente em um arquivo .env
05 - pnpm db:seed (opcional: comando para geração de dados fictícios para o banco de dados)
06 - docker compose up -d (Para criar as imagens dos banco de dados utilizados)
07 - pnpm run dev
```

## 📽️ Demonstração







## 🚀 Tecnologias

O projeto foi desenvolvido utilizando as seguintes tecnologias:

Servidor:
- [<img alt="" src="https://nodejs.org/favicon.ico" width="16px" /> Node](https://nodejs.org)
- [<img alt="" src="https://fastify.dev/img/favicon.ico" width="16px" /> Fastify](https://fastify.dev/)
- [<img alt="" src="https://biomejs.dev/img/favicon.svg" width="16px" /> Biome](https://biomejs.dev)
- [<img alt="" src="https://www.docker.com/favicon.ico" width="16px" /> Docker](https://www.docker.com/)
- [<img alt="" src="https://orm.drizzle.team/favicon.ico" width="16px" /> Drizzle](https://orm.drizzle.team/)
- [<img alt="" src="https://zod.dev/icon.png?39fe259ddd7f4224" width="16px" /> Zod](https://zod.dev/)
- [<img alt="" src="https://www.gstatic.com/lamda/images/gemini_favicon_f069958c85030456e93de685481c559f160ea06b.png" width="16px" /> Gemini](https://gemini.google.com/app?hl=pt-BR)

## :memo: Licença
Este projeto está sob a licença do MIT. Consulte a [LICENÇA](LICENSE) para obter detalhes.

