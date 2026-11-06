<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Faisal Nadaf, DevOps Engineer and Full-Stack Developer, with an isometric illustration of server racks, containers, a monitoring panel and a cloud" />
</p>

<p align="center">
  <img src="assets/typing.svg" width="720" alt="Automating deploys with GitHub Actions. Containerizing apps with Docker Compose. Shipping to AWS EC2, Vercel, Netlify and Render. Building full-stack apps with React, Next.js and Node.js. Learning Kubernetes, Terraform and Grafana." />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/faisal-nadaf-429160281/"><img src="assets/social/linkedin.svg" height="40" alt="LinkedIn" /></a>&nbsp;
  <a href="https://x.com/faisal_nadaf"><img src="assets/social/x.svg" height="40" alt="X / Twitter" /></a>&nbsp;
  <a href="https://faisal-development.netlify.app"><img src="assets/social/portfolio.svg" height="40" alt="Portfolio website" /></a>&nbsp;
  <a href="mailto:faisalfnadaf@gmail.com"><img src="assets/social/email.svg" height="40" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FaisalNadaf&label=profile%20views&color=22d3ee&style=flat-square" alt="Profile views" />
</p>

<img src="assets/divider.svg" width="100%" alt="" />

## 01 · About me

I'm a developer from **Belgaum, Karnataka, India**, moving from full-stack development into **DevOps**. I've spent the last few years shipping web and mobile apps with **React, Next.js, Node.js and Flutter**, and now I focus on what happens after the code is written: packaging apps into containers, automating their deployments, and running them on cloud infrastructure.

Building the apps myself means I treat infrastructure as part of the product. I want deploys that are repeatable, configuration that stays out of the code, and a pipeline that turns `git push` into a running service.

<table>
  <tr>
    <td width="50%" valign="top">
      <b>🔁 CI/CD automation</b><br />
      GitHub Actions workflows that deploy on every push to <code>main</code>, with credentials kept in GitHub Secrets.
    </td>
    <td width="50%" valign="top">
      <b>📦 Containers</b><br />
      Dockerfiles and Docker Compose stacks for React and Next.js apps, including a Next.js + PostgreSQL setup.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <b>☁️ Cloud deployments</b><br />
      AWS EC2 (Ubuntu) over SSH, plus Vercel, Netlify and Render blueprints with health checks and auto-deploy.
    </td>
    <td width="50%" valign="top">
      <b>🧩 Full-stack and AI</b><br />
      MERN and Next.js + Prisma apps, Flutter mobile apps, and Gemini, OpenAI and TensorFlow integrations.
    </td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%" alt="" />

## 02 · DevOps toolchain

How I take a project from idea to production. Each stage lists tools I've used in my own repositories, and the dashed items are the ones I'm learning now.

<p align="center">
  <img src="assets/devops-lifecycle.svg" width="100%" alt="DevOps lifecycle loop. Plan: GitHub repos, README specs, branch per feature. Code: Git, TypeScript, JavaScript, Python, Dart. Build: npm, Vite, Next.js, Dockerfile builds, Prisma generate. Test: ESLint, Vitest, Playwright. Release: GitHub Actions on push to main, GitHub Secrets. Deploy: AWS EC2 over SSH, Docker Compose, Vercel, Netlify, Render. Operate: Ubuntu Linux, Compose restarts, environment-based config. Monitor: health checks, Vercel Analytics, and Prometheus with Grafana (learning)." />
</p>

