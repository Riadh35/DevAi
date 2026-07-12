<!--
  README du DÉPÔT PUBLIC (diffusion binaires-only).
  À copier dans le nouveau dépôt public, avec les captures dans docs/screenshots/.
  Ne contient AUCUNE info personnelle. Remplacer Riadh35/DevAi et les
  liens de Release avant publication.
-->

<div align="center">

# 🤖 DevAI

### Un agent de développement IA qui tourne **100 % sur votre machine**

Chat avec des modèles locaux, agent outillé, bibliothèque de prompts, mémoire
durable — **sans jamais envoyer votre code dans le cloud.**

[![Télécharger](https://img.shields.io/badge/⬇_Télécharger-DevAI--Setup.exe-2ea44f?style=for-the-badge)](https://github.com/Riadh35/DevAi/releases/latest)
&nbsp;
![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows)
![100% local](https://img.shields.io/badge/100%25-local-8957e5?style=for-the-badge)

</div>

---

## Pourquoi DevAI ?

- 🔒 **Confidentialité totale.** Tout s'exécute en local via [Ollama](https://ollama.com).
  Votre code et vos conversations ne quittent jamais votre poste — idéal quand le
  cloud n'est pas une option (données sensibles, hors-ligne, souveraineté).
- 🧰 **Un vrai agent, pas juste un chat.** Il lit et écrit des fichiers, lance des
  commandes, cherche sur le web, analyse du code — avec **validation humaine** avant
  chaque action sensible.
- 📚 **Bibliothèque de prompts prête à l'emploi** — développement, code, web, UI/UX,
  debug, tests, docs, git. Un clic pour pré-remplir le chat ou copier.
- 🧠 **Mémoire durable.** L'agent retient les faits, conventions et pièges de vos
  projets d'une session à l'autre — après votre validation.
- 🛟 **Filets de sécurité.** Chaque fichier est sauvegardé avant modification
  (restauration en un clic) ; la mémoire est sauvegardée automatiquement.
- ⚡ **Léger.** Installateur autonome ~130 Mo, aucune installation de Python requise.

## Installation

1. **Installez [Ollama](https://ollama.com)** (le moteur de modèles local), puis
   récupérez un modèle :
   ```
   ollama pull llama3.1:latest
   ```
2. **Téléchargez DevAI** depuis la
   [dernière Release](https://github.com/Riadh35/DevAi/releases/latest) :
   - **`DevAI-Setup.exe`** — installateur classique, ou
   - **`DevAI-…-portable.zip`** — version portable : décompressez, puis lancez `DevAI.bat`.
3. **Lancez DevAI.** L'application s'ouvre dans votre navigateur sur
   `http://localhost:8000`.

> 💡 Aucune installation de Python n'est nécessaire : DevAI embarque son propre
> runtime. Seul **Ollama** est requis (gratuit).

## Configuration requise

- **Windows 10 / 11** (64 bits)
- **[Ollama](https://ollama.com)** installé et lancé
- ~130 Mo d'espace disque (hors modèles Ollama)
- Un modèle Ollama installé (ex. `llama3.1:latest`, `qwen2.5-coder:7b`)

## FAQ

**Mes données sortent-elles de ma machine ?**
Non. DevAI parle uniquement à Ollama en local. Aucune télémétrie, aucun cloud.

**Faut-il une carte graphique ?**
Non, mais un GPU accélère fortement les modèles. Ollama fonctionne aussi sur CPU.

**Puis-je utiliser mes propres modèles ?**
Oui — tout modèle disponible dans `ollama list` est sélectionnable dans l'app.

**Ça marche hors-ligne ?**
Oui, une fois Ollama et un modèle installés.

## Support

Un problème ? Ouvrez une [issue](https://github.com/Riadh35/DevAi/issues).
L'onglet **Diagnostic** de l'application donne l'état du backend, d'Ollama et des skills.

---

<sub>DevAI est distribué en tant qu'application gratuite. Voir `LICENSE` / `NOTICE`
pour les conditions d'utilisation et les composants tiers.</sub>
