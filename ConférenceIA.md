# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">L'Intelligence Artificielle</div>



---

Maitre Corbeau sur un arbre ?

---

Maitre Corbeau sur un arbre perché
http://andreetgyps.a.n.pic.centerblog.net/o/6b0e0247.jpg

---
# Tokenisation

Les tokens en traitement du langage naturel (NLP) sont comme les syllabes en poésie. Tout comme les syllabes sont les éléments constitutifs du rythme et de la structure d'un poème, les tokens sont les unités fondamentales qui permettent aux modèles d'IA de traiter et de comprendre le texte.

## "Maitre Corbeau sur un arbre perché" → décasyllabe
- **Syllabes dans un poème :** Maitre Corbeau sur un arbre perché.
- **Tokens en NLP :** [Mai ##tre Cor ##beau sur un ar### bre perché.].

---

# Token dans les Modèles d'IA

La limite de tokens définit le nombre maximum de tokens qu'un modèle peut traiter dans une seule entrée. Des limites de tokens plus élevées permettent de gérer des contextes plus longs, rendant les modèles plus efficaces pour des tâches comme la synthèse, l'analyse de code et la génération de documents.

| Modèle         | Taille Max (tokens) | Pages Livre de Poche Approx. |
|----------------|---------------------|------------------------------|
| GPT-5          | 128 000             | ~512                         |
| Llama 3.1      | 128 000             | ~512                         |
| Mistral Large  | 64 000              | ~256                         |

---

# Embedding

## Transformer les Tokens en Représentations Numériques

<div style="display: flex; align-items: center; gap: 20px;">

    <div style="flex: 1;">

L'embedding transforme les tokens en vecteurs, qui servent de véritables points d'entrée pour le LLM.

    </div>

    <div style="flex: 1;">

![Exemple d'Embedding](https://causewriter.ai/wp-content/uploads/2023/08/image-2.png)

    </div>
</div>

---

# Comment la Tokenisation et l'Embedding Fonctionnent Ensemble :
**Tokenisation :**
- Divise le texte en tokens (par exemple, mots, sous-mots ou caractères).
- Exemple : "Maitre Corbeau sur un arbre perché" → [Mai ##tre Cor ##beau sur un ar### bre perché.].

**Embedding :**
- Associe chaque token à un vecteur de haute dimension dans un espace continu.
- Exemple : [Mai ##tre Cor ##beau sur un ar### bre perché.]. → [[0.12, 0.45, ...], [0.34, 0.67, ...], [0.89, 0.23, ...]].

---

# Pourquoi l'Embedding est Important :
- **Compréhension Sémantique :** Les tokens ayant des significations similaires ont des embeddings plus proches dans l'espace vectoriel.


```mermaid
graph LR
  A["Input Phrase: 'Maitre Corbeau sur un arbre perché'"] --> B["Tokenization: [Mai ##tre Cor ##beau sur un ar### bre perché.]"]
  B --> C["Embedding: Dense Numerical Vectors"]

  C["Tokenization Output"]
  C --> D["Token: 'Mai'"]
  D --> D1["Vector: [0.12, 0.45, 0.78, ...]"]
  C --> E["Token: '##tre'"]
  E --> E1["Vector: [0.34, 0.67, 0.89, ...]"]
  C --> F["Token: 'Cor'"]
  F --> F1["Vector: [0.56, 0.23, 0.91, ...]"]
  C --> G["Token: '##beau'"]
  G --> G1["Vector: [0.78, 0.12, 0.34, ...]"]
  C --> H["Token: 'sur'"]
  H --> H1["Vector: [0.45, 0.89, 0.67, ...]"]
  ```

---



## 🤔 Qu’est-ce que l’IA ?
- Intelligence artificielle = capacité d’un programme à **simuler l’intelligence humaine**
- Exemple : reconnaître des images, jouer à des jeux, comprendre le langage

---

## 🌟 Pourquoi l’IA est importante aujourd’hui
- Smartphones, assistants vocaux, recommandations
- IA pour la santé, l’industrie, l’art et la science

---

## 1950 – Alan Turing
- Publie "Computing Machinery and Intelligence"
- Propose le **Test de Turing**
- Question : une machine peut-elle penser ?

---

## 1956 – Naissance officielle de l’IA
- Conférence de **Dartmouth**
- Objectif : créer des machines capables de penser
- Début de l’IA symbolique

La naissance du mot "Intelligence Artificielle"
**La Conférence de Dartmouth** s'est tenue en 1956 au Dartmouth College dans le New Hampshire, aux États-Unis. Elle a réuni des pionniers comme John McCarthy, Marvin Minsky, Claude Shannon et Allen Newell. C'est lors de cette rencontre historique que le terme "Intelligence Artificielle" a été inventé par John McCarthy. Les participants pensaient pouvoir créer une machine pensante en quelques mois
https://lh6.googleusercontent.com/2fOknOCOKRB53elLxNJQfA9CGVh1uud99HhsWp2eMJIvCge-mEPiJuKtQN0GIXOPaACYj-OBNccNrBHAzApkaMESTnylTGDqMVciQOM1C10dAXdg1kzKlDIM3jDpFWdz44PWxCJ8

---

## 1960 – Perceptrons
- **Frank Rosenblatt** invente le perceptron
- Neurone artificiel = base des réseaux de neurones
- Limité : ne résout pas les problèmes non linéaires comme le XOR

---

## 🔍 Le Problème XOR : Limite du Perceptron Simple

Le perceptron simple ne peut pas résoudre le problème **XOR (OU exclusif)**, qui nécessite une séparation non linéaire. Le XOR renvoie vrai uniquement si **une seule** des deux entrées est vraie, pas les deux en même temps.

**Pourquoi c'est important ?**
- Cette limitation a montré qu'un seul neurone ne suffit pas
- A conduit au **premier hiver de l'IA** (1974-1980) : baisse de financements et d'intérêt pour la recherche


---

## 1980 – Perceptrons multicouches
- Introduction des **couches multiples**
- Permet de résoudre des problèmes plus complexes
- Base des IA modernes

## 🧠 Réseaux multicouches : une vraie révolution
- Les couches multiples permettent d'apprendre des relations complexes que le perceptron simple ne pouvait pas résoudre

---


## 🏆 Les Parrains de l'IA

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

**Les Pères Fondateurs du Deep Learning**

Trois chercheurs ont révolutionné l'IA moderne et partagé le **Prix Turing 2018** (le "Nobel de l'informatique") :

**Geoffrey Hinton** 🇬🇧
- Réseaux de neurones profonds
- Rétropropagation moderne
- "Parrain du Deep Learning"

**Yann LeCun** 🇫🇷
- Réseaux convolutifs (CNN)
- Reconnaissance d'images

**Yoshua Bengio** 🇨🇦
- Traitement du langage naturel
- Représentations distribuées
- Éthique de l'IA

https://www.intelligenthq.com/wp-content/uploads/2023/09/godfathers-of-ai.jpg

    </div>

    <div style="flex: 1;">

**Leur Impact**

- Ont persisté quand personne ne croyait aux réseaux de neurones
- Leurs travaux ont permis : reconnaissance vocale, voitures autonomes, traduction automatique
- Forment aujourd'hui la nouvelle génération de chercheurs


    </div>
</div>


---

## 1980s – Geoffrey Hinton
- Travaux sur **l’apprentissage profond**
- Redécouvre et perfectionne les réseaux multicouches
- Précurseur du deep learning moderne

---

## 1980s – Yann LeCun
- Travaux sur les **CNN (Convolutional Neural Networks)**
- Applications : reconnaissance de chiffres manuscrits
- Début du succès du deep learning

---

## 1990s – Yoshua Bengio
- Travaux sur **les représentations distribuées**
- Réseaux neuronaux plus profonds
- Précurseur des réseaux très larges et profonds actuels

---

## 1997 – Deep Blue
- IA d’IBM bat Garry Kasparov aux échecs
- Exemple d’IA spécialisée
- Démonstration de puissance de calcul + stratégie
![Garry Kasparov vs Deep Blue](https://tse1.mm.bing.net/th/id/OIP.3liapdpAF6vYvBQnLSOGvQHaFA?cb=defcache2defcache=1&rs=1&pid=ImgDetMain&o=7&rm=3)
---

## 2006 – Renaissance du Deep Learning
- Hinton et Bengio relancent le deep learning
- Techniques modernes : **réseaux profonds et GPU**
- Préparation pour révolution visuelle et textuelle

---

## 2012 – AlexNet
- Réseau de neurones convolutif profond
- Gagne le concours **ImageNet**
- Révolutionne la vision par ordinateur

![Architecture AlexNet](https://i.ytimg.com/vi/ZUc0Mib5DeI/maxresdefault.jpg)

---

## 🏆 AlexNet : La Révolution de 2012

**Qu'est-ce qu'AlexNet ?**
- Réseau de neurones convolutif profond créé par Alex Krizhevsky, Ilya Sutskever et Geoffrey Hinton
- 8 couches (5 convolutives + 3 entièrement connectées)
- 60 millions de paramètres

**La Performance**
- Gagne le concours ImageNet 2012
- Taux d'erreur : 15,3% (vs 26,2% pour le second)
- Révolutionne la reconnaissance d'images

**Les Innovations Clés**
- Utilisation de **GPU** pour l'entraînement

![Architecture AlexNet](https://i.ytimg.com/vi/ZUc0Mib5DeI/maxresdefault.jpg)

---

**Pourquoi c'est important ?**
- Prouve que le deep learning fonctionne
- Lance l'ère moderne de l'IA
- Inspire tous les modèles actuels

    </div>
</div>

---

## 🎯 AlexNet : L'Équipe qui a Changé l'IA

**Les Créateurs**
- **Alex Krizhevsky** : Doctorant, développeur principal
- **Ilya Sutskever** : Co-auteur, futur cofondateur d'OpenAI
- **Geoffrey Hinton** : Superviseur, "Parrain du Deep Learning"

---

**Le Destin d'Ilya Sutskever**
- Après AlexNet, rejoint Google Brain
- 2015 : Cofonde **OpenAI** avec Sam Altman
- Rôle clé dans le développement de **GPT** et **ChatGPT**
- Chief Scientist chez OpenAI jusqu'en 2024

---

## 🔍 Impact d’AlexNet
- Montre que le deep learning fonctionne à grande échelle
- GPU rend l’entraînement possible
- Début de la domination du deep learning dans l’industrie

---

## 🎮 IA et Jeux vidéo
- IA apprend en jouant
- Exemple : OpenAI Five, AlphaGo
- Stratégie, anticipation, coordination

---

## 2016 – AlphaGo
- Développé par **Demis Hassabis, DeepMind**
- Bat le champion de Go
- Apprentissage par renforcement + réseaux profonds

---

## 🎯 Comment AlphaGo a Battu Lee Sedol

**Le Match Historique (Mars 2016)**
- AlphaGo affronte Lee Sedol, champion du monde de Go
- Victoire 4-1 : choc pour la communauté du Go
- Considéré comme impossible 10 ans auparavant

---

**Les Techniques d'AlphaGo**
- **Apprentissage supervisé** : étude de 30 millions de positions de parties de professionnels
- **Apprentissage par renforcement** : l'IA joue contre elle-même des millions de fois
- **Recherche arborescente Monte Carlo** : évalue les meilleurs coups possibles
- Combinaison de réseaux neuronaux profonds et d'algorithmes de recherche

---

**Le Coup 37 : Le Moment Légendaire**
- Deuxième partie : AlphaGo joue un coup jamais vu auparavant
- Les commentateurs le jugent d'abord "ridicule"
- Se révèle être un coup de génie qui change la partie
- Démontre que l'IA peut créer des stratégies innovantes

---

**Impact**
- Révolutionne la compréhension du jeu de Go
- Prouve que l'IA peut surpasser l'intuition humaine
- Lee Sedol déclare : "AlphaGo m'a montré que je ne savais rien"

---

## 🌌 SETI @ Home
- Projet pour détecter vie extraterrestre
- Utilise la puissance de calcul **des ordinateurs des bénévoles**
- Exemple de **distributed computing** et science collaborative

---

## 🎮 AlphaStar : Champion de StarCraft II

**Le Défi StarCraft II**
- Jeu de stratégie en temps réel extrêmement complexe
- Nécessite planification, gestion de ressources, micro-gestion
- Plus de 10^26 actions possibles (vs 10^170 pour le Go)

**Les Performances d'AlphaStar**
- Décembre 2018 : Bat des joueurs professionnels
- Atteint le niveau "Grandmaster" (top 0,2% des joueurs)
- Gère simultanément : économie, armée, stratégie

**Les Techniques Utilisées**
- **Apprentissage par imitation** : étudie des millions de parties humaines
- **Apprentissage par renforcement** : joue contre différentes versions de lui-même
- **Architecture neuronale** : réseaux transformers pour comprendre le contexte du jeu
- Traite environ 22 000 observations par seconde

**Innovation Clé**
- AlphaStar ne joue pas de manière surhumaine (APM limité à un niveau humain)
- Démontre une compréhension stratégique profonde
- Capable d'adapter sa stratégie en temps réel

**Impact**
- Prouve que l'IA peut maîtriser des environnements complexes et imprévisibles
- Applications : logistique, gestion de ressources, planification

---
<!-- .slide: data-layout="text-image" data-img="https://image1.slideserve.com/2915781/brain-size-in-mammals-l.jpg" data-alt="Taille du cerveau chez les mammifères" -->

## 🧠 Le cerveau humain
- Taille moyenne : 1600 cm³
- Néandertal : 1300 cm³
- Limité pour nouveaux neurones
- Synapses : pratiquement illimitées

https://image1.slideserve.com/2915781/brain-size-in-mammals-l.jpg
---

## 🧬 AlphaFold : De SETI@Home au Pliage de Protéines

**Le Lien avec SETI@Home**
- SETI@Home : calcul distribué pour chercher des signaux extraterrestres
- Même principe appliqué au pliage de protéines : **Folding@home**
- Des milliers d'ordinateurs volontaires calculent comment les protéines se replient

**AlphaFold : La Révolution**
- Développé par DeepMind (2020)
- Résout un problème vieux de 50 ans : prédire la structure 3D des protéines
- Une protéine = chaîne d'acides aminés qui se replie d'une façon précise

**Pourquoi c'est Important ?**
- La forme d'une protéine détermine sa fonction
- Comprendre le pliage = comprendre les maladies
- Applications : conception de médicaments, lutte contre les virus

**Les Performances**
- Prédit la structure de 200 millions de protéines
- Précision comparable aux méthodes expérimentales
- Réduit de plusieurs années à quelques heures le temps de recherche

**Impact sur la Science**
- Prix Nobel de Chimie 2024 décerné à Demis Hassabis (DeepMind)
- Accélère la recherche médicale mondiale
- Données ouvertes : accessibles à tous les chercheurs

![AlphaFold Protein Structure](https://cdn.the-scientist.com/assets/articleNo/68887/aImg/43733/alphafold-l.png)

---

## ⚡ Énergie : cerveau vs IA
| Système | Consommation |
|---------|--------------|
| Cerveau humain | ~20 W |
| GPU IA | ~250–400 W par unité |

---

## 🧠 Comparatif cerveau vs IA
- Cerveau : flexible, économe en énergie, généraliste
- IA : rapide, spécialisée, énergivore

---

## ⏳ Singularité technologique
- Moment hypothétique où IA surpassera l’intelligence humaine
- Débat : emploi, éthique, contrôle
- Sujet fascinant et controversé

---

## 🤖 L’AGI : qu’est-ce que c’est ?
- AGI = **Artificial General Intelligence**
- IA capable de comprendre, apprendre et agir **comme un humain**
- Contrairement à l’IA actuelle, qui est spécialisée

---

## 🧠 Différence IA spécialisée vs AGI
| IA spécialisée | AGI |
|----------------|-----|
| Fait une seule tâche | Peut apprendre toutes les tâches |
| Exemple : AlphaGo | Exemple : résoudre un problème, créer, planifier |
| Limité à un domaine | Flexible et généraliste |

---

## 🌌 Pourquoi l’AGI est fascinante
- Potentiel énorme : science, médecine, exploration spatiale
- Risques : contrôle, éthique, emploi
- Question clé : que se passe-t-il si elle devient **plus intelligente que nous** ?

---

## 🔮 Vers l’AGI
- Combinaison :
  - Réseaux profonds
  - Mémoire et planification
  - Compréhension du langage et raisonnement
- Objectif : IA **polyvalente et autonome**

---

## ⚖️ Éthique et AGI
- Sécurité : éviter comportements imprévisibles
- Transparence : comment prend-elle ses décisions ?
- Responsabilité : qui contrôle l’AGI ?

---

## 🖥️ Démonstration : Moshi de Kuytai
- Génération de texte et images
- Interaction avec le public
- Illustrer puissance et limites de l’IA

---

## 🧮 Types d’apprentissage
- Supervisé : données étiquetées
- Non supervisé : motifs détectés automatiquement
- Par renforcement : essais et erreurs + récompenses

---

## 🔍 Apprentissage supervisé
- Exemple : reconnaissance d’images (chat vs chien)
- IA apprend à partir d’exemples connus

---

## 🔍 Apprentissage non supervisé
- IA découvre des motifs sans étiquettes
- Exemple : clustering, segmentation

---

## 🔄 Apprentissage par renforcement
- IA agit dans un environnement, reçoit feedback
- Exemple : AlphaGo, OpenAI Five

---

## ⚙️ GPU et Deep Learning
- Calcul parallèle massif
- Permet l’entraînement rapide de réseaux profonds
- Différence clé avec CPU : vitesse et échelle

---

## 🌐 IA et vie quotidienne
- Smartphones, assistants vocaux
- Recommandations : Netflix, YouTube, Spotify
- Voitures autonomes

---

## 🏥 IA et santé
- Détection précoce de maladies
- Analyse d’images médicales
- Personnalisation des traitements

---

## 🎨 IA et créativité
- Génération d’images, textes, musique
- Limites : créativité encadrée, pas d’intuition


---

# Neurones Artificiels  
<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

Modèle mathématique du neurone artificiel  

Fonctions d'activation : ReLU, Sigmoid, Tanh  

Similarités et différences avec les neurones biologiques ?  

</div>

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

    ![Structure du Neurone Artificiel](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Artificial_neuron_structure.svg/1024px-Artificial_neuron_structure.svg.png)  
    *Illustration d'un neurone artificiel*
    </div>
</div>


---

# Réseaux de Neurones Artificiels

Les réseaux de neurones artificiels (RNA) sont des modèles computationnels inspirés de la structure et du fonctionnement des réseaux neuronaux biologiques. 

Ils sont composés de couches interconnectées de neurones artificiels, où chaque neurone traite les entrées, applique une fonction d'activation et transmet la sortie à la couche suivante. 

**Les RNA** sont largement utilisés pour des tâches telles que la reconnaissance de motifs, la classification et la régression dans divers domaines.

---

# Paramètres et Poids dans les Réseaux de Neurones

Dans les réseaux de neurones, les **paramètres** font référence aux valeurs ajustables que le modèle apprend pendant l'entraînement. Ceux-ci incluent :

**Poids :**

- Représentent la force de la connexion entre les neurones.
- Ajustés pendant l'entraînement pour minimiser l'erreur entre les sorties prédites et réelles.

**Biais :**
- Ajoutés à la somme pondérée des entrées pour décaler la fonction d'activation.
- Aident le modèle à mieux s'adapter aux données en permettant une flexibilité dans les frontières de décision.

---

# Paramètres et Poids dans les Réseaux de Neurones

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

**Pourquoi Ils Sont Importants :**

- **Les poids et les biais** sont les composants essentiels qui permettent aux réseaux de neurones d'apprendre des motifs et de faire des prédictions. En mettant à jour de manière itérative ces valeurs à l'aide d'algorithmes d'optimisation comme la descente de gradient, le réseau améliore ses performances sur la tâche donnée.
    </div>

    <div style="flex: 1;">
**Exemple :**

- Dans un réseau de neurones simple, si l'entrée est `X`, le poids est `W` et le biais est `B`, la sortie d'un neurone est calculée comme :
$$\text{sortie} = \text{fonction\_activation}(W \cdot X + B)$$

    </div>
</div>
---

# Mistral 7B : Nombre de Paramètres

<div style="display: flex; align-items: center; gap: 20px;">

    <div style="flex: 1;">

Le modèle Mistral 7B est un modèle de fondation de pointe avec **7 milliards de paramètres**.


**Comparaison :**
- **GPT-4 :** Environ 175 milliards de paramètres estimés.
- **LLaMA 2 (13B) :** 13 milliards de paramètres.

    </div>

    <div style="flex: 1;">

![Comparaison des Paramètres de Modèles](https://www.geeky-gadgets.com/wp-content/uploads/2023/09/New-Mistral-7B-instruct-model-from-Mistral-AI.webp)

    </div>
</div>
---

# Perceptron Multicouche (PMC)
<div style="display: flex; align-items: center; gap: 20px;">

    <div style="flex: 1;">

Un Perceptron Multicouche (PMC) est un type de réseau de neurones artificiels composé d'une couche d'entrée, d'une ou plusieurs couches cachées et d'une couche de sortie. Chaque couche consiste en des nœuds (neurones) interconnectés où les entrées sont traitées à travers des connexions pondérées, des fonctions d'activation et des biais. 

Les PMC sont largement utilisés pour des tâches d'apprentissage supervisé telles que la classification et la régression, tirant parti de leur capacité à modéliser des relations complexes et non linéaires dans les données.

Le concept du PMC a été introduit pour la première fois en 1969 par Marvin Minsky et Seymour Papert dans leur livre *Perceptrons*, qui a posé les bases de la recherche sur les réseaux de neurones.

    </div>

    <div style="flex: 1;">

![PMC](https://media.licdn.com/dms/image/D5612AQG2n-h9rBE2NA/article-cover_image-shrink_600_2000/0/1701597139460?e=2147483647&v=beta&t=kTHU5V1z66QpFeikBYqQ4Gwgu-o3V8DlwKWOub6Rr2M)

    </div>

</div>
---



---
# ML : Apprentissage par Renforcement​

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">
Agents apprenant par essais et erreurs​

Systèmes de récompense​
    </div>

    <div style="flex: 1;">

<iframe width="560" height="315" src="https://www.youtube.com/embed/spfpBrBjntg?si=68Z-oEMzvfxk8p6x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    </div>

</div>
---

# ML : Apprentissage par Renforcement​
<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

- Systèmes de conduite autonome apprenant des stratégies de conduite optimales par simulation.
- Systèmes de régulateur de vitesse adaptatif optimisant l'efficacité énergétique et la sécurité.
- Systèmes d'assistance au stationnement apprenant à naviguer dans des scénarios de stationnement complexes.

    </div>
    <div style="flex: 1;">  

<iframe width="560" height="315" src="https://www.youtube.com/embed/KPLYhRBCcvk?autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**Source :** [AlphaStar : Niveau grand maître dans StarCraft II utilisant l'apprentissage par renforcement multi-agents](https://deepmind.google/discover/blog/alphastar-grandmaster-level-in-starcraft-ii-using-multi-agent-reinforcement-learning/)

    </div>
</div>
---


## Réseau de Neurones en Action

<div style="display: flex; align-items: center; gap: 20px;">

    <div style="flex: 1;">

L'animation montre le processus de reconnaissance de chiffres manuscrits à l'aide d'un réseau de neurones. 

Elle visualise comment le modèle traite les images d'entrée, extrait les caractéristiques et prédit le chiffre correspondant.

    </div>

    <div style="flex: 1;">

![Réseau de Neurones en Action](https://i.makeagif.com/media/3-22-2022/boUeR6.gif)

    </div>
</div>

---

# Base de Données MNIST : Reconnaissance de Chiffres Manuscrits

<div style="display: flex; align-items: center; gap: 20px;">

    <div style="flex: 1;">

La base de données MNIST (Modified National Institute of Standards and Technology) est un benchmark largement utilisé en apprentissage automatique et en vision par ordinateur. Elle se compose de 70 000 images en niveaux de gris de chiffres manuscrits (0 à 9), chacune de taille 28x28 pixels. La base de données est utilisée pour entraîner et évaluer des modèles pour des tâches de reconnaissance de chiffres.

**Importance :**
- MNIST sert de point de départ pour tester et comparer les algorithmes d'apprentissage automatique.
- Elle aide à comprendre comment les réseaux de neurones peuvent classifier des nombres basés sur des motifs de pixels.

**Historique :**
- MNIST a été introduite en 1998 par **Yann LeCun, Corinna Cortes et Christopher J.C. Burges** dans le cadre de leurs recherches sur les réseaux de neurones et l'apprentissage automatique.

**Applications :**
- Reconnaissance de chiffres dans les systèmes postaux.
- Expériences fondamentales en apprentissage profond.

    </div>
    <div style="flex: 1;">


![Exemple de la Base MNIST](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

Exemple de reconnaissance de chiffres manuscrits de la base de données MNIST

    </div>
</div>



---

## **2. Les Bases de l'IA (20 min)**
**Objectif** : Rendre compréhensible le fonctionnement de l'IA
- **2.1** Comparaison neurone biologique/neurone artificiel (5 min)
  - Schéma simple : Corps cellulaire/dendrites vs entrées/poids
  - Analogie : "Comme une recette de cuisine très précise"
- **2.2** Historique accessible (5 min)
  - Alan Turing, Yann Le Cun, SETI@Home
  - Les jeux vidéo et l'IA (Black & White, Theme Park)
- **2.3** Limites et réalités (10 min)
  - Cerveau humain (1600 cm³) vs GPU (consommation énergétique)
## 🧪 Le Test de Turing : Peut-on Tromper un Humain ?

---
## Le test de Turing
**Principe :**
- Test proposé par Alan Turing en 1950
- Une machine peut-elle convaincre un humain qu'elle est elle-même humaine lors d'une conversation ?

**Comment ça marche :**
1. Un humain dialogue avec deux interlocuteurs cachés
2. L'un est une machine, l'autre un humain
3. Si l'humain ne peut pas distinguer qui est qui, la machine "réussit" le test

**Exemple concret :**
- Vous discutez par écrit avec deux personnes
- L'une parle de ses vacances, l'autre aussi
- Laquelle est l'IA ? Si vous ne pouvez pas le dire, l'IA a réussi !

**Limites du test :**
- Réussir ne signifie pas "penser" vraiment
- Une IA peut imiter sans comprendre
- Débat : intelligence simulée vs intelligence réelle

**Aujourd'hui :**
- En 2027 on ne pourra pas faire la disctinction entre un humain et une IA


---

## Applications Concrètes (25 min)**
  - Génération d'une image simple ("un chat dans un jardin")
  - Génération d'un poème avec le public
-  Exemples du quotidien (10 min)
  - Reconnaissance vocale, recommandations, traduction automatique
-  Détecter l'IA (5 min)
  - "Cette image a-t-elle été générée par une IA ?" (quiz visuel)

---

## **4. Questions Clés (20 min)**
**Objectif** : Répondre aux interrogations courantes
- **4.1** "L'IA est-elle plus intelligente que nous ?"
- **4.2** "Peut-on lui faire confiance ?" 
- **4.3** "Va-t-elle nous remplacer ?"