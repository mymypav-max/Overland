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
- Le monde reste reconnaissable et proche du nôtre dans ses paysages et ses lieux habités.
- Le cadre principal est une **grande île connue depuis longtemps dans le monde entier**, avec des lieux habités, des localités abandonnées, des grottes et des régions naturelles variées.
- L’île est réputée pour ses animaux : ils ressemblent à des animaux ordinaires du monde réel, mais possèdent des pouvoirs surnaturels ou élémentaires.
- Des personnes venues du monde entier — notamment des chercheurs et des explorateurs — se rendent sur l’île pour étudier ses animaux et tenter de comprendre ce phénomène.
- À ce stade, l’île est le seul endroit connu où des animaux possèdent ces pouvoirs.
- Les fossiles découverts sur l’île indiquent que des espèces préhistoriques possédaient elles aussi des pouvoirs. Cela révèle que le phénomène existait déjà dans un passé très lointain.
- **Les pouvoirs des animaux constituent le seul phénomène mystérieux établi sur l’île.** Aucun autre phénomène fantastique propre à l’île n’est actuellement défini.
- Le centre de l’île pourrait être occupé par un grand cratère laissé par l’impact d’une météorite à la fin du Crétacé, il y a environ 66 millions d’années. Cette catastrophe aurait entraîné la disparition de la civilisation ancienne et l’extinction de nombreuses espèces préhistoriques.
- Beaucoup pensent que la météorite est à l’origine des pouvoirs des animaux, mais cette explication n’a jamais pu être prouvée. La révélation finale montrera que cette croyance est erronée : les pouvoirs proviennent d’une pierre magique créée par la civilisation ancienne, qui est restée active après sa disparition.
- Les grottes et certains lieux isolés peuvent contenir des animaux sauvages, des objets, des fossiles et des indices sur l’histoire de l’île.

### Histoire ancienne et pierre — validé comme direction narrative

- Une civilisation ancienne, dotée d’une intelligence très avancée, vivait sur l’île à la fin du Crétacé.
- Cette civilisation a créé une **pierre magique** capable de conférer des pouvoirs aux animaux, notamment pour l’aider à se défendre.
- La pierre est restée active après la disparition de ses créateurs et confère encore des pouvoirs aux animaux actuels de l’île.
- Le fonctionnement exact de la pierre restera un mystère. Le récit doit révéler son rôle dans l’origine des pouvoirs, sans imposer d’explication technique ou scientifique à sa magie.
- Une météorite a frappé l’île et provoqué la catastrophe qui a entraîné la disparition de la civilisation. Le cratère central en serait le vestige. La météorite n’est toutefois **pas** la source des pouvoirs animaux.
- Le protagoniste découvrira des symboles gravés sur des ruines et/ou portés par des talismans. Ces découvertes permettront progressivement de comprendre comment déverrouiller la pierre.
- La pierre sera découverte vers le milieu de l’aventure. Le joueur comprendra alors qu’il doit retrouver **dix symboles** pour la déverrouiller, ce qui donne un objectif à long terme sans révéler trop tôt toute l’explication.
- Une fois les dix symboles réunis et saisis sur la pierre, une séquence narrative révélera l’existence de la civilisation ancienne, la fonction défensive de la pierre, la catastrophe météoritique et la véritable origine des pouvoirs animaux.

### À concevoir

- La carte, les régions, leur ordre de découverte et leurs particularités.
- La place des villes, laboratoires, ruines et autres lieux importants dans le récit.
- La répartition des dix symboles, leurs indices et la façon dont le joueur les saisit sur la pierre.
- Le contenu précis de la séquence de révélation finale et les détails de l’histoire ancienne.

## 3. Les animaux

### Validé

