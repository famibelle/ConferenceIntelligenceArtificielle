# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">L'Intelligence Artificielle</div>

---
<!-- .slide: data-layout="two-column" data-img="https://makeaicontent.com/wp-content/uploads/2023/11/DALL%C2%B7E-2023-11-15-19.27.49-A-realistic-image-depicting-harmony-between-human-and-AI-showing-a-human-hand-reaching-out-towards-a-robotic-hand.-The-image-should-capture-a-moment--1024x585.png" -->
## 🤔 Qu’est-ce que l’IA ?
- Intelligence artificielle = capacité d’un programme à **simuler l’intelligence humaine**

---
<!-- .slide: data-layout="two-column" data-img="https://synoptekmark.b-cdn.net/wp-content/uploads/2023/07/ai-ml-dl-and-generative-ai-face-off.webp" -->
## IA vs IA générative

**Intelligence artificielle (IA)** Imiter l’intelligence humaine.

**Apprentissage automatique (ML)** Systèmes qui apprennent et s’améliorent à partir de l’expérience sans être explicitement programmés.

**Apprentissage profond (DL)** Réseaux de neurones pour modéliser des motifs complexes dans les données.

**IA générative** peut créer ou générer de nouveaux contenus, idées ou données qui ressemblent à la créativité humaine.

---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Histoire de l’IA</div>

---
<!-- .slide: data-layout="two-column" data-img="https://cdn.britannica.com/14/84514-050-AF43A0D9/Alan-M-Turing-1951.jpg" -->
## 1950 – Alan Turing
- Publie **Computing Machinery and Intelligence**
- Propose le **Test de Turing**
- Question : une machine peut-elle penser ?

---
<!-- .slide: data-layout="two-column" data-img="https://image3.slideserve.com/6546540/turing-s-imitation-game-l.jpg" data-alt="Le Jeu de l'imitation de Turing" -->
## La proposition de Turing (Jeu de l’imitation)
- Expérience pensée où un interrogateur converse uniquement par écrit avec deux entités cachées: un humain et une machine.
- Objectif: décider qui est l’humain à partir des réponses en langage naturel.
- Règle de succès: si l’interrogateur ne distingue pas de façon fiable la machine de l’humain, la machine *réussit* le test.

---
<!-- .slide: data-layout="two-column" data-img="https://cryptoconexion.com/wp-content/uploads/2023/08/Dartmouth-1956-Tw.jpg" -->

## 1956 – Naissance officielle de l’Intelligence Artificielle
- Conférence de **Dartmouth**
- Objectif : créer des machines capables de penser

> Le terme **Intelligence Artificielle** est inventé

---

## La Conférence de Dartmouth
En 1956 au Dartmouth College dans le New Hampshire, aux États-Unis. 
 
Elle a réuni **John McCarthy, Marvin Minsky, Claude Shannon et Allen Newell**. 

C'est lors de cette rencontre historique que le terme **Intelligence Artificielle** a été inventé par John McCarthy. 

> Les participants pensaient pouvoir créer une machine pensante en quelques mois ...

---
<!-- .slide: data-layout="two-column" data-img="https://perceptrondemo.com/assets/rosenblatt-wiring-perceptron-940c6e47.jpg" -->
## 1960 – Le Perceptron
- **Frank Rosenblatt** invente le perceptron
- Neurone artificiel = base des réseaux de neurones
- Limité : ne résout pas les problèmes non linéaires comme le XOR

---
<!-- .slide: data-layout="two-column" data-img="https://miro.medium.com/max/1290/1*LSEtAtqzAtIP8A7G4gdDMA@2x.jpeg" -->
## Le perceptron de Rosenblatt en bref
- Neurone binaire: somme pondérée des entrées + biais, puis seuil.
- Résout les problèmes linéairement séparables (AND, OR).
- Limite majeure: XOR non séparable → besoin de couches cachées.

---
<!-- .slide: data-layout="two-column" data-img="https://news.cornell.edu/sites/default/files/styles/story_thumbnail_xlarge/public/2019-09/0925_rosenblatt_main.jpg?itok=BCWmlVvO" -->

## L'intuition de Rosenblatt

> "Devices of this sort are expected ultimately to be capable of concept formation, language translation, collation of military intelligence, and the solution of problems through inductive logic."
<div style="font-size: 0.6em; line-height: 1.3;">
<strong>Traduction :</strong><br>
« On s’attend à ce que des dispositifs de ce type soient, à terme, capables de la formation de concepts, de la traduction de langues, de la compilation de renseignements militaires et de la résolution de problèmes par la logique inductive. »
</div>

<em>Frank Rosenblatt, 1957</em>

---
<!-- .slide: data-layout="two-column" data-img="https://media.geeksforgeeks.org/wp-content/uploads/20240328125139/XOR-Gate.png" -->
## 🔍 Le Problème XOR : Limite du Perceptron Simple

