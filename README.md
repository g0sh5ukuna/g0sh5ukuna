<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
  <img src="assets/banner-light.svg" width="100%" alt="Josué SOUNON, consultant DevSecOps freelance : audit, CI/CD sécurisé, hardening, conformité APDP et RGPD. Fondateur de Gonruwa Technologie, Abomey-Calavi / Cotonou, Bénin." />
</picture>

<br><br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/joshsounon07)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanueldegbey3@gmail.com?subject=Mission%20DevSecOps)
![CTF](https://img.shields.io/badge/CTF-kur0r0-24292F?style=for-the-badge)

</div>

<br>

J'audite, je durcis et j'automatise la sécurité d'applications déjà construites.
Je livre aussi des projets complets de bout en bout, seul : architecture, code,
pipeline, déploiement, exploitation.

> [!IMPORTANT]
> **Je ne livre pas qu'un rapport.** Chaque faille corrigée est prouvée par un test,
> et un contrôle en CI empêche qu'elle revienne.

<br>

## Offres

<table>
<tr>
<td width="50%" valign="top">

#### 🔍 &nbsp;Audit applicatif

Revue de code orientée exploitation, selon l'**OWASP Top 10:2025** et l'**ASVS 5.0**.
Django/DRF, FastAPI, Next.js, Flutter, Solidity.

**→ Rapport priorisé par exploitabilité réelle.**

</td>
<td width="50%" valign="top">

#### ⚙️ &nbsp;CI/CD sécurisé

SAST, SCA, scan de secrets et analyse IaC intégrés au pipeline,
plutôt qu'un contrôle en fin de chaîne.

**→ Merge bloqué au-delà d'un seuil de sévérité.**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🛡️ &nbsp;Hardening infrastructure

Ubuntu LTS, UFW + Fail2Ban, SSH par clés uniquement, Nginx avec CSP, HSTS
et rate limiting, Certbot, conteneurs non-root et multi-stage.

**→ Surface d'attaque réduite.**

</td>
<td width="50%" valign="top">

#### 🎯 &nbsp;Triage de vulnérabilités

Une CVE critique jamais atteinte par un chemin d'exécution passe après
une injection moyenne sur un endpoint public.

**→ Priorités fixées par l'exploitabilité, pas par le score CVSS brut.**

</td>
</tr>
</table>

<br>

## Méthode

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

## Le contexte ouest-africain, concrètement

C'est la partie que les prestataires hors zone traitent mal, ou pas du tout.

| Sujet | Ce que ça change |
|:--|:--|
| **Paiement** | Stripe n'ouvre pas de compte marchand aux entreprises établies au Bénin. On passe par des agrégateurs locaux comme FedaPay ou Kkiapay, et le moyen dominant est le Mobile Money, pas la carte. Le parcours de paiement, la gestion des échecs et la réconciliation changent, pas seulement le nom du prestataire. |
| **Données personnelles** | Un traitement au Bénin relève de la **loi n° 2017-20 portant Code du numérique** et de l'**APDP**. Dès que vous servez aussi des personnes dans l'Union européenne, le RGPD s'ajoute : deux régimes à satisfaire en même temps. |
| **Réseau** | Connexion instable, forfait data compté : budget de performance, dégradation gracieuse, pas de bundle de 3 Mo. |

<br>

## Stack

| Domaine | Outils |
|:--|:--|
| **Backend** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/DRF-A30000?style=flat-square&logo=django&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Frontend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Infra** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) |
| **Sécurité** | `Semgrep` `Bandit` `Trivy` `OSV-Scanner` `Gitleaks` `TruffleHog` `Checkov` |
| **Mobile & blockchain** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white) |

<br>

## Activité

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

### Un audit, une mission, une question ?

Décrivez votre application, votre stack et votre contexte.

[![Écrire un e-mail](https://img.shields.io/badge/%C3%89crire_un_e--mail-0969DA?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanueldegbey3@gmail.com?subject=Mission%20DevSecOps)
[![Ouvrir un ticket](https://img.shields.io/badge/Ouvrir_un_ticket-24292F?style=for-the-badge&logo=github&logoColor=white)](https://github.com/g0sh5ukuna/g0sh5ukuna/issues/new?title=Prise+de+contact&body=Bonjour+Josu%C3%A9,)

</div>
