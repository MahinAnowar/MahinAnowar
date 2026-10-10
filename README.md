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
    <td align="center"><h3><!-- nsu-users -->4,283<!-- /nsu-users --></h3><sub>students on NSU Insights</sub></td>
  </tr>
</table>

<p align="center">
  <img src="https://github-readme-stats-seven-sandy-98.vercel.app//api?username=MahinAnowar&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=tokyonight&locale=en&hide_border=true&order=1" height="165" alt="stats graph"  />
  <img src="https://github-readme-stats-seven-sandy-98.vercel.app//api/top-langs?username=MahinAnowar&locale=en&hide_title=false&layout=compact&card_width=395&langs_count=6&theme=tokyonight&hide_border=true&order=2" height="165" alt="languages graph"  />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=MahinAnowar&locale=en&mode=daily&theme=tokyonight&hide_border=true&border_radius=5&order=3" height="165" alt="streak graph"  />
</p>

## Open source

I work on bugs that are hard to pin down: stream and timer edge cases, timezone maths, module loading, type-level regressions. I find the root cause, keep the change small, and back it with a regression test wherever the project allows.

<table align="center" width="100%">
  <tr>
    <td width="50%" valign="top">
      <img src="https://avatars.githubusercontent.com/u/9950313?s=64&v=4" width="20" height="20" alt="" />&nbsp;<b>Node.js</b>&nbsp;<sub>★&nbsp;122.3k</sub>
      <h4>One failed connection froze all the healthy ones</h4>
      <sub>A v20.10 regression in <code>pipe()</code>: a destination that errored mid-write was never cleared from the drain set, starving the rest.</sub><br /><br />
      <a href="https://github.com/nodejs/node/pull/64310">#64310 →</a>
    </td>
    <td width="50%" valign="top">
      <img src="https://avatars.githubusercontent.com/u/64235328?s=64&v=4" width="20" height="20" alt="" />&nbsp;<b>React Router</b>&nbsp;<sub>★&nbsp;56.6k</sub>
      <h4>Cancelled page loads crashed the server</h4>
      <sub>A buffered timer kept writing into an aborted RSC stream and took down the Node process. Merged as submitted.</sub><br /><br />
      <a href="https://github.com/remix-run/react-router/pull/15286">#15286 →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="https://avatars.githubusercontent.com/u/103283236?s=64&v=4" width="20" height="20" alt="" />&nbsp;<b>Jest</b>&nbsp;<sub>★&nbsp;45.6k</sub>
      <h4>ES-module resolvers never loaded</h4>
      <sub>Custom resolvers written as ES modules always threw on load. Rebuilt to the maintainer's design; all 103 CI checks passed.</sub><br /><br />
      <a href="https://github.com/jestjs/jest/pull/16332">#16332 →</a>
    </td>
    <td width="50%" valign="top">
      <img src="https://avatars.githubusercontent.com/u/319983?s=64&v=4" width="20" height="20" alt="" />&nbsp;<b>Celery</b>&nbsp;<sub>★&nbsp;28.9k</sub>
      <h4>Scheduled jobs ran twice, or not at all</h4>
      <sub>Crontab compared datetimes from different timezones. Both are now normalised into the schedule's timezone.</sub><br /><br />
      <a href="https://github.com/celery/celery/pull/10420">#10420 →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <img src="https://avatars.githubusercontent.com/u/32372333?s=64&v=4" width="20" height="20" alt="" />&nbsp;<b>Axios</b>&nbsp;<sub>★&nbsp;109.3k</sub>
      <h4>Form fields saved in the wrong shape</h4>
      <sub><code>formToJSON</code> split keys like <code>user-name</code> into nested objects. Also removed a quadratic-time regex path.</sub><br /><br />
      <a href="https://github.com/axios/axios/pull/11006">#11006 →</a>
    </td>
    <td width="50%" valign="top">
      <img src="https://avatars.githubusercontent.com/u/170270?s=64&v=4" width="20" height="20" alt="" />&nbsp;<b>type-fest</b>&nbsp;<sub>★&nbsp;17.4k</sub>
      <h4>A popular type helper quietly changed data</h4>
      <sub><code>Writable&lt;T&gt;</code> corrupted readonly index signatures. Replaced with a homomorphic mapped type.</sub><br /><br />
      <a href="https://github.com/sindresorhus/type-fest/pull/1470">#1470 →</a>
    </td>
  </tr>
</table>


