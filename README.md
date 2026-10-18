<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0f,50:0d1b2a,100:1a1a2e&height=220&section=header&text=Gabriel%20Correa&fontSize=52&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=Desenvolvedor%20Full%20Stack%20%7C%20Sistemas%20integrados%20com%20IA&descAlignY=60&descSize=17&descColor=60a5fa" alt="Banner: Gabriel Correa, Desenvolvedor Full Stack | Sistemas integrados com IA"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=60A5FA&center=true&vCenter=true&width=700&lines=Desenvolvedor+Full+Stack;React+%7C+TypeScript+%7C+Java+%7C+Python;Sistemas+integrados+com+IA;ADS+na+FIAP+%E2%80%94+m%C3%A9dia+9%2C05%2F10" alt="Desenvolvedor Full Stack. React, TypeScript, Java, Python. Sistemas integrados com IA."/>

<br/><br/>

<a href="https://www.linkedin.com/in/gcorrea4/"><img src="https://img.shields.io/badge/LinkedIn-gcorrea4-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
&nbsp;
<a href="mailto:gabrielcorreasouza46@gmail.com"><img src="https://img.shields.io/badge/E--mail-gabrielcorreasouza46-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>

</div>

<br/>

> 🇺🇸 **EN in 3 lines**
> Full Stack Developer building AI-integrated systems (React, TypeScript, Java, Python). Studying Systems Analysis and Development (Tecnólogo) at FIAP, global average 9.05/10 (GPA 3.60/4.00), São Paulo, Brazil.
> Projects: LifeOps (AI scheduling assistant on IBM watsonx), Estelar (satellite telemedicine, team project) and Turma do Bem (volunteer dentist platform, top 7 teams, team project). English C1 (EF SET, Jun/2026).

---

## 👋 Sobre mim

Tenho 20 anos, moro em São Paulo/SP e curso Análise e Desenvolvimento de Sistemas (Tecnólogo) na **FIAP**, com média global **9,05/10** (GPA 3,60/4,00). Gosto de construir sistemas full stack em que a IA é uma peça de um fluxo maior, e não a decisão final: regras determinísticas, validação e revisão humana vêm primeiro.

Meus projetos combinam front-end em React/TypeScript, APIs em Java (Quarkus) e Python (FastAPI/Flask), bancos relacionais e serviços de IA como IBM watsonx, Gemini e scikit-learn. Tenho inglês **C1** (EF SET, jun/2026).

---

## 🚀 Projetos em destaque

<table>
<tr>
<td width="100%">

### ⚙️ LifeOps &nbsp;<sub>10/2026</sub>
**Problema:** organizar tarefas em torno de compromissos fixos sem deixar a IA decidir sozinha.

- **Motor determinístico** calcula os horários válidos; o **IBM watsonx (Llama 3.3 70B)** só escolhe um `candidate_id` e explica a escolha.
- A pessoa **aprova, modifica ou rejeita**; o agendamento é uma ação separada, revalidada contra conflitos e prazos.
- Fallback determinístico, trilha de auditoria e códigos de motivo calculados pelo backend. **255 testes** (pytest) passando.

<img src="https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>
<img src="https://img.shields.io/badge/Python%203.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3.12"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy"/>
<img src="https://img.shields.io/badge/MySQL%208-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL 8"/>
<img src="https://img.shields.io/badge/IBM%20watsonx-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM watsonx"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>

<a href="https://github.com/gcorrea4/lifeops"><img src="https://img.shields.io/badge/Reposit%C3%B3rio-lifeops-0d1117?style=for-the-badge&logo=github&logoColor=60a5fa&labelColor=0d1117" alt="Repositório do LifeOps"/></a>
&nbsp;
<a href="https://boblifeops.vercel.app"><img src="https://img.shields.io/badge/Demo-Vercel-1d4ed8?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Demo do LifeOps"/></a>

<sub>⏸️ **Demo pausada:** o backend na Azure foi desligado em 18/10/2026 para evitar cobrança. A página abre, mas as ações mostram "demo pausada". Veja o <a href="https://github.com/gcorrea4/lifeops/blob/master/docs/screenshots/00-bob.gif">GIF</a> e as <a href="https://github.com/gcorrea4/lifeops/tree/master/docs/screenshots">capturas de tela</a> no repositório. Desenvolvido com apoio de IBM Bob, Codex e Claude Code, com revisão humana.</sub>

<img src="https://raw.githubusercontent.com/gcorrea4/lifeops/master/docs/screenshots/00-bob.gif" width="100%" alt="GIF de demonstração do LifeOps: tarefas, recomendação e decisão"/>

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### 🛰️ Estelar &nbsp;<sub>07/2026 · projeto em equipe · FIAP Global Solution 2026/1</sub>
**Problema:** levar telemedicina, via satélite, a regiões remotas. São **4 serviços integrados**: front-end React/Vite (Vercel), API Java/Quarkus/Oracle (Azure), API de risco clínico Python/Flask (Render) e API de IA de triagem Python/Flask/scikit-learn (Render).

