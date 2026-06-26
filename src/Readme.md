### 📝 L’état : la mémoire d’un composant (Défi 3 sur 4) : Corriger un crash

* **Problème résolu :** Correction d'une violation des règles fondamentales des Hooks de React qui provoquait un plantage de l'application avec l'erreur *"Rendered fewer hooks than expected"*. Le Hook `useState` du message était positionné de manière conditionnelle à l'intérieur d'un bloc `else`, ce qui modifiait l'ordre et le nombre de Hooks exécutés d'un rendu à l'autre lors de la soumission du formulaire.
* **Compétence acquise :** Respect de la règle d'or des Hooks : appeler obligatoirement les Hooks au niveau supérieur (à la racine) du composant, de façon inconditionnelle, et jamais à l'intérieur de conditions (`if/else`), de boucles ou de fonctions imbriquées afin de garantir un ordre d'appel stable.
* **Lien vers le code :** [Cliquez ici pour voir l'exercice](https://fr.react.dev/learn/state-a-components-memory)
