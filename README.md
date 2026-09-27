# Hi there, I'm Hieu Ngo (NTHieu-bk) 👋

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=NTHieu-bk&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" />
</p>

A passionate **Backend / Fullstack Software Engineer** dedicated to building resilient enterprise architectures, deterministic state machines, and bulletproof concurrency controls.

- 🎓 **Education:** Computer Science / Software Engineering at **Ho Chi Minh City University of Technology (HCMUT — VNU-HCM)**.
- 🔭 **Current Focus:** Enterprise-grade **.NET 10 Clean Architecture**, **PostgreSQL 17 Concurrency**, and **Distributed System Reliability**.
- 🛡️ **Security Philosophy:** Strict **Zero-Trust Backend Validation** — mitigating OWASP Top 10 API vulnerabilities (BOLA/IDOR, Race Conditions, Privilege Escalation).
- 💬 **Ask me about:** `.NET Core`, `Clean Architecture`, `EF Core Concurrency & Indexing`, `PostgreSQL Query Optimization`, `State Machine Design`.
- 📫 **Connect with me:** Reach out for collaboration or technical exchanges!

---

### 🚀 Spotlight Project: DoctorCare — Healthcare Scheduling Engine

<table>
  <tr>
    <td width="100%">
      <h3>🏥 <a href="https://github.com/NTHieu-bk/doctor-booking">DoctorCare — Enterprise Healthcare Booking Platform</a></h3>
      <p>
        A production-grade online medical scheduling engine architected under strict <b>Clean Architecture (4 layers)</b> and <b>Domain-Driven Design (DDD)</b> principles.
      </p>
      <ul>
        <li><b>Atomic Concurrency Defense:</b> Multi-tier race condition prevention using <i>PostgreSQL Filtered Unique Indexes</i> (<code>"Status" NOT IN ('Cancelled', 'Rejected')</code>), resolving millisecond-level booking collisions with deterministic <code>409 Conflict</code>.</li>
        <li><b>Zero-Trust Identity Scoping:</b> Complete eradication of OWASP BOLA/IDOR by overriding client-supplied IDs with cryptographic claims from stateless JWTs.</li>
        <li><b>Deterministic State Machine:</b> Enforced 5-state lifecycle (<i>Pending &rarr; Confirmed &rarr; Completed</i>, with terminal immutability and a 4-hour lead-time cancellation guard).</li>
        <li><b>Automated Testing & Invariant Verification:</b> 42 xUnit unit tests verifying edge-case domain policies, half-hour slot constraints, and role tenancy.</li>
      </ul>
      <p>
        <b>Tech Stack:</b> <code>.NET 10</code> • <code>C#</code> • <code>PostgreSQL 17</code> • <code>EF Core</code> • <code>Docker</code> • <code>Next.js 16</code> • <code>xUnit</code>
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Stack & Tooling

<p align="left">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>

<p align="left">
  <!-- Frameworks & Ecosystem -->
  <img src="https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET 10" />
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="EF Core" />
  <img src="https://img.shields.io/badge/Next.js_16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
</p>

<p align="left">
  <!-- Databases & Infrastructure -->
  <img src="https://img.shields.io/badge/PostgreSQL_17-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

---

### 📊 GitHub Activity & Insights

<p align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=NTHieu-bk&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Hieu's GitHub Stats" width="49%" />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=NTHieu-bk&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="47%" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=NTHieu-bk&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="97%" />
</p>

---

<p align="center">
  <i>"Architecture is not about making things complicated; it is about drawing clear boundaries that make complex invariants manageable."</i>
</p>
