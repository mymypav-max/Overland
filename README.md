# Overland

> Document maître de conception — version initiale

Overland est un projet de jeu vidéo personnel (« homemade »), conçu pour être développé progressivement et, à terme, joué sur une borne d’arcade. Ce document centralise les décisions de conception. Il ne constitue pas encore un cahier des charges technique.

## Statut des décisions

- **Validé** : décision confirmée.
- **À concevoir** : sujet à préciser avant de le considérer comme décidé.
- **Piste** : idée intéressante, mais non validée.

## 1. Vision du jeu

### Validé

- RPG d’aventure **2D en vue de dessus**, avec une direction artistique en pixel art relativement fin et lisible.
- Aventure solo, avec une durée visée indicative d’environ **15 à 20 heures** pour l’aventure principale et l’exploration associée. Le contenu sera développé progressivement, en commençant par une première portion jouable ; cette durée pourra évoluer selon la richesse du monde et le rythme de développement.
- Exploration d’un monde composé de villes et villages, routes, forêts, montagnes, grottes, zones côtières et lieux abandonnés.
- Rencontres, capture et entraînement d’animaux dotés de pouvoirs surnaturels ou élémentaires.
- Combats tactiques au tour par tour contre des animaux sauvages et des personnages possédant leur propre équipe.
- Ton d’aventure chaleureux mêlant exploration, humour, amitié et mystères.
- Projet personnel, sans objectif de commercialisation imposé.

### À concevoir

- Le scénario principal complet, les personnages importants et la progression narrative détaillée.
- La structure précise du monde et le nombre de régions.
- Le rythme de progression et la durée effective du jeu.

## 2. Le monde d’Overland

### Validé

- **Overland** est le nom de travail du jeu et peut également être le nom de son monde.
- Le jeu se déroule à un **instant donné** : le joueur ne voyage pas entre différentes époques.
- Le passé est découvert à travers ses vestiges : fossiles, animaux préhistoriques, grottes, ruines, lieux abandonnés et autres indices.
- Le monde reste reconnaissable et proche du nôtre dans ses paysages et ses lieux habités, tout en étant affecté par un phénomène mystérieux lié aux pouvoirs des animaux.
- Le cadre principal envisagé et retenu est une **grande île connue depuis longtemps dans le monde entier**, avec des lieux habités, des localités abandonnées, des grottes et des régions naturelles variées.
- L’île est réputée pour ses animaux : ils ressemblent à des animaux ordinaires du monde réel, mais possèdent des pouvoirs surnaturels ou élémentaires.
- Des personnes venues du monde entier — notamment des chercheurs et des explorateurs — se rendent sur l’île pour étudier ses animaux et tenter de comprendre ce phénomène.
- À ce stade, l’île est le seul endroit connu où des animaux possèdent ces pouvoirs.
- Les fossiles découverts sur l’île indiquent que des espèces préhistoriques possédaient elles aussi des pouvoirs. Cela suggère que le phénomène est ancien, sans en expliquer l’origine.
- Les grottes et certains lieux isolés peuvent contenir des animaux sauvages, des captures rares, des objets, des fossiles, des secrets et des indices sur ce phénomène.

### À concevoir

- La nature exacte du phénomène mystérieux et son rôle dans l’histoire.
- La carte, les régions, leur ordre de découverte et leurs particularités.
- La place des villes, laboratoires, ruines et autres lieux importants dans le récit.
- Les règles précises du phénomène et les raisons pour lesquelles il est propre à l’île.

### Piste — origine du phénomène

Une météorite ayant frappé l’île il y a des millions d’années a été évoquée comme explication possible des pouvoirs, y compris ceux des animaux préhistoriques. Cette hypothèse n’est **pas validée** et ne doit pas être considérée comme l’explication définitive.

## 3. Les animaux

### Validé

- Les créatures sont des **animaux reconnaissables**, enrichis de pouvoirs surnaturels ou élémentaires ; elles ne sont pas simplement des monstres abstraits.
- Les animaux rencontrés à l’état sauvage doivent tous pouvoir être capturés.
- Une capture réussie ajoute l’animal à l’équipe transportée ou au système de stockage. Aucun système d’apprivoisement préalable fondé sur la confiance n’est prévu.
- Les animaux gagnent de l’expérience et des niveaux grâce aux combats.
- Chaque espèce possède au minimum une forme jeune et une forme adulte.
- Chaque espèce a son propre niveau d’évolution. À ce niveau, l’évolution vers la forme adulte se déclenche automatiquement.
- Les espèces rencontrées dans les régions plus avancées sont généralement de niveau supérieur, afin que le joueur puisse renouveler ou renforcer son équipe sans devoir tout recommencer au niveau 1.

