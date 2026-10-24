<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&pause=500&width=520&lines=Hey!+Welcome+to+my+GitHub.;I'm+Jimmy+He." alt="Hey! Welcome to my GitHub. I'm Jimmy He." />
</a>

Software engineer focused on full-stack and backend web development. M.S. in Computer Science at Boston University (December 2026); B.S. in Computer Science and Data Science from UW-Madison.

Looking for new grad software engineering roles starting in 2027.

[Portfolio](https://www.jimmyhe05.com) · [Resume](https://www.jimmyhe05.com/jimmy_he_resume.pdf) · [LinkedIn](https://linkedin.com/in/jimmyhe05) · [Email](mailto:jimmyhe05@gmail.com)

---

## Projects

### [Karaoke Reservation System](https://github.com/jimmyhe05/karaoke-reservation-operations-system) · [Live demo](https://karaoke-reservation-system.onrender.com/)
Room booking web app for a three-room karaoke venue: customer requests, staff approval, pricing, and live staff updates. Personal project.
- Prevents double-bookings by locking the room row (`SELECT ... FOR UPDATE`) and checking overlaps in the same transaction
- Database adapter runs the same SQL on SQLite locally and PostgreSQL (Neon) in deployment, with a migration runner
- Pushes booking changes to the staff panel with Server-Sent Events; 77 passing pytest tests

`FastAPI` `Python` `PostgreSQL` `SQLAlchemy` `Docker` `pytest`

### [Symporter](https://se-symporter-clean.vercel.app/) · BU Spark! client project
Research matching platform connecting undergraduates with faculty, built from client Figma designs in a four-person Agile team.
- Built two-role sign-up, role-protected pages, dashboards, the application pipeline, interview scheduling, and in-app messaging
- Role-based access with Clerk, Next.js middleware, and server-side ownership checks on every API route
- Every pull request ran lint and Jest tests in GitHub Actions before our technical project manager reviewed and merged it

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Clerk` `Jest`

### [NUU Mobile Churn Analytics Platform](https://github.com/jimmyhe05/ML-Powered-Customer-Analytics-Platform) · industry capstone
Churn analytics dashboard for a phone manufacturer, built with a team of data scientists who trained the models.
- Built the React front end: navigation, an analytics page of ten chart components, data upload, and batch churn prediction
- Built Flask endpoints that load CSV and Excel uploads into PostgreSQL and serve the chart aggregates

`React` `Flask` `PostgreSQL` `pandas`

### [Cal.diy](https://github.com/calcom/cal.diy) · open source
- Fixed a billing bug where add-on charges were dropped for additional seat bookings ([#29639](https://github.com/calcom/cal.diy/pull/29639), merged)
- Proposed a row-locking fix for concurrent bookings bypassing booking limits ([#29646](https://github.com/calcom/cal.diy/pull/29646), open)

`TypeScript` `Next.js` `Prisma`

### [Legends: Monsters and Heroes](https://github.com/jimmyhe05/legends-monsters-and-heroes)
Turn-based Java RPG built around object-oriented design: Strategy for monster targeting, Template Method for leveling up, Factory for loading heroes, monsters, and items, and Memento for save and load.

`Java` `OOP` `Design patterns`

---

## Skills

- **Languages:** Python, TypeScript, JavaScript, Java, SQL, HTML/CSS
- **Frameworks:** React, Next.js, FastAPI, Flask
- **Data and tools:** PostgreSQL, SQLite, Prisma, Docker, Git, GitHub Actions, Google Cloud Platform
- **Testing:** pytest, Jest, React Testing Library

---

## GitHub Stats

<table align="center" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td valign="top" width="50%">
      <img src="https://github-readme-stats-fast.vercel.app/api?username=jimmyhe05&show_icons=true&hide_rank=true&theme=github_dark&hide_border=true" width="100%" alt="GitHub stats"/>
    </td>
    <td valign="top" width="50%">
      <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=jimmyhe05&layout=compact&theme=github_dark&hide_border=true" width="100%" alt="Top languages"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="https://github-readme-stats-fast.vercel.app/api/streak?username=jimmyhe05&theme=github_dark&hide_border=true" width="60%" alt="Contribution streak"/>
    </td>
  </tr>
</table>
