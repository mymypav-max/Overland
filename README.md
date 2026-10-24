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
- La pierre sera découverte vers le milieu de l’aventure, et non à la fin. Le joueur comprendra alors qu’il doit retrouver **dix symboles** pour la déverrouiller, ce qui donne un objectif à long terme sans révéler trop tôt toute l’explication.
- La piste narrative retenue pour sa découverte est que la pierre est dissimulée derrière une roche et des restes fossilisés d’un ou plusieurs membres de la civilisation ancienne, qui se seraient sacrifiés pour la protéger et la cacher lors de la catastrophe. Des parties de ces restes auraient déjà été étudiées par les scientifiques, mais leur disposition d’ensemble aurait été interprétée comme une formation naturelle ou des fossiles atypiques sans que leur rôle soit compris.
- Une fois les dix symboles réunis et saisis sur la pierre, une séquence narrative révélera l’existence de la civilisation ancienne, la fonction défensive de la pierre, la catastrophe météoritique et la véritable origine des pouvoirs animaux.

### À concevoir

- La carte, les régions, leur ordre de découverte et leurs particularités.
- La place des villes, laboratoires, ruines et autres lieux importants dans le récit.
- La répartition des dix symboles, leurs indices et la façon dont le joueur les saisit sur la pierre.
- Les espèces compatibles avec la capacité de terrain permettant de briser les rochers et certains obstacles rocheux. Environ cinq à six espèces pourraient l’utiliser, afin de conserver une petite énigme d’exploration sans rendre une espèce unique indispensable. La liste des espèces et le nom de la capacité restent à définir.
- Le contenu précis de la séquence de révélation finale et les détails de l’histoire ancienne.

## 3. Les animaux

### Validé

- Les créatures sont des **animaux reconnaissables**, enrichis de pouvoirs surnaturels ou élémentaires ; elles ne sont pas simplement des monstres abstraits.
- Les animaux rencontrés à l’état sauvage doivent tous pouvoir être capturés.
- Une capture réussie ajoute l’animal à l’équipe transportée ou au système de stockage. Aucun système d’apprivoisement préalable fondé sur la confiance n’est prévu.
- Les animaux gagnent de l’expérience et des niveaux grâce aux combats.
- Chaque lignée animale possède au minimum un stade jeune et un stade adulte. L’évolution peut être une maturation de la même espèce (par exemple : jeune loutre → loutre adulte) ou, dans certains cas fantastiques explicitement conçus comme tels, une transformation vers une autre forme animale (par exemple : chat Bengal → tigre du Bengale).
- Chaque lignée a son propre niveau d’évolution. À ce niveau, le passage au stade adulte ou à la forme évoluée se déclenche automatiquement.
- Une évolution standard au sein de la même espèce peut principalement améliorer les caractéristiques (notamment les PV) et renforcer certaines compétences, sans exiger un changement radical de silhouette ou d’espèce.
- Les espèces rencontrées dans les régions plus avancées sont généralement de niveau supérieur, afin que le joueur puisse renouveler ou renforcer son équipe sans devoir tout recommencer au niveau 1.
- Chaque animal possède un **niveau** et des **points de vie (PV)**. Son nombre de PV augmente à chaque niveau gagné ; la formule exacte reste à définir.
- Chaque animal peut connaître **quatre attaques au maximum**. Les animaux de bas niveau, notamment avant leur évolution, peuvent en connaître moins.
- Chaque attaque possède sa propre puissance destructrice, son risque d’échec (précision) et un nombre limité d’utilisations.
- Chaque espèce apprend certaines nouvelles attaques à des niveaux qui lui sont propres.
- Si un animal connaît déjà quatre attaques lorsqu’il peut en apprendre une nouvelle, le joueur peut remplacer l’une des attaques existantes par la nouvelle.

### Familles de compétences — principe de conception

Les compétences seront réparties entre deux grandes familles :
- **Compétences élémentaires** : associées à un type élémentaire validé.
- **Compétences communes** (nom provisoire, éventuellement appelées « classiques ») : sans affiliation élémentaire, elles représentent notamment des actions physiques ou des capacités animales qu’une diversité d’espèces peut maîtriser, indépendamment de leur type élémentaire.

Par exemple, **Charge** peut être accessible à de nombreuses espèces différentes, comme dans Pokémon, tandis que **Morsure** dépendra de la capacité de l’animal à mordre. Certaines compétences communes pourront être connues dès le départ par certaines espèces ou apprises au fil de la progression. Leur attribution dépendra de la morphologie et de la conception de chaque espèce, et non de son seul type élémentaire.

**À concevoir : catalogue des compétences communes.** Charge et Morsure sont les deux premiers exemples identifiés, mais la liste devra être développée pour couvrir d’autres actions physiques et capacités animales. Le catalogue, le nom définitif de cette famille, les conditions d’apprentissage et les espèces pouvant apprendre chaque compétence restent à définir.

### Types élémentaires — base retenue et classification à poursuivre

Les sept types suivants constituent la base retenue pour la classification d’Overland :
- Feu
- Eau
- Sol
- Plante
- Combat
- Roche
- Électrique