**Minha parte:**
- A **API de IA de triagem** (Python, Flask, scikit-learn).
- A **integração do módulo de risco clínico** à plataforma: encapsulei em API REST a regra de pontuação original, criada por Eric Maciel.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black" alt="Render"/>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"/>
<img src="https://img.shields.io/badge/Quarkus-4695EB?style=flat-square&logo=quarkus&logoColor=white" alt="Quarkus"/>
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle"/>

<a href="https://github.com/gcorrea4/GlobalSolution2026"><img src="https://img.shields.io/badge/Reposit%C3%B3rio-GlobalSolution2026-0d1117?style=for-the-badge&logo=github&logoColor=60a5fa&labelColor=0d1117" alt="Repositório do Estelar"/></a>
&nbsp;
<a href="https://global-solution2026.vercel.app/"><img src="https://img.shields.io/badge/Demo-Vercel-1d4ed8?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Demo do Estelar"/></a>

<sub>As APIs Python ficam no plano gratuito do Render e podem demorar cerca de 1 minuto para "acordar" na primeira requisição.</sub>

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### 🦷 Turma do Bem — Challenge Sprint &nbsp;<sub>08/2025–06/2026 · equipe de 3</sub>
**Problema:** conectar jovens em vulnerabilidade a dentistas voluntários. Entre os **7 melhores times** do desafio, apresentado na sede da ONG.

- **Score TdB** de priorização (urgência clínica + vulnerabilidade social), mapa Leaflet com heatmap e dashboards por perfil (admin, dentista, paciente).
- Triagem com **Gemini 2.5 Flash**; back-end Java 17 / Quarkus 3.8.5 / Oracle XE 21c com JDBC/DAO, **JWT RS256 + BCrypt** e tickets com máquina de 6 estados.
- **91 testes unitários**, CI com GitHub Actions e deploy em Azure App Service + ACR.

**Minha parte:** desenvolvimento técnico full stack e apresentação, junto com o Eric.

<img src="https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Tailwind%204-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind 4"/>
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest"/>
<img src="https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white" alt="Leaflet"/>
<img src="https://img.shields.io/badge/Java%2017-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java 17"/>
<img src="https://img.shields.io/badge/Quarkus-4695EB?style=flat-square&logo=quarkus&logoColor=white" alt="Quarkus"/>
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle"/>
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure"/>
<img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>

<a href="https://github.com/gcorrea4/Challenge-Sprint"><img src="https://img.shields.io/badge/Reposit%C3%B3rio-Challenge--Sprint-0d1117?style=for-the-badge&logo=github&logoColor=60a5fa&labelColor=0d1117" alt="Repositório do Challenge Sprint"/></a>
&nbsp;
<a href="https://challenge-sprint-rose.vercel.app/"><img src="https://img.shields.io/badge/Demo-Vercel-1d4ed8?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0d1117" alt="Demo do Challenge Sprint"/></a>

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### 🧠 SkillUp — AI Learning Path Orchestrator &nbsp;<sub>11/2025</sub>
**Problema:** montar trilhas de estudo personalizadas integrando vários serviços de IA e mensageria.

- Orquestrador **Node-RED** de 5 APIs/serviços: Gemini, IBM Watson Assistant, Telegram Bot, STT e TTS.
- Trilhas de estudo geradas dinamicamente e **comandos de voz**.
- Arquitetura **fault-tolerant** com ponto único de entrada.

<img src="https://img.shields.io/badge/Node--RED-8F0000?style=flat-square&logo=nodered&logoColor=white" alt="Node-RED"/>
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js"/>
<img src="https://img.shields.io/badge/Google_Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini"/>
<img src="https://img.shields.io/badge/IBM_Watson-BE95FF?style=flat-square&logo=ibmwatson&logoColor=black" alt="IBM Watson Assistant"/>
<img src="https://img.shields.io/badge/Telegram_Bot-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram Bot"/>

<a href="https://github.com/gcorrea4/skillup-ai-orchestrator"><img src="https://img.shields.io/badge/Reposit%C3%B3rio-skillup--ai--orchestrator-0d1117?style=for-the-badge&logo=github&logoColor=60a5fa&labelColor=0d1117" alt="Repositório do SkillUp"/></a>

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### 👜 Catálogo Nana Correa Ateliê
Site-vitrine de bolsas de crochê feito para uma artesã: fotos, detalhes de cada peça em modal e contato direto por WhatsApp com mensagem pré-preenchida.

<img src="https://img.shields.io/badge/React%2019-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 19"/>
<img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/Tailwind%204-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind 4"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite"/>