Le perceptron simple ne peut pas résoudre le problème **XOR (OU exclusif)**, qui nécessite une séparation non linéaire.

**Pourquoi c'est important ?**
> Cette limitation a conduit au **premier hiver de l'IA** (1974-1980) : baisse de financements et d'intérêt pour la recherche

---
<!-- .slide: data-layout="two-column" data-img="https://media.licdn.com/dms/image/D5612AQG2n-h9rBE2NA/article-cover_image-shrink_600_2000/0/1701597139460?e=2147483647&v=beta&t=kTHU5V1z66QpFeikBYqQ4Gwgu-o3V8DlwKWOub6Rr2M" -->
## 1980 – Le Perceptron multicouche
- Introduction des **couches multiples**
- Permet de résoudre des problèmes plus complexes
- Base des IA modernes

---

## <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 8vw; font-weight: bold; width: 100%;">Au fait c'est quoi un Neurone Artificiel, et c'est quoi un Réseau de Neurones Artificiels ?</div>

---

## Un Neurone Biologique
<!-- .slide: data-layout="two-column" data-img="https://www.researchgate.net/profile/Christos-Pliatsikas/publication/376253955/figure/fig1/AS:11431281218483806@1705590629078/Neuron-anatomy-Created-with-BioRendercom.png" -->

**Structure :**  
- Dendrites  
- Soma  
- Axone  

**Fonctionnement des synapses :**  
- Transmission de signaux chimiques et électriques  

---
<!-- .slide: data-layout="two-column" data-img="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c6/Artificial_neuron_structure.svg/1024px-Artificial_neuron_structure.svg.png" -->
## Un Neurone Artificiel

Modèle mathématique du neurone artificiel

Fonctions d’activation : ReLU, Sigmoïde, Tanh

Similarités et différences avec les neurones biologiques ?

---
<!-- .slide: data-layout="two-column" data-video="https://datascientest.com/wp-content/uploads/2020/06/DP_2.png" -->

## Réseaux de Neurones Artificiels

Les réseaux de neurones artificiels sont des modèles computationnels inspirés de la structure et du fonctionnement des réseaux neuronaux biologiques. 

Ils sont composés de couches interconnectées de neurones artificiels, où chaque neurone traite les entrées, applique une fonction d'activation et transmet la sortie à la couche suivante. 

> Les Réseaux de Neurones Artificiels sont les unités fondamentales des IA.

---
<!-- .slide: data-layout="two-column" data-img="https://i.makeagif.com/media/3-22-2022/boUeR6.gif" -->
## Réseau de Neurones en Action

L'animation montre le processus de reconnaissance de chiffres manuscrits à l'aide d'un réseau de neurones. 

Elle visualise comment le modèle traite les images d'entrée, extrait les caractéristiques et prédit le chiffre correspondant.

---

<!-- .slide: data-layout="two-column" data-video="https://youtu.be/FwFduRA_L6Q?si=seVi3mjawRWwdIj1" -->

## Démonstration de réseau convolutionnel de 1989 par Yann Le Cun

**LeNet-1** premier réseau convolutionnel capable de reconnaître des chiffres manuscrits avec une bonne vitesse et précision.

Il a été développée début 1989 au département **Adaptive System Research**, dirigé par **Larry Jackel**, chez Bell Labs à Holmdel (New Jersey).

Cette démonstration « en temps réel » tournait sur une carte DSP installée dans un PC 486, avec une caméra vidéo et une carte d’acquisition. 

---
<!-- .slide: data-layout="two-column" data-img="https://www.intelligenthq.com/wp-content/uploads/2023/09/godfathers-of-ai.jpg" data-alt="Les Pères Fondateurs du Deep Learning" -->

## 🏆 Les Parrains de l'IA

**Les Pères Fondateurs du Deep Learning**

Trois chercheurs ont révolutionné l'IA moderne et partagé le **Prix Turing 2018** (le "Nobel de l'informatique") :

- Ont persisté quand personne ne croyait aux réseaux de neurones
- Leurs travaux ont permis : reconnaissance vocale, voitures autonomes, traduction automatique

**Geoffrey Hinton** 🇬🇧

**Yann Le Cun** 🇫🇷

**Yoshua Bengio** 🇨🇦

---
<!-- side.slide: data-layout="two-column" data-img="https://upload.wikimedia.org/wikipedia/commons/thumb/6/66/Geoffrey_E._Hinton%2C_2024_Nobel_Prize_Laureate_in_Physics_%283x4_cropped%29.jpg/250px-Geoffrey_E._Hinton%2C_2024_Nobel_Prize_Laureate_in_Physics_%283x4_cropped%29.jpg" -->


## 1980s – Geoffrey Hinton
- Travaux sur **l’apprentissage profond**
- Redécouvre et perfectionne les réseaux multicouches
- Précurseur du deep learning moderne