Les types **Glace**, **Air**, **Poison**, **Psy**, **Ténèbres** et **Dragon** sont également validés. La liste des types reste ouverte tant que les autres candidats n’ont pas été examinés. Le type **Insecte** a été examiné et écarté : il décrit avant tout une famille biologique et risquerait de faire doublon avec Plante, Poison ou Combat selon les pouvoirs attribués à l’animal. Les insectes restent bien entendu admissibles dans le catalogue animalier. Le type **Normal** a également été examiné et écarté : les attaques physiques ou instinctives classiques (par exemple morsure ou charge) doivent pouvoir être apprises par des animaux de n’importe quel type, sans être réservées à un type Normal. Le type **Acier** a lui aussi été examiné et écarté : il correspond mal à la typologie des espèces d’Overland et risquerait de faire doublon avec Roche. Le type **Fée** a également été examiné et écarté, car il ne correspond pas à la typologie des espèces animales et de leurs pouvoirs envisagée pour Overland.

Principes de conception retenus :
- Le type principal d’un animal doit être intuitivement lié à sa nature, à son milieu de vie ou à ses caractéristiques naturelles. Par exemple, l’hippocampe et le poisson-lune semblent naturellement relever du type Eau.
- La répartition des espèces entre les types principaux devra être raisonnablement équilibrée, sans imposer artificiellement des effectifs strictement identiques si cela nuit à la cohérence de la classification.
- Le statut de chaque type — principal, secondaire ou éventuellement les deux — sera déterminé à partir des compétences qui lui seront associées. Psy, Ténèbres et Dragon sont envisagés comme des types exclusivement secondaires ; Poison pourrait l’être également, mais cela reste incertain. Ces orientations sont provisoires et devront être confirmées après la conception des compétences. Le fait que certains types soient exclusivement secondaires ne signifie pas que tous les autres seront exclusivement principaux : parmi les autres types, certains pourront être principaux, secondaires, ou remplir les deux rôles.
- Pour la phase actuelle de conception, viser environ **dix compétences par type élémentaire**. Ce volume est un objectif provisoire, pas une limite définitive : il pourra être ajusté lorsque la conception des systèmes de combat, des espèces et de leur progression sera plus complète. Le fait que certains types soient exclusivement secondaires ne signifie pas que tous les autres seront exclusivement principaux : parmi les autres types, certains pourront être principaux, secondaires, ou remplir les deux rôles.
- Le système pourra permettre à certains animaux d’avoir un **type principal et un type secondaire**. Le second type vise avant tout à élargir la palette de compétences accessibles à l’animal ; il ne doit pas automatiquement le rendre plus puissant ni augmenter ses statistiques. Les associations envisagées restent à étudier individuellement ; par exemple, ours polaire : Eau en type principal et Glace en type secondaire ; éléphant : Sol en type principal et éventuellement Psy en type secondaire. Ces exemples sont des pistes, pas des affectations définitivement validées.
- Les autres types possibles, les affectations de chaque espèce et le tableau des forces et faiblesses restent à concevoir.

### Compétences de type Feu — première sélection de conception

Le principe d’une première sélection d’environ dix compétences de type Feu inspirées de Pokémon est validé pour la phase de conception. Cette sélection reste provisoire : les compétences, leurs effets et leurs valeurs seront réévalués lorsque le système de combat sera plus précis.

Liste de travail actuelle (neuf compétences pour le moment) :
- Flammèche
- Roue de Feu
- Crocs Feu
- Poing de Feu
- Lance-Flammes
- Déflagration
- Canicule
- Nitrocharge
- Boutefeu

Feu Follet a été retirée de la sélection actuelle, car son rôle de compétence de statut centrée sur la brûlure risquait de faire doublon avec les brûlures persistantes que d’autres compétences peuvent provoquer et avec les dégâts persistants de Canicule. La sélection compte donc provisoirement neuf compétences ; le nombre cible d’environ dix reste indicatif, et une éventuelle compétence de remplacement pourra être envisagée plus tard.

Roue de Feu et Nitrocharge sont toutes deux conservées, avec des rôles distincts : Roue de Feu met l’accent sur l’impact enflammé, tandis que Nitrocharge privilégie la charge et la mobilité, avec une éventuelle amélioration de la vitesse de l’utilisateur à examiner lors de la conception détaillée. Crocs Feu et Poing de Feu sont des attaques physiques accessibles selon la morphologie de l’animal : la première nécessite de pouvoir mordre, la seconde de pouvoir frapper avec un membre adapté. Leur rôle envisagé est de causer des dégâts directs modestes et de pouvoir provoquer une brûlure persistante. Une brûlure infligeant des dégâts pendant plusieurs tours pourra être provoquée par plusieurs compétences, mais pas nécessairement de façon systématique ; les compétences capables de provoquer cet état, les conditions d’application, sa durée et ses effets exacts restent à définir ultérieurement. Pour Canicule, les principes suivants sont validés : la vague de chaleur qu’elle déclenche améliore les compétences de l’animal qui l’a lancée, affecte négativement les compétences de l’animal qui la subit et inflige des dégâts à chaque tour tant qu’elle persiste. Les moyens de dissiper cet effet, les compétences et types affectés, la durée et les valeurs numériques restent à concevoir. Tornade a été citée uniquement comme exemple possible de contre, sans décision à ce stade.

### Règles de combat — validé

