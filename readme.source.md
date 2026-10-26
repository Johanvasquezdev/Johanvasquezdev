```aura width=1040 height=300
<div style={{
  width: '100%', height: '100%', display: 'flex', alignItems: 'center',
  padding: '34px 42px', boxSizing: 'border-box',
  background: 'linear-gradient(110deg, #080914 0%, #100F28 58%, #090B18 100%)',
  border: '1px solid #30265b', borderRadius: 20, position: 'relative',
  overflow: 'hidden', fontFamily: 'Inter'
}}>
  <svg width="520" height="300" viewBox="0 0 520 300" style={{ position: 'absolute', right: 0, top: 0 }}>
    <defs>
      <radialGradient id="skyGlow">
        <stop offset="0%" stopColor="#8B5CF6" stopOpacity=".28" />
        <stop offset="100%" stopColor="#6D4AFF" stopOpacity="0" />
      </radialGradient>
      <linearGradient id="beam">
        <stop offset="0%" stopColor="#D8CCFF" stopOpacity="0" />
        <stop offset="100%" stopColor="#FFFFFF" />
      </linearGradient>
    </defs>
    <circle cx="340" cy="122" r="145" fill="url(#skyGlow)" />
    <g fill="#F4F4F5">
      <circle cx="35" cy="30" r="1.2"><animate attributeName="opacity" values=".18;1;.18" dur="3.6s" begin=".2s" repeatCount="indefinite" /></circle>
      <circle cx="83" cy="89" r="1"><animate attributeName="opacity" values=".2;.9;.2" dur="4.3s" begin=".8s" repeatCount="indefinite" /></circle>
      <circle cx="141" cy="42" r="1.4"><animate attributeName="opacity" values=".15;1;.15" dur="5s" begin="1.1s" repeatCount="indefinite" /></circle>
      <circle cx="185" cy="135" r="1"><animate attributeName="opacity" values=".2;.95;.2" dur="3.9s" begin=".5s" repeatCount="indefinite" /></circle>
      <circle cx="221" cy="50" r="1.2"><animate attributeName="opacity" values=".18;1;.18" dur="4.5s" begin="1.6s" repeatCount="indefinite" /></circle>
      <circle cx="261" cy="28" r="1"><animate attributeName="opacity" values=".2;.9;.2" dur="3.2s" begin=".4s" repeatCount="indefinite" /></circle>
      <circle cx="299" cy="66" r="1.3"><animate attributeName="opacity" values=".15;1;.15" dur="4.8s" begin=".9s" repeatCount="indefinite" /></circle>
      <circle cx="446" cy="42" r="1.2"><animate attributeName="opacity" values=".18;1;.18" dur="3.8s" begin="1.3s" repeatCount="indefinite" /></circle>
      <circle cx="489" cy="104" r="1"><animate attributeName="opacity" values=".2;.9;.2" dur="5.2s" begin=".7s" repeatCount="indefinite" /></circle>
      <circle cx="470" cy="246" r="1.3"><animate attributeName="opacity" values=".15;1;.15" dur="3.7s" begin="1.4s" repeatCount="indefinite" /></circle>
      <circle cx="409" cy="278" r="1"><animate attributeName="opacity" values=".2;.95;.2" dur="4.6s" begin=".6s" repeatCount="indefinite" /></circle>
      <circle cx="328" cy="266" r="1.2"><animate attributeName="opacity" values=".15;1;.15" dur="3.4s" begin="1.8s" repeatCount="indefinite" /></circle>
      <circle cx="212" cy="264" r="1"><animate attributeName="opacity" values=".18;.9;.18" dur="4.9s" begin=".3s" repeatCount="indefinite" /></circle>
    </g>
    <path d="M400 154 A42 42 0 1 0 441 94 A32 32 0 1 1 400 154" fill="#D8CCFF" fillOpacity=".92" />
    <ellipse cx="420" cy="128" rx="75" ry="26" transform="rotate(-24 420 128)" fill="none" stroke="#A78BFA" strokeOpacity=".48" strokeWidth="1.2" />
    <g transform="rotate(-24 420 128)">
      <circle cx="495" cy="128" r="3" fill="#FFFFFF" />
      <animateTransform attributeName="transform" type="rotate" from="0 420 128" to="360 420 128" dur="24s" repeatCount="indefinite" />
    </g>
    <g opacity="0">
      <path d="M0 0 L74 0" fill="none" stroke="url(#beam)" strokeWidth="2" strokeLinecap="round" />
      <animate attributeName="opacity" values="0;1;0;0" keyTimes="0;.07;.18;1" dur="6.8s" begin="1.4s" repeatCount="indefinite" />
      <animateMotion path="M 145 75 L 340 142" dur="6.8s" begin="1.4s" repeatCount="indefinite" />
    </g>
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', gap: 9, position: 'relative' }}>
    <div style={{ color: '#B29DFF', fontSize: 12, letterSpacing: '2px', fontWeight: 700 }}>SOFTWARE ENGINEERING STUDENT · ITLA</div>
    <div style={{ color: '#F4F4F5', fontSize: 40, fontWeight: 800, letterSpacing: '-1px' }}>Johan Gabriel Vasquez</div>
    <div style={{ color: '#D1CDE0', fontSize: 16 }}>Full-stack developer building useful systems with code, data, and AI.</div>
    <div style={{ color: '#A78BFA', fontSize: 12, fontWeight: 700, letterSpacing: '1px' }}>C#  ·  TYPESCRIPT  ·  BACKEND  ·  AI</div>
  </div>
  <div style={{
    position: 'absolute', right: 34, top: 35, width: 342, height: 230, padding: 17,
    boxSizing: 'border-box', display: 'flex', flexDirection: 'column', gap: 12,
    background: 'rgba(12, 12, 30, 0.88)', border: '1px solid rgba(178,157,255,0.5)',
    borderRadius: 16, color: '#F4F4F5'
  }}>
    <div style={{ display: 'flex', alignItems: 'center', gap: 14 }}>
      <div style={{ width: 82, height: 82, padding: 3, borderRadius: 44, background: 'linear-gradient(135deg, #B29DFF, #6D4AFF)', display: 'flex', alignItems: 'center', justifyContent: 'center' }}>
        <img src="https://avatars.githubusercontent.com/u/232927980?v=4" width={76} height={76} style={{ borderRadius: 40, objectFit: 'cover' }} />
      </div>
      <div style={{ display: 'flex', flexDirection: 'column', gap: 6 }}>
        <div style={{ color: '#B29DFF', fontSize: 10, fontWeight: 700, letterSpacing: '1.5px' }}>PROFILE SCAN · ONLINE</div>
        <div style={{ color: '#F4F4F5', fontSize: 19, fontWeight: 700 }}>Johan Vasquez</div>
        <div style={{ color: '#B9B3CC', fontSize: 12 }}>Dominican Republic · ITLA</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', gap: 6, fontSize: 11, color: '#D4D0E4' }}>
      <div style={{ display: 'flex', justifyContent: 'space-between' }}><span>CORE STACK</span><span style={{ color: '#C8B8FF' }}>C# / TypeScript</span></div>
      <div style={{ display: 'flex', justifyContent: 'space-between' }}><span>FOCUS</span><span style={{ color: '#C8B8FF' }}>APIs / Cloud / AI</span></div>
      <div style={{ display: 'flex', justifyContent: 'space-between' }}><span>LEARNING</span><span style={{ color: '#C8B8FF' }}>Go / Flutter</span></div>
    </div>
    <svg width="305" height="10" viewBox="0 0 305 10">
      <rect x="0" y="3" width="305" height="4" rx="2" fill="#282440" />
      <rect x="0" y="3" width="52" height="4" rx="2" fill="#B29DFF">
        <animate attributeName="width" values="52;252;116;52" dur="5s" repeatCount="indefinite" />
      </rect>
    </svg>
    <div style={{ color: '#8E86AA', fontSize: 9, letterSpacing: '1.3px' }}>LOADING PROJECT SIGNALS  ·  07 ACTIVE</div>
  </div>
</div>
```