---
<!-- .slide: data-layout="two-column" data-img="https://i.la-croix.com/x/smart/2016/03/01/1200743436/Yann-LeCun-responsable-laboratoire-intelligence-artificielle-chez-Facebook_0.jpg"-->
## 1980s – Yann LeCun
- Travaux sur les **CNN (Convolutional Neural Networks)**
- Applications : reconnaissance de chiffres manuscrits
- Début du succès du deep learning

---
<!-- .slide: data-layout="two-column" data-img="https://www.actuia.com/storage/uploads/2018/04/yoshua-bengio.jpg" data-alt="Yoshua Bengio" -->
## 1990s – Yoshua Bengio
- Travaux sur **les représentations distribuées**
- Réseaux neuronaux plus profonds
- Précurseur des réseaux très larges et profonds actuels

---
<!-- .slide: data-layout="two-column" data-img="https://tse1.mm.bing.net/th/id/OIP.3liapdpAF6vYvBQnLSOGvQHaFA" -->

## 1997 – Deep Blue
- L'ordinateur d’IBM bat Garry Kasparov aux échecs
- Démonstration de force brute d’algorithmes

---
<!-- .slide: data-layout="two-column" data-img="https://miro.medium.com/v2/resize:fit:640/format:webp/1*tnFwtQfQUsPsmFmOlJtUSw.png" -->
## ImageNet (en bref)

- Jeu de données d’images à grande échelle lancé en 2009
- ~14 M d’images annotées à la main, ~20 000 catégories (synsets WordNet)
- Utilisé pour entraîner et évaluer des modèles de vision par ordinateur

---

<!-- .slide: data-layout="two-column" data-img="https://i.ytimg.com/vi/ZUc0Mib5DeI/maxresdefault.jpg" -->

## 🏆 AlexNet : La Révolution de 2012

- Réseau de neurones convolutif profond créé par **Alex Krizhevsky, Ilya Sutskever et Geoffrey Hinton**
- 8 couches (5 convolutives + 3 entièrement connectées)
- 60 millions de paramètres

---
<!-- .slide: data-layout="two-column" data-img="https://www.pinecone.io/_next/image/?url=https%3A%2F%2Fcdn.sanity.io%2Fimages%2Fvr8gru94%2Fproduction%2F1937562f4ac2507386e0a1965602544f697bb439-665x419.png&w=750&q=75" -->
## 🏆 AlexNet : La Révolution de 2012

**Gagne le concours ImageNet 2012**
- Taux d'erreur : 15,3% (vs 26,2% pour le second)
- Révolutionne la reconnaissance d'images

---
<!-- .slide: data-layout="two-column" data-img="https://computerhistory.org/wp-content/uploads/2025/01/fig-69-REDUCED-bedroom-computer-used-for-breakthrough-1024x771.jpg" -->

## 🏆 AlexNet : La Révolution de 2012

**Les Innovations Clés**
- Utilisation de **GPU Nvidia** pour l'entraînement
- **NVIDIA GTX 580 GPU** avec 3GB de mémoire
- Ordinateur de chambre utilisé pour la percée

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
- Après AlexNet, rejoint **Google Brain**
- 2015 : Cofonde **OpenAI** avec Sam Altman
- Rôle clé dans le développement de **GPT** et **ChatGPT**
- Chief Scientist chez **OpenAI** jusqu'en 2024

---
<!-- .slide: data-layout="two-column" data-img="https://i.huffpost.com/gen/4072998/images/o-JEU-DE-GO-facebook.jpg" -->

## Le défi du jeu de Go
- Jeu de stratégie chinois vieux de plus de 2500 ans
- Complexité extrême: il y a plus de positions possibles que d'atomes dans l'univers observable

> Seul l'intuition humaine peut le maîtriser

---
<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/watch?v=g-dKXOlsf98" -->
## 2016 - AlphaGo
- Développé par **Demis Hassabis, DeepMind**
- Apprentissage par renforcement + réseaux profonds

---
<!-- .slide: data-layout="two-column" data-img="https://imgv2-1-f.scribdassets.com/img/document/698305505/original/462b61234a/1707724024?v=1" -->
## AlphaGo bat Lee Sedol 4-1

- 2016 AlphaGo affronte **Lee Sedol**, champion du monde de Go
- **Victoire 4-1** : choc pour la communauté du Go
- Considéré comme impossible 10 ans auparavant


---
<!-- .slide: data-layout="two-column" data-video="https://youtu.be/whNvUWRQPhY" -->

## Le Coup 37 : Le Moment Légendaire
- Deuxième partie : AlphaGo joue un coup jamais vu auparavant
- Les commentateurs le jugent d'abord **ridicule**, une erreur grossière
- Se révèle être un coup de génie qui change la partie

> AlphaGo m'a montré que je ne savais rien

<em>Lee Sedol</em>

