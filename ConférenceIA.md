# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">L'Intelligence Artificielle</div>


---

## 🤔 Qu’est-ce que l’IA ?
- Intelligence artificielle = capacité d’un programme à **simuler l’intelligence humaine**
- Exemple : reconnaître des images, jouer à des jeux, comprendre le langage

---

## 🌟 Pourquoi l’IA est importante aujourd’hui
- Smartphones, assistants vocaux, recommandations
- IA pour la santé, l’industrie, l’art et la science


---
<!-- .slide: data-layout="two-column" data-img="https://synoptekmark.b-cdn.net/wp-content/uploads/2023/07/ai-ml-dl-and-generative-ai-face-off.webp" -->
# AI VS GENERATIVE AI​

<div style="display: flex; align-items: center; gap: 20px;">
  <div style="flex: 1;">

**ARTIFICIAL INTELLIGENCE** is a field of computer science that aims to create systems capable of imitating or simulating human intelligence.​

**MACHINE LEARNING** focuses on building systems that learn and improve from experience without being explicitly programmed.​

**DEEP LEARNING** uses neural networks with many layers to model complex patterns in data.​

**GENERATIVE AI** can create or generate new content, ideas, or data that resemble human creativity.​



---

# Neurones biologiques  
<!-- .slide: data-layout="two-column" data-img="https://www.researchgate.net/profile/Christos-Pliatsikas/publication/376253955/figure/fig1/AS:11431281218483806@1705590629078/Neuron-anatomy-Created-with-BioRendercom.png" -->

**Structure :**  
- Dendrites  
- Soma  
- Axone  

**Fonctionnement des synapses :**  
- Transmission de signaux chimiques et électriques  


---
<!-- .slide: data-layout="two-column" data-img="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Artificial_neuron_structure.svg/1024px-Artificial_neuron_structure.svg.png" -->
# Neurones artificiels
<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

Modèle mathématique du neurone artificiel  

Fonctions d’activation : ReLU, Sigmoïde, Tanh  

Similarités et différences avec les neurones biologiques ?  


---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Histoire de l’IA</div>

---

## 1950 – Alan Turing
- Publie "Computing Machinery and Intelligence"
- Propose le **Test de Turing**
- Question : une machine peut-elle penser ?

---
<!-- .slide: data-layout="two-column" data-img="https://image3.slideserve.com/6546540/turing-s-imitation-game-l.jpg" data-alt="Le Jeu de l'imitation de Turing" -->
### La proposition de Turing (Jeu de l’imitation)
- Expérience pensée où un interrogateur converse uniquement par écrit avec deux entités cachées: un humain et une machine.
- Objectif: décider qui est l’humain à partir des réponses en langage naturel.
- Règle de succès: si l’interrogateur ne distingue pas de façon fiable la machine de l’humain, la machine *réussit* le test.
- Motivation: remplacer “Les machines peuvent-elles penser ?” par une évaluation comportementale mesurable.
- Contraintes: échange textuel (sans vision ni audio), sujets libres, durée limitée.

https://image3.slideserve.com/6546540/turing-s-imitation-game-l.jpg

---
<!-- .slide: data-layout="two-column" data-img="https://lh6.googleusercontent.com/2fOknOCOKRB53elLxNJQfA9CGVh1uud99HhsWp2eMJIvCge-mEPiJuKtQN0GIXOPaACYj-OBNccNrBHAzApkaMESTnylTGDqMVciQOM1C10dAXdg1kzKlDIM3jDpFWdz44PWxCJ8" -->

## 1956 – Naissance officielle de l’IA
- Conférence de **Dartmouth**
- Objectif : créer des machines capables de penser
- Début de l’IA symbolique

La naissance du mot "Intelligence Artificielle"

---

**La Conférence de Dartmouth** s'est tenue en 1956 au Dartmouth College dans le New Hampshire, aux États-Unis. Elle a réuni des pionniers comme John McCarthy, Marvin Minsky, Claude Shannon et Allen Newell. C'est lors de cette rencontre historique que le terme "Intelligence Artificielle" a été inventé par John McCarthy. Les participants pensaient pouvoir créer une machine pensante en quelques mois

---

## 1960 – Perceptrons
- **Frank Rosenblatt** invente le perceptron
- Neurone artificiel = base des réseaux de neurones
- Limité : ne résout pas les problèmes non linéaires comme le XOR

---

### Le perceptron de Rosenblatt en bref
- Neurone binaire: somme pondérée des entrées + biais, puis seuil.
- Résout les problèmes linéairement séparables (AND, OR).
- Limite majeure: XOR non séparable → besoin de couches cachées.

