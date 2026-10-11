<!--
ATHARV ROKADE — FIELD REPORT / 001
Original desktop + mobile illustration system: ./assets/*.svg
Responsive pictures select larger type art below 640px; GitHub renders the desktop fallback otherwise.
Full-width case cards avoid mobile table shrinking and horizontal overflow.
Design intentionally uses repository-hosted SVG artwork, not external stat-image generators.
To install: upload README.md AND the assets/ folder to the main branch of atharv834/atharv834.
Images are intentionally dark-backed so they display consistently in GitHub light and dark modes.
-->

<div align="center">

<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/00-hero-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/00-hero.svg" width="100%" alt="Atharv Rokade — security researcher and bug bounty hunter" />
</picture>

<br />

<a href="https://medium.com/@lordofheaven1234"><img src="https://img.shields.io/badge/RESEARCH%20JOURNAL-READ%20ARTICLES-CAFF5B?style=for-the-badge&labelColor=111A20&logo=medium&logoColor=white" alt="Research journal" /></a>
<a href="https://github.com/Atharv834?tab=repositories"><img src="https://img.shields.io/badge/GITHUB-EXPLORE%20PROJECTS-6EE7EF?style=for-the-badge&labelColor=111A20&logo=github&logoColor=white" alt="GitHub projects" /></a>
<a href="mailto:atharv04@duck.com"><img src="https://img.shields.io/badge/CONTACT-SEND%20AN%20EMAIL-FF9E80?style=for-the-badge&labelColor=111A20&logo=gmail&logoColor=white" alt="Contact by email" /></a>

<br /><br />

<strong>Independent security research · Web applications · Cloud exposure · Responsible disclosure</strong>

<br />

<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/01-impact-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/01-impact.svg" width="100%" alt="Selected bug bounty earnings, ten plus disclosure acknowledgements and CAPv2 certification" />
</picture>

</div>

<br />

### `// THE PERSON BEHIND THE REPORTS`

I'm **Atharv Rokade**, also known as **`lordofheaven1234`** — a security researcher from India. I investigate issues in real systems, write clear technical case studies, and report findings through responsible disclosure. My work focuses on **XSS, SQL injection, IDOR, SSTI, authentication, business logic, and cloud misconfigurations**.

`CAPv2 — Certified Application Pentester (2025)` · `HackerOne / Bugcrowd / Private Programs` · `Open to Collaboration`

<br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-02-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-02.svg" width="100%" alt="Section 02" />
</picture>
</div>

<br />

<div align="center">
<a href="https://infosecwriteups.com/from-innocent-messages-to-total-takeover-how-i-hacked-a-professional-network-2033537d5d6a">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/02-ato-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/02-ato-wide.svg" width="100%" alt="Account takeover via professional network messages" />
</picture>
</a>
</div>

<br />

<div align="center">
<a href="https://infosecwriteups.com/sql-injection-in-password-reset-full-database-one-email-f091269b9fec">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/03-sqli-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/03-sqli-wide.svg" width="100%" alt="SQL injection in a password reset flow" />
</picture>
</a>
</div>

<br />

<div align="center">
<a href="https://infosecwriteups.com/how-i-found-2-bugs-on-bbcs-subdomains-and-made-it-into-their-hall-of-fame-86fc4be89e68">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/04-bbc-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/04-bbc-wide.svg" width="100%" alt="BBC SSTI and hyperlink injection case study" />
</picture>
</a>
</div>

<br />

<div align="center">
<a href="https://infosecwriteups.com/i-typed-000000-and-the-app-thought-mfa-was-already-on-8c21968e117a">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/05-mfa-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/05-mfa-wide.svg" width="100%" alt="MFA state confusion case study" />
</picture>
</a>
</div>

<div align="center"><sub>Click any case file to open the full public write-up. Research descriptions are summaries, not exploit instructions.</sub></div>

<br /><br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-03-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-03.svg" width="100%" alt="Section 03" />
</picture>
</div>

<br />

**A finding matters most when it reaches the people who can fix it.** My disclosure record includes government, technology, media, and academic programs.

**U.S. Department of Transportation** · Information disclosure · High  
[Official acknowledgement ↗](https://usdot.responsibledisclosure.com/hc/en-us/articles/18234850057363-Acknowledgements)

**Accenture** · Information disclosure · High  
[Official acknowledgement ↗](https://accenture.responsibledisclosure.com/hc/en-us/articles/360040573233-Acknowledgments)

**BBC News** · SSTI + hyperlink injection · Medium  
[Research write-up ↗](https://infosecwriteups.com/how-i-found-2-bugs-on-bbcs-subdomains-and-made-it-into-their-hall-of-fame-86fc4be89e68)

**Princeton University** · Reflected XSS · Medium  
[Disclosure post ↗](https://www.linkedin.com/posts/atharvrokade_bugbounty-responsibledisclosure-rxss-activity-7350144058394054656-jxTM)

**LG Electronics** · Business logic flaw · Medium  
[Recognition post ↗](https://www.linkedin.com/posts/atharvrokade_bugbounty-loa-cybersecurity-activity-7349685468516569088-eevN)

<details>
<summary><strong>＋ View six more acknowledged / fixed findings</strong></summary>

<br />

- **Brazilian Government** — S3 bucket misconfiguration · High · Acknowledged
- **Indian Government** — Security vulnerability · Medium · Acknowledged
- **ASUS** — Reflected XSS · Fixed
- **Samsung VPN Portal** — Reflected XSS · Low · Acknowledged
- **Nokia** — Rate limiting issue · Low · Acknowledged
- **SAP Community** — Business logic error · Low · Acknowledged

</details>

<br />

#### `// SELECTED BOUNTY PAYOUTS`

- **$1,000** — Information disclosure, crypto platform · [Payout post ↗](https://www.linkedin.com/posts/atharvrokade_bugbounty-hardworkpaysoff-hacking-activity-7301445216408891393-2BmT/)
- **$100** — Stored XSS, redacted platform · [Payout post ↗](https://www.linkedin.com/posts/atharvrokade_bugbounty-cybersecurity-ethicalhacking-activity-7277708643796439040-afej/)
- **$50** — Misconfiguration, crypto platform · Private program

<sub>Public recognitions, private acknowledgements, and fixed findings are not necessarily equivalent to individual Hall of Fame listings. Selected payout amounts are historical disclosures, not live totals.</sub>

<br /><br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-04-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-04.svg" width="100%" alt="Section 04" />
</picture>
</div>

<br />

<div align="center">
<a href="https://github.com/Atharv834/S3BucketMisconf">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/06-project-s3-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/06-project-s3-wide.svg" width="100%" alt="Open source S3BucketMisconf cloud security research" />
</picture>
</a>
</div>

Discovers candidate S3 buckets and helps validate exposure. Python, AWS CLI, multithreading and result reports.

<br />

<div align="center">
<a href="https://github.com/Atharv834/EthicalHacking">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/07-project-ethical-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/07-project-ethical-wide.svg" width="100%" alt="Open source EthicalHacking security knowledge base" />
</picture>
</a>
</div>

Practical reference commands and notes for recon, web testing, enumeration, and related security workflows.

<br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/08-workflow-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/08-workflow.svg" width="100%" alt="Four-step security research workflow: discover, validate, assess, disclose" />
</picture>
</div>

<br /><br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-05-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-05.svg" width="100%" alt="Section 05" />
</picture>
</div>

<br />

<div align="center">
<a href="https://infosecwriteups.com/i-bought-a-1-599-government-book-for-1-the-server-approved-it-8a832499b1fb">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/10-note-price-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/10-note-price-wide.svg" width="100%" alt="Price validation research" />
</picture>
</a>
</div>

<br />

<div align="center">
<a href="https://infosecwriteups.com/i-typed-000000-as-the-otp-the-website-let-me-in-bc88383479d9">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/11-note-otp-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/11-note-otp-wide.svg" width="100%" alt="OTP verification research" />
</picture>
</a>
</div>

<br />

<div align="center">
<a href="https://lordofheaven1234.medium.com/the-sleeper-agent-bug-how-one-html-payload-lay-hidden-for-months-to-attack-my-inbox-9d3f1e9df60e">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/12-note-html-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/12-note-html-wide.svg" width="100%" alt="Stored HTML injection research" />
</picture>
</a>
</div>

<div align="center">

<a href="https://medium.com/@lordofheaven1234"><strong>↗ Browse all security research & field notes</strong></a>

</div>

<details>
<summary><strong>＋ Open the 2025 research archive</strong></summary>

<br />

- [I Didn't Plan to Find a P1… But My Script Had Other Plans](https://lordofheaven1234.medium.com/%EF%B8%8F-%EF%B8%8F-i-didnt-plan-to-find-a-p1-but-my-script-had-other-plans-77691a46985b)
- [Data Breach Dilemma: 1000+ Leaked IDs and a Failed Disclosure Attempt](https://lordofheaven1234.medium.com/data-breach-dilemma-i-found-1000-leaked-ids-but-a-robot-wouldnt-let-me-warn-a-top-university-50d876970813)
- [From Broken VMs to One-Click Recon: How I Fixed My Setup](https://lordofheaven1234.medium.com/%EF%B8%8F-from-broken-virtual-machines-to-one-click-recon-how-i-finally-fixed-my-setup-3f51076ccbe2)
- [I Almost Bought a $239 Domain for $1](https://lordofheaven1234.medium.com/i-almost-bought-a-239-domain-for-1-a-ghost-level-bug-no-ones-watching-2ffe740279cd)

</details>

<br /><br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-06-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-06.svg" width="100%" alt="Section 06" />
</picture>
</div>

<br />

**`01 / OFFENSIVE TESTING`**  
`Burp Suite Pro` · `Nuclei` · `Metasploit` · `SQLMap` · `OWASP ZAP`

**`02 / RECON & NETWORK`**  
`Nmap` · `Shodan` · `Subfinder` · `theHarvester` · `Wireshark` · `Nessus`

**`03 / BUILD & CLOUD`**  
`Python` · `Bash` · `JavaScript` · `Docker` · `AWS` · `Kali Linux`

<div align="center">

<img src="https://skillicons.dev/icons?i=python,bash,js&theme=dark" alt="Python, Bash, JavaScript" />

<br />
<img src="https://skillicons.dev/icons?i=docker,aws,linux&theme=dark" alt="Docker, AWS, Linux" />

<br /><br />

<a href="https://github.com/atharv834"><img src="https://img.shields.io/github/followers/atharv834?label=FOLLOWERS&color=CAFF5B&labelColor=111A20&style=flat-square" alt="GitHub followers" /></a>
<img src="https://komarev.com/ghpvc/?username=atharv834&label=PROFILE+VIEWS&color=6EE7EF&style=flat-square" alt="Profile views" />

</div>

<details>
<summary><strong>＋ View GitHub activity</strong></summary>

<br />

<div align="center">
<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=atharv834&bg_color=090F16&color=CAFF5B&line=6EE7EF&point=CAFF5B&area=true&area_color=162B2F&hide_border=true&custom_title=GITHUB%20CONTRIBUTIONS" alt="GitHub contribution history" />
</div>

</details>

<br /><br />

<div align="center">
<picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-07-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/section-07.svg" width="100%" alt="Section 07" />
</picture>

<br />

<a href="mailto:atharv04@duck.com"><picture>
  <source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/09-footer-mobile.svg" />
  <img src="https://raw.githubusercontent.com/atharv834/atharv834/main/assets/09-footer.svg" width="100%" alt="Open for collaboration, contact atharv04@duck.com" />
</picture></a>

<br />

<a href="mailto:atharv04@duck.com"><strong>EMAIL</strong></a> &nbsp; / &nbsp;
<a href="https://www.linkedin.com/in/atharvrokade"><strong>LINKEDIN</strong></a> &nbsp; / &nbsp;
<a href="https://medium.com/@lordofheaven1234"><strong>MEDIUM</strong></a> &nbsp; / &nbsp;
<a href="https://github.com/atharv834"><strong>GITHUB</strong></a>

<br /><br />

<sub>Designed as a security field report · © Atharv Rokade · Responsible disclosure only.</sub>

</div>