---
<!-- .slide: data-layout="two-column" data-img="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExZzZoZXBhZnU1M2Q0ajZ0cmE0cWdwcm83Y25pNmk1NXp2OW4xNnpvYyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/fVK2mkgyIHUkw/giphy.gif" -->

## Le Défi StarCraft II
- Jeu de stratégie en temps réel
- Extrêmement complexe
- Nécessite planification, gestion de ressources, micro-gestion
- Brouillard de guerre : informations incomplètes

---
<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/watch?v=cUTMhmVh1qs" -->
## Décembre 2018 : AlphaStar bat des joueurs professionnels de StarCraft II
- Atteint le niveau **Grandmaster** (top 0,2% des joueurs)
- **AlphaStar** est devenue une IA pro de **Starcraft 2** en s'entraînant, comme un humain
- **A joué plus de 200 ans** de parties en 2 semaines
- **Fais preuve de créativité et d'intuition**

---
## 🧬 Pliage moléculaire en médecine

- La forme d’une protéine dicte son rôle (ex. enzymes, anticorps, récepteurs).
- Trop de formes possibles (nombre de combinaisons astronomique).
- Le pliage dépend de nombreux facteurs (eau, liaisons, ions, pH, température, etc.).
- **Demande des capacités de calcul énormes.**

---
<!-- .slide: data-layout="two-column" data-img="https://iadatavision.wordpress.com/wp-content/uploads/2023/03/alphafold-db-1.png" -->

## AlphaFold : La Révolution
- Développé par DeepMind (2020)
- Résout un problème vieux de 50 ans : prédire la structure 3D des protéines
- Prédit la structure de 200 millions de protéines (soit quasiment toutes les protéines du vivant)
---
<!-- .slide: data-layout="two-column" data-video="https://youtu.be/gg7WjuFs8F4?si=k0zLPdsV-yJ4RBKs" -->

## AlphaFold
- A fait avancer la recherche biomédicale de plusieurs décades en quelques mois
- **Avant AlphaFold**, les scientifiques avaient déterminé expérimentalement environ **200 000 structures de protéines**
- **Avec AlphaFold**, plus de **200 millions de structures de protéines** qui sont désormais disponibles gratuitement
- **Prix Nobel de Chimie 2024** décerné conjointement à Demis Hassabis (DeepMind), John Jumper (DeepMind) et David Baker (University of Washington)

---

<!-- .slide: data-layout="two-column" data-img="https://cbmm.mit.edu/sites/default/files/styles/colorbox_for_node_images/public/news-events/65e80469-36b7-44de-bb8c-0ddb5b00.jpeg?itok=br6JZi3g" -->

## Qui est Demis Hassabis ?
- Né en 1976 à Londres, Royaume-Uni.
- Enfance : prodige des échecs, atteint le rang de maître international à 13 ans.
- Études : diplômé en informatique de l’Université de Cambridge, doctorat en neurosciences cognitives à UCL.

---

## Demis Hassabis et les Jeux vidéo 🎮
- A commencé sa carrière dans les jeux vidéo à 17 ans.
- **Syndicate (1993)**
Rôle : Playtester (testeur de jeu) dans ses débuts chez Bullfrog Productions.

- **Theme Park (1994)**
Lead Programmer (programmeur principal)

- **Republic: The Revolution (2003)**
Rôle : Executive Designer (concepteur exécutif) et concept principal du jeu.
Studio : Elixir Studios, société qu’il a fondée en 1998 à Londres.

- **Evil Genius (2004)**
Rôle : Executive Designer et Concept.
Studio : Elixir Studios, toujours sous sa direction.

---

<!-- .slide: data-layout="two-column" data-img="https://news.aikoreacommunity.com/content/images/2024/01/20240109_181100.png" -->
## 2017 – Attention is All You Need
- le Transformer est une architecture d’IA (2017) qui comprend le contexte des phrases grâce à un mécanisme appelé **attention**.
- **l’attention permet au modèle de se concentrer sur les mots les plus utiles de la phrase**

---
<!-- .slide: data-layout="two-column" data-img="https://inside-machinelearning.com/wp-content/uploads/2021/10/AttentionViz.png" -->

## Le Mécanisme de l’Attention
- Petite illustration: dans la phrase **Le chat de ma grand mère mange la souris**, 
- L’attention se concentre sur **mange** et **souris**, pas sur **chat** ou **grand mère**.
- Avant la machine aurait compris que **ma grand mère qui mange la souris !**

---

## Équation du mécanisme d’attention

Le mécanisme d’attention peut s’exprimer mathématiquement ainsi :

$$\text{Attention}(Q,K,V) = \text{softmax}\left(\frac{Q K^T}{\sqrt{d_k}}\right) V$$

Où :
- $Q$ (Query) : ce que l’on recherche
- $K$ (Key) : ce avec quoi on compare
- $V$ (Value) : l’information à récupérer
- $d_k$ : dimension des vecteurs de clés (utilisée pour le facteur d’échelle)