> "Devices of this sort are expected ultimately to be capable of concept formation, language translation, collation of military intelligence, and the solution of problems through inductive logic."
 <em>— Frank Rosenblatt, 1957</em>
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

<!-- .slide: data-layout="text-video" data-video="https://youtu.be/FwFduRA_L6Q?si=seVi3mjawRWwdIj1" -->

## Démonstration de réseau convolutionnel de 1989 par Yann Le Cun

Il s’agit d’une démonstration de « LeNet-1 », le premier réseau convolutionnel capable de reconnaître des chiffres manuscrits avec une bonne vitesse et précision.

Elle a été développée début 1989 au département Adaptive System Research, dirigé par Larry Jackel, chez Bell Labs à Holmdel (New Jersey).

Cette démonstration « en temps réel » tournait sur une carte DSP installée dans un PC 486, avec une caméra vidéo et une carte d’acquisition. 
https://youtu.be/FwFduRA_L6Q?si=seVi3mjawRWwdIj1


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
<!-- .slide: data-layout="text-image" data-img="https://tse1.mm.bing.net/th/id/OIP.3liapdpAF6vYvBQnLSOGvQHaFA?cb=defcache2defcache=1&rs=1&pid=ImgDetMain&o=7&rm=3" data-alt="Garry Kasparov vs Deep Blue]" -->

## 1997 – Deep Blue
- IA d’IBM bat Garry Kasparov aux échecs
- Démonstration de force brute d’algorithmes

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
- Utilisation de **GPU Nvidia** pour l'entraînement