- Les créatures sont des **animaux reconnaissables**, enrichis de pouvoirs surnaturels ou élémentaires ; elles ne sont pas simplement des monstres abstraits.
- Les animaux rencontrés à l’état sauvage doivent tous pouvoir être capturés.
- Une capture réussie ajoute l’animal à l’équipe transportée ou au système de stockage. Aucun système d’apprivoisement préalable fondé sur la confiance n’est prévu.
- Les animaux gagnent de l’expérience et des niveaux grâce aux combats.
- Chaque espèce possède au minimum une forme jeune et une forme adulte.
- Chaque espèce a son propre niveau d’évolution. À ce niveau, l’évolution vers la forme adulte se déclenche automatiquement.
- Les espèces rencontrées dans les régions plus avancées sont généralement de niveau supérieur, afin que le joueur puisse renouveler ou renforcer son équipe sans devoir tout recommencer au niveau 1.
- Chaque animal possède un **niveau** et des **points de vie (PV)**. Son nombre de PV augmente à chaque niveau gagné ; la formule exacte reste à définir.
- Chaque animal peut connaître **quatre attaques au maximum**. Les animaux de bas niveau, notamment avant leur évolution, peuvent en connaître moins.
- Chaque attaque possède sa propre puissance destructrice, son risque d’échec (précision) et un nombre limité d’utilisations.
- Chaque espèce apprend certaines nouvelles attaques à des niveaux qui lui sont propres.
- Si un animal connaît déjà quatre attaques lorsqu’il peut en apprendre une nouvelle, le joueur peut remplacer l’une des attaques existantes par la nouvelle.

### Types élémentaires envisagés

- Feu
- Eau
- Terre / Roche
- Plante / Feuille

Cette liste initiale pourra évoluer ; elle ne fixe pas encore le tableau des forces et faiblesses.

### Règles de combat — validé

- Les combats se déroulent au tour par tour, en s’inspirant du modèle de Pokémon.
- Lors d’un combat contre un animal sauvage, le joueur joue en premier.
- Lorsqu’un animal sauvage adverse est mis KO, le combat prend fin et l’animal du joueur gagne de l’expérience.
- Pour tenter de capturer un animal sauvage, il faut soit réduire ses PV à un niveau faible, soit lui infliger un état tel que le sommeil ou l’empoisonnement. Les seuils et probabilités précis restent à concevoir.
- Contre un animal sauvage, le joueur peut choisir de changer d’animal ou de fuir. Si son animal actif est mis KO, il doit choisir un autre animal apte au combat ou fuir.
- Contre un dresseur, si l’animal actif du joueur est mis KO, le joueur doit le remplacer tant qu’il lui reste des animaux aptes au combat ; il ne peut pas fuir le combat.
- Si tous les animaux du joueur sont mis KO lors d’un combat contre un dresseur, le combat est perdu et le joueur est automatiquement renvoyé dans un centre de santé, où les PV et les utilisations des attaques de ses animaux sont restaurés.
- Si tous les animaux du dresseur adverse sont mis KO, le joueur remporte le combat et gagne de l’argent.

### À concevoir

- Les caractéristiques de combat en plus des PV : attaque, défense, vitesse et éventuelles caractéristiques supplémentaires.
- La formule de dégâts, en s’inspirant de Pokémon : dans les jeux principaux récents, elle part du niveau de l’attaquant, de la puissance de l’attaque et du rapport entre sa statistique offensive (Attaque ou Attaque spéciale) et la statistique défensive correspondante (Défense ou Défense spéciale). Les dégâts sont ensuite modifiés par différents facteurs, notamment l’efficacité du type, le bonus lié au type de l’utilisateur, les coups critiques et une variation aléatoire. La formule exacte et les facteurs retenus pour Overland restent à définir.
- L’ordre des actions pendant les combats, notamment contre les dresseurs : le choix entre un ordre déterminé par les caractéristiques des animaux (comme la vitesse), un tirage au sort ou une autre règle reste à trancher.
- La taille de l’équipe de combat et les règles détaillées de gestion de l’équipe.
- Le tableau des forces et faiblesses entre types élémentaires.
- Les effets de statut disponibles (sommeil, empoisonnement, etc.), leur durée et leur fonctionnement.
- Les conditions exactes de capture, notamment le seuil de PV et les chances de réussite selon l’état de l’animal.
- La restauration des utilisations des attaques hors combat et les objets utilisables pendant les combats.
- La répartition de l’expérience, la quantité d’expérience requise pour monter de niveau et l’éventuelle expérience accordée aux animaux mis KO.
- Le catalogue des espèces et l’équilibrage entre elles.
- Les objets permettant d’enseigner des attaques à un animal, sur un principe proche des CT/CS de Pokémon, mais avec un nombre volontairement limité de ces objets et de compétences enseignables. Leur nom, leur disponibilité et leurs règles d’utilisation restent à définir.
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
- Les règles concrètes de capture, les chances de réussite et l’animation. Le principe général peut assumer une inspiration directe de Pokémon ; il n’est pas nécessaire de réinventer cette mécanique pour elle-même.
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
- La recherche de symboles découverts sur des ruines et/ou des talismans mène à une pierre ancienne, découverte vers le milieu de l’aventure. Le joueur doit réunir dix symboles pour la déverrouiller ; leur saisie déclenche la révélation finale sur la civilisation disparue et l’origine des pouvoirs animaux.