### Types élémentaires envisagés

- Feu
- Eau
- Terre / Roche
- Plante / Feuille

Cette liste initiale pourra évoluer ; elle ne fixe pas encore le tableau des forces et faiblesses.

### À concevoir

- Les caractéristiques, techniques, rôles tactiques et règles de combat.
- La taille de l’équipe de combat et les règles détaillées de gestion de l’équipe.
- Le catalogue des espèces et l’équilibrage entre elles.
- La progression des niveaux et les conditions exactes de rencontre.

## 4. Capture et stockage des animaux

### Validé

- Le protagoniste utilise **un appareil technologique unique** pour capturer et transporter les animaux. Il ne s’agit pas d’une collection de capsules individuelles.
- L’appareil est une invention technologique humaine conçue spécifiquement pour capturer les animaux de l’île. Il n’est pas établi comme un artefact ancien ou un objet magique ; son fonctionnement ne doit pas révéler à lui seul l’origine du phénomène mystérieux.
- L’appareil utilise des **charges consommables** pour effectuer les captures.
- **Chaque tentative de capture consomme une charge**, que la tentative réussisse ou échoue.
- Les charges peuvent être achetées ou récupérées pendant l’aventure.
- L’appareil peut transporter directement jusqu’à **six animaux**.
- Lorsqu’une capture supplémentaire dépasse cette capacité, l’animal est transféré vers un **système de stockage distant** (type cloud), où il reste disponible pour le joueur.

### À concevoir

- Le nom, l’apparence et le fonctionnement précis de l’appareil.
- Le mécanisme concret de capture et son animation.
- Le fonctionnement détaillé du stockage distant et la façon dont le joueur y accède.
- Le nombre de charges obtenues à l’achat ou en exploration, leur prix et leur fréquence de disponibilité.
- Les chances de capture et les facteurs qui les influencent.

## 5. Évolutions

### Validé

- L’évolution jeune → adulte est automatique au niveau propre à chaque espèce.
- Certaines espèces pourront posséder une évolution spéciale supplémentaire, accessible sous une condition particulière.
- Des fossiles spécifiques pourront débloquer une forme ancienne pour certains animaux modernes compatibles. Exemple de principe : un grand félin moderne pourrait accéder à une forme inspirée du Smilodon grâce à un fossile approprié. Il s’agit d’une transformation fictive, pas d’une affirmation selon laquelle le Smilodon serait l’ancêtre direct du tigre.
- Ces évolutions spéciales ne seront pas accessibles à n’importe quelle espèce avec n’importe quel fossile.

### À concevoir

- Les conditions précises des évolutions spéciales et leurs effets sur le gameplay.
- La place des formes spéciales dans l’équilibrage général.

## 6. Fossiles et animaux préhistoriques

Deux systèmes distincts sont prévus.

### A. Fossiles de résurrection — validé

- Des fossiles découverts notamment dans les grottes pourront être apportés à un laboratoire accessible au cours de l’aventure.
- Un scientifique pourra les utiliser pour faire renaître certaines espèces éteintes.
- L’animal obtenu est une jeune forme qui se développe selon les mêmes règles générales que les autres animaux.
- Exemple : un fossile de vélociraptor permettrait d’obtenir un jeune vélociraptor.
- Toutes les espèces éteintes ne doivent pas nécessairement être ressuscitables.

### B. Fossiles d’évolution ancestrale — validé

- Certains fossiles servent à débloquer une forme ancienne particulière pour un animal moderne compatible.
- Ils ne servent pas à ressusciter une espèce séparée : leur fonction est de permettre une évolution spéciale.

### Principe d’équilibrage — validé

Les animaux préhistoriques ne doivent pas être automatiquement plus puissants que les animaux modernes. Les types, techniques, caractéristiques et rôles tactiques doivent préserver l’intérêt des différentes espèces.

## 7. Exploration et progression

### Validé

- L’exploration du monde et la découverte de nouvelles régions font partie du cœur du jeu.
- Les grottes constituent des zones d’exploration, de combat et de capture, avec la possibilité de trouver des fossiles, objets rares, secrets et indices narratifs.
- La progression vers des régions plus avancées permet de rencontrer des animaux plus puissants.
- Le joueur affrontera également des personnages humains possédant leurs propres équipes d’animaux.
- L’objectif narratif central est une **enquête et une exploration visant à comprendre pourquoi les animaux de l’île possèdent des pouvoirs et pourquoi ce phénomène n’est connu que sur cette île**.

### À concevoir

