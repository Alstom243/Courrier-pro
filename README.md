# Courrier-pro
# 🏛️ Courrier Pro v1.2 - Ministère des Sports et Loisirs RDC

![PHP](https://img.shields.io/badge/PHP-8.0%2B-blue)
![MySQL](https://img.shields.io/badge/MySQL-5.7%2B-orange)
![Status](https://img.shields.io/badge/Status-Production-green)
![RDC](https://img.shields.io/badge/Made%20in-RDC-blue)

Système complet de gestion des courriers administratifs - 7 étapes + Audit IGF + Accusé Réception avec QR

### 🎯 Workflow 7 Étapes

1. **📥 Charge d'études** - Réception & enregistrement (Audit T1)
2. **👔 DIRCAB - Triage** - Affectation (Audit T2) 
3. **📝 Traitement** - Rédaction réponse
4. **✅ DIRCAB - Validation Définitive** - Verrouille + Filigrane VERT + QR + Notif WhatsApp SECAB
5. **📤 SECAB** - Envoi file impression (Audit T3)
6. **🖨️ Opérateurs x5** - File commune FIFO + Lock temps réel + Anti-conflit
7. **📦 Archives Centrales** - Archivage + Génération AR + QR Officiel (Audit T4 & T5)

### 🚀 Fonctionnalités v1.2 Finale

- ✅ Double validation DIRCAB (Triage + Définitive)
- ✅ Filigrane VERT validé + QR code
- ✅ File d'impression commune 5 opérateurs avec temps d'attente
- ✅ Accusé de réception PDF joint avec 5 temps humains
- ✅ Audit 5 temps complet exportable Excel pour IGF
- ✅ Dashboard Ministre lecture seule + détection retards >7j
- ✅ Sans framework - PHP pur pour maintenance facile

### 💻 Installation (2 min)

```bash
1. git clone https://github.com/Alstom243/Courrier-pro.git
2. Importer database.sql dans phpMyAdmin
3. Configurer config/db.php (user/pass)
4. http://localhost/Courrier-pro/