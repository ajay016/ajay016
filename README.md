<!-- Profile README for github.com/ajay016 -->

<div align="center">
  <img width="100%" alt="Ajay Ghosh — Backend Software Engineer" src="https://capsule-render.vercel.app/api?type=waving&amp;height=205&amp;color=0:0B1220,50:12365A,100:0F766E&amp;section=header&amp;text=AJAY%20GHOSH&amp;fontSize=47&amp;fontColor=FFFFFF&amp;fontAlignY=38&amp;desc=Backend%20Software%20Engineer%20%7C%20Python%20%26%20Django&amp;descSize=19&amp;descAlignY=60&amp;animation=fadeIn" />

  <h3>Building reliable systems for transactions, automation &amp; real-time operations.</h3>

  <p>
    <a href="https://linkedin.com/in/ajay-ghosh"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" /></a>
    <a href="mailto:ajayghosh28@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" /></a>
    <a href="https://stackoverflow.com/users/2972318/ajay"><img alt="Stack Overflow" src="https://img.shields.io/badge/Stack%20Overflow-F58025?style=for-the-badge&amp;logo=stackoverflow&amp;logoColor=white" /></a>
    <a href="https://github.com/ajay016"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" /></a>
  </p>

  <sub>📍 Dhaka, Bangladesh &nbsp; • &nbsp; 3+ years of professional experience &nbsp; • &nbsp; Software Engineer at IGL Web Ltd</sub>
</div>

---

### 👋 A little about me

I'm a **backend-focused software engineer** working primarily with **Python, Django, PostgreSQL, Redis, and Celery**. I build and maintain production applications where a failed transaction, duplicate order, or slow query has a real-world impact.

My work spans **real-time booking platforms, eSIM commerce and fulfillment, biometric HR systems, and high-throughput automation**. I enjoy designing reliable APIs, untangling concurrency issues, improving database performance, and making complex workflows easier to operate.

### 📈 Engineering highlights

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%"><strong>300+</strong><br /><sub>REST API endpoints<br />HR SaaS platform</sub></td>
      <td align="center" width="25%"><strong>96% fewer</strong><br /><sub>DB queries<br />677 → 27 per page</sub></td>
      <td align="center" width="25%"><strong>BDT 1.1M+</strong><br /><sub>Monthly ticket sales<br />MK Shipping</sub></td>
      <td align="center" width="25%"><strong>1,580+</strong><br /><sub>Automated tests<br />Nomadly platform</sub></td>
    </tr>
  </table>
</div>

### 🏗️ Featured production work

<!-- Project 01 -->
<table>
  <tr>
    <td>
      <h3>01 &nbsp; Workforce — Attendance &amp; Payroll HR SaaS</h3>
      <p><strong>Multi-company workforce operations powered by biometric attendance.</strong></p>
      <p>Co-built the platform in a two-person team, connecting ZKTeco fingerprint and face-recognition devices to attendance, overtime, leave, and payroll workflows.</p>
      <ul>
        <li>Created <strong>300+ REST endpoints</strong> with API-key protection, two-step authentication, throttling, and documentation.</li>
        <li>Cut attendance-page database queries from <strong>677 to 27</strong> by persisting computed results.</li>
        <li>Delivered configurable attendance policies, a live presence board, and correction workflows.</li>
      </ul>
      <p><code>Python</code> <code>Django</code> <code>DRF</code> <code>PostgreSQL</code> <code>ZKTeco</code></p>
      <p><a href="https://workforce.iglweb.com">↗ Live platform</a> &nbsp;·&nbsp; <a href="https://workforce.iglweb.com/api/docs">↗ API documentation</a></p>
    </td>
  </tr>
</table>

<!-- Project 02 -->
<table>
  <tr>
    <td>
      <h3>02 &nbsp; Nomadly — eSIM Platform &amp; Marketplace</h3>
      <p><strong>End-to-end eSIM sales, automated provisioning, customer self-service, and AI-assisted support.</strong></p>
      <p>Integrated Airalo and eSIM Access with Digiseller/Plati.market and GGsel, including concurrent order processing and provider fulfillment.</p>
      <ul>
        <li>Designed <strong>idempotent purchasing</strong>, retry and recovery mechanisms, and manual review for uncertain transactions.</li>
        <li>Built a bilingual customer portal with passwordless sign-in, installation guides, data-usage tracking, and alerts.</li>
        <li>Implemented an <strong>order-aware AI support assistant</strong> with guided troubleshooting and live operator handoff.</li>
        <li>Added <strong>1,580+ automated tests</strong>; AI support passed <strong>123/124</strong> evaluation scenarios.</li>
      </ul>
      <p><code>Django</code> <code>Celery</code> <code>Redis</code> <code>Provider APIs</code> <code>AI Integration</code></p>
      <p><a href="https://nomadly.cloud">↗ Nomadly</a> &nbsp;·&nbsp; <a href="https://marketplace.nomadly.cloud">↗ Marketplace</a></p>
    </td>
  </tr>