The deployment path below is based on my [Applied DevOps & Deployment Engineering](https://github.com/FaisalNadaf/APPLIED-DEVOPS-AND-DEPLOYMENT-ENGINEERING) project. The green arc is what runs today. The dashed registry step is the next improvement: build the image in CI, push it to a registry, and have the server pull it.

<p align="center">
  <img src="assets/architecture.svg" width="100%" alt="Deployment architecture: Developer pushes to GitHub, GitHub Actions runs the pipeline, Docker packages the app, a container registry (planned next step) stores the image, AWS EC2 runs it with Docker Compose, and health checks monitor it. Today GitHub Actions deploys over SSH, running git pull and docker compose up --build on the server." />
</p>

<img src="assets/divider.svg" width="100%" alt="" />

## 03 · Tech stack

<table>
  <tr>
    <td width="50%" valign="top">
      <b>☁️ Cloud &amp; hosting</b><br /><br />
      <img src="https://skillicons.dev/icons?i=aws,vercel,netlify,firebase&theme=dark" height="40" alt="AWS, Vercel, Netlify, Firebase" /><br />
      <sub>+ Render · Cloudflare Workers (basics)</sub>
    </td>
    <td width="50%" valign="top">
      <b>📦 Containers &amp; CI/CD</b><br /><br />
      <img src="https://skillicons.dev/icons?i=docker,githubactions,git,github&theme=dark" height="40" alt="Docker, GitHub Actions, Git, GitHub" /><br />
      <sub>+ Docker Compose · GitHub Secrets</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>🐧 Linux &amp; shell</b><br /><br />
      <img src="https://skillicons.dev/icons?i=linux,ubuntu,bash&theme=dark" height="40" alt="Linux, Ubuntu, Bash" /><br />
      <sub>Ubuntu servers on AWS EC2</sub>
    </td>
    <td valign="top">
      <b>💻 Languages</b><br /><br />
      <img src="https://skillicons.dev/icons?i=ts,js,py,dart,java&theme=dark" height="40" alt="TypeScript, JavaScript, Python, Dart, Java" /><br />
      <sub>Most of my code is TypeScript and JavaScript</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>🧩 Backend &amp; APIs</b><br /><br />
      <img src="https://skillicons.dev/icons?i=nodejs,express,flask,prisma&theme=dark" height="40" alt="Node.js, Express, Flask, Prisma" /><br />
      <sub>+ Socket.io · JWT auth · REST APIs</sub>
    </td>
    <td valign="top">
      <b>🗄️ Databases</b><br /><br />
      <img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql&theme=dark" height="40" alt="MongoDB, PostgreSQL, MySQL" /><br />
      <sub>+ Firestore · Redis (basics)</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>🎨 Frontend &amp; mobile</b><br /><br />
      <img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,threejs,flutter&theme=dark" height="40" alt="React, Next.js, Vite, Tailwind CSS, Three.js, Flutter" /><br />
      <sub>Where I started, and still ship</sub>
    </td>
    <td valign="top">
      <b>🤖 AI &amp; testing</b><br /><br />
      <img src="https://skillicons.dev/icons?i=tensorflow,vitest&theme=dark" height="40" alt="TensorFlow, Vitest" /><br />
      <sub>+ Gemini &amp; OpenAI APIs · Playwright · ESLint</sub>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <b>🌱 Currently learning</b>: the next layer of the DevOps stack<br /><br />
      <img src="https://skillicons.dev/icons?i=kubernetes,terraform,prometheus,grafana,nginx&theme=dark" height="40" alt="Kubernetes, Terraform, Prometheus, Grafana, Nginx" /><br />
      <sub>Kubernetes · Terraform · Prometheus · Grafana · Nginx. Not production experience yet.</sub>
    </td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%" alt="" />

## 04 · Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FaisalNadaf/APPLIED-DEVOPS-AND-DEPLOYMENT-ENGINEERING"><img src="assets/projects/auto-deploy.svg" width="100%" alt="Auto-Deploy Pipeline project cover" /></a>
      <h3><a href="https://github.com/FaisalNadaf/APPLIED-DEVOPS-AND-DEPLOYMENT-ENGINEERING">Auto-Deploy Pipeline</a></h3>
      A React app packaged with Docker and Docker Compose. A GitHub Actions workflow SSHes into an Ubuntu EC2 instance on every push to <code>main</code>, pulls the latest code and rebuilds the containers.
      <br /><br /><code>Docker</code> <code>Compose</code> <code>GitHub Actions</code> <code>AWS EC2</code> <code>React</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FaisalNadaf/INNB001-FARM-SARTHI-AI"><img src="assets/projects/farm-sarthi-ai.svg" width="100%" alt="Farm Sarthi AI project cover" /></a>
      <h3><a href="https://github.com/FaisalNadaf/INNB001-FARM-SARTHI-AI">Farm Sarthi AI</a></h3>
      A cross-platform Flutter app for farmers. It sends a photo of a rice leaf to a TensorFlow/Keras model served by a Flask API, then shows the predicted disease, its symptoms and remedies in several languages.
      <br /><br /><code>Flutter</code> <code>TensorFlow</code> <code>Flask</code> <code>OpenCV</code> <code>MongoDB</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FaisalNadaf/JGI-GANAKA-VIDYA"><img src="assets/projects/institute-portal.svg" width="100%" alt="Institute Partner Portal project cover" /></a>
      <h3><a href="https://github.com/FaisalNadaf/JGI-GANAKA-VIDYA">Institute Partner Portal</a></h3>
      An admin console for partner institutes on a rural learning platform, sharing one MongoDB database with the student app. The API is deployed through a Render blueprint with a health-check path, auto-deploy and generated secrets.
      <br /><br /><code>React</code> <code>Express</code> <code>MongoDB</code> <code>JWT</code> <code>Render</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FaisalNadaf/3D-products-wear-and-test"><img src="assets/projects/3d-products.svg" width="100%" alt="3D Product Experiences project cover" /></a>
      <h3><a href="https://github.com/FaisalNadaf/3D-products-wear-and-test">3D Product Experiences</a></h3>
      A multi-page showcase with a jewellery try-on, a watch configurator, a T-shirt designer and a curtain visualizer. Camera tracking runs on the device with self-hosted MediaPipe, so no images are uploaded.
      <br /><br /><code>Three.js</code> <code>React Three Fiber</code> <code>MediaPipe</code> <code>TypeScript</code> <code>Vite</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/FaisalNadaf/CHAT_APP"><img src="assets/projects/realtime-chat.svg" width="100%" alt="Real-Time Chat App project cover" /></a>
      <h3><a href="https://github.com/FaisalNadaf/CHAT_APP">Real-Time Chat App</a></h3>
      A MERN chat app with Socket.io messaging, online presence, JWT authentication and Zustand for global state, with error handling on both client and server.
      <br /><br /><code>MongoDB</code> <code>Express</code> <code>React</code> <code>Node.js</code> <code>Socket.io</code>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/FaisalNadaf/taskify-ai-agent"><img src="assets/projects/taskify-ai.svg" width="100%" alt="Taskify AI Agent project cover" /></a>
      <h3><a href="https://github.com/FaisalNadaf/taskify-ai-agent">Taskify AI Agent</a></h3>
      A Next.js task manager that reads each task's description and uses Gemini to sort it into high, medium or low priority automatically.
      <br /><br /><code>Next.js</code> <code>TypeScript</code> <code>Gemini API</code> <code>Tailwind CSS</code>
    </td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%" alt="" />

## 05 · GitHub analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=FaisalNadaf&theme=tokyonight" width="100%" alt="Faisal's GitHub profile summary and contribution graph" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=FaisalNadaf&theme=tokyonight" width="49%" alt="GitHub stats: stars, commits, pull requests, issues and contributions" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=FaisalNadaf&theme=tokyonight" width="49%" alt="Top languages by commit" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=FaisalNadaf&background=0B1124&border=1F2B4D&ring=22D3EE&fire=8B5CF6&currStreakNum=E8EEFA&sideNums=E8EEFA&currStreakLabel=22D3EE&sideLabels=8C9CBA&dates=8C9CBA&stroke=1F2B4D&border_radius=12" width="60%" alt="GitHub contribution streak" />
</p>

<img src="assets/divider.svg" width="100%" alt="" />

## 06 · Now learning

- **Container registries.** Building images in GitHub Actions and pushing them to GHCR, so servers pull a tested image instead of building on the host.
- **Kubernetes.** Moving from single-host Docker Compose to Deployments, Services and rolling updates.
- **Terraform.** Defining the EC2 and networking setup as code instead of configuring it by hand.
- **Prometheus and Grafana.** Going beyond health checks to metrics, dashboards and alerts.

## 07 · Hackathons and builds

- [**EVOGEN Hackathon 2025**](https://github.com/FaisalNadaf/EVOGEN-HACKATHON-2025): a web app built during the event.
- [**HackVyuha**](https://github.com/FaisalNadaf/hackvyuha-21): a CCTV detection prototype with a Python detection module, a backend and a client.
- [**Nova Creator Cosmic Dev Night**](https://github.com/FaisalNadaf/Nova-Creator-Cosmic-dev-night-challenge): a Titanic survival prediction model with feature engineering and model comparison.

<!-- Add verified certifications here, e.g.  - **AWS Certified Cloud Practitioner** (issuer, year) -->

<img src="assets/divider.svg" width="100%" alt="" />

## 08 · Let's connect

I'm open to **DevOps, cloud and full-stack roles**, freelance work and collaborations. The fastest way to reach me is [email](mailto:faisalfnadaf@gmail.com) or [LinkedIn](https://www.linkedin.com/in/faisal-nadaf-429160281/). You can also see more of my work on my [portfolio](https://faisal-development.netlify.app).

<p align="center">
  <img src="assets/footer.svg" width="100%" alt="Build, ship, observe, repeat. Thanks for stopping by." />
</p>
