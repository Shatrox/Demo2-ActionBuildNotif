Demo 02 - CICD
Pour lancer le projet démo
```yaml
# Installation des Node_Modules
npm i

# Tester le code
npm run test

# Build le projet TS → JS
npm run build

# Lancer le projet buildé
npm run start

```

## Mise en place d'une action CI/CD (GitHub)
- Créer le repertoire .github/workflows
- Dans ce repertoire créer un fichier <Action-name>.yaml
- Dans le fichier, definir: 
    - Le nom du workflows
    - Les déclancheurs
    - Les jobs