- Les combats se déroulent au tour par tour, en s’inspirant du modèle de Pokémon.
- Lors d’un combat contre un animal sauvage, le joueur joue en premier.
- Lorsqu’un animal sauvage adverse est mis KO, le combat prend fin et l’animal du joueur gagne de l’expérience.
- Pour tenter de capturer un animal sauvage, il faut soit réduire ses PV à un niveau faible, soit lui infliger un état tel que le sommeil ou l’empoisonnement. Les seuils et probabilités précis restent à concevoir.
- Contre un animal sauvage, le joueur peut choisir de changer d’animal ou de fuir. Si son animal actif est mis KO, il doit choisir un autre animal apte au combat ou fuir.
- Contre un dresseur, si l’animal actif du joueur est mis KO, le joueur doit le remplacer tant qu’il lui reste des animaux aptes au combat ; il ne peut pas fuir le combat.
- Si tous les animaux du joueur sont mis KO lors d’un combat contre un dresseur, le combat est perdu et le joueur est automatiquement renvoyé dans un centre de santé, où les PV et les utilisations des attaques de ses animaux sont restaurés.
- Si tous les animaux du dresseur adverse sont mis KO, le joueur remporte le combat et gagne de l’argent.

### Caractéristiques des animaux — validé

Chaque animal possède six caractéristiques de combat :

- **PV** : quantité de dégâts que l’animal peut subir avant d’être mis KO.
- **Attaque** : utilisée pour calculer les dégâts des attaques physiques.
- **Défense** : utilisée pour calculer les dégâts subis des attaques physiques.
- **Attaque spéciale** : utilisée pour calculer les dégâts des attaques spéciales.
- **Défense spéciale** : utilisée pour calculer les dégâts subis des attaques spéciales.
- **Vitesse** : caractéristique disponible pour le système de combat ; son éventuel rôle dans l’ordre des actions reste à décider.

Les PV augmentent à chaque niveau gagné. La formule exacte d’évolution des PV et des autres caractéristiques avec le niveau reste à concevoir.

### À concevoir

- La formule de dégâts retenue comme base de conception est celle de la troisième génération de Pokémon (notamment Rouge Feu / Vert Feuille), adaptée au modèle d’Overland : niveau de l’attaquant, puissance de l’attaque et caractéristiques offensives et défensives correspondantes. La catégorie physique ou spéciale sera déterminée attaque par attaque, plutôt que par le type élémentaire. Les modificateurs retenus et les valeurs numériques restent à préciser et à tester.
- L’ordre des actions pendant les combats, notamment contre les dresseurs : le choix entre un ordre déterminé par les caractéristiques des animaux (comme la vitesse), un tirage au sort ou une autre règle reste à trancher.
- La taille de l’équipe de combat et les règles détaillées de gestion de l’équipe.
- Le tableau des forces et faiblesses entre types élémentaires.
- Les effets de statut disponibles (sommeil, empoisonnement, etc.), leur durée et leur fonctionnement.
- Les conditions exactes de capture, notamment le seuil de PV et les chances de réussite selon l’état de l’animal.
- La restauration des utilisations des attaques hors combat et les objets utilisables pendant les combats.
- La répartition de l’expérience, la quantité d’expérience requise pour monter de niveau et l’éventuelle expérience accordée aux animaux mis KO.
- Le catalogue détaillé des espèces et l’équilibrage entre elles. L’objectif provisoire est de viser environ **40 à 60 espèces de base**, chaque espèce possédant au minimum une forme jeune et une forme adulte, soit environ 80 à 120 formes avant les éventuelles formes spéciales. Ce volume est un objectif de conception, pas une limite définitive.
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
- Des fossiles spécifiques pourront débloquer une forme ancienne pour certains animaux modernes compatibles. La lignée chat Bengal (forme jeune) → tigre du Bengale (forme adulte) pourra accéder à une forme ancestrale spéciale inspirée du Smilodon grâce à un fossile approprié. Il s’agit d’une transformation fictive, pas d’une affirmation selon laquelle le Smilodon serait l’ancêtre direct du tigre.
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
- Exemples de candidats à la résurrection : Vélociraptor et **Psittacosaurus**. Le Psittacosaurus est retenu à la place du Ptéranodon dans la liste de travail des espèces à ressusciter ; il s’agit d’un petit dinosaure herbivore à bec.
- Toutes les espèces éteintes ne doivent pas nécessairement être ressuscitables. L’objectif provisoire est d’en sélectionner au moins six ou sept.

### B. Fossiles d’évolution ancestrale — validé

- Certains fossiles servent à débloquer une forme ancienne particulière pour un animal moderne compatible.
- Ils ne servent pas à ressusciter une espèce séparée : leur fonction est de permettre une évolution spéciale.
- Associations proposées pour ce système : **cerf élaphe → forme inspirée du Mégalocéros**, **requin blanc → forme inspirée du Mégalodon**, et **bec-en-sabot du Nil → forme inspirée du Ptéranodon**. Ces transformations sont des choix fantastiques de conception, pas des affirmations d’ascendance biologique.

### Principe d’équilibrage — validé

Les animaux préhistoriques ne doivent pas être automatiquement plus puissants que les animaux modernes. Les types, techniques, caractéristiques et rôles tactiques doivent préserver l’intérêt des différentes espèces.

