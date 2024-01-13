<h1> La piscine a 42</h1>

```
Les informations qui suivent datent de comment j'ai passe ma piscine en 2023, il n'est pas impossible que certaines informations ne soient plus a jour.
```

<h2> Fonctionnement global :</h2>

La piscine est un mois intensif durant lequel vous serez amenes a recontrer 16 batteries d'exercices en tout. </br>

<h3> Les days</h3>
<p> Les days (batterie d'exercices) sont propose dans un ordre (Shell 00, Shell 01, C00, C01, ...) donc pour arriver au day C05, il faut avoir realise avant les days Shell00, Shell01, C00, C01, C02, C03 et C04. Vous n'avez pas besoin de finir tous les days a la fin de la piscine pour etre pris, rares sont ceux qui y arrivent, le plus important est votre progression personnelle. Il faut plutot se concentrer sur apprendre les notions, toujours avancer, et aller aider les autres.</br>
Ces 16 batteries sont divisees sur 2 themes </br>
. Le Shell, il y 2 days a valider portant sur le Shell. Beaucoup se decouragent a ce moment la mais il ne faut pas, c'est important de comprendre le Shell avant d'avancer plus loin, ca vous permettra d'etre a l'aise plus tard sur les ordinateurs et vous serez vraiment a l'aise pendant vos autres days/projets. </br>
. Le C, il y a 14 days de C. Ils portent tous sur une notion specifique en C ou en tout cas un theme global (les pointeurs, arguments du main, les maths, les fichiers headers, structures, ...). Ces days sont de plus en plus difficiles, donc n'hesitez pas a aller demander de l'aide aux autres quand vous n'arrivez pas a resoudre un probleme, ca vous permettra surement de debloquer l'exercice mais aussi de le voir sous un nouvel angle et vous aurez appris quelque chose. </p>

<h3> Les corrections</h3>
<p> Chaque days que vous aurez finis devra etre corrige pour s'assurer de sa validite et qu'il n'y a pas d'erreur dans votre code. Pour ce faire, vous devrez etre corriges par 2 pairs, puis par un programme appele la moulinette (votre pire ennemie durant votre piscine). Chaque correction vous coute 1 point de correction, sachant que vous commencez votre piscine avec 3 ou 5 points (je ne sais plus), donc vous devrez rapidement en recuperer plus. Le systeme est bien fait, vous pourrez recuperer des points de correction en allant corriger les autres. </br>
Pour ce faire, vous devrez poser des slots de correction, puis si quelqu'un s'inscrit sur votre slot, vous aurez une notification de l'heure de correction et de sa place, pour realiser la correction.

```
POINT DE VUE DU CORRIGE :
	- Il ne faut laisser que les fichiers .c dans le repertoire final (pas de a.out, rien qui n'est pas indique 
		dans le sujet).
	- Verifiez bien avant de 'set as finished' que vous avez bien envoye la version souhaitee, a la norme, ... 
		(faites juste un git clone dans votre sgoinfre et verifiez ou faites verifier par quelqu'un a cote).
	- Faites attention a bien avoir les points avant de 'set as finished' car les 2 corrections doivent etre 
		faites dans une duree de 24h apres avoir 'set as finished'.
	- Faites les retours de commentaires juste apres la correction, sur votre PC pour ne pas avoir de soucis 
		au niveau du projet.

POINT DE VUE DU CORRECTEUR :
	- Suivez bien la fiche de correction
	- Interessez vous au code que vous avez sous les yeux et restez ouverts a de nouvelles methodes ; vous 
		apprendrez plus comme ca qu'en restant sur une seule methode de realisation.
	- Expliquez a la personne que vous corrigez ses erreurs si vous le pouvez et aidez le a s'ameliorer.
	- En cas de desaccord ou si necessaire, n'hesitez pas a demander l'aide d'une personne tierce.
	- Realisez la correction et les retours de commentaires sur les PC de 42, rapidement apres la correction 
		(le mieux est de le faire directement pendant).
```
</p>

<h3> La moulinette</h3>
J'ai parle de norme dans ce paragraphe, qu'est ce que c'est ? La norme a 42 est un ensemble de regles a suivre pour ecrire vos fichiers de code en C. Il faut suivre ces regles et effectuer regulierement la commande 'norminette' dans le terminal. Cette commande permet de verifier si les fichiers .c que vous avec dans le repertoire sont bien a la norme de 42.
<p> La moulinette est un programme qui vient checker les fichiers que vous avez rendus. Elle vient regarder s'il n'y a pas de faute de norme, mais aussi que tout compile bien et que vous respectez les regles donnees dans le sujet. Vous devrez gerer tous les cas, renvoyer les bonnes valeurs, ... Tout faire. </br>
</p>

<h3> Les exams</h3>
<p> En plus des days qui sont vos projets sur le mois en entier, vous aller rencontrer d'autres types d'evaluation ; toutes les semaines, vous allez avoir le vendredi apres-midi une evaluation de 4h sur les PC. </br>
Durant ces 4h, vous ferez face a une batterie d'exercice, de difficulte croissante, tires aleatoirement dans une banque d'exercice. Votre but est d'aller le plus loin possible, ne pas avoir 100 n'est pas une fatalite ; il faut montrer que vous maitrisez vos connaissances et que vous savez faire ce que vous avez deja rendu dans vos days. Montrer votre progression durant le mois reste le plus important. </br>
Le dernier examen est different ; il dure 8h, et vous aurez plus d'exercices a faire. C'est sur celui la qu'il faut performer, et montrer tout ce que vous savez faire.

```
Fonctionnement des examens :
-- AVANT L'EXAMEN --
	Il faut vous enregistrer a l'evenement ET au projet examen. Ne s'inscrire qu'a l'un des 2 ne suffit pas.

-- PENDANT L'EXAMEN --
	En arrivant en examen, vous serez disposes dans les clusters. Pensez a BIEN VIDER VOS POCHES (meme un 
		morceau de papier provenant d'une sucrette a cafe ne passe pas), eteindre vos telephones, ne pas avoir 
			de montre connectee, 3 feuilles de brouillon vierges et votre cartes(les regles sont tres strictes).
	Une fois l'heure de debut, pour se connecter, les logins sont :
	- exam
	- exam
Une fois connectes, il faut aller dans le terminal, et faire la commande
	examshell
pour vous enregistrer a l'examen. Vous devrez alors enregistrer vos logins personnels, et une batterie 
	d'exercices sera alors presentee.
N'oubliez pas de faire :
	git add *
	git commit -m "Votre commit"
	git push
avant de soumettre une correction (c'est une erreur assez frequente).
Pour soumettre votre exercice a la correction, il suffit de faire
	grademe
A la fin de l'exam, il vous suffit de vous lever, et de faire
	finish 
dans le terminal avant de partir.
```
</p>

<h3> Les rushs</h3>
<p> Durant les 3 premiers week-ends de la piscine, vous pourrez vous inscrire a des rushs. Les rushs sont des projets en groupe de 3 qui durent 2 jours, et que vous devrez faire corriger durant la semaine qui suit. Les groupes sont fait de maniere aleatoire, donc les niveaux ne sont pas forcement equivalent au saint Les faire est tres interessant car vous serez en contact avec des gens nouveaux, et de niveaux differents, parfois vous devrez expliquer des notions aux membres de votre groupe, mais parfois c'est a vous qu'ils expliqueront donc pour apprendre c'est le top. 
</p>

<h3> Le BSQ</h3>
<p> Durant la deniere semaine, vous aurez la possibilite de faire un projet en duo. Vous choisissez votre duo avant de commencer le projet, et ce dernier est interessant a faire, il demande cependant du travail et de la rigueur.
</p>

<h3> La vie a 42 durant la piscine</h3>
<p> Le mois est tres intenssif (~200h pour ma part), mais il ne faut pas oublier de prendre soin de vous ; pensez a dormir, faire du sport et bien manger, votre sante est tres importante. Les tuteurs et le BDE sont la pour organiser quelques events, n'hesitez pas a participer, ainsi qu'aux autres events proposes sur l'intra ; ca permet de decompresser un peu, de rencontrer des gens et de sortir un peu de cette bulle. </br>
Il existe aussi un outil social, qui se nomme le Voxotron. Le Voxotron est un vote realise toute les semaines, durant lequel vous votez pour les 10 personnes qui vous ont le plus aide dans la semaine, ou les 10 que vous avez preferees, ... En tout cas ces votes permettent de jauger la sociabilite.
</p>

<h3> Mes conseils pour bien demarrer la piscine </h3>
- N'hesitez pas a aller parler aux autres. C'est super important et ca permet de passer une super piscine.</br>
- Installez <a href="https://ohmyz.sh/">OhMyZsh</a> sur votre terminal, ca sera plus simple (mais faites attention vous n'y aurez pas acces durant les examens) </br>
- Prenez votre aise avec Git </br>
- Participez a des events, et allez parler aux gens, c'est trop trop cool ! </br>
- Ne stressez pas trop, et essayez de rendre votre piscine cool (les deguisements ca aide beaucoup 👀) </br>
- Soyez indulgent avec tout le monde (meme le bocal), c'est un mois intensif pour vous, mais aussi pour le staff, les tuteurs, ...