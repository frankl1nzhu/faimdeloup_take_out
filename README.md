# Faimdeloup_take_out

<br>

### Présentation

Faimdeloup_take_out (FDL) est un projet conçu spécifiquement pour les commandes livraisons des restaurants, comprenant un tableau de bord de gestion système. Ce tableau de bord est destiné à être utilisé par les personnels internes des reataurants, leur permettant de gérer et de maintenir les plats, les menus, les commandes, etc. du restaurant.

<br>

### Technologies utilisées

##### Gateway Layer

- Nginx

##### Application Layer

- Spring Boot
- Spring et Spring MVC
- Lombok

##### Data Layer

- MySQL
- MyBatis
- MyBatisPlus

##### Outils

- Git
- Maven
- Junit

<br>

#### Database

La base de données se trouve dans **src/main/resources/MySQLData**.

![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-database.png)

### Détails

1. Téléchargez tout le projet, ouvrez-le avec IntelliJ IDEA et et attendez que toutes les dépendances de Maven soient importées.

2. Connecter les données dans MySQLData.

3. Exécutez l'application FaimdeloupApplication, puis accédez à http://localhost:8080/backend/page/login/login.html dans votre navigateur.

4. Entrez username: admin et password: 123456 pour se connecter.

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-login.png#w80)
   

### Employés

​	Chaque employé a un nom, une poste, un tel et un état.

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-employee.png)

- Vous pouvez cliquer **+Add Employé** pour ajouter un employé

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-addEmployee.png)

- **Editer** pour modifier les employés

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-EditerEmployee.png)

- **Disabled** ou **Enabled** pour changer l'état.



###  Catégories

​	Chaque catégorie a un nom, un type, un temps de renouvellement et un ordre

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-category.png)



### Plats

​	Chaque plat a un nom, une image, une catégorie, un prix, un état et une heure de la dernière opération

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-plat.png)
   
​	Les images sont dans **src/main/resources/dishImages**

​	Ces plats sont inspirés du menu d'un restaurant près de chez moi. (Hippopotamus)

### Menus

​	Chaque menu a un nom, une image, une catégorie, un prix, un état et une heure de la dernière oprération

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-menu.png)

​		Pour ajouter un menu, vous pouvez cliquer sur **+ Nouveau menu**

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-nouveauMenu.png)

​		Un menu peut être un **menu soir** ou un **menu midi**

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-menuCategory.png)

​		Vous pouvez ajouter plusieurs plats pour un menu, en cliquant **+ Ajouter des plats**

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-ajouterDesPlats.png)

### Ordres

​	Chaque ordre a un numéro, un statut, un nom de client, un tel, une adresse, un temps de commande et un montant reçu

​	![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-ordre.png)

​	Vous pouvez chercher les ordres par la **date de commande**

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-chercherCommande.png)

### Déconnecter

Quand vous avez fini les actions, vous pouvez vous déconnecter en cliquant sur le petit symbole en haut à droite de l'écran

   ![image](https://github.com/frankl1nzhu/faimdeloup_take_out/blob/main/src/main/resources/githubImages/image-deconnecter.png)