## About

I'm a software engineering student at ITLA and a full-stack developer in the Dominican Republic. I build complete applications, from APIs and data models to cloud deployment. My work spans clean architecture, application security, AI-assisted analysis, and product-focused web apps.

**Most used:** C# and TypeScript. **Currently learning:** Go and Flutter.

## What I'm building

- **[Armelis](https://github.com/Johanvasquezdev/Armelis):** Open-source application security intelligence for AI-assisted teams. It maps vulnerabilities into attack paths and helps teams prioritize fixes.
- **[Meridas](https://github.com/Johanvasquezdev/Meridas-Assistant):** A proprietary operational evidence intelligence system. It checks answers against source documents, detects conflicting versions, and routes unresolved questions for human review.
- **[MedAgenda](https://github.com/Johanvasquezdev/MedAgenda):** A healthcare scheduling system for patients, doctors, and administrators, with a .NET API and web and desktop clients.
- **[Artemis Banking](https://github.com/Johanvasquezdev/ArtemisBankingPro):** A .NET 9 banking application built with Onion Architecture, CQRS, and Azure Functions.
- **AegisSpace:** A multi-cloud change observatory concept for tracking infrastructure events, detecting Terraform drift, and comparing AI agents.
- **Ossandra:** An operational intelligence platform connecting CRM, POS, and inventory with observability, security, analytics, and AI.
- **PyroGravity (Flame in Freefall):** A NASA Space Apps Challenge 2026 team prototype for exploring and comparing microgravity combustion experiments. I'm building its evidence-backed AI analysis component.

## Tech stack

### Languages

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white" alt="C#" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3" />
</p>

### Frontend and mobile

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Vue-4FC08D?style=flat&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white" alt="Flutter" />
</p>

### Backend and architecture

<p>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/REST_APIs-4B5563?style=flat" alt="REST APIs" />
  <img src="https://img.shields.io/badge/Clean_Architecture-6D4AFF?style=flat" alt="Clean Architecture" />
</p>

### Data, cloud, and delivery

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white" alt="Azure" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=FF9900" alt="AWS" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white" alt="Terraform" />
</p>

### AI, security, and tools

<p>
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/RAG-4B5563?style=flat" alt="RAG" />
  <img src="https://img.shields.io/badge/CCNA-1BA0D7?style=flat&logo=cisco&logoColor=white" alt="CCNA" />
  <img src="https://img.shields.io/badge/TCP%2FIP-374151?style=flat" alt="TCP/IP" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat&logo=visualstudio&logoColor=white" alt="Visual Studio" />
  <img src="https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat&logo=intellijidea&logoColor=white" alt="IntelliJ IDEA" />
</p>

## GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Johanvasquezdev&show_icons=true&hide_border=true&theme=transparent" alt="Johan's GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Johanvasquezdev&hide_border=true&theme=transparent" alt="GitHub contribution streak" />
</p>

## Let's connect

<p align="center">
  <a href="https://www.linkedin.com/in/johan-gabriel-vasquez-5b539a312/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn" /></a>
  <a href="mailto:johanvasquezdev3@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-6D4AFF?style=for-the-badge&logo=gmail" alt="Email" /></a>
</p>

