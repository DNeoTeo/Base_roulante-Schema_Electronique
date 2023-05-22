# Base_roulante-Schema_Electronique

## Introduction

Dans le cadre du module Challenge, j’ai choisi de participer à la compétition de la coupe de France de Robotique 2023. Ce défi n’est pas envisageable tout seul. Avec des membres de l’association DTRE nous avons décidé de former une équipe. Ce « hackathon » nous a amené le défi de gérer et d’organiser une équipe de 29 personnes. À travers ce projet, j’ai pu travailler sur les différentes thématiques techniques telles que la programmation orienté objet, la mécanique ou encore l’électronique.

L’évènement a débuté le 10 septembre 2022 lors de la conférence de présentation de Planète Science organisé sur le campus d’EPITA. Ils y ont délivré la première version du règlement qui fut mis à jour quelques mois plus tard pour des questions d’homogénéités et pour clarifier certains points déséquilibré remontées par les équipes. Ce première évènement en début d’année nous a permis de poser toutes nos questions aux organisateurs et aux équipes vétéranes. Puisque nous sommes tous totalement novice de cette compétition. Le thème de cette année étant « The Cherry on the cake » pour fêter les 30 ans d’Eurobot, Planète Science demande aux équipes participant à la coupe de France de robotique de « cuisiner pour faire la fête ». 
Les missions fixées par le règlement de la 30ème édition sont : 

  − Fabriquer des gâteaux − Positionner la cerise sur les gâteaux   
  − Ranger le surplus des cerises dans le panier   
  − Se déguiser pour faire la fête. 
  
Sur le campus d’EPITA nous avons rencontré les organisateurs et des équipes habitués auprès desquelles nous avons pu prendre de précieux conseils.

Au début, Yasin, un membre de la DTRE et moi-même avons beaucoup travaillé en duo pour démarrer le projet puis nous avons délégué certaines parties aux membres qui ont rejoint l’équipe. J’ai ainsi participé à : 
  - Tous les entretiens des membres de l’équipe, 
  - La définition du budget (Annexe – Budget), 
  - La demande de subvention auprès de l’école ([Lien](https://docs.google.com/presentation/d/1tvP93IFA4L__9xUBjh1RfveQjmiez2jK/edit?usp=sharing&ouid=110299042600853966410&rtpof=true&sd=true)), 
  - Relecture du rapport PST de mi-année ([Lien](https://etesiea.sharepoint.com/:w:/r/sites/LesCavistes/Shared%20Documents/Rapport-PST/Rapport_PST_CDF_de_Robotique_2023.docx?d=w7245fce72372446c8502f77247498078&csf=1&web=1&e=gcsRpB)), 
  - Discussion avec les différents pôles pour connaître leur stratégie, 
  - Suivi de certains groupes pour s’assurer qu’ils n’avaient pas de problème à avancer, 
  - Récupération d’archive auprès d’une ancienne équipe ([Lien](https://etesiea.sharepoint.com/sites/LesCavistes/Shared%20Documents/Forms/AllItems.aspx?csf=1&web=1&e=nhDVeM&cid=38b68eae%2D38fa%2D46e4%2Db0cc%2D20c76cc6e8ef&RootFolder=%2Fsites%2FLesCavistes%2FShared%20Documents%2FGeneral%2FP%C3%B4les%2FBases%20roulante%2FArchives%20%2D%202012%20%2D%20Laval%20%2D%20RED&FolderCTID=0x012000E9F15A1BEC881E4E86D8D69B8AE829E8)) 
 
En plus de cette partie organisationnelle, je suis dans le pôle Base roulante spécialité électronique. J’ai ainsi réalisé plein de recherche pour le choix des composants de la base roulantes. 
Toutes les recherches sont dans le NoteBook suivant : [Elec – Base roulante](https://etesiea.sharepoint.com/:o:/r/sites/LesCavistes/_layouts/15/Doc.aspx?sourcedoc=%7B89e0934c-7b01-4295-8348-e438ad04fc94%7D&action=edit&wd=target(Notes%20de%20R%C3%A9union%2FElec%20-%20Notes%20de%20r%C3%A9unions.one%7Cb93d645d-10fc-47ad-a43a-4c280d625987%2FElec%20%E2%80%93%20Base%20roulante%7Cc344ee84-79c5-4be7-819a-d46dd6609212%2F)&wdorigin=703&wdpreservelink=1) ([Web view](https://etesiea.sharepoint.com/:o:/r/sites/LesCavistes/_layouts/15/Doc.aspx?sourcedoc=%7B89e0934c-7b01-4295-8348-e438ad04fc94%7D&action=edit&wd=target(Notes%20de%20R%C3%A9union%2FElec%20-%20Notes%20de%20r%C3%A9unions.one%7Cb93d645d-10fc-47ad-a43a-4c280d625987%2FElec%20%E2%80%93%20Base%20roulante%7Cc344ee84-79c5-4be7-819a-d46dd6609212%2F)&wdorigin=703&wdpreservelink=1)) Ce notebook est divisé en deux parties, à gauche la liste des composants adéquats pour toute la base roulante et ceux acheté pour le prototype n°1. Et à droite différentes parties théoriques et pistes de recherches pour bien choisir les composants. J’ai réalisé une chaîne fonctionnelle permet de visualiser l’ensemble de notre système : prise de décision avec la chaîne d’information, distribution de l’alimentation avec la chaîne d’énergie. On voit ainsi les composants nécessaires en fonction de leur rôle dans les 2 chaînes. Le diagramme électronique illustre la manière dont nos composants vont être reliés entre eux.

### La chaîne fonctionnelle

![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/4b52f379-9fc4-45d7-8c97-01a3810d3c9d)

### Diagramme électrique

![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/bd998902-fc33-4c08-a847-95ef4dc42f5d)

Premier prototype de la base roulante : https://drive.google.com/file/d/1hqDrjrIA7VDXRb-9ib1nsVt9VAf5gUXD/view?usp=share_link

En même que de mettre sur pieds, le prototype, j’ai commencé à faire les bibliothèques de composant sur eagle ainsi que les circuits imprimés. 

### Emergency_button (Board, Schematics et Librairy)

![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/dfd948d6-6de0-492a-a8ff-63c5902816c7)

![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/304929e5-47da-4e3e-85a3-8d4495a05a8b)

![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/90834144-048d-48f8-a775-4b0e82a93229)

### Entrainement sur EAGLE

J’ai ainsi appris à créer des PCBs sur EAGLE avec la création de librairies ce qui inclut la création de schématics et de boards. Cette entrainement m’a permis de me familiariser avec les librairies de composants et l’IDE d’EAGLE.

![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/28d4533f-32e9-4836-9b73-6ac3bcbcf954)
![image](https://github.com/DNeoTeo/Base_roulante-Schema_Electronique/assets/48857676/86e38a42-5f7d-4cc2-996d-3044e859ed92)



