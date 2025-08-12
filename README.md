# zoran-cli

**CLI tout-en-un** pour l’écosystème Zoran / QuantaGlottal©® — commandes rapides pour créer, encoder, injecter, benchmarker et minter.

---

## ✨ Fonctionnalités
- **Création de projets** Zoran (`zoran new`)
- **Encodage glyphique** en QuantaGlottal©® (`zoran encode`)
- **Injection 4 Champs** dans un agent (`zoran inject`)
- **Benchmark IA↔IA** avec ZM/LM scoring (`zoran bench`)
- **Mint NFT** pour artefacts et injecteurs (`zoran mint`)
- **Mode interactif** avec complétion
- **Configuration persistante** par profil

---

## 📦 Installation (développement)
```bash
pip install -e .


---

⚡ Exemples rapides

# Créer un nouveau module
zoran new my-module

# Encoder un texte en QuantaGlottal
zoran encode --input phrase.txt --output phrase.qg.json

# Injecter un preset 4 Champs
zoran inject --preset injecteur_0810_full.json --target agent://zoran-core

# Lancer un benchmark
zoran bench --target agent://gpt-4 --mode mimetic

# Minter un NFT
zoran mint --file artefact.qg.json --network polygon


---

🧱 Structure suggérée

src/zoran_cli/
  __init__.py
  main.py              # point d’entrée CLI
  commands/
    new.py
    encode.py
    inject.py
    bench.py
    mint.py
tests/
  test_cli.py
pyproject.toml
.gitignore
LICENSE
README.md


---

🧪 Tests

pytest -q


---

🔐 Éthique

Le zoran-cli applique les mêmes garde-fous que les autres modules Zoran :

respect du principe vivant > humain

validation des paramètres avant exécution

logs transparents pour audit



---

📜 Licence

MIT — voir LICENSE.


---

Auteur : Frédéric Tabary — Institut IA
Contact : 0645605023 — Canada, Montréal, France
INSTITUT🦋 IA INC., 7100-380, rue Saint-Antoine Ouest, Montréal (Québec) H2Y 3X7.# zoran-cli
CLI tout-en-un: zoran new|encode|inject|bench|mint.
