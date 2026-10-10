<h1 align="center">Mahin Anowar</h1>

<p align="center">
  <b>Full-stack &amp; AI engineer</b> · Dhaka, Bangladesh (GMT+6)<br />
  I build web apps and AI features end to end, and fix bugs at the root, including in Node.js, Jest and React Router.
</p>

<p align="center">
  <a href="https://mahin-anowar.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-1A1B27?style=for-the-badge&logo=googlechrome&logoColor=5EEAD4" alt="Portfolio" /></a>
  <a href="https://www.fiverr.com/mahin_anowar"><img src="https://img.shields.io/badge/Fiverr-1A1B27?style=for-the-badge&logo=fiverr&logoColor=1DBF73" alt="Fiverr" /></a>
  <a href="https://www.linkedin.com/in/mahin-anowar/"><img src="https://custom-icon-badges.demolab.com/badge/LinkedIn-1A1B27?style=for-the-badge&logo=linkedin-white&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mahinanowar479@gmail.com"><img src="https://img.shields.io/badge/Email-1A1B27?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" /></a>
  <a href="https://drive.google.com/file/d/1HgB9FaUGY8ew3eF3J5SSpZmbuqiwiY1e/"><img src="https://img.shields.io/badge/Resume-1A1B27?style=for-the-badge&logo=googledocs&logoColor=4285F4" alt="Resume" /></a>
</p>

<table align="center">
  <tr>
    <td align="center"><h3>48</h3><sub>merged pull requests</sub></td>
    <td align="center"><h3>19</h3><sub>open-source projects</sub></td>
    <td align="center"><h3>789k</h3><sub>combined GitHub stars</sub></td>
    <td align="center"><h3>4,283</h3><sub>students on NSU Insights</sub></td>
  </tr>
</table>

## Open source

I work on bugs that are hard to pin down: stream and timer edge cases, timezone maths, module loading, type-level regressions. I find the root cause, keep the change small, and back it with a regression test wherever the project allows.

| Project | Fix | PR |
| :-- | :-- | :-- |
| **Node.js** | A v20.10 regression stalled `pipe()` forever: when one destination errored mid-write it was never cleared from the drain set, starving every healthy destination. | [#64310](https://github.com/nodejs/node/pull/64310) |
| **React Router** | Aborting a request mid-stream left a buffered timer writing into a cancelled RSC stream, taking down the Node process. Merged as submitted. | [#15286](https://github.com/remix-run/react-router/pull/15286) |
| **Jest** | Custom resolvers written as ES modules always threw on load. Rebuilt the fix to the maintainer's design; all 103 CI checks passed. | [#16332](https://github.com/jestjs/jest/pull/16332) |
| **Celery** | Crontab tasks silently skipped or double-fired when an aware timestamp arrived in another timezone. Both datetimes are now normalised into the schedule's timezone. | [#10420](https://github.com/celery/celery/pull/10420) |
| **Axios** | `formToJSON` split keys like `user-name` into nested objects. Fixed, and removed a quadratic-time regex path along the way. | [#11006](https://github.com/axios/axios/pull/11006) |
| **type-fest** | `Writable<T>` corrupted readonly index signatures. Replaced with a homomorphic mapped type that strips only `readonly`. | [#1470](https://github.com/sindresorhus/type-fest/pull/1470) |
| **Jest** | Three packages pinned a `glob` that resolved a flagged `brace-expansion`, putting a security advisory in every Jest user's audit. Merged within a day. | [#16397](https://github.com/jestjs/jest/pull/16397) |

> "lgtm" · [@mcollina](https://github.com/nodejs/node/pull/64310#pullrequestreview-4631728132), Node.js Technical Steering Committee<br />
> "thanks, looks really good!" · [@SimenB](https://github.com/jestjs/jest/pull/16332#pullrequestreview-4943438961), Jest maintainer<br />
> "Good catch, thanks." · [@ai](https://github.com/postcss/postcss/pull/2112#issuecomment-4983459741), creator of PostCSS

<details>
  <summary><b>All merged pull requests by project</b></summary>
  <br />
  <table>
    <tr><th align="left">Project</th><th align="right">Stars</th><th align="right">Merged</th></tr>
    <tr><td><a href="https://github.com/nodejs/node"><b>Node.js</b></a></td><td align="right">122.3k</td><td align="right"><a href="https://github.com/nodejs/node/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/axios/axios"><b>Axios</b></a></td><td align="right">109.3k</td><td align="right"><a href="https://github.com/axios/axios/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/remix-run/react-router"><b>React Router</b></a></td><td align="right">56.6k</td><td align="right"><a href="https://github.com/remix-run/react-router/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">2</a></td></tr>
    <tr><td><a href="https://github.com/jestjs/jest"><b>Jest</b></a></td><td align="right">45.6k</td><td align="right"><a href="https://github.com/jestjs/jest/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">5</a></td></tr>
    <tr><td><a href="https://github.com/payloadcms/payload"><b>Payload</b></a></td><td align="right">45.2k</td><td align="right"><a href="https://github.com/payloadcms/payload/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/colinhacks/zod"><b>Zod</b></a></td><td align="right">44.1k</td><td align="right"><a href="https://github.com/colinhacks/zod/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/novuhq/novu"><b>Novu</b></a></td><td align="right">40.1k</td><td align="right"><a href="https://github.com/novuhq/novu/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/directus/directus"><b>Directus</b></a></td><td align="right">38.4k</td><td align="right"><a href="https://github.com/directus/directus/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">4</a></td></tr>
    <tr><td><a href="https://github.com/typeorm/typeorm"><b>TypeORM</b></a></td><td align="right">36.7k</td><td align="right"><a href="https://github.com/typeorm/typeorm/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/medusajs/medusa"><b>Medusa</b></a></td><td align="right">36.7k</td><td align="right"><a href="https://github.com/medusajs/medusa/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">3</a></td></tr>
    <tr><td><a href="https://github.com/sequelize/sequelize"><b>Sequelize</b></a></td><td align="right">30.3k</td><td align="right"><a href="https://github.com/sequelize/sequelize/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/postcss/postcss"><b>PostCSS</b></a></td><td align="right">29k</td><td align="right"><a href="https://github.com/postcss/postcss/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">5</a></td></tr>
    <tr><td><a href="https://github.com/celery/celery"><b>Celery</b></a></td><td align="right">28.9k</td><td align="right"><a href="https://github.com/celery/celery/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">4</a></td></tr>
    <tr><td><a href="https://github.com/recharts/recharts"><b>Recharts</b></a></td><td align="right">27.6k</td><td align="right"><a href="https://github.com/recharts/recharts/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">7</a></td></tr>
    <tr><td><a href="https://github.com/eslint/eslint"><b>ESLint</b></a></td><td align="right">27.6k</td><td align="right"><a href="https://github.com/eslint/eslint/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/rollup/rollup"><b>Rollup</b></a></td><td align="right">26.3k</td><td align="right"><a href="https://github.com/rollup/rollup/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/sindresorhus/type-fest"><b>type-fest</b></a></td><td align="right">17.4k</td><td align="right"><a href="https://github.com/sindresorhus/type-fest/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1</a></td></tr>
    <tr><td><a href="https://github.com/faker-js/faker"><b>Faker</b></a></td><td align="right">15.5k</td><td align="right"><a href="https://github.com/faker-js/faker/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">6</a></td></tr>
    <tr><td><a href="https://github.com/reduxjs/redux-toolkit"><b>Redux Toolkit</b></a></td><td align="right">11.2k</td><td align="right"><a href="https://github.com/reduxjs/redux-toolkit/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">2</a></td></tr>
  </table>
  <sub>As of October 2026. Each count links to the merged PRs on that project.</sub>
</details>

## What I build

**[NSU Insights](https://nsuinsights.com)**: an academic planning platform for North South University, used by 4,283 students who have written 3,615 teacher reviews. I planned, designed, built and run it alone: reviews, grade-distribution charts, a class-schedule planner with clash detection, and NSU Panda, a Gemini assistant with function calling and voice.<br />
<sub>React · TypeScript · Node.js · Express · MongoDB · Firebase Auth · Google Gemini · PWA</sub>

**Automata One (Phoenix Education)**, junior full-stack developer, Jan – Aug 2026: built a promotional pricing system with FastAPI as the single price authority (Redis-cached, race-safe) across catalogue, cart and checkout; a notifications pipeline over Web Push and SSE; and was the top committer on the company website.<br />
<sub>TypeScript · Next.js · FastAPI · PostgreSQL · Redis</sub>

## Stack

<p>
  <b>Languages</b>&nbsp;
  <img src="https://img.shields.io/badge/TypeScript-1A1B27?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-1A1B27?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Python-1A1B27?style=flat-square&logo=python&logoColor=FFD43B" alt="Python" />
  <img src="https://custom-icon-badges.demolab.com/badge/SQL-1A1B27?style=flat-square&logo=database&logoColor=white" alt="SQL" />
</p>
<p>
  <b>Frontend</b>&nbsp;
  <img src="https://img.shields.io/badge/React-1A1B27?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-1A1B27?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-1A1B27?style=flat-square&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/TanStack_Query-1A1B27?style=flat-square&logo=reactquery&logoColor=FF4154" alt="TanStack Query" />
</p>
<p>
  <b>Backend &amp; data</b>&nbsp;
  <img src="https://img.shields.io/badge/Node.js-1A1B27?style=flat-square&logo=nodedotjs&logoColor=5FA04E" alt="Node.js" />
  <img src="https://img.shields.io/badge/FastAPI-1A1B27?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
  <img src="https://img.shields.io/badge/PostgreSQL-1A1B27?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-1A1B27?style=flat-square&logo=mongodb&logoColor=47A248" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Redis-1A1B27?style=flat-square&logo=redis&logoColor=FF4438" alt="Redis" />
</p>
<p>
  <b>AI</b>&nbsp;
  <img src="https://img.shields.io/badge/Google_Gemini-1A1B27?style=flat-square&logo=googlegemini&logoColor=8E75B2" alt="Google Gemini" />
  <img src="https://custom-icon-badges.demolab.com/badge/OpenAI-1A1B27?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Claude-1A1B27?style=flat-square&logo=claude&logoColor=D97757" alt="Claude" />
</p>
<p>
  <b>Delivery</b>&nbsp;
  <img src="https://img.shields.io/badge/Docker-1A1B27?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-1A1B27?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Vercel-1A1B27?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/Jest-1A1B27?style=flat-square&logo=jest&logoColor=C21325" alt="Jest" />
</p>

## GitHub activity

<p align="center">
  <img src="https://github-readme-stats-seven-sandy-98.vercel.app//api?username=MahinAnowar&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=tokyonight&locale=en&hide_border=true&order=1" width="400" alt="stats graph"  />
  <img src="https://github-readme-stats-seven-sandy-98.vercel.app//api/top-langs?username=MahinAnowar&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=6&theme=tokyonight&hide_border=true&order=2" width="400" alt="languages graph"  />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=MahinAnowar&locale=en&mode=daily&theme=tokyonight&hide_border=true&border_radius=5&order=3" width="400" alt="streak graph"  />
</p>

## Work with me

I take on freelance projects, as fixed-price packages on Fiverr or directly for larger work, and I'm open to remote part-time and contract roles.

| Service | From | |
| :-- | :-- | :-- |
| **Bug fixing**: the root cause found, fixed, and explained | $40 | [Fiverr](https://www.fiverr.com/s/1EA1Rak) |
| **Figma to code**: pixel-accurate React or Next.js, every screen size | $60 | [Fiverr](https://www.fiverr.com/s/DmB9Ab7) |
| **AI chatbots and integrations**: GPT, Gemini or Claude on your own data | $100 | [Fiverr](https://www.fiverr.com/s/3AGaYyL) |
| **Full-stack SaaS**: sign-in, payments, dashboard and API | $150 | [Fiverr](https://www.fiverr.com/s/L3dyawQ) |

Something larger or ongoing? [Send a project brief](https://mahin-anowar.vercel.app/#contact) or [email me](mailto:mahinanowar479@gmail.com).

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MahinAnowar/MahinAnowar/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MahinAnowar/MahinAnowar/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/MahinAnowar/MahinAnowar/output/pacman-contribution-graph.svg">
</picture>

![](https://komarev.com/ghpvc/?username=MahinAnowar)