### À concevoir

- Les grands défis qui rythmeront l’aventure et remplaceront les structures trop directement inspirées des jeux de capture de créatures connus.
- Les événements, objectifs et récompenses qui ouvriront l’accès aux nouvelles régions.
- Les moyens de déplacement et les éventuels raccourcis entre lieux déjà visités.

## 8. Histoire et personnages

### Validé

- L’histoire s’intègre à un monde où les animaux possèdent des pouvoirs et où certains lieux conservent des traces d’une civilisation ancienne. Les pouvoirs des animaux sont le seul phénomène mystérieux établi sur l’île.
- Le protagoniste est une personne ordinaire, éventuellement issue d’un milieu scientifique et passionnée par les animaux. Il ne s’agit pas d’un élu : sa curiosité et sa démarche d’enquête sont centrales.
- Le protagoniste se rend sur l’île avec l’intention d’explorer, d’étudier les animaux et de comprendre l’origine de leurs pouvoirs. Le chien ne déclenche donc pas la quête principale.
- Le protagoniste arrive sur l’île avec son chien, un animal ordinaire venu de l’extérieur. Le chien accompagne d’abord le protagoniste, puis devient progressivement l’un des animaux utilisables en combat lorsqu’il développe des pouvoirs.
- Le chien est un **compagnon permanent et non échangeable**, présent tout au long de l’aventure. Il occupe une place particulière dans l’équipe et dans la relation avec le protagoniste.
- Après avoir passé un certain temps sur l’île, le chien développe progressivement des pouvoirs. Ce changement constitue un indice concret qu’un animal né à l’extérieur peut lui aussi acquérir des pouvoirs après son arrivée sur l’île.
- Le changement du chien est un élément de découverte important pour le protagoniste, mais pas la raison initiale de sa venue ni une explication complète du mystère.
- Les relations entre personnages, les rencontres récurrentes et les rivalités peuvent participer à l’aventure.
- Le laboratoire et la recherche sur les fossiles pourront avoir un rôle narratif.

### Début de l’aventure — direction validée

- Le jeu commence **directement sur l’île, au niveau du port**, afin de montrer clairement que le protagoniste vient d’arriver.
- L’ambiance du début est calme, chaleureuse et accueillante. La présence d’animaux dotés de pouvoirs ne rend pas l’île globalement hostile ; certains lieux pourront présenter des dangers particuliers, mais l’exploration ordinaire doit rester paisible.
- Peu après son arrivée, le protagoniste peut appeler son père pour lui confirmer qu’il est arrivé et qu’il va commencer à enquêter sur le mystère des pouvoirs animaux. D’autres appels pourront ponctuer l’aventure afin de lui raconter les découvertes du protagoniste.
- Une personne travaillant dans le domaine scientifique attend le protagoniste au port. Ils ont déjà communiqué par téléphone ou messagerie avant le voyage, et ce contact l’a aidé à préparer son séjour.
- Ce contact travaille dans un laboratoire ou en est responsable. **Le laboratoire se trouve dans une ville que le joueur découvrira plus tard** : il ne fait donc pas partie du lieu de départ et n’est pas visité au début de l’aventure.
- Le contact scientifique aide le protagoniste à prendre ses premiers repères et à commencer l’exploration. La première destination exacte après le port reste à définir.

### À concevoir

- Le nom, la personnalité, la profession exacte et l’histoire personnelle du protagoniste.
- L’espèce, la personnalité et les pouvoirs du chien, ainsi que le rythme et le moment précis de leur apparition.
- Le déroulement détaillé de l’enquête, les personnages importants, les éventuelles factions, l’antagoniste et la conclusion.
- Les détails précis de la civilisation ancienne et de la séquence finale, sans chercher à expliquer le fonctionnement magique de la pierre.

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
- Assumer les inspirations de game design issues de jeux de référence, notamment Pokémon pour la capture et les combats, sans chercher à réinventer systématiquement des mécaniques éprouvées. Préserver l’identité propre d’Overland dans son univers, ses animaux, son exploration, sa narration et la présentation de ses systèmes ; éviter la reprise directe d’éléments distinctifs tels que les noms, personnages ou habillages emblématiques.
- Ne pas développer l’architecture technique avant d’avoir clarifié les besoins de jeu essentiels.

