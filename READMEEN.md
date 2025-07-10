### 🌐 EN-US
#### [PT-BR](https://github.com/ArthurFakhouri/nlw-agents-server/blob/main/README.md)

<h4 align="center"> 
	:heavy_check_mark: 🚀 NLW-Agents 🚀 :heavy_check_mark:
</h4>

<p align="center">
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#%EF%B8%8F-demo">Demo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## 🈸 Project
NLW-Agents is a project based on the LetMeAsk project that took place at the Rocketseat event. This project allows you to create a room, and in each room, you can record your voice.
This audio will be transcribed and used to answer potential questions in the room.

<b>Features:</b>
- [✅] Rooms should be available.
- [✅] Room creation should be available.
- [✅] Questions in a room should be available.
- [✅] Question creation should be available.
- [✅] Audio file upload should be available.

## 🔧 How to run
### Server
Go to the folder where you cloned the project, open the terminal and run the commands to run the web:
```bash
01 - cd server
02 - npm i -g pnpm (Installation of pnpm globally)
03 - pnpm i
04 - Configure the environment variables in a .env file
05 - pnpm db:seed (optional: command to generate fictional data to database)
06 - docker compose up -d (to create used database images)
07 - pnpm run dev
```

## 📽️ Demo


https://github.com/user-attachments/assets/2cc6dad7-b572-4c15-9118-b7a8dea80245








## 🚀 Technologies

The project was developed using the following technologies:

- [<img alt="" src="https://nodejs.org/favicon.ico" width="16px" /> Node](https://nodejs.org)
- [<img alt="" src="https://fastify.dev/img/favicon.ico" width="16px" /> Fastify](https://fastify.dev/)
- [<img alt="" src="https://biomejs.dev/img/favicon.svg" width="16px" /> Biome](https://biomejs.dev)
- [<img alt="" src="https://www.docker.com/favicon.ico" width="16px" /> Docker](https://www.docker.com/)
- [<img alt="" src="https://orm.drizzle.team/favicon.ico" width="16px" /> Drizzle](https://orm.drizzle.team/)
- [<img alt="" src="https://www.postgresql.org/favicon.ico" width="16px" /> PostgreSQL](https://www.postgresql.org/)
- [<img alt="" src="https://zod.dev/icon.png?39fe259ddd7f4224" width="16px" /> Zod](https://zod.dev/)
- [<img alt="" src="https://www.gstatic.com/lamda/images/gemini_favicon_f069958c85030456e93de685481c559f160ea06b.png" width="16px" /> Gemini](https://gemini.google.com/app?hl=pt-BR)

## :memo: License
This project is licensed under the MIT License. See [LICENSE] for details.

