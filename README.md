# 🚀 Programme de résolution de labyrinthe 

Bienvenue sur le dépôt de mon TP d'**initiation à l'IA** dans le cadre de ma troisième année en licence informatique à l'université d'*Avignon*.

---

## 🖥️ Présentation du programme

Ce programme permet de **résoudre un labyrinthe**, trouve un chemin pour se rendre d'une case départ à une case d'arrivée.

Grâce à la librairie `argparse`, le programme peut être exécuté avec des options :
- `-h` pour faire appel au "manuel" d'utilisation du programme.
- `[-d, -b, -a]` pour sélectionner l'un des trois parcours de résolution. Si aucune option n'est indiquée, le parcours en profondeur sera exécuté.

---

## 📊 Présentation des 3 parcours de résolution

- Le **parcours en profondeur** (`-d`) utilise une **pile LIFO**.
- Le **parcours en largeur** (`-b`) utilise une **file FIFO**.
- Le dernier parcours (`-a`) est une **amélioration du parcours en largeur** qui se base sur **la distance parcourue depuis la case départ** et sur **la distance de Manhattan**.

La dernière implémentation (`-a`) propose la *solution optimale* dans **4 des 5 exemples de labyrinthes**, le moins efficace est le *parcours en profondeur* même si paradoxalement, c'est celui qui propose la solution optimale pour le labyrinthe n°4, confirmant l'utilité d'avoir plusieurs modes pour résoudre le labyrinthe.

---

## ⚙️ Installation

1. Cloner le repository
2. Entrer toutes les commandes présentes dans le fichier `CONFIG.TXT`
3. Prendre connaissance du **manuel du programme** avec la commande `python3 maze.py -h`

-- 

## 🎥 Gifs 