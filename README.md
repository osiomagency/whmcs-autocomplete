## 🌟 Présentation

Le module **WHMCS Auto-Fill** ajoute une recherche automatique d’entreprises dans le **formulaire d’inscription WHMCS**, afin de simplifier la création de compte pour les clients professionnels.

Lorsqu’un utilisateur commence à taper le nom de sa société, une liste d’entreprises correspondantes s’affiche instantanément.
En un clic, les champs **Nom de société** et **Numéro de TVA** sont automatiquement remplis.

Ce module offre une expérience d’inscription moderne, rapide et fluide — parfaitement intégrée à l’interface native de WHMCS.

![image](https://i.imgur.com/97c4B36.jpeg)

---

## 🚀 Fonctionnalités actuelles

✅ Recherche automatique d’entreprise depuis une base de données publique française
✅ Remplissage automatique des champs :
* Nom de la société
* Numéro de TVA
✅ Conteneur de résultats généré automatiquement (aucune modification HTML nécessaire)
✅ Design moderne compatible **Bootstrap 5** et **Lagom**
✅ Aucun paramétrage requis — le module fonctionne dès l’installation
✅ Fonctionne uniquement sur la page d’inscription (register)

---

## 🧩 Fonctionnalités prévues

🔹 Autocomplétion des **adresses** (rue, code postal, ville)
🔹 Indicateur de chargement pendant la recherche
🔹 Options de personnalisation dans l’administration (nombre de résultats, apparence, etc.)
🔹 Intégration possible sur d’autres formulaires WHMCS (édition, etc.)

---

## ⚙️ Installation

### 📦 Étape unique :

Déposez simplement le fichier du module dans le dossier suivant :

```
/includes/hooks/
```

Exemple :

```
/includes/hooks/registerAutocomplete.php
```

Et... c’est tout ✅
Le module s’activera automatiquement sur la page d’inscription WHMCS.

Aucune configuration, aucun template à modifier.

---

## 🧠 Fonctionnement

Lorsqu’un utilisateur saisit le nom d’une société :

1. Le module recherche automatiquement les entreprises correspondantes
2. L’utilisateur sélectionne une entreprise
3. Les champs **nom de société** et **numéro de TVA** se remplissent automatiquement

---

## 💻 Compatibilité

| Élément                  | Compatibilité                    |
| ------------------------ | -------------------------------- |
| **WHMCS**                | 8.x à 9.x                        |
| **PHP**                  | 8.x                              |
| **Thèmes**               | Lagom, Twenty-One, Bootstrap 4/5 |
| **Dépendances externes** | Aucune                           |
| **Clé API requise**      | ❌ Non                            |

---

## 🔒 Conformité et sécurité

Toutes les données proviennent de sources publiques légales et sont traitées côté client.
Aucune donnée personnelle n’est collectée ni transmise à des tiers.

---

## 🧾 Licence

Ce module est distribué sous **licence libre d’utilisation** pour tous projets WHMCS.
Crédit : **OSIOM AGENCY — Agence digitale**
🌐 [https://osiom.fr](https://osiom.fr)

---

## 💬 Support

Besoin d’aide ou d’une intégration personnalisée ?
Contacte le support OSIOM :
📧 **[hello@osiom.fr](mailto:hello@osiom.fr)**
🌍 **[osiom.fr](https://osiom.fr)**