---
<!-- .slide: data-layout="two-column" data-img="https://miro.medium.com/v2/resize:fit:1200/1*QhE-IttZzUBITxMsK74QSQ.png" -->
## 🎯 Impact des Transformers
- Révolutionne le traitement du langage naturel (NLP)
- Base des modèles comme BERT, GPT, T5

> C'est le T dans GPT !

---
<!-- .slide: data-layout="two-column" data-img="https://www.tooltester.com/wp-content/uploads/2023/02/ChatGPT-launch-timeline-to-GPT-4-768x439.jpg" -->

## 🚀 ChatGPT !
- Adoption record (>100 M utilisateurs/mois)
- Popularisation de l’IA générative et accélération de son adoption dans tous les secteurs

---

## Quiz: Que signifie GPT ?

- A) General Principles of Technology
- B) Guided Pretrained Text
- C) Generative Pretrained Transformer

---

## A quoi sert le Mécanisme d’Attention ?
- A) À améliorer la vitesse de calcul
- B) À permettre au modèle de se concentrer sur les parties importantes du texte
- C) À être concentré plus longtemps pendant les conférences 
---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Comment la machine apprend ?</div>

---
<!-- .slide: data-layout="two-column" data-img="https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/07/Supervised-Learning-in-ML.jpg" -->
## ML : Apprentissage supervisé

Utilisation de données étiquetées

Tâches de classification et de régression

---
<!-- .slide: data-layout="two-column" data-img="https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/07/Unsupervised-Learning-in-ML.jpg" -->

## ML : Apprentissage non supervisé

Découverte de structures cachées

Techniques de clustering et de réduction de dimensionnalité

---
<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/embed/spfpBrBjntg?si=68Z-oEMzvfxk8p6x&autoplay=1&mute=1" data-mute="true" -->

## ML : Apprentissage par Renforcement​

Agents apprenant par essais et erreurs​

Systèmes de récompense​

---
<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/embed/KPLYhRBCcvk?autoplay=1&mute=1" data-mute="true" -->

## ML : Apprentissage par Renforcement​

- Systèmes de conduite autonome apprenant des stratégies de conduite optimales par simulation.
- Systèmes de régulateur de vitesse adaptatif optimisant l'efficacité énergétique et la sécurité.
- Systèmes d'assistance au stationnement apprenant à naviguer dans des scénarios de stationnement complexes.