## 7. Catalogue animalier — propositions en cours

> **Statut : catalogue de travail, non validé dans son ensemble.** Les espèces ci-dessous sont des candidates issues des échanges de conception. Leur présence dans cette liste ne signifie pas qu’elles sont définitivement retenues. Les choix explicitement approuvés sont signalés séparément. Le catalogue pourra dépasser l’objectif initial de 40 à 60 espèces si la variété obtenue le justifie.

### A. Animaux modernes — pistes

Chaque lignée retenue devra avoir au minimum un stade jeune et un stade adulte. Dans de nombreux cas, il s’agira simplement du même animal à deux âges différents : par exemple, une jeune loutre évolue en loutre adulte, avec davantage de PV et certaines compétences plus puissantes. Une transformation vers une autre espèce, comme chat Bengal → tigre du Bengale, reste une exception fantastique à assumer explicitement. Les pouvoirs, attaques, niveaux d’évolution et habitats restent à concevoir individuellement.

**Mammifères**
- Maine Coon — lignée féline distincte, avec une forme jeune de chaton Maine Coon puis une forme adulte Maine Coon.
- Chat Bengal → tigre du Bengale : lignée unique dont la forme jeune est un chat Bengal et la forme adulte un tigre du Bengale. Cette transformation fantastique est assumée ; le tigre du Bengale n’est pas compté comme une lignée de base séparée.
- Chien de type dogue du Tibet — inspiration possible pour une lignée de chien puissante.
- Renard roux.
- Renard polaire.
- Lion.
- Léopard des neiges.
- Ours brun — espèce compatible avec la capacité de terrain permettant de briser certains rochers.
- Rhinocéros — lignée ajoutée au catalogue de travail : la forme jeune est un bébé rhinocéros et la forme adulte un rhinocéros. Il est compatible avec la capacité de terrain Brise-Roc.
- Éléphant d’Afrique — lignée ajoutée au catalogue de travail : la forme jeune est un éléphanteau et la forme adulte un éléphant d’Afrique. Il est compatible avec la capacité de terrain Brise-Roc et peut accéder à une forme ancestrale spéciale inspirée du mammouth laineux.
- Kangourou roux.
- Capybara.
- Rat brun.
- Écureuil roux.
- Tatou à neuf bandes.
- Pangolin indien.
- Cerf élaphe — candidat lié à une évolution ancestrale inspirée du Mégalocéros.
- Sanglier — espèce compatible avec la capacité de terrain permettant de briser certains rochers.
- Macaque → gorille — lignée candidate au catalogue de travail : la forme jeune est un macaque et la forme adulte un gorille. Cette évolution fantastique est retenue comme direction de conception, sans prétention de réalisme zoologique.
- Hippopotame — nouvelle lignée ajoutée au catalogue de travail, avec une forme jeune de bébé hippopotame évoluant en hippopotame adulte. Cette lignée est compatible avec la capacité de terrain permettant de briser certains rochers.
- Panda roux.
- Ornithorynque.
- Loutre — candidate retenue ; progression standard d’une jeune loutre vers une loutre adulte plus puissante, sans changement d’espèce.

**Oiseaux**
- Pigeon biset.
- Pie bavarde.
- Aigle royal.
- Chouette effraie.
- Casoar à casque.
- Bec-en-sabot du Nil — candidat lié à une évolution ancestrale inspirée du Ptéranodon.

**Reptiles et autres animaux à sang froid**
- Iguane vert.
- Dragon de Komodo.
- Cobra royal.
- **Crocodile du Nil — espèce candidate retenue** pour remplacer le python vert arboricole.
- Tortue alligator.

**Animaux aquatiques et marins**
- Carpe koï.
- Anguille électrique.
- Poisson-lune.
- Méduse à crinière de lion.
- **Poulpe géant du Pacifique — piste explicitement conservée.**
- Hippocampe.
- Requin blanc — candidat lié à une évolution ancestrale inspirée du Mégalodon.
- Orque.

**Invertébrés**
- **Mante religieuse géante — piste conservée**, avec une forme adulte fantastiquement plus grande que l’animal réel.

Le python vert arboricole est écarté afin d’éviter deux lignées de serpents ; le crocodile du Nil est retenu comme espèce candidate à sa place. Le crabe-araignée géant a été évoqué, mais reste à réévaluer : la place globale des invertébrés dans le catalogue n’est pas encore convaincante. L’axolotl a été écarté. Le papillon Atlas n’est pas retenu dans cette liste de travail à ce stade.

### B. Espèces préhistoriques — candidates à la résurrection

Ces espèces seraient obtenues sous forme jeune grâce à un fossile et au laboratoire, puis progresseraient selon les règles générales.

- Vélociraptor.
- Tricératops.
- Stégosaure.
- Tyrannosaure.
- **Psittacosaurus — candidat explicitement retenu**, en remplacement du Ptéranodon dans la liste de résurrection.
- Mégathérium — candidat retenu pour remplacer le mammouth laineux dans la liste de résurrection.
- **Dunkleosteus — septième espèce de résurrection retenue**, notamment pour introduire un animal préhistorique aquatique dans le catalogue. Son habitat de rencontre envisagé est constitué des zones côtières.