<a href="https://nanacorreaatelie.com.br"><img src="https://img.shields.io/badge/Site-nanacorreaatelie.com.br-1d4ed8?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0d1117" alt="Site do Catálogo Nana Correa Ateliê"/></a>

</td>
<td width="50%" valign="top">

### 🐾 Anima &nbsp;<sub>projeto em grupo · em desenvolvimento</sub>
Até aqui, o módulo de IA e a simulação são desenvolvidos por mim. Monitoramento do estado comportamental de pets com ESP32 e IA. O hardware físico ainda não foi construído, então o modelo é treinado com **dataset sintético**.

- Random Forest (scikit-learn) com 96,25% de acurácia **nos dados sintéticos**, não em sensores reais.
- Simulação do firmware ESP32 no Wokwi e consumidor MQTT em Python.

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32"/>

</td>
</tr>
</table>

<div align="center">

📁 [Ver todos os repositórios](https://github.com/gcorrea4?tab=repositories)

</div>

---

<div align="center">

## 🛠️ Stack

</div>

<table>
<tr><td><b>Linguagens</b></td><td>
<img src="https://skillicons.dev/icons?i=ts,js,java,py,cs,flutter&perline=6" alt="TypeScript, JavaScript, Java, Python, C#, Flutter"/> &nbsp;SQL
</td></tr>
<tr><td><b>Front-end</b></td><td>
<img src="https://skillicons.dev/icons?i=react,html,css,tailwind,bootstrap,vite,figma&perline=7" alt="React, HTML5, CSS3, Tailwind, Bootstrap, Vite, Figma"/> &nbsp;Leaflet
</td></tr>
<tr><td><b>Back-end</b></td><td>
<img src="https://skillicons.dev/icons?i=nodejs,fastapi,flask,spring&perline=4" alt="Node.js, FastAPI, Flask, Spring Boot"/> &nbsp;Quarkus · REST
</td></tr>
<tr><td><b>Dados</b></td><td>
<img src="https://skillicons.dev/icons?i=oracle,mysql,mongodb&perline=3" alt="Oracle, MySQL, MongoDB"/>
</td></tr>
<tr><td><b>IA</b></td><td>
<img src="https://img.shields.io/badge/IBM_watsonx-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM watsonx"/>
<img src="https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini API"/>
<img src="https://img.shields.io/badge/Watson_Assistant-BE95FF?style=flat-square&logo=ibmwatson&logoColor=black" alt="Watson Assistant"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Node--RED-8F0000?style=flat-square&logo=nodered&logoColor=white" alt="Node-RED"/>
</td></tr>
<tr><td><b>Cloud</b></td><td>
<img src="https://skillicons.dev/icons?i=azure,docker,vercel&perline=3" alt="Azure, Docker, Vercel"/> &nbsp;Render
</td></tr>
<tr><td><b>Práticas</b></td><td>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,vitest,eslint,postman,vscode&perline=7" alt="Git, GitHub, GitHub Actions, Vitest, ESLint, Postman, VS Code"/>
<br/>pytest · Agile/Scrum · CI/CD · DDD · Clean Architecture
</td></tr>
</table>

---

<div align="center">

## 🎓 Formação e certificados

</div>

- **Análise e Desenvolvimento de Sistemas** (Tecnólogo), FIAP: média global 9,05/10 (GPA 3,60/4,00).
- 🏅 **Certificado de Qualificação Profissional em Análise de Sistemas e Prototipagem Web**, FIAP (dez/2025).
- 🏅 **Inglês C1**, EF SET (jun/2026).
- 🏅 **IBM Python for Data Science** (out/2026).
- **FIAP:** Engenharia de Software, Responsive Web Development e Java Fundamentos.
- **Alura:** MTA JavaScript e Git & GitHub.

---

<div align="center">

## 📊 Estatísticas do GitHub

<img height="170" src="https://github-readme-stats.vercel.app/api?username=gcorrea4&show_icons=true&hide_border=true&bg_color=0d1117&title_color=60a5fa&icon_color=60a5fa&text_color=c9d1d9&ring_color=1d4ed8" alt="Estatísticas do GitHub de gcorrea4"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gcorrea4&layout=compact&hide_border=true&bg_color=0d1117&title_color=60a5fa&text_color=c9d1d9&langs_count=8" alt="Linguagens mais usadas por gcorrea4"/>

</div>

---

<div align="center">

## 📬 Contato

<a href="https://www.linkedin.com/in/gcorrea4/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
&nbsp;
<a href="mailto:gabrielcorreasouza46@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"/></a>
&nbsp;
<a href="https://github.com/gcorrea4"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:0d1b2a,100:0a0a0f&height=120&section=footer&animation=twinkling" alt=""/>

</div>
