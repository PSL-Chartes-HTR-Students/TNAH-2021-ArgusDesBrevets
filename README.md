## Transcription "Argus des brevets d'invention"

[![DOI](https://zenodo.org/badge/425807963.svg)](https://zenodo.org/badge/latestdoi/425807963)

Auteurs:

- Virgile Reignier
- Maxime Humeau
- Valentin De Craene

## Introduction et présentation du projet

L’[argus des brevets ](https://gallica.bnf.fr/ark:/12148/bpt6k1418369x.r=Argus%20des%20brevets%20d%27invention...%20Liste%20des%20brevets%20d%C3%A9pos%C3%A9s%20et%20d%C3%A9livr%C3%A9s%20en%20France%2C%20publi%C3%A9e%20par%20l%27Office%20des%20brevets%20d%27invention...?rk=42918;4 "argus des brevets ")de 1910 se présente sous la forme d’un imprimé contemporain, organisé en rubriques regroupant de manière chronologique puis thématique les brevets déposés en France. Cette énumération et présentation succincte des brevets est répartie en deux colonnes et présente des abréviations normalisées. Dès lors, ce présent guide de contribution au projet entend présenter l’ensemble des normes de transcriptions adoptées au cours de ce projet de transcription, réalisé sur la plateforme[ E-scriptorium](https://traces6.paris.inria.fr/ " E-scriptorium"), dans le cadre du cours Git du [master TNAH à l’ENC](https://www.chartes.psl.eu/fr/cursus/master-technologies-numeriques-appliquees-histoire "master TNAH à l’ENC").

------------

## Choix de transcription

En premier lieu, nous avons décidé de fonder notre transcription sur les recommandations publiées dans l’ouvrage *L’édition critique des textes contemporains, XIXe-XXIe siècle*, par Christine Nougaret, Elisabeth Parinet et Florence Clavaud. Néanmoins, certaines adaptations ont été nécessaires afin de fournir un jeu de données issue de la transcription, qui soit à la fois proche du document source et exploitable par la suite.
Ainsi, concernant les abréviations, nous avons décidé de conserver la graphie originale au sein de la transcription. Ce choix fut guidé par deux éléments : d’une part, la volonté de conserver une graphie intègre, afin de fournir aux chercheurs s’intéressant à ce sujet un texte facilement exploitable de manière automatique, comme par exemple une analyse quantitative des types de sociétés (anonymes, familiales,…) déposant des brevets. Cette décision fut motivée par la facilité de résolution et compréhension des abréviations par le lecteur. D'autre part, il nous semble que cette approche permettrait une réutilisation générales des données, telle qu'un processus d'apprentissage machine.

Nous avons été amené à réaliser certains choix relevant de la transcription et de l’édition du document. Pour ce faire, nous nous sommes référé au *Lexique typographique en usage à l’Imprimerie nationale* :
- les tirets en fin de ligne faisant la césure au sein des mots ont été rétablis (ex : direc-tion).
- les numéros de page en haut de page ont été transcris ainsi : « _ N _ » où N correspond au numéro de page.
- en cas de caractères mal imprimés ou usés, ceux-ci ont été rétablis dans la mesure où ils sont facilement interprétables (mais non devinables) par le lecteur. 
------------

## Mise en forme et guide de contribution
    
Le document transcrit se présente donc sous forme d’une page au format A4, séparée en deux colonnes. Cette présentation implique différents travaux en amont :
- la délimitation des zones (les colonnes du document, les zones de titres, les zones de sous-titres, les zones de numéros de pages

| Nom de la zone  | Zone (XML) |
| ------------ | ------------ |
|  Colonne de gauche |   ColonneG |
| Colonne de  droite | ColonneD  |
| Numéro de page  |  NumPage |
|  Titre (niv.1) |  Titre |
|  Titre (niv.2) | SousTitre  |
| Titre (niv.3)  | SousSousTitre  |



- le nommage des zones
- la correction éventuelle des masques ou lignes afin d’éviter la superposition de deux lignes dans l'interface de transcription.
- la renumérotation en déliant puis reliant les lignes, afin d’obtenir une pagination suivant l’organisation en double colonnes (nous encourageons le lecteur à se référer à l’[issue 11](https://github.com/ValentinDeCraene/TNAH-2021--ARGUS_DES_BREVETS-/issues/11 "issue 11") proposant un « tutoriel » pour obtenir ce résultat).



Le résultat de la transcription a ensuite été exporté et mis en ligne sur le dépôt Github au format XML et jpg.

La répartition des transcriptions, par page, a été la suivante :
- **Valentin** : pages 2 à 8 incluses,  
- **Maxime** : pages 9 à 13 incluses,   
- **Virgile** : pages 14 à 18 incluses.

Dans une perspective de contribution au projet, il conviendrait de poursuivre la transcription jusqu’à la fin du document, contenant au total 58 pages. Nous avons fait le choix de travailler et contribuer sous la forme de branches personnelles, sur lesquelles nous faisons nos « commits » et nos « pushs ». Une fois les transcriptions terminées et envoyées par le biais des "pushs", une « pull request » est effectuée afin de « merge » vers la branche « main ».

------------

## Index des abréviations conservées:

Voici un index de ces dites abréviations:
- « Sté anme » pour société anonyme.
- « Cie » pour « compagnie » (et variante anglo-saxonne « Cy » pour « Compagny »).
- « Applic. » pour applicable à.
- « Perf. » pour perfectionnant.