Le Smilodon est réservé à l’évolution ancestrale spéciale de la lignée chat Bengal → tigre du Bengale ; il n’est pas compté comme candidat à la résurrection. Le mammouth laineux est réservé à une éventuelle évolution ancestrale de l’éléphant et n’est donc pas candidat à la résurrection.

Les sept espèces de résurrection retenues à ce stade sont le Vélociraptor, le Tricératops, le Stégosaure, le Tyrannosaure, le Psittacosaurus, le Mégathérium et le Dunkleosteus. Le Dunkleosteus apporte une espèce préhistorique aquatique à cette sélection ; son habitat de rencontre est fixé aux zones côtières. Le Mégalocéros est pour l’instant associé à une évolution ancestrale du cerf élaphe, et le Ptéranodon à une évolution ancestrale du bec-en-sabot ; ils ne sont donc pas comptés ici comme espèces de résurrection retenues.

### C. Évolutions ancestrales liées aux fossiles — associations proposées

Ces transformations sont fantastiques et ne supposent pas une relation d’ascendance biologique directe. Elles constituent des pistes de conception, pas encore un catalogue définitif.

- Chat Bengal (forme jeune) → tigre du Bengale (forme adulte) → Smilodon (forme ancestrale spéciale débloquée par fossile). Le Smilodon est donc associé à la lignée du tigre du Bengale, et non retenu comme candidat distinct à la résurrection.
- Éléphant d’Afrique (forme adulte) → forme ancestrale inspirée du mammouth laineux, débloquée par un fossile spécifique (association retenue ; le mammouth est réservé à cette évolution ancestrale et ne sera pas ressuscité séparément).
- Ours brun → Arctodus (forme ancestrale retenue, inspirée de l’ours à face courte ; transformation fantastique, sans relation d’ascendance directe affirmée).
- Cerf élaphe → forme inspirée du Mégalocéros.
- Requin blanc → forme inspirée du Mégalodon.
- Bec-en-sabot du Nil → forme inspirée du Ptéranodon.

Une forme spéciale reste rattachée à sa lignée moderne compatible ; elle ne compte pas automatiquement comme une espèce de base supplémentaire. D’autres associations pourront être proposées après validation des lignées modernes et des espèces préhistoriques.

### D. Principes de sélection du catalogue

- Privilégier des animaux réels reconnaissables et visuellement distincts, plutôt que de multiplier des espèces très similaires.
- Des espèces moins communes ou plus singulières peuvent être préférées à des choix génériques lorsque cela enrichit le catalogue.
- Une évolution standard peut représenter simplement le passage du stade jeune au stade adulte de la même espèce, avec une hausse des PV et le renforcement de certaines compétences.
- Les transformations fantastiques vers une autre espèce ou vers une forme ancestrale restent possibles, mais doivent être identifiées comme des exceptions propres à certaines lignées.
- Les formes évoluées peuvent devenir plus grandes, changer nettement de silhouette ou s’inspirer de créatures légendaires, à condition de conserver un lien visuel lisible avec l’animal de départ.
- Le jeu n’a pas vocation à être une encyclopédie scientifique : certaines évolutions et associations fossiles peuvent être librement fantastiques.
- La répartition par habitat doit rester cohérente quand cela améliore la lisibilité du monde, sans imposer un réalisme écologique strict à chaque rencontre.
- Les espèces, évolutions, attaques, pouvoirs et équilibres restent à valider individuellement.

## 8. Exploration et progression

### Validé

- L’exploration du monde et la découverte de nouvelles régions font partie du cœur du jeu.
- La capacité de terrain **Brise-Roc** permet de briser certains rochers et obstacles rocheux afin de libérer des passages dans l’aventure. Elle permettra également de dégager la roche et les restes fossilisés qui dissimulent la Pierre. Six lignées sont retenues comme compatibles avec cette capacité : rhinocéros, ours brun, éléphant d’Afrique, sanglier, macaque → gorille (forme adulte) et bébé hippopotame → hippopotame adulte. Chaque espèce l’exécute d’une manière adaptée à sa force physique.
- Lorsqu’il examine un obstacle rocheux bloquant un passage, le protagoniste peut penser : « Hmm… Je pense qu’on pourrait briser ces rochers. » Devant la roche et les fossiles qui dissimulent la Pierre, le message est plus énigmatique : « Ces roches semblent cacher quelque chose… Je me demande si on pourrait les briser. » Ces messages suggèrent qu’une action est possible sans nommer directement Brise-Roc ni révéler l’animal requis. Le déclenchement exact du message reste à préciser.
- Plusieurs espèces pourront utiliser cette capacité, mais leur nombre restera limité : environ cinq à six espèces sont envisagées, afin que trouver un animal compatible constitue une petite énigme d’exploration sans rendre une seule espèce indispensable. Les espèces compatibles et le nom de la capacité restent à définir.
- Les grottes constituent des zones d’exploration, de combat et de capture, avec la possibilité de trouver des fossiles, objets rares, secrets et indices narratifs.
- La progression vers des régions plus avancées permet de rencontrer des animaux plus puissants.
- Le joueur affrontera également des personnages humains possédant leurs propres équipes d’animaux.
- L’objectif narratif central est une **enquête et une exploration visant à comprendre pourquoi les animaux de l’île possèdent des pouvoirs et pourquoi ce phénomène n’est connu que sur cette île**.
- La recherche de symboles découverts sur des ruines et/ou des talismans mène à une pierre ancienne, découverte vers le milieu de l’aventure. Le joueur doit réunir dix symboles pour la déverrouiller ; leur saisie déclenche la révélation finale sur la civilisation disparue et l’origine des pouvoirs animaux.

