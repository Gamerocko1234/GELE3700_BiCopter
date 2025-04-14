# GELE3700_BiCopter
Comment téléchargé le fichier Simulink?
- Simplement téléchargé la copie brute (Raw Copy) en selectionant ArduinoDUE.slx sur le dessus de ce message.

Comment faire fonctionner le Bi-Copter?
- Après avoir branché le Bi-Copter au port USB de l'ordinateur hôte, Il faut faire l'installation du fichier Simulink et du Simulink Support Package for Arduino Hardware
qui est disponible dans la section Add-Ons - Get Hardware Support Pakages sur MultiSim.

- À cette étape, le code devrait souvrire dans Simulink sans difficulté.
Afin de communiquer avec le Bi-Copter, il faut aller dans la section Hardware - Settings - Hardware Implementation et selectionner le Arduino DUE.
Après avoir confirmé le choix, le code est prêt à être lancé en utilisant Monitor & Tune avec une valeur de temps spécifier (inf recommandé)!

Difficultés:
- Si la DEL verte du controleur ne s'allume pas lors du branchement du port USB ou l'ordinateur hôte ne trouve pas le Arduino, veuillez premièrement observé si les connexions sont bien fait derrière le Bi-Copter. Si tout est bien branché, il risque d'être un problème avec la carte de controle, veuillez ouvrir le boitier et référé au rapport placé ci-haut comme guide d'instructions.