---

## Journal des décisions

Ce document est la source de vérité du projet pendant la première phase. Toute nouvelle décision validée sera intégrée ici, en mettant à jour la section concernée plutôt qu’en créant automatiquement un document séparé.

- **Initialisation** : nom de travail *Overland* ; monde situé à un instant donné ; passé révélé par ses vestiges ; conception centralisée dans ce document unique.
- **Durée cible** : environ 15 à 20 heures pour l’aventure principale et l’exploration associée, avec un développement progressif à partir d’une première portion jouable.
- **Cadre et mystère** : grande île connue de longue date, célèbre pour ses animaux dotés de pouvoirs. Ces pouvoirs sont le seul phénomène mystérieux établi sur l’île.
- **Civilisation ancienne et pierre** : direction narrative validée. Une civilisation à l’intelligence très avancée vivait sur l’île à la fin du Crétacé. Elle a créé une pierre magique pour conférer des pouvoirs aux animaux et se défendre. La pierre est restée active après la disparition de la civilisation, lors d’une catastrophe provoquée par une météorite il y a environ 66 millions d’années. Le cratère au centre de l’île est le vestige supposé de l’impact ; contrairement à la croyance commune, la météorite n’est pas la source des pouvoirs.
- **Symboles et révélation** : le joueur découvre la pierre vers le milieu de l’aventure, puis apprend qu’il doit réunir dix symboles trouvés sur des ruines et/ou des talismans. Leur saisie déverrouille la pierre et déclenche une séquence révélant l’histoire de la civilisation, la catastrophe et le rôle de la pierre. Son fonctionnement magique restera inexpliqué.
- **Protagoniste et chien** : protagoniste ordinaire venu enquêter ; chien venu de l’extérieur et compagnon permanent non échangeable. Le chien accompagne d’abord le protagoniste, puis développe progressivement des pouvoirs et devient l’un de ses animaux de combat. Cette évolution révèle qu’un animal né hors de l’île peut acquérir des pouvoirs après son arrivée.
- **Début de l’aventure** : le jeu commence au port de l’île, dans une ambiance calme et accueillante. Le protagoniste appelle son père pour confirmer son arrivée ; d’autres appels pourront rapporter ses découvertes. Un contact scientifique déjà connu à distance l’accueille et l’a aidé à préparer son séjour. Ce contact travaille dans un laboratoire situé dans une ville qui sera découverte plus tard. La première excursion et les détails de cette introduction restent à concevoir.
- **Capture et stockage** : appareil technologique unique, charges consommables à chaque tentative, capacité de transport de six animaux et stockage distant pour les captures supplémentaires.
- **Attaques et progression des animaux** : chaque animal possède un niveau et des PV qui augmentent à chaque niveau gagné. Quatre attaques au maximum par animal, chacune ayant sa propre puissance, son risque d’échec et son nombre d’utilisations. Les animaux peuvent connaître moins d’attaques à bas niveau ; chaque espèce apprend de nouvelles attaques à des niveaux qui lui sont propres. Si les quatre emplacements sont occupés, une nouvelle attaque peut remplacer une attaque connue. Des objets d’apprentissage inspirés du principe des CT/CS de Pokémon sont envisagés, en nombre limité ; leurs détails restent à concevoir.
- **Règles de combat** : contre un animal sauvage, le joueur joue en premier ; mettre l’adversaire KO termine le combat et rapporte de l’expérience à l’animal du joueur. La capture exige des PV faibles ou un état tel que le sommeil ou l’empoisonnement. Contre un dresseur, le joueur doit remplacer tout animal KO tant qu’il en reste d’aptes au combat ; si toute son équipe est KO, il est renvoyé dans un centre de santé pour restaurer PV et utilisations d’attaques. Mettre toute l’équipe adverse KO fait gagner le combat et de l’argent. L’ordre des actions contre les dresseurs et les détails des dégâts restent à concevoir.