<details>
  <summary><b>All 48 merged pull requests, by project</b></summary>
  <br />
  <table align="center" width="100%">
    <tr>
      <td align="center" width="20%"><a href="https://github.com/nodejs/node"><img src="https://avatars.githubusercontent.com/u/9950313?s=80&v=4" width="40" height="40" alt="" /><br /><b>Node.js</b></a><br /><sub>★&nbsp;122.3k · <a href="https://github.com/nodejs/node/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/axios/axios"><img src="https://avatars.githubusercontent.com/u/32372333?s=80&v=4" width="40" height="40" alt="" /><br /><b>Axios</b></a><br /><sub>★&nbsp;109.3k · <a href="https://github.com/axios/axios/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/remix-run/react-router"><img src="https://avatars.githubusercontent.com/u/64235328?s=80&v=4" width="40" height="40" alt="" /><br /><b>React Router</b></a><br /><sub>★&nbsp;56.6k · <a href="https://github.com/remix-run/react-router/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">2&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/jestjs/jest"><img src="https://avatars.githubusercontent.com/u/103283236?s=80&v=4" width="40" height="40" alt="" /><br /><b>Jest</b></a><br /><sub>★&nbsp;45.6k · <a href="https://github.com/jestjs/jest/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">5&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/payloadcms/payload"><img src="https://avatars.githubusercontent.com/u/62968818?s=80&v=4" width="40" height="40" alt="" /><br /><b>Payload</b></a><br /><sub>★&nbsp;45.2k · <a href="https://github.com/payloadcms/payload/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
    </tr>
    <tr>
      <td align="center" width="20%"><a href="https://github.com/colinhacks/zod"><img src="https://avatars.githubusercontent.com/u/3084745?s=80&v=4" width="40" height="40" alt="" /><br /><b>Zod</b></a><br /><sub>★&nbsp;44.1k · <a href="https://github.com/colinhacks/zod/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/novuhq/novu"><img src="https://avatars.githubusercontent.com/u/77433905?s=80&v=4" width="40" height="40" alt="" /><br /><b>Novu</b></a><br /><sub>★&nbsp;40.1k · <a href="https://github.com/novuhq/novu/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/directus/directus"><img src="https://avatars.githubusercontent.com/u/15967950?s=80&v=4" width="40" height="40" alt="" /><br /><b>Directus</b></a><br /><sub>★&nbsp;38.4k · <a href="https://github.com/directus/directus/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">4&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/typeorm/typeorm"><img src="https://avatars.githubusercontent.com/u/20165699?s=80&v=4" width="40" height="40" alt="" /><br /><b>TypeORM</b></a><br /><sub>★&nbsp;36.7k · <a href="https://github.com/typeorm/typeorm/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/medusajs/medusa"><img src="https://avatars.githubusercontent.com/u/62591822?s=80&v=4" width="40" height="40" alt="" /><br /><b>Medusa</b></a><br /><sub>★&nbsp;36.7k · <a href="https://github.com/medusajs/medusa/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">3&nbsp;merged</a></sub></td>
    </tr>
    <tr>
      <td align="center" width="20%"><a href="https://github.com/sequelize/sequelize"><img src="https://avatars.githubusercontent.com/u/3591786?s=80&v=4" width="40" height="40" alt="" /><br /><b>Sequelize</b></a><br /><sub>★&nbsp;30.3k · <a href="https://github.com/sequelize/sequelize/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/postcss/postcss"><img src="https://avatars.githubusercontent.com/u/8296347?s=80&v=4" width="40" height="40" alt="" /><br /><b>PostCSS</b></a><br /><sub>★&nbsp;29k · <a href="https://github.com/postcss/postcss/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">5&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/celery/celery"><img src="https://avatars.githubusercontent.com/u/319983?s=80&v=4" width="40" height="40" alt="" /><br /><b>Celery</b></a><br /><sub>★&nbsp;28.9k · <a href="https://github.com/celery/celery/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">4&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/recharts/recharts"><img src="https://avatars.githubusercontent.com/u/13690587?s=80&v=4" width="40" height="40" alt="" /><br /><b>Recharts</b></a><br /><sub>★&nbsp;27.6k · <a href="https://github.com/recharts/recharts/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">7&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/eslint/eslint"><img src="https://avatars.githubusercontent.com/u/6019716?s=80&v=4" width="40" height="40" alt="" /><br /><b>ESLint</b></a><br /><sub>★&nbsp;27.6k · <a href="https://github.com/eslint/eslint/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
    </tr>
    <tr>
      <td align="center" width="20%"><a href="https://github.com/rollup/rollup"><img src="https://avatars.githubusercontent.com/u/12554859?s=80&v=4" width="40" height="40" alt="" /><br /><b>Rollup</b></a><br /><sub>★&nbsp;26.3k · <a href="https://github.com/rollup/rollup/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/sindresorhus/type-fest"><img src="https://avatars.githubusercontent.com/u/170270?s=80&v=4" width="40" height="40" alt="" /><br /><b>type-fest</b></a><br /><sub>★&nbsp;17.4k · <a href="https://github.com/sindresorhus/type-fest/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">1&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/faker-js/faker"><img src="https://avatars.githubusercontent.com/u/97165289?s=80&v=4" width="40" height="40" alt="" /><br /><b>Faker</b></a><br /><sub>★&nbsp;15.5k · <a href="https://github.com/faker-js/faker/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">6&nbsp;merged</a></sub></td>
      <td align="center" width="20%"><a href="https://github.com/reduxjs/redux-toolkit"><img src="https://avatars.githubusercontent.com/u/13142323?s=80&v=4" width="40" height="40" alt="" /><br /><b>Redux Toolkit</b></a><br /><sub>★&nbsp;11.2k · <a href="https://github.com/reduxjs/redux-toolkit/pulls?q=is%3Apr+author%3AMahinAnowar+is%3Amerged">2&nbsp;merged</a></sub></td>
      <td width="20%"></td>
    </tr>
  </table>
  <sub>As of October 2026. Each count links to the merged pull requests on that project.</sub>