**Source :** [AlphaStar : Niveau grand maître dans StarCraft II utilisant l'apprentissage par renforcement multi-agents](https://deepmind.google/discover/blog/alphastar-grandmaster-level-in-starcraft-ii-using-multi-agent-reinforcement-learning/)

---

## <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Maitre Corbeau sur un arbre _____ </div>

---

## Maître Corbeau sur un arbre <u>perché</u>
![Poesie](http://andreetgyps.a.n.pic.centerblog.net/o/6b0e0247.jpg)

---

## "Maître Corbeau sur un arbre perché" → décasyllabe
- **Syllabes dans un poème :** Maî-tre Cor-beau sur un ar-bre per-ché.
- **Tokens en NLP :** [Maî ##tre Cor ##beau sur un ar ##bre per ##ché.].

---
<!-- .slide: data-layout="two-column" data-img="https://cdn.prod.website-files.com/61e7d259b7746e3f63f0b6be/6630e466c569a5f73cd81c9e_Understanding%20LLM%20Billing_%20From%20Characters%20to%20Tokens-p-800.jpg"-->
## Les Tokens sont aux LLMs ce que les syllabes sont à la poésie

Tout comme les syllabes sont les éléments constitutifs du rythme et de la structure d'un poème, les tokens sont les unités fondamentales qui permettent aux modèles d'IA de traiter et de comprendre le texte.

---

## Tokens dans les Modèles d'IA

La limite de tokens définit le nombre maximum de tokens qu'un modèle peut traiter dans une seule entrée. Des limites de tokens plus élevées permettent de gérer des contextes plus longs, rendant les modèles plus efficaces pour des tâches comme la synthèse, l'analyse de code et la génération de documents.

| Modèle         | Taille Max (tokens) | Pages de Livre de Poche |
|----------------|---------------------|------------------------------|
| GPT-5          | 128 000             | ~512                         |
| Llama 3.1      | 128 000             | ~512                         |
| Mistral Large  | 64 000              | ~256                         |

---
<!-- .slide: data-layout="two-column" data-img="https://causewriter.ai/wp-content/uploads/2023/08/image-2.png)" -->

## Embedding: Transformer les Tokens en Représentations Numériques

L'**embedding** transforme les **tokens** en **vecteurs**, qui servent de points d'entrée pour le **LLM**.

- Associe chaque token à un vecteur de haute dimension dans un espace continu.
- Exemple : 
- [Mai ##tre Cor ##beau sur un ar### bre perché.]. → [[0.12, 0.45, ...], [0.34, 0.67, ...], [0.89, 0.23, ...]].

---

## Paramètres et Poids dans les Réseaux de Neurones

- **Les poids et les biais** sont les paramètres  d'un réseaux de neurone. En mettant à jour de manière itérative ces valeurs à l'aide d'algorithmes d'optimisation comme **la descente de gradient**, le réseau améliore ses performances sur la tâche donnée.

**Poids et biais au niveau mathématique :**

- Dans un réseau de neurones simple, si l'entrée est `X`, le poids est `W` et le biais est `B`, et $f$ est la fonction d'activation.

La sortie d'un neurone est calculée comme :

$$\text{sortie} = f(W \cdot X + B)$$


---
<!-- .slide: data-layout="two-column" data-img="https://shearwaterjapan.com/wp-content/uploads/2025/04/llm-300x200.png" -->
## un LLMs est un modèle avec beaucoup beaucoup ... beaucoup de paramètres
- **L**: Large
- **L**: Language
- **M**: Model

---
<!-- .slide: data-layout="two-column" data-img="https://www.geeky-gadgets.com/wp-content/uploads/2023/09/New-Mistral-7B-instruct-model-from-Mistral-AI.webp" -->
## Mistral 7B : Nombre de Paramètres

Le modèle Mistral 7B est un modèle de fondation avec **7 milliards de paramètres**.

**Comparaison :**
- **GPT-4 :** Environ 175 milliards de paramètres estimés.
- **LLaMA 2 (13B) :** 13 milliards de paramètres.
- **GPT-5 :** entre 500 et 1500 milliards de paramètres selon les rumeurs.

---
<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/embed/FdZvMoP0dRU?autoplay=1&mute=1" data-mute="true" -->
## YOLO

**Y**ou

**O**nly

**L**ook

**O**nce

- Modèle de détection d'objets en temps réel
---

## Comment la voiture voit-elle le monde ?

<div style="display: flex; justify-content: center; align-items: center; height: 100vh; width: 100%;">
    <video controls autoplay muted playsinline width="640" height="480">
        <source src="https://digitalassets.tesla.com/tesla-contents/video/upload/f_auto,q_auto/network.mp4" type="video/mp4">
        Votre navigateur ne prend pas en charge la balise vidéo.
    </video>
</div>


---
<!-- .slide: data-layout="two-column" data-img="https://media.licdn.com/dms/image/v2/D5612AQEjGGrWMf79pA/article-cover_image-shrink_720_1280/B56ZYz6vWpGoAM-/0/1744627806105?e=2147483647&v=beta&t=Bd-5S7UUOmFMZ_8UUHvqIosaJ5EohNQRUyn-nbO62E0" -->
## Les Successeurs des LLM (vision de Yann Le Cun)
- JEPA : apprentissage auto-supervisé qui prédit des parties manquantes.
- World Models : modèles prédictifs du monde (vidéo/audio/action) pour raisonner et planifier.

---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Comment l'Homme se positionne vis à vis de l'IA ?</div>

---

<!-- .slide: data-layout="text-image" data-img="https://image1.slideserve.com/2915781/brain-size-in-mammals-l.jpg" data-alt="Taille du cerveau chez les mammifères" -->

## 🧠 Le cerveau humain
- Taille moyenne : 1600 cm³
- Néandertal : 1800 cm³

|                      | Cerveau humain | Intelligence Artificielle |
|----------------------|----------------|----------------|
| Consommation         | ~20 W          | ~1 000 MW      |
| Neurones (approx.)   | ~86 milliards  | ~300 millions (GPT-5)  |
| Nouveaux neurones    | Limité par la boite cranienne | No limit|

Le cerveau humain est aujourd'hui **100 millions de fois plus économe en énergie** qu'une IA.

---

## Comparaison des performances de l'IA et des humains
![Comparaison des performances de l'IA et des humains — Our World in Data](https://upload.wikimedia.org/wikipedia/commons/1/11/Comparaison_des_performances_de_l%27IA_et_des_humains_-_Our_World_in_Data.svg?download)

---
# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Et Demain ?</div>

---
changement de paradigme
1er revolution indus : lnenergie se transforme en force
2eme energie devient con'aissance (Internet)
3   energie devient intelligence (QI)

---
<!-- .slide: data-layout="two-column" data-img="https://www.geeky-gadgets.com/wp-content/uploads/2023/06/What-is-AGI.jpg" -->
## L'AGI: Artificial General Intelligence

L'IA capable de comprendre, apprendre et agir **comme un humain**

| IA spécialisée | AGI |
|----------------|-----|
| Fait une seule tâche | Peut apprendre toutes les tâches |
| Exemple : AlphaGo | Exemple : résoudre un problème, créer, planifier |
| Limité à un domaine | **polyvalente et autonome** |

---
<!-- .slide: data-layout="two-column" data-img="https://media.licdn.com/dms/image/D4D12AQGyGyJI7Ht9fw/article-cover_image-shrink_600_2000/0/1668837711973?e=2147483647&v=beta&t=aGrDI4vzxLQz976zymt5s0DWTCp6GeG6UXLtKzmOxns" -->

## La Singularité Technologique
- Point hypothétique où l’IA dépasse l’intelligence humaine et s’auto-améliore rapidement.
- Timeline incertaine
- Scénario graduel ou abrupt ?

---

## à votre avis la singularité technologique arrivera quand ?
- jamais
- dans 50 ans
- dans 20 ans

---
<!-- .slide: data-layout="two-column" data-img="https://miro.medium.com/v2/resize:fit:1358/1*na6eVIVet02RemFEjSDA4w.png" -->
## Loi de Moore appliquée à l'IA
- Chaque nouvelle génération de modèles d’IA multiplie par 10 sa capacité à interval fixe

---

<!-- .slide: data-layout="two-column" data-img="https://content.api.news/v3/images/bin/e39c59e786ff255e6a7d1c4ae9d9611b" data-alt="Terence Tao" -->
## Terence Tao
- Médaille Fields 2006
- QI estimé (non officiel) : ~220, L'homme le plus intelligent du monde
- Théorème Green–Tao: progressions arithmétiques dans les nombres premiers

> En 2030, une IA sera t'elle capable de résoudre la plupart des problèmes mathématiques que Terence Tao peut résoudre ?

---

<!-- .slide: data-layout="two-column" data-img="https://controverity.com/wp-content/uploads/2026/01/elon2026-1024x536.webp" -->

## La singularity arrive avec 30 ans d'avance

> 2026 est l'année de la singularité technologique.

Elon Musk le 4 janvier 2026

---

<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/watch?v=zGfac0-MY20" data-mute="false" -->

## L'IA est elle meilleure que nous ?
Ecoutons ce qu'en pense Cédric Villani 
- Mathématicien français, *médaille Fields 2010* pour ses travaux en théorie cinétique (équations de Boltzmann et de Landau).
- Auteur du rapport national 2018 sur l’IA *Donner un sens à l’intelligence artificielle* (stratégie française et européenne).
- Ancien directeur de l’Institut Henri-Poincaré

---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Un futur pas si lointain ...</div>

---

<!-- .slide: data-layout="two-column" data-img="https://www.numerama.com/wp-content/uploads/2023/04/concoursia-cover.jpg" -->

## L’image d’une IA a dupé les organisateurs du plus prestigieux concours de photos
Le 14 avril 2023, l’artiste allemand Boris Eldagsen a gagné la catégorie « Open » du **Sony World Photography Awards**, 

Problème : la photo présentée a été réalisée en partie avec de l’intelligence artificielle.

---
## IA et humains : vers une indistinction ?
<!-- .slide: data-layout="two-column" data-video="https://youtu.be/ARxHvTScXMY?si=K77qc-_mvKUfFskK" -->
Dès 2027 on ne pourra pas faire la distinction entre un humain et une IA

**Prompt** *A stylish woman walks down a Tokyo street filled with warm glowing neon and animated city signage. She wears a black leather jacket, a long red dress, and black boots, and carries a black purse. She wears sunglasses and red lipstick. She walks confidently and casually. The street is damp and reflective, creating a mirror effect of the colorful lights. Many pedestrians walk about.*

---
<!-- .slide: data-layout="two-column" data-img="https://www.eoi.es/blogs/redinnovacionEOI/files/2015/08/Jan2V_Film_Her.jpg" -->
## 2013 🎬 Film "Her" avec Joaquin Phoenix
- Relation intime entre un homme et une IA avancée
- Thèmes: attachement émotionnel, empathie simulée, solitude

---
<!-- .slide: data-layout="two-column" data-img="https://static.milibris.com/thumbnail/issue/1a2ac231-e35e-41be-a8f2-e3bf978e79a7/front/catalog-cover-large.jpeg" -->

## Magazine Libération du 22 janvier 2026

Le test de Turing est officiellement passé par toute IA grand public qui tient aujourd'hui dans votre poche.

---

<!-- .slide: data-layout="two-column" data-img="https://img-api.mac4ever.com/1179/0/af7e438e7e_qu-est-ce-que-le-slop-ce-curieux-phenomene-envahissant.webp" -->

## IA Slop ou la bouillie générée par IA qui pollue le web

- Contenu généré automatiquement de faible qualité, produit à grande échelle.

> "It’s becoming harder to detect what’s real and what’s AI-generated. This is particularly critical when it comes to deepfakes. 

Neal Mohan, CEO de YouTube, mercredi 21 janvier 2026.

---
<!-- .slide: data-layout="two-column" data-img="https://www.editions-harmattan.fr/media/359309/download/9782336526898r.jpg?v=1" -->
## la  course à l'IA entretenue par les tensions géopolitiques entre les blocs USA CHINE EUROPE

L’IA devient un champ de bataille entre les États-Unis, la Chine et l’Europe

---

## Atelier Interactif : Comment détecter une image générée par IA ?

https://this-person-does-not-exist.com/en

---

## Parlons avec le Général de Gaulle
https://unmute.sh/

---
# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Merci pour votre attention</div>

---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Questions ?</div>

---

# <div style="display: flex; justify-content: center; align-items: center; height: 100vh; text-align: center; font-size: 10vw; font-weight: bold; width: 100%;">Pour aller plus loin ...</div>

---

## Base de Données MNIST : Reconnaissance de Chiffres Manuscrits


La base de données MNIST (Modified National Institute of Standards and Technology) est un benchmark largement utilisé en apprentissage automatique et en vision par ordinateur. Elle se compose de 70 000 images en niveaux de gris de chiffres manuscrits (0 à 9), chacune de taille 28x28 pixels. La base de données est utilisée pour entraîner et évaluer des modèles pour des tâches de reconnaissance de chiffres.

**Importance :**
- MNIST sert de point de départ pour tester et comparer les algorithmes d'apprentissage automatique.
- Elle aide à comprendre comment les réseaux de neurones peuvent classifier des nombres basés sur des motifs de pixels.

**Historique :**
- MNIST a été introduite en 1998 par **Yann LeCun, Corinna Cortes et Christopher J.C. Burges** dans le cadre de leurs recherches sur les réseaux de neurones et l'apprentissage automatique.

**Applications :**
- Reconnaissance de chiffres dans les systèmes postaux.
- Expériences fondamentales en apprentissage profond.


![Exemple de la Base MNIST](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

Exemple de reconnaissance de chiffres manuscrits de la base de données MNIST

---
<!-- .slide: data-layout="two-column" data-img="https://media.licdn.com/dms/image/D5612AQG2n-h9rBE2NA/article-cover_image-shrink_600_2000/0/1701597139460?e=2147483647&v=beta&t=kTHU5V1z66QpFeikBYqQ4Gwgu-o3V8DlwKWOub6Rr2M" -->

## Le Perceptron Multicouche

Le **Perceptron Multicouche** est un type de réseau de neurones artificiels composé d'une couche d'entrée, d'une ou plusieurs couches cachées et d'une couche de sortie. 

Chaque couche consiste en des neurones interconnectés où les entrées sont traitées à travers des connexions pondérées, des fonctions d'activation et des biais.

Le concept du PMC a été introduit pour la première fois en 1969 par *Marvin Minsky et Seymour Papert* dans leur livre *Perceptrons*

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

<!-- .slide: data-layout="two-column" data-img="https://medias.pourlascience.fr/api/v1/images/view/5a82ac588fe56f7c1c01b7e3/wide_1000-webp/image.jpg" -->
## Les Techniques d'AlphaGo
- **Apprentissage supervisé** : étude de 30 millions de positions de parties de professionnels
- **Apprentissage par renforcement** : l'IA joue contre elle-même des millions de fois

---

<!-- .slide: data-layout="two-column" data-video="https://youtu.be/UuhECwm31dM?si=5-9yNHVsPns0mCSq" -->

## L'IA dans StarCraft II bat le meilleur joueur humain

> La grande incertitude [liée au manque] d'informations en période de guerre est d'une difficulté particulière parce que toutes les actions doivent dans une certaine mesure être planifiées avec une légère zone d'ombre (…) comme l'effet d'un brouillard [...].

— Carl von Clausewitz, *De la guerre*

---
<!-- .slide: data-layout="two-column" data-video="https://youtu.be/EyWsnc7cB_w?si=BvUJi0RrmLqog1BR" -->

## 1999 SETI@Home
- Calcul distribué pour chercher des signaux extraterrestres
- Des milliers d'ordinateurs volontaires cherchent des signaux extraterrestres dans les données radio

---
<!-- .slide: data-layout="two-column" data-video="https://www.youtube.com/watch?v=b8GS9l3xZiY" -->
## Foldit 
- Un jeu où des joueurs s'amusent à plier des protéines,  basé sur le moteur Rosetta (University of Washington).
- Exploite **l’intuition humaine** pour explorer l’espace de conformations, générant des données utiles à l’IA et à la conception de médicaments.

---

<!-- .slide: data-layout="two-column" data-img="https://techcrunch.com/wp-content/uploads/2019/01/motionalpha.gif" -->
## Les Techniques Utilisées
- **Apprentissage par imitation** : étudie des millions de parties humaines
- **Apprentissage par renforcement** : joue contre différentes versions de lui-même
- **A joué plus de 200 ans** de parties en 2 semaines
- **Fais preuve de créativité et d'intuition**

---
## Questions Clés
- "L'IA est-elle plus intelligente que nous ?"
- "Peut-on lui faire confiance ?" 
- "Va-t-elle nous remplacer ?"