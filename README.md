<div align="center">

# Josué SOUNON

**Consultant DevSecOps freelance** · Fondateur de **Gonruwa Technologie**<br>
Abomey-Calavi / Cotonou, Bénin

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=1000&color=0969DA&center=true&vCenter=true&width=620&lines=Audit+applicatif+%C2%B7+OWASP+%26+ASVS;S%C3%A9curit%C3%A9+int%C3%A9gr%C3%A9e+au+CI%2FCD;Hardening+Linux+%C2%B7+Nginx+%C2%B7+Docker;Conformit%C3%A9+Loi+2017-20+%C2%B7+APDP+%C2%B7+RGPD;CTF+%3A+kur0r0" alt="Audit applicatif · CI/CD sécurisé · Hardening · Conformité APDP et RGPD · CTF : kur0r0" />

[![Disponible](https://img.shields.io/badge/Disponible-missions_freelance-2EA043?style=for-the-badge)](mailto:emmanueldegbey3@gmail.com?subject=Mission%20DevSecOps)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/joshsounon07)
[![Email](https://img.shields.io/badge/Me_contacter-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanueldegbey3@gmail.com)

</div>

---

J'interviens sur des applications déjà construites pour les **auditer**, les **durcir** et
**automatiser leur sécurité**. Je livre aussi des projets complets de bout en bout, seul :
architecture, code, pipeline, déploiement, exploitation.

> **Je ne livre pas qu'un rapport.** Chaque faille corrigée est prouvée par un test,
> et un contrôle en CI empêche qu'elle revienne.

<br>

## 🔐 &nbsp;Services

| Mission | Ce que vous obtenez |
|:--|:--|
| **Audit applicatif** | Revue de code orientée exploitation, selon l'OWASP Top 10:2025 et l'ASVS 5.0. Django/DRF, FastAPI, Next.js, Flutter, Solidity. Rapport priorisé par exploitabilité réelle. |
| **CI/CD sécurisé** | La sécurité intégrée au pipeline plutôt qu'en fin de chaîne : SAST, SCA, scan de secrets, analyse IaC, et blocage du merge au-delà d'un seuil de sévérité. |
| **Hardening infrastructure** | Ubuntu LTS, UFW + Fail2Ban, SSH par clés uniquement sur port non standard, Nginx avec CSP, HSTS et rate limiting, Certbot, conteneurs non-root et multi-stage. |
| **Triage de vulnérabilités** | Priorisation selon l'exploitabilité dans *votre* contexte, pas selon le score CVSS brut. Une CVE critique jamais atteinte par un chemin d'exécution passe après une injection moyenne sur un endpoint public. |
| **Remédiation** | Correction, test qui prouve la correction, garde-fou en CI contre la régression. |
| **Projet de bout en bout** | Architecture, développement, pipeline, déploiement et exploitation, avec la sécurité intégrée dès la conception. |

<br>

## 🧭 &nbsp;Méthode

| 1 · Diagnostic | 2 · Rapport | 3 · Correction | 4 · Garde-fou |
|:--|:--|:--|:--|
| Cause racine identifiée avant toute modification. | Failles classées par exploitabilité réelle. | Corrigée, puis prouvée par un test. | Contrôle ajouté en CI pour bloquer la régression. |

<details>
<summary><b>Principes de travail</b></summary>

<br>

**Diagnostic avant correction. Toujours.**
Un symptôme n'est pas une cause. Je remonte à la cause racine avant d'écrire une ligne,
sinon on corrige le même bug trois fois sous trois formes différentes.

**Pas de macroplanning.**
Le problème est découpé en actions courtes, chacune avec un critère de validation binaire.
On avance quand c'est prouvé (compilation, test, log), pas quand ça a l'air de marcher.

**Honnêteté sur le risque.**
Si une décision d'architecture a un angle mort, je le dis avant, pas au post-mortem.
Si un délai est intenable, je le dis à la signature, pas à la livraison.

**Fait, estimation, opinion : toujours distingués.**
Une version, un article de loi, une CVE : sourcé, ou pas affirmé.

</details>

<br>

## 🌍 &nbsp;Le contexte ouest-africain, concrètement

| Sujet | Ce que ça change |
|:--|:--|
| **Paiement** | Stripe n'ouvre pas de compte marchand aux entreprises établies au Bénin. On passe par des agrégateurs locaux comme FedaPay ou Kkiapay, et le moyen dominant est le Mobile Money, pas la carte bancaire. Le parcours de paiement, la gestion des échecs et la réconciliation changent, pas seulement le nom du prestataire. |
| **Données personnelles** | Un traitement au Bénin relève de la **loi n° 2017-20 portant Code du numérique** et de l'**APDP**. Dès que vous servez aussi des personnes dans l'Union européenne, le RGPD s'ajoute : deux régimes à satisfaire en même temps. |
| **Réseau** | Connexion instable et forfait data compté : budget de performance, dégradation gracieuse, pas de bundle de 3 Mo. |

C'est la partie que les prestataires hors zone traitent mal, ou pas du tout.

<br>

## ⚙️ &nbsp;Stack technique

| Domaine | Technologies |
|:--|:--|
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Infra** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Sécurité** | `Semgrep` `Bandit` `Trivy` `OSV-Scanner` `Gitleaks` `TruffleHog` `Checkov` |
| **Mobile & blockchain** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white) |

<br>

## 📊 &nbsp;Activité

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=g0sh5ukuna&show_icons=true&hide_border=true&bg_color=00000000&title_color=0969da&text_color=768390&icon_color=0969da" alt="Statistiques GitHub" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=g0sh5ukuna&layout=compact&hide_border=true&langs_count=8&bg_color=00000000&title_color=0969da&text_color=768390" alt="Langages les plus utilisés" />

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=g0sh5ukuna&hide_border=true&bg_color=00000000&color=768390&line=0969da&point=0969da&area=true&area_color=0969da" />
  <img width="95%" alt="Graphe d'activité GitHub" src="https://github-readme-activity-graph.vercel.app/graph?username=g0sh5ukuna&hide_border=true&bg_color=00000000&color=57606a&line=0969da&point=0969da&area=true&area_color=0969da" />
</picture>

</div>

---

<div align="center">

**Disponible pour missions DevSecOps, audits de sécurité et développement full-stack.**

Une question, une mission, un audit ?
<a href="https://github.com/g0sh5ukuna/g0sh5ukuna/issues/new?title=Prise+de+contact&body=Bonjour+Josu%C3%A9,">Ouvrez un ticket</a>
ou <a href="mailto:emmanueldegbey3@gmail.com?subject=Mission%20DevSecOps">écrivez-moi directement</a>.

</div>