### À concevoir

- Les grands défis qui rythmeront l’aventure et remplaceront les structures trop directement inspirées des jeux de capture de créatures connus.
- Les événements, objectifs et récompenses qui ouvriront l’accès aux nouvelles régions.
- Les moyens de déplacement et les éventuels raccourcis entre lieux déjà visités.

## 9. Histoire et personnages

### Validé

- L’histoire s’intègre à un monde où les animaux possèdent des pouvoirs et où certains lieux conservent des traces d’une civilisation ancienne. Les pouvoirs des animaux sont le seul phénomène mystérieux établi sur l’île.
- Le protagoniste est une personne ordinaire, éventuellement issue d’un milieu scientifique et passionnée par les animaux. Il ne s’agit pas d’un élu : sa curiosité et sa démarche d’enquête sont centrales.
- Le protagoniste se rend sur l’île avec l’intention d’explorer, d’étudier les animaux et de comprendre l’origine de leurs pouvoirs. Le chien ne déclenche donc pas la quête principale.
- Le protagoniste arrive sur l’île avec son chien, un animal ordinaire venu de l’extérieur. Le chien accompagne d’abord le protagoniste, puis devient progressivement l’un des animaux utilisables en combat lorsqu’il développe des pouvoirs.
- Le chien est un **compagnon permanent et non échangeable**, présent tout au long de l’aventure. Il occupe une place particulière dans l’équipe et dans la relation avec le protagoniste.
- Après avoir passé un certain temps sur l’île, le chien développe progressivement des pouvoirs. Ce changement constitue un indice concret qu’un animal né à l’extérieur peut lui aussi acquérir des pouvoirs après son arrivée sur l’île.
- Le changement du chien est un élément de découverte important pour le protagoniste, mais pas la raison initiale de sa venue ni une explication complète du mystère.
- Lorsqu’il arrive devant le site où la pierre est dissimulée derrière la roche et les restes fossilisés de membres de la civilisation ancienne, le chien adopte un comportement inhabituel et difficile à expliquer. Comme il a déjà commencé à développer ses pouvoirs sur l’île, le protagoniste soupçonne un lien entre cette réaction, les fossiles et le phénomène des pouvoirs animaux. La réaction reste inexpliquée à ce stade et sert d’indice ; elle ne révèle pas automatiquement la pierre.
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
- La scène précise de découverte de la pierre, le comportement exact du chien et le déclenchement exact des messages d’indice face aux obstacles rocheux.
- Les détails précis de la civilisation ancienne et de la séquence finale, sans chercher à expliquer le fonctionnement magique de la pierre.

## 10. Plateforme et contraintes de réalisation

### Validé

- Le jeu est destiné à terme à une borne d’arcade.
- La jouabilité doit pouvoir reposer sur un joystick et des boutons, sans exiger de clavier ou de souris pendant le jeu.
- La compatibilité avec une éventuelle exécution sur Raspberry Pi devra être étudiée tôt, plutôt que repoussée à la fin.
- Le projet doit rester réaliste pour un développement personnel et progresser par étapes.

### À concevoir

- Le moteur et les outils de développement.
- La résolution, les dimensions des sprites, l’interface et les contrôles exacts.
- La plateforme cible définitive et la stratégie de test sur la borne.