![Architecture AlexNet](https://i.ytimg.com/vi/ZUc0Mib5DeI/maxresdefault.jpg)

---

**Pourquoi c'est important ?**
- Prouve que le deep learning fonctionne
- Lance l'ère moderne de l'IA
- Inspire tous les modèles actuels

    </div>
</div>

---

<!-- .slide: data-layout="two-column" data-img="https://www.zdnet.com/a/img/resize/cbdfcc9ffe02c07ec17d656be49e670a55e467ec/2025/03/20/1fff3c66-1148-433b-859b-e53ca710522c/u-of-toronto-2013-hinton-krizhevsky-sutskever.jpg?auto=webp&width=1280" data-alt="Geoffrey Hinton, Alex Krizhevsky et Ilya Sutskever (Université de Toronto, 2013)" -->

## 🎯 AlexNet : L'Équipe qui a Changé l'IA

**Les Créateurs**
- **Alex Krizhevsky** : Doctorant, développeur principal
- **Ilya Sutskever** : Co-auteur, futur cofondateur d'OpenAI
- **Geoffrey Hinton** : Superviseur, "Parrain du Deep Learning"

---
<!-- .slide: data-layout="two-column" data-img="https://d92co48ro6fll.cloudfront.net/gradual/videos/scale/transformX/posters/what-s-next-for-ai-systems-language-models-with-ilya-sutskever-of-openai.jpg" data-alt="Ilya Sutskever" -->
## Le fabuleux destin d'Ilya Sutskever
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

---

**Les Performances d'AlphaStar**
- Décembre 2018 : Bat des joueurs professionnels
- Atteint le niveau "Grandmaster" (top 0,2% des joueurs)
- Gère simultanément : économie, armée, stratégie

---

**Les Techniques Utilisées**
- **Apprentissage par imitation** : étudie des millions de parties humaines
- **Apprentissage par renforcement** : joue contre différentes versions de lui-même
- **Architecture neuronale** : réseaux transformers pour comprendre le contexte du jeu
- Traite environ 22 000 observations par seconde

---
**Innovation Clé**
- AlphaStar ne joue pas de manière surhumaine (APM limité à un niveau humain)
- Démontre une compréhension stratégique profonde
- Capable d'adapter sa stratégie en temps réel

---
<!-- .slide: data-layout="two-column" data-video="https://youtu.be/UuhECwm31dM?si=5-9yNHVsPns0mCSq" -->
## L'IA dans StarCraft II bat le meilleur joueur humain

> La grande incertitude [liée au manque] d'informations en période de guerre est d'une difficulté particulière parce que toutes les actions doivent dans une certaine mesure être planifiées avec une légère zone d'ombre qui (…) comme l'effet d'un brouillard ou d'un clair de lune, donne aux choses des dimensions exagérées ou non naturelles.

— Carl von Clausewitz, "De la guerre"

---
<!-- .slide: data-layout="two-column" data-img="https://cdn.mos.cms.futurecdn.net/uMHimeHetVYcCSt8ExUM8.jpg" -->

## SETI : Recherche d’intelligences extraterrestres
- Objectif : détecter des technosignatures (émissions radio étroites, impulsions laser) d’origine non naturelle.
- Méthodes : radiotélescopes (Allen Telescope Array, Green Bank), observations optiques, analyse de spectres, filtrage des interférences terrestres.
- Problème : le volume de recherche immense et pas assez de capacité de calcul.


---
<!-- .slide: data-layout="two-column" data-video="https://youtu.be/EyWsnc7cB_w?si=BvUJi0RrmLqog1BR" -->

## 1999 SETI@Home
- Calcul distribué pour chercher des signaux extraterrestres
- Des milliers d'ordinateurs volontaires cherchent des signaux extraterrestres dans les données radio

---
## 🧬 Pliage moléculaire en médecine

## Pourquoi c’est important
- La forme d’une protéine dicte son rôle (ex. enzymes, anticorps, récepteurs).
- Un mauvais pliage peut provoquer des maladies (Alzheimer, Parkinson, mucoviscidose).
- Aide à concevoir des médicaments ciblés et à mieux diagnostiquer.

---

## Pourquoi c’est difficile
- Trop de formes possibles (nombre de combinaisons astronomique).
- Le pliage dépend de nombreux facteurs (eau, liaisons, ions, pH, température, etc.).
- Les modèles informatiques sont coûteux et doivent être vérifiés en laboratoire.

---

## Impact
- Meilleure compréhension de la fonction des protéines et moins d’effets indésirables.
- Conception plus précise de thérapies.
- Découvertes accélérées grâce au calcul avancé et à l’IA.


---
<!-- .slide: data-layout="two-column" data-img="https://upload.wikimedia.org/wikipedia/en/3/35/LifeWithPlayStation_Folding.jpg" -->

## 🧬 Folding@home : Pliage des Protéines Distribué
- Projet de calcul distribué lancé en 2000 par Stanford pour simuler le repliement des protéines.
- Des volontaires prêtent CPU/GPUleur ordinateurs pour exécuter des calculs.
- Objectifs: comprendre le repliement, les dysfonctionnements et interactions, accélérer la recherche sur Alzheimer, cancers, maladies infectieuses.

---

**AlphaFold : La Révolution**
- Développé par DeepMind (2020)
- Résout un problème vieux de 50 ans : prédire la structure 3D des protéines
- Une protéine = chaîne d'acides aminés qui se replie d'une façon précise

**Pourquoi c'est Important ?**
- La forme d'une protéine détermine sa fonction
- Comprendre le pliage = comprendre les maladies
- Applications : conception de médicaments, lutte contre les virus

---

https://youtu.be/gg7WjuFs8F4?si=k0zLPdsV-yJ4RBKs


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
<!-- .slide: data-layout="two-column" data-img="https://news.aikoreacommunity.com/content/images/2024/01/20240109_181100.png" -->
## 2017 – Attention is All You Need
- En bref: le Transformer est une architecture d’IA (2017) qui comprend le contexte des phrases grâce à un mécanisme appelé “attention”.
- Idée clé: l’attention permet au modèle de se concentrer sur les mots les plus utiles pour la tâche (traduire, résumer, répondre).
- Petite illustration: dans “Le chat de ma grand mère mange la souris”, le mot “mange” regarde “chat” et “souris” pour comprendre qui fait quoi.



---

## 🚀 OpenAI et l’impact de ChatGPT
- Lancement en nov. 2022, adoption record (>100 M utilisateurs/mois)
- Popularisation de l’IA générative et accélération de son adoption dans tous les secteurs

---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Comment la machine apprend</div>

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

# ML : Apprentissage supervisé

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

Utilisation de données étiquetées

Tâches de classification et de régression

    </div>

    <div style="flex: 1;">

![Apprentissage supervisé](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/07/Supervised-Learning-in-ML.jpg)

    </div>
</div>
---

# ML : Apprentissage supervisé

- Maintenance prédictive des composants du véhicule (ex. plaquettes de frein, pneus).
- Analyse du comportement des conducteurs et évaluation du risque.
- Reconnaissance et classification des panneaux de signalisation.
- Systèmes d’alerte de franchissement de ligne.

---

# ML : Apprentissage non supervisé

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">

Découverte de structures cachées

Techniques de clustering et de réduction de dimensionnalité
    </div>

    <div style="flex: 1;">

![Apprentissage non supervisé](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/07/Unsupervised-Learning-in-ML.jpg)

    </div>
    
</div>

---
# ML : Apprentissage non supervisé
- Regroupement des profils de conduite pour des offres d’assurance personnalisées.
- Regroupement des schémas de trafic pour optimiser la navigation et l’itinéraire.
- Segmentation des données d’usage du véhicule pour des campagnes marketing ciblées.

---
# ML : Apprentissage par renforcement

<div style="display: flex; align-items: center; gap: 20px;">
    <div style="flex: 1;">
Agents apprenant par essais et erreurs

Systèmes de récompense
    </div>

    <div style="flex: 1;">

<iframe width="560" height="315" src="https://www.youtube.com/embed/spfpBrBjntg?si=68Z-oEMzvfxk8p6x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    </div>

</div>
---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Maitre Corbeau sur un arbre ?</div>

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

<!-- .slide: data-layout="text-image" data-img="https://image1.slideserve.com/2915781/brain-size-in-mammals-l.jpg" data-alt="Taille du cerveau chez les mammifères" -->

## 🧠 Le cerveau humain
- Taille moyenne : 1600 cm³
- Néandertal : 1300 cm³
- Limité pour nouveaux neurones
- Synapses : pratiquement illimitées


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

## 🤖 L’AGI : qu’est-ce que c’est ?
- AGI = **Artificial General Intelligence**
- IA capable de comprendre, apprendre et agir **comme un humain**
- Contrairement à l’IA actuelle, qui est spécialisée


---
![Comparaison des performances de l'IA et des humains — Our World in Data](https://upload.wikimedia.org/wikipedia/commons/1/11/Comparaison_des_performances_de_l%27IA_et_des_humains_-_Our_World_in_Data.svg?download)
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/spfpBrBjntg?si=68Z-oEMzvfxk8p6x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
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
<!-- .slide: data-layout="two-column" data-img="https://media.licdn.com/dms/image/D4D12AQGyGyJI7Ht9fw/article-cover_image-shrink_600_2000/0/1668837711973?e=2147483647&v=beta&t=aGrDI4vzxLQz976zymt5s0DWTCp6GeG6UXLtKzmOxns" -->

## Singularité technologique en IA
- Point hypothétique où l’IA dépasse l’intelligence humaine et s’auto-améliore rapidement.
- Timeline incertaine; scénario graduel ou abrupt.

---

<!-- .slide: data-layout="two-column" data-img="https://controverity.com/wp-content/uploads/2026/01/elon2026-1024x536.webp" -->

## Timeline pas si incertaine que ça :

> "2026 est l'année de la singularité technologique."

Elon Musk le 4 janvier 2026

---

## Le test de Turing
**Principe :**
- Test proposé par Alan Turing en 1950
- Une machine peut-elle convaincre un humain qu'elle est elle-même humaine lors d'une conversation ?

---

<!-- .slide: data-layout="two-column" data-img="https://media.geeksforgeeks.org/wp-content/uploads/Turing-Diagram-159676.png" -->

## Comment ça marche :
1. Un humain dialogue avec deux interlocuteurs cachés
2. L'un est une machine, l'autre un humain
3. Si l'humain ne peut pas distinguer qui est qui, la machine "réussit" le test
---

## Exemple concret :
- Vous discutez par écrit avec deux personnes
- L'une parle de ses vacances, l'autre aussi
- Laquelle est l'IA ? Si vous ne pouvez pas le dire, l'IA a réussi !

---
## Et demain ? :
- Dès 2027 on ne pourra pas faire la disctinction entre un humain et une IA

---
<!-- .slide: data-layout="two-column" data-img="https://www.eoi.es/blogs/redinnovacionEOI/files/2015/08/Jan2V_Film_Her.jpg" -->
## 🎬 Her (2013) avec Joaquin Phoenix
- Relation intime entre un homme et une IA avancée
- Thèmes: attachement émotionnel, empathie simulée, solitude, autonomie de l’IA.

---
<!-- .slide: data-layout="two-column" data-img="https://static.milibris.com/thumbnail/issue/1a2ac231-e35e-41be-a8f2-e3bf978e79a7/front/catalog-cover-large.jpeg" -->

## 2026 la une du magazine Libération du 22 janvier 2026

Le test de Turing est officiellement passé par toute IA grand public qui tient aujourd'hui dans votre poche.
---

# Atelier Interactif : Comment détecter une image générée par IA ?

https://this-person-does-not-exist.com/en


---

## Parlons avec le Général de Gaulle
https://unmute.sh/

---

## Applications Concrètes
  - Génération d'une image simple ("un chat dans un jardin")
  - Génération d'un poème avec le public
-  Exemples du quotidien (10 min)
  - Reconnaissance vocale, recommandations, traduction automatique
-  Détecter l'IA (5 min)
  - "Cette image a-t-elle été générée par une IA ?" (quiz visuel)

---

## **Questions Clés (20 min)**
- "L'IA est-elle plus intelligente que nous ?"
- "Peut-on lui faire confiance ?" 
- "Va-t-elle nous remplacer ?"