</details>

## What I build

**[NSU Insights](https://nsuinsights.com)**: an academic planning platform for North South University, used by <!-- nsu-users -->4,283<!-- /nsu-users --> students who have written <!-- nsu-reviews -->3,615<!-- /nsu-reviews --> teacher reviews. I planned, designed, built and run it alone: reviews, grade-distribution charts, a class-schedule planner with clash detection, and NSU Panda, a Gemini assistant with function calling and voice.<br />
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

## Work with me

I take on freelance projects, as fixed-price packages on Fiverr or directly for larger work, and I'm open to remote part-time and contract roles.

<table align="center" width="100%">
  <tr><th align="left">Service</th><th>Basic</th><th>Standard</th><th>Premium</th><th></th></tr>
  <tr>
    <td><b>Bug fixing</b><br /><sub>The root cause found, fixed and explained</sub></td>
    <td align="center"><b>$40</b><br /><sub>Small Bug Fixes<br />1 day</sub></td><td align="center"><b>$100</b><br /><sub>Medium-Level Fixes<br />3 days</sub></td><td align="center"><b>$220</b><br /><sub>Complex Fix + Review<br />7 days</sub></td>
    <td align="center"><a href="https://www.fiverr.com/s/1EA1Rak">Order</a></td>
  </tr>
  <tr>
    <td><b>Figma to code</b><br /><sub>Pixel-accurate React or Next.js, every screen size</sub></td>
    <td align="center"><b>$60</b><br /><sub>Landing Page<br />2 days</sub></td><td align="center"><b>$180</b><br /><sub>Multi-Page Site<br />5 days</sub></td><td align="center"><b>$400</b><br /><sub>Complete Website<br />7 days</sub></td>
    <td align="center"><a href="https://www.fiverr.com/s/DmB9Ab7">Order</a></td>
  </tr>
  <tr>
    <td><b>AI chatbots & integrations</b><br /><sub>GPT, Gemini or Claude on your own data</sub></td>
    <td align="center"><b>$100</b><br /><sub>Basic AI Integration<br />1 day</sub></td><td align="center"><b>$300</b><br /><sub>Custom AI Chatbot<br />4 days</sub></td><td align="center"><b>$700</b><br /><sub>Advanced AI Solution<br />7 days</sub></td>
    <td align="center"><a href="https://www.fiverr.com/s/3AGaYyL">Order</a></td>
  </tr>
  <tr>
    <td><b>Full-stack SaaS</b><br /><sub>Sign-in, payments, dashboard and API</sub></td>
    <td align="center"><b>$150</b><br /><sub>SaaS Starter<br />7 days</sub></td><td align="center"><b>$450</b><br /><sub>SaaS MVP<br />14 days</sub></td><td align="center"><b>$950</b><br /><sub>SaaS Platform<br />21 days</sub></td>
    <td align="center"><a href="https://www.fiverr.com/s/L3dyawQ">Order</a></td>
  </tr>
</table>

Something larger or ongoing? [Send a project brief](https://mahin-anowar.vercel.app/#contact) or [email me](mailto:mahinanowar479@gmail.com).

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MahinAnowar/MahinAnowar/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MahinAnowar/MahinAnowar/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/MahinAnowar/MahinAnowar/output/pacman-contribution-graph.svg">
</picture>

![](https://komarev.com/ghpvc/?username=MahinAnowar)
