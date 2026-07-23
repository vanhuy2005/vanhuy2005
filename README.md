## Hi, I'm Nguyen Van Quang Huy 👋

📍 Ho Chi Minh City | 🎓 Third-year IT Student @ HCMC University of Education | 🔍 Seeking Internship

![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/-React-61DAFB?style=flat&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?style=flat&logo=express&logoColor=white) ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white) ![Laravel](https://img.shields.io/badge/-Laravel-FF2D20?style=flat&logo=laravel&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat&logo=redis&logoColor=white) ![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=flat&logo=firebase&logoColor=black) ![Socket.io](https://img.shields.io/badge/-Socket.io-010101?style=flat&logo=socketdotio&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Framer Motion](https://img.shields.io/badge/-Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white) ![GSAP](https://img.shields.io/badge/-GSAP-88CE02?style=flat&logo=greensock&logoColor=black) ![Zustand](https://img.shields.io/badge/-Zustand-453F39?style=flat) ![JWT](https://img.shields.io/badge/-JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white) ![Cloudinary](https://img.shields.io/badge/-Cloudinary-3448C5?style=flat&logo=cloudinary&logoColor=white)

> Fullstack Software Engineer. Shipped **9 end-to-end projects** across streaming, real-time chat, EdTech, e-commerce, alumni networking & route optimization — with measurable results.

>Language: Vietnamese (native), English (proficient), Chinese (fundamental)

>Certifications & Honors & Awards: Updating

📫 [nguyen.van.quang.huy.2105@gmail.com](mailto:nguyen.van.quang.huy.2105@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nvqhuy2005) · [CV](%5BCV%5D%5BNguy%E1%BB%85n%20V%C4%83n%20Quang%20Huy%5D%5BFrontend_Intern%5D.pdf)

### Projects

<details>
<summary>🎬 <b>Netflix Clone</b> — Multi-Profile Streaming UI</summary>

> React 19 · Firebase · Framer Motion · Tailwind CSS

**Situation:** Users need a seamless streaming experience that supports multiple personal accounts with independent watch histories on a single device.

**Task:** Build an intuitive streaming interface with a secure profile gate feature and real-time user data synchronization.

**Action:** Developed the front-end using React 19 and Tailwind CSS, designing a hierarchical data structure on Firestore (`users/uid/profiles`). Implemented code splitting, debounced search, and smooth transitions using Framer Motion to elevate the visual experience.

**Result:** Achieved **sub-100ms** latency for "My List" synchronization, reduced API overhead by **~40%**, and maintained stable **60fps** shared element transitions.

[Live Demo](https://n3tflix-vanhuy2005-deployment-v1.netlify.app/) · [Source](https://github.com/vanhuy2005/netflix)

<!-- <img src="https://raw.githubusercontent.com/vanhuy2005/netflix/main/public/preview-image.png" width="100%" /> -->
</details>

<details>
<summary>💬 <b>ChatHub</b> — Real-Time Messaging Platform</summary>

> Socket.io · Zustand · Node.js · Express · MongoDB

**Situation:** Modern messaging apps require instant response times and high security to ensure uninterrupted communication.

**Task:** Build a real-time chat platform capable of processing messages instantly while preventing web security vulnerabilities.

**Action:** Utilized Socket.io with Node.js/Express for the messaging flow and typing indicators. Designed an Optimistic UI with skeleton loaders to keep the interface stable, and secured the authentication flow using JWT in HTTP-Only cookies.

**Result:** Successfully deployed the app with 32 custom themes, delivering a smooth user experience with zero Cumulative Layout Shift (CLS) and robust protection against XSS attacks.

[Live Demo](https://real-time-chat-v1.onrender.com) · [Source](https://github.com/vanhuy2005/real-time-chat)

<!-- <img src="https://raw.githubusercontent.com/vanhuy2005/real-time-chat/main/screenshots/chat-interface.png" width="100%" /> -->
</details>

<details>
<summary>🛒 <b>FruitHub</b> — E-commerce with admin dashboard</summary>

> React 19 · Node.js · Express · MongoDB · Cloudinary · JWT · Render 

- Cart engine via `useReducer` + Context API
- Role-Based Access Control with JWT-protected admin routes
- Server-side pagination, sorting & debounced search

[Live Demo] [Client](https://github.com/vanhuy2005/fresh-fruit-web) [Server](https://fresh-fruit-web-deployment-server.onrender.com/) [Source](https://github.com/vanhuy2005/fresh-fruit-web)

<!-- <img src="https://raw.githubusercontent.com/vanhuy2005/fresh-fruit-web/main/client/public/home-preview.png" width="100%" /> -->
</details>

<details>
<summary>🍽️ <b>ScanToOrder</b> — Digital menu & kitchen management for restaurants</summary>

> React · Node.js · PostgreSQL · Socket.io

- QR-based digital menu — customers scan, browse, and order from their phone
- Real-time order pipeline connecting customers → waitstaff → kitchen via WebSocket
- Kitchen display system with order queue, priority sorting, and completion tracking
- Built for mid-scale restaurants — manages multiple tables, split bills, and order history

_Private repository_

</details>

<details>
<summary>🚗 <b>EV Router</b> — Smart Route Planner for Electric Vehicles</summary>

> Python · Flask · MongoDB · Folium · A\* Algorithm

**Situation:** EV drivers in Vietnam struggle to find optimal routes with charging stations while avoiding geographical obstacles and unnecessary tolls.

**Task:** Design a smart routing system to calculate real-world costs and automatically suggest logical charging stops on long, complex routes (e.g., North-South).

**Action:** Built an A\* heuristic AI pathfinding algorithm on a Python/Flask backend. Established an anchor-point system to prevent sea-crossing paths and developed an anti-ghost cost filter to deduplicate charges from overlapping toll cameras.

**Result:** The system automatically analyzes and proposes smart charging strategies (charging only enough to reach the next high-power station), significantly saving user wait time while providing real-time cost breakdowns for electricity and tolls.

[Source](https://github.com/vanhuy2005/ev-router)

</details>

<details>
<summary>🌐 <b>Static E-Commerce</b> — Pure HTML/CSS/JS</summary>

> HTML5 · CSS3 · Vanilla JavaScript

- Pixel-perfect Flexbox + Grid layout, no frameworks
- Mobile-first responsive design
- Vanilla JS DOM manipulation & event delegation

[Source](https://github.com/vanhuy2005/static-ecommerce)

<!-- <img src="https://raw.githubusercontent.com/vanhuy2005/static-ecommerce/main/preview-desktop.png" width="100%" /> -->
</details>

---

### GitHub Stats
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=vanhuy2005&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=adbac7&currStreakNum=adbac7&sideNums=adbac7&dates=adbac7" height="150" />
</div>