## 11. Principes de conception

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
- **Symboles et révélation** : le joueur découvre la pierre vers le milieu de l’aventure, puis apprend qu’il doit réunir dix symboles trouvés sur des ruines et/ou des talismans. Leur saisie déverrouille la pierre et déclenche une séquence révélant l’histoire de la civilisation, la catastrophe et le rôle de la pierre. Son fonctionnement magique restera inexpliqué. La piste retenue pour sa découverte est que la pierre est dissimulée derrière une roche et des restes fossilisés d’un ou plusieurs membres de la civilisation ancienne, qui se seraient sacrifiés pour la protéger et la cacher lors de la catastrophe. Des fragments auraient déjà été étudiés sans que leur disposition et leur rôle soient compris. Le chien, qui a déjà commencé à développer ses pouvoirs, réagit de manière inhabituelle devant le site et pousse le protagoniste à s’y intéresser ; cette réaction reste inexpliquée et sert d’indice. Une capacité de terrain unique, fondée sur la force physique des animaux, permettra de briser certains rochers et obstacles rocheux pour libérer des passages et dégager la roche qui dissimule la Pierre. Environ cinq à six espèces compatibles sont envisagées : le joueur devra découvrir un animal capable de l’utiliser, sans qu’une seule espèce soit indispensable. Le nom de la capacité et la liste des espèces compatibles restent à définir.
- **Protagoniste et chien** : protagoniste ordinaire venu enquêter ; chien venu de l’extérieur et compagnon permanent non échangeable. Le chien accompagne d’abord le protagoniste, puis développe progressivement des pouvoirs et devient l’un de ses animaux de combat. Cette évolution révèle qu’un animal né hors de l’île peut acquérir des pouvoirs après son arrivée.
- **Début de l’aventure** : le jeu commence au port de l’île, dans une ambiance calme et accueillante. Le protagoniste appelle son père pour confirmer son arrivée ; d’autres appels pourront rapporter ses découvertes. Un contact scientifique déjà connu à distance l’accueille et l’a aidé à préparer son séjour. Ce contact travaille dans un laboratoire situé dans une ville qui sera découverte plus tard. La première excursion et les détails de cette introduction restent à concevoir.
- **Capture et stockage** : appareil technologique unique, charges consommables à chaque tentative, capacité de transport de six animaux et stockage distant pour les captures supplémentaires.
- **Attaques et progression des animaux** : chaque animal possède un niveau et des PV qui augmentent à chaque niveau gagné. Quatre attaques au maximum par animal, chacune ayant sa propre puissance, son risque d’échec et son nombre d’utilisations. Les animaux peuvent connaître moins d’attaques à bas niveau ; chaque espèce apprend de nouvelles attaques à des niveaux qui lui sont propres. Si les quatre emplacements sont occupés, une nouvelle attaque peut remplacer une attaque connue. Des objets d’apprentissage inspirés du principe des CT/CS de Pokémon sont envisagés, en nombre limité ; leurs détails restent à concevoir.
- **Familles de compétences** : distinguer les compétences élémentaires, associées à un type, des compétences communes (nom provisoire), sans affiliation élémentaire et accessibles à différentes espèces indépendamment de leur type. Charge peut convenir à de nombreuses espèces ; Morsure dépendra de la morphologie. Certaines compétences communes pourront être connues dès le départ ou apprises pendant la progression selon l’espèce. La création d’un catalogue plus complet de compétences communes est à concevoir ; Charge et Morsure ne sont que les deux premiers exemples identifiés.
- **Volume provisoire de compétences** : viser environ dix compétences par type élémentaire pendant la phase de conception initiale. Ce nombre pourra être revu à la hausse ou à la baisse lorsque le système de combat, le catalogue des espèces et leur progression seront mieux définis. Pour le type Feu, une première sélection de conception a été établie ; elle compte actuellement neuf compétences, Feu Follet ayant été retirée car son rôle risquait de faire doublon avec les brûlures persistantes et Canicule. Le nombre d’environ dix compétences reste un objectif provisoire, et une compétence de remplacement pourra être envisagée plus tard. Roue de Feu met l’accent sur l’impact enflammé, tandis que Nitrocharge privilégie la charge et la mobilité. Crocs Feu et Poing de Feu sont des attaques physiques dont l’accès dépendra de la morphologie de l’animal ; elles pourraient infliger des dégâts directs modestes et provoquer une brûlure persistante. Une brûlure sur plusieurs tours pourra être provoquée par plusieurs compétences, sans que ce soit systématique ; les compétences concernées, les conditions d’application et les effets exacts restent à définir. Pour Canicule, les principes suivants sont validés : la vague de chaleur améliore les compétences de l’animal qui l’a lancée, affecte négativement les compétences de l’animal qui la subit et inflige des dégâts à chaque tour tant qu’elle persiste. Les moyens de dissiper cet effet, la durée, les valeurs numériques et les compétences ou types affectés restent à concevoir. Tornade a été citée uniquement comme exemple possible de contre, sans décision à ce stade.
- **Catalogue d’animaux** : objectif provisoire de 40 à 60 lignées de base. Chaque lignée possède au minimum un stade jeune et un stade adulte, généralement au sein de la même espèce, ce qui représente environ 80 à 120 formes avant les éventuelles formes spéciales. Une évolution peut principalement augmenter les PV et renforcer certaines compétences sans changer d’espèce (ex. jeune loutre → loutre adulte). Des transformations fantastiques entre espèces, comme chat Bengal → tigre du Bengale, restent des exceptions explicites. Le volume pourra être ajusté au fil de la conception.
- **Fossiles et catalogue préhistorique** : distinction confirmée entre fossiles de résurrection (qui donnent une espèce préhistorique distincte, obtenue jeune au laboratoire) et fossiles d’évolution ancestrale (qui débloquent une forme spéciale pour une espèce moderne compatible). Le Psittacosaurus remplace le Ptéranodon parmi les candidats à la résurrection ; le Mégathérium remplace le mammouth laineux dans cette liste. Le mammouth laineux est réservé à une éventuelle forme ancestrale de l’éléphant et ne serait pas ressuscité séparément. Le Smilodon est réservé à une forme ancestrale spéciale de la lignée chat Bengal → tigre du Bengale et n’est pas candidat à la résurrection. Autres associations proposées : éléphant → mammouth laineux, cerf élaphe → Mégalocéros, requin blanc → Mégalodon, bec-en-sabot du Nil → forme inspirée du Ptéranodon. L’Arctodus est retenu comme forme ancestrale de l’ours brun. Sept espèces de résurrection sont maintenant retenues : Vélociraptor, Tricératops, Stégosaure, Tyrannosaure, Psittacosaurus, Mégathérium et Dunkleosteus, associé aux zones côtières.
- **Catalogue moderne — ajustements** : la loutre est retenue comme candidate, avec une évolution standard de jeune loutre à loutre adulte plus puissante. Le python vert arboricole est écarté pour éviter deux lignées de serpents ; le crocodile du Nil est retenu comme espèce candidate à sa place. La lignée chat Bengal → tigre du Bengale est une seule lignée fantastique : chat Bengal jeune, tigre du Bengale adulte, puis forme ancestrale inspirée du Smilodon accessible par fossile. Le Maine Coon reste une lignée distincte, avec un chaton Maine Coon puis sa forme adulte. La liste des mammifères ne compte plus le tigre du Bengale séparément.
- **Capacité de terrain — briser les rochers** : une capacité unique fondée sur la force physique permettra de briser certains rochers et obstacles pour ouvrir des passages et dégager la roche qui dissimule la Pierre. Le rhinocéros, l’ours brun, l’éléphant d’Afrique et le sanglier sont des candidats retenus pour la liste des espèces compatibles ; le gorille est également retenu comme candidat à examiner. Environ cinq à six espèces compatibles sont visées, mais la liste finale reste à définir. La lignée macaque jeune → gorille adulte est retenue comme direction de conception fantastique et ajoutée au catalogue de travail. L’hippopotame est ajouté au catalogue de travail avec une évolution classique de bébé hippopotame à hippopotame adulte. Le rhinocéros est ajouté au catalogue de travail avec une évolution de bébé rhinocéros à rhinocéros adulte. L’éléphant d’Afrique est ajouté au catalogue de travail avec une évolution d’éléphanteau à éléphant adulte et une forme ancestrale spéciale inspirée du mammouth laineux, accessible grâce à un fossile spécifique ; le mammouth laineux reste réservé à cette évolution et ne sera pas ressuscité séparément. Six lignées sont retenues comme compatibles avec la capacité de terrain **Brise-Roc** : rhinocéros, ours brun, éléphant d’Afrique, sanglier, macaque → gorille et bébé hippopotame → hippopotame adulte. Chaque espèce exécute cette capacité selon sa morphologie et sa force physique. Les messages d’indice envisagés sont « Hmm… Je pense qu’on pourrait briser ces rochers. » pour les rochers bloquant un passage et « Ces roches semblent cacher quelque chose… Je me demande si on pourrait les briser. » pour l’obstacle dissimulant la Pierre ; ils suggèrent une possibilité sans donner la solution directement.
- **Classification élémentaire** : sept types constituent la base retenue : Feu, Eau, Sol, Plante, Combat, Roche et Électrique. Glace, Air, Poison, Psy, Ténèbres et Dragon sont également validés. Les types Insecte, Normal, Acier et Fée ont été examinés puis écartés. Insecte décrit avant tout une famille biologique et risque de faire doublon avec Plante, Poison ou Combat selon les pouvoirs attribués ; les insectes restent admissibles dans le catalogue animalier. Normal n’est pas retenu, car les attaques physiques ou instinctives classiques (par exemple morsure ou charge) doivent pouvoir être apprises par des animaux de n’importe quel type, sans être réservées à un type Normal. Acier correspond mal à la typologie des espèces d’Overland et risquerait de faire doublon avec Roche. Fée ne correspond pas à la typologie des espèces animales et de leurs pouvoirs envisagée pour Overland. Le statut de chaque type — principal, secondaire ou éventuellement les deux — sera déterminé à partir des compétences qui lui seront associées. Psy, Ténèbres et Dragon sont envisagés comme des types exclusivement secondaires ; Poison pourrait l’être également, mais cela reste incertain. Ces orientations sont provisoires et devront être confirmées après la conception des compétences. Le type principal doit être intuitivement lié à la nature, au milieu de vie ou aux caractéristiques naturelles de l’animal, et la répartition entre types devra être raisonnablement équilibrée. Le système pourra permettre un type secondaire pour certaines espèces, principalement afin d’élargir leur palette de compétences, sans augmenter automatiquement leur puissance ou leurs statistiques. Ours polaire (Eau principal, Glace secondaire) et éléphant (Sol principal, Psy secondaire) sont des exemples à étudier, pas des affectations définitivement validées. Les affectations de chaque espèce et le tableau des forces et faiblesses restent à concevoir.
- **Caractéristiques et règles de combat** : six caractéristiques par animal (PV, Attaque, Défense, Attaque spéciale, Défense spéciale et Vitesse). Les PV augmentent à chaque niveau gagné. Contre un animal sauvage, le joueur joue en premier ; mettre l’adversaire KO termine le combat et rapporte de l’expérience à l’animal du joueur. La capture exige des PV faibles ou un état tel que le sommeil ou l’empoisonnement. Contre un dresseur, le joueur doit remplacer tout animal KO tant qu’il en reste d’aptes au combat ; si toute son équipe est KO, il est renvoyé dans un centre de santé pour restaurer PV et utilisations d’attaques. Mettre toute l’équipe adverse KO fait gagner le combat et de l’argent. La formule de dégâts s’appuiera sur celle de Pokémon Rouge Feu / Vert Feuille, adaptée à Overland, avec une catégorie physique ou spéciale définie attaque par attaque. Les modificateurs et valeurs numériques restent à tester ; l’ordre des actions contre les dresseurs reste à concevoir.