</table>

<!-- Project 03 -->
<table>
  <tr>
    <td>
      <h3>03 &nbsp; MK Shipping — Real-Time Ticketing</h3>
      <p><strong>Concurrent bookings and live seat availability for passenger vessels.</strong></p>
      <ul>
        <li>Built real-time booking updates with <strong>Django Channels, WebSockets, and Redis</strong>.</li>
        <li>Implemented dynamic vessel layouts, seat/cabin/vehicle booking, and multi-stop route pricing.</li>
        <li>Supports <strong>50+ bookings per day</strong> and <strong>BDT 1.1M+ in monthly ticket sales</strong>.</li>
      </ul>
      <p><code>Django</code> <code>Channels</code> <code>Redis</code> <code>WebSockets</code> <code>JavaScript</code></p>
      <p><a href="https://mkshippinglines.com">↗ Live platform</a></p>
    </td>
  </tr>
</table>

<!-- Project 04 -->
<table>
  <tr>
    <td>
      <h3>04 &nbsp; Razer — Bulk Purchase Automation</h3>
      <p><strong>High-throughput purchase workflows with concurrency and operational recovery.</strong></p>
      <ul>
        <li>Automated purchasing through <strong>Playwright</strong>, persistent browser sessions, and concurrent workers.</li>
        <li>Used <strong>Celery and Redis</strong> for task orchestration, retries, error tracking, and rate-limit handling.</li>
      </ul>
      <p><code>Python</code> <code>Playwright</code> <code>Celery</code> <code>Redis</code></p>
      <p><a href="https://rzrautobot.com">↗ Project website</a></p>
    </td>
  </tr>
</table>

### 🧰 My toolkit

<div align="center">
  <p><strong>Backend &amp; APIs</strong></p>
  <p>
    <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" />
    <img alt="Django" src="https://img.shields.io/badge/Django-092E20?style=flat-square&amp;logo=django&amp;logoColor=white" />
    <img alt="Django REST Framework" src="https://img.shields.io/badge/Django%20REST%20Framework-A30000?style=flat-square" />
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&amp;logo=javascript&amp;logoColor=black" />
  </p>
  <p><strong>Data, queues &amp; real-time</strong></p>
  <p>
    <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&amp;logo=postgresql&amp;logoColor=white" />
    <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&amp;logo=mysql&amp;logoColor=white" />
    <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&amp;logo=redis&amp;logoColor=white" />
    <img alt="Celery" src="https://img.shields.io/badge/Celery-37814A?style=flat-square&amp;logo=celery&amp;logoColor=white" />
    <img alt="WebSockets" src="https://img.shields.io/badge/WebSockets-0F766E?style=flat-square" />
  </p>
  <p><strong>Automation &amp; infrastructure</strong></p>
  <p>
    <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&amp;logo=playwright&amp;logoColor=white" />
    <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&amp;logo=docker&amp;logoColor=white" />
    <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=black" />
    <img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=flat-square&amp;logo=nginx&amp;logoColor=white" />
    <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&amp;logo=git&amp;logoColor=white" />
    <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&amp;logo=postman&amp;logoColor=white" />
  </p>
</div>

<details>
  <summary><strong>📁 More projects &amp; integrations</strong></summary>
  <br />
  <ul>
    <li><a href="https://felnatech.com"><strong>Felna Tech E-commerce</strong></a> — Django APIs, multi-vendor product and order management, authentication.</li>
    <li><a href="https://t.me/MSNGAMER_E_STORE_BOT"><strong>Telegram Voucher Purchase Bot</strong></a> — Transaction API and automated voucher purchasing workflows.</li>
    <li><strong>Facebook Messenger Admin</strong> — Conversation management, synchronization, and message history through the Meta API.</li>
    <li><strong>Online Bus Ticketing</strong> — Django route management, scheduling, and booking operations.</li>
  </ul>
</details>

### 💭 Engineering principles

> Build for the failure cases, not just the happy path. Make transactions safe, APIs clear, queries efficient, and production behavior observable.

---

<div align="center">
  <h3>Let's connect</h3>
  <p>Interested in backend engineering, reliable transaction systems, or automation?</p>
  <p>
    <a href="mailto:ajayghosh28@gmail.com"><strong>✉️ Email me</strong></a> &nbsp;·&nbsp;
    <a href="https://linkedin.com/in/ajay-ghosh"><strong>LinkedIn</strong></a> &nbsp;·&nbsp;
    <a href="https://stackoverflow.com/users/2972318/ajay"><strong>Stack Overflow</strong></a>
  </p>
  <sub>Some featured systems are commercial projects; their source code is not publicly available.</sub>
</div>

<!-- End of profile README -->