- Les grands défis qui rythmeront l’aventure et remplaceront les structures trop directement inspirées des jeux de capture de créatures connus.
- Les événements, objectifs et récompenses qui ouvriront l’accès aux nouvelles régions.
- Les moyens de déplacement et les éventuels raccourcis entre lieux déjà visités.

## 8. Histoire et personnages

### Validé

- L’histoire doit s’intégrer à un monde où les animaux possèdent des pouvoirs et où certains lieux conservent des traces d’un passé mystérieux.
- Le protagoniste est une personne ordinaire, éventuellement issue d’un milieu scientifique et passionnée par les animaux. Il ne s’agit pas d’un élu : sa curiosité et sa démarche d’enquête sont centrales.
- Le protagoniste se rend sur l’île avec l’intention d’explorer, d’étudier les animaux et de comprendre l’origine de leurs pouvoirs. Le chien ne déclenche donc pas la quête principale.
- Le protagoniste arrive sur l’île avec son chien, un animal ordinaire venu de l’extérieur.
- Le chien est un **compagnon permanent et non échangeable**, présent tout au long de l’aventure. Il occupe une place particulière dans l’équipe et dans la relation avec le protagoniste.
- Le chien pourrait développer un pouvoir après avoir passé un certain temps sur l’île. Ce changement constituerait un indice concret qu’un phénomène actif peut agir sur un animal après son arrivée, et que les pouvoirs ne s’expliquent peut-être pas uniquement par une caractéristique génétique des animaux nés sur l’île.
- Le changement du chien serait une découverte importante pour le protagoniste, mais pas la raison initiale de sa venue ni une explication complète du mystère.
- Les relations entre personnages, les rencontres récurrentes et les rivalités peuvent participer à l’aventure.
- Le laboratoire et la recherche sur les fossiles pourront avoir un rôle narratif.

### À concevoir

- Le nom, la personnalité, la profession exacte et l’histoire personnelle du protagoniste.
- L’espèce, la personnalité et le pouvoir du chien, ainsi que le moment précis où il commence à manifester ce pouvoir.
- Le déroulement détaillé de l’enquête, les personnages importants, les éventuelles factions, l’antagoniste et la conclusion.
- L’explication définitive du phénomène mystérieux. Aucune explication n’est validée à ce stade.

## 9. Plateforme et contraintes de réalisation

### Validé

- Le jeu est destiné à terme à une borne d’arcade.
- La jouabilité doit pouvoir reposer sur un joystick et des boutons, sans exiger de clavier ou de souris pendant le jeu.
- La compatibilité avec une éventuelle exécution sur Raspberry Pi devra être étudiée tôt, plutôt que repoussée à la fin.
- Le projet doit rester réaliste pour un développement personnel et progresser par étapes.

### À concevoir

- Le moteur et les outils de développement.
- La résolution, les dimensions des sprites, l’interface et les contrôles exacts.
- La plateforme cible définitive et la stratégie de test sur la borne.

## 10. Principes de conception

- Privilégier une expérience cohérente et réalisable plutôt que multiplier les systèmes.
- Ne pas créer de règles complexes pour couvrir des cas hypothétiques très improbables.
- Garder les décisions confirmées distinctes des propositions encore ouvertes.
- Éviter de copier directement les noms, objets, personnages, interfaces ou structures emblématiques d’autres jeux.
- Ne pas développer l’architecture technique avant d’avoir clarifié les besoins de jeu essentiels.

---

## Journal des décisions

Ce document est la source de vérité du projet pendant la première phase. Toute nouvelle décision validée sera intégrée ici, en mettant à jour la section concernée plutôt qu’en créant automatiquement un document séparé.

- **Initialisation** : nom de travail *Overland* ; monde situé à un instant donné ; passé révélé par ses vestiges ; conception centralisée dans ce document unique.
- **Durée cible** : environ 15 à 20 heures pour l’aventure principale et l’exploration associée, avec un développement progressif à partir d’une première portion jouable.
- **Cadre et mystère** : grande île connue de longue date, célèbre pour ses animaux dotés de pouvoirs ; l’enquête principale cherche à comprendre l’origine et la spécificité insulaire du phénomène. L’hypothèse d’une météorite reste une piste non validée.
- **Protagoniste et chien** : protagoniste ordinaire venu enquêter ; chien venu de l’extérieur et compagnon permanent non échangeable. Le développement d’un pouvoir chez le chien après son arrivée est une piste narrative destinée à révéler que le phénomène pourrait agir activement sur les animaux.
- **Capture et stockage** : appareil technologique unique, charges consommables à chaque tentative, capacité de transport de six animaux et stockage distant pour les captures supplémentaires.
