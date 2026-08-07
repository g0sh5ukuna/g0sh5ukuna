<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3000&pause=1000&color=0969DA&center=true&vCenter=true&width=620&lines=Consultant+DevSecOps+freelance;Audit+%C2%B7+Hardening+%C2%B7+CI%2FCD+s%C3%A9curis%C3%A9;Conformit%C3%A9+RGPD+%26+APDP+B%C3%A9nin;CTF+handle+%3A+kur0r0" alt="Josué SOUNON" />

**Josué SOUNON** · *Conceptor*
Abomey-Calavi / Cotonou, Bénin

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/joshsounon07)
[![Email](https://img.shields.io/badge/Me_contacter-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanueldegbey3@gmail.com)

</div>

---

Consultant DevSecOps freelance. J'interviens sur des applications déjà construites pour
les auditer, les durcir et automatiser leur sécurité — et je livre aussi des projets
complets de bout en bout, seul : architecture, code, pipeline, déploiement, exploitation.

Fondateur de **Gonruwa Technologie**.

<br>

<details>
<summary><b>🔐 &nbsp;Sur quoi j'interviens</b></summary>

<br>

**Audit applicatif**
Revue de code orientée exploitation, référentiels OWASP Top 10:2025 et ASVS 5.0.
Django/DRF, FastAPI, Next.js, Flutter, Solidity. Rapport priorisé par exploitabilité réelle.

**Shift-left CI/CD**
Intégration de la sécurité dans le pipeline plutôt qu'en fin de chaîne :
SAST (Semgrep, Bandit) · SCA (Trivy, OSV-Scanner) · scan de secrets (Gitleaks, TruffleHog) ·
IaC (Checkov) · gating de merge sur seuils de sévérité.

**Hardening infrastructure**
Ubuntu LTS · UFW + Fail2Ban · SSH sur port non-standard, clés uniquement ·
Nginx avec CSP, HSTS, rate limiting · Certbot · conteneurs non-root, multi-stage,
surface d'attaque réduite.

**Triage de vulnérabilités**
Priorisation par exploitabilité dans *ton* contexte, pas par score CVSS brut.
Une CVE critique dans une dépendance jamais atteinte par un chemin d'exécution
passe après une injection moyenne sur un endpoint public.

**Remédiation**
Je ne livre pas qu'un rapport. Je corrige, je prouve la correction par un test,
et je laisse le garde-fou en CI pour que la faille ne revienne pas.

</details>

<details>
<summary><b>🧭 &nbsp;Comment je travaille</b></summary>

<br>

**Diagnostic avant correction. Toujours.**
Un symptôme n'est pas une cause. Je remonte à la cause racine avant d'écrire une ligne,
sinon on corrige le même bug trois fois sous trois formes différentes.

**Pas de macroplanning.**
Le problème est décomposé en actions courtes, chacune avec un critère de validation binaire.
On avance quand c'est prouvé — compilation, test, log — pas quand ça a l'air de marcher.

**Honnêteté sur le risque.**
Si une décision d'architecture a un angle mort, je le dis avant, pas au post-mortem.
Si un délai est intenable, je le dis à la signature, pas à la livraison.

**Distinction explicite** entre fait vérifié, estimation raisonnée et opinion.
Une version, un article de loi, un CVE : sourcé ou pas affirmé.

</details>

<details>
<summary><b>⚙️ &nbsp;Stack technique</b></summary>

<br>

**Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Frontend**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Infra & sécurité**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Mobile & blockchain**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

</details>

<details>
<summary><b>🌍 &nbsp;Le contexte ouest-africain, concrètement</b></summary>

<br>

**Paiement.** Un service vendu au Bénin ne peut pas encaisser avec Stripe.
La couverture UEMOA passe par FedaPay ou Kkiapay, et le moyen dominant est le
Mobile Money, pas la carte bancaire. Ça change le parcours de paiement, la gestion
des échecs, la réconciliation — pas juste le nom du prestataire.

**Données personnelles.** Un traitement au Bénin relève de la **loi n° 2017-20
(Code du Numérique)** et de l'**APDP**, pas seulement du RGPD. Deux régimes distincts
à satisfaire en même temps dès qu'on sert des clients des deux côtés.

**Réseau.** Concevoir pour une connexion instable et un forfait data compté :
budget de performance, dégradation gracieuse, pas de bundle de 3 Mo.

C'est la partie que les prestataires hors zone traitent mal, ou pas du tout.

</details>

<br>

## 📊 &nbsp;Activité

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=g0sh5ukuna&show_icons=true&hide_border=true&bg_color=00000000&title_color=0969da&text_color=768390&icon_color=0969da" alt="stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=g0sh5ukuna&layout=compact&hide_border=true&langs_count=8&bg_color=00000000&title_color=0969da&text_color=768390" alt="langages" />

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/g0sh5ukuna/g0sh5ukuna/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/g0sh5ukuna/g0sh5ukuna/output/snake.svg" />
  <img alt="graphe de contributions animé" src="https://raw.githubusercontent.com/g0sh5ukuna/g0sh5ukuna/output/snake.svg" />
</picture>

</div>

---

<div align="center">

**Disponible pour missions DevSecOps, audits de sécurité et développement full-stack.**

<sub>Une question, une mission, un audit ?
<a href="https://github.com/g0sh5ukuna/g0sh5ukuna/issues/new?title=Prise+de+contact&body=Bonjour+Josu%C3%A9,">Ouvre un ticket</a> ou écris-moi directement.</sub>

</div>
