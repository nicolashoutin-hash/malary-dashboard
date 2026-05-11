# Malary — Agent Contrôleur IA

Tableau de bord d'orchestration IA pour l'entreprise **Malary** et sa suite de produits **Flow**.

---

## 🏢 Entreprise

**Malary** est une startup française spécialisée dans la surveillance intelligente des flux et de la sécurité. Elle développe la suite Flow, un ensemble d'applications B2B propulsées par l'IA.

---

## 📦 Suite Flow

| Produit | Statut | Description |
|---|---|---|
| **FlowAlert** | ✅ Lancé | Surveillance foule temps réel, style Waze |
| **FlowCity** | 🔜 À venir | — |
| **FlowSafe** | 🔜 À venir | — |
| **FlowHotel** | 🔜 À venir | — |
| **FlowSite** | 🔜 À venir | — |
| **FlowSchool** | 🔜 À venir | — |

---

## 🤖 Agents IA

Le dashboard orchestre **4 agents IA** propulsés par Claude Sonnet (Anthropic) :

### 🧠 Agent Contrôleur
Supervise et orchestre les trois agents spécialisés. Donne une vision stratégique globale sur Malary et la suite Flow.

### 🧮 Agent Comptabilité
- Suivi des finances de l'entreprise Malary
- Calcul MRR, ARR, point mort
- Surveillance CAC et LTV
- Alertes budget
- Projection financière suite Flow

### 📣 Agent Marketing
- Génération de contenu LinkedIn, Instagram, Facebook
- Planning éditorial mensuel
- Positionnement Malary et FlowAlert
- Ciblage B2B : sécurité privée, mairies, événementiel

### 🎯 Agent Prospection
- Cold emails personnalisés par segment
- Séquences de relance automatisées
- Qualification et scoring leads
- Mise à jour CRM
- 3 segments : sécurité privée (149€/mois), mairies (199€/mois), événementiel (299€/mois)

---

## 💰 Contexte financier

| Poste | Montant |
|---|---|
| Investissement initial | ~822 € |
| Charges fixes mensuelles | ~39 €/mois |
| MRR actuel | 0 € |
| Objectif MRR (12 mois) | 10 000 € |
| Objectif clients | 50 clients payants |

---

## 🛠 Stack technique

- **Frontend** : HTML · CSS · JavaScript (vanilla)
- **IA** : API Anthropic — Claude Sonnet (`claude-sonnet-4-20250514`)
- **App** : FlutterFlow + Firebase
- **Déploiement dashboard** : GitHub Pages / Vercel

---

## 🚀 Installation

### 1. Cloner le repo
```bash
git clone https://github.com/tonpseudo/malary-dashboard.git
```

### 2. Ouvrir le fichier
Double-clique sur `index.html` dans ton navigateur **ou** utilise Live Server dans VS Code.

### 3. Configurer la clé API
1. Va sur [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys)
2. Crée une clé API (`sk-ant-...`)
3. Colle-la dans le champ en haut du dashboard
4. La clé est sauvegardée automatiquement dans ton navigateur

---

## ⚠️ Sécurité

- Ne commite **jamais** ta clé API dans le code
- Garde ce repository en **privé**
- La clé API est stockée uniquement dans le `localStorage` de ton navigateur
- Traite ta clé API comme un mot de passe

---

## 📋 Fonctionnalités

- [x] Agent Contrôleur — vision stratégique Malary
- [x] Agent Comptabilité — rapport financier, scénarios MRR
- [x] Agent Marketing — posts LinkedIn, Instagram, Facebook, planning éditorial
- [x] Agent Prospection — cold emails, séquences relance, 3 segments
- [x] Métriques temps réel (MRR, investissement, charges)
- [x] Console de commande libre
- [x] Clé API sauvegardée en local
- [ ] Agent Comptabilité connecté à Stripe
- [ ] Connexion CRM (HubSpot)
- [ ] Connexion Meta Business Suite
- [ ] Déploiement mobile

---

## 📄 Licence

Projet privé — © Malary. Tous droits réservés.
