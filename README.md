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

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321160058269.png" alt="image-20240321160058269" style="zoom: 80%;" />

### Détails

1. Téléchargez tout le projet, ouvrez-le avec IntelliJ IDEA et et attendez que toutes les dépendances de Maven soient importées.

2. Connecter les données dans MySQLData.

3. Exécutez l'application FaimdeloupApplication, puis accédez à http://localhost:8080/backend/page/login/login.html dans votre navigateur.

4. Entrez username: admin et password: 123456 pour se connecter.

   <img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321161900240.png" alt="image-20240321161900240" style="zoom: 55%;" />
   
   

#### Employés

​	Chaque employé a un nom, une poste, un tel et un état.

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321162518305.png" alt="image-20240321162518305" style="zoom: 40%;" />

- Vous pouvez cliquer **+Add Employé** pour ajouter un employé

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321163100087.png" alt="image-20240321163100087" style="zoom: 40%;" />

- **Editer** pour modifier les employés

  <img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321163240356.png" alt="image-20240321163240356" style="zoom: 40%;" />

- **Disabled** ou **Enabled** pour changer l'état.



####  Catégories

​	Chaque catégorie a un nom, un type, un temps de renouvellement et un ordre

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321164950146.png" alt="image-20240321164950146" style="zoom:40%;" />



#### Plats

​	Chaque plat a un nom, une image, une catégorie, un prix, un état et une heure de la dernière opération

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321165507121.png" alt="image-20240321165507121" style="zoom:40%;" />

​	Les images sont dans **src/main/resources/dishImages**

​	Ces plats sont inspirés du menu d'un restaurant près de chez moi. (Hippopotamus)

#### Menus

​	Chaque menu a un nom, une image, une catégorie, un prix, un état et une heure de la dernière oprération

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321170513264.png" alt="image-20240321170513264" style="zoom:40%;" />

​		Pour ajouter un menu, vous pouvez cliquer sur **+ Nouveau menu**

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321170744337.png" alt="image-20240321170744337" style="zoom:40%;" />

​		Un menu peut être un **menu soir** ou un **menu midi**

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321170841163.png" alt="image-20240321170841163" style="zoom: 67%;" />

​		Vous pouvez ajouter plusieurs plats pour un menu, en cliquant **+ Ajouter des plats**

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321170946287.png" alt="image-20240321170946287" style="zoom: 50%;" />

#### Ordres

​	Chaque ordre a un numéro, un statut, un nom de client, un tel, une adresse, un temps de commande et un montant reçu

​	<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321171218891.png" alt="image-20240321171218891" style="zoom:40%;" />

​	Vous pouvez chercher les ordres par la **date de commande**

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321171557079.png" alt="image-20240321171557079" style="zoom:50%;" />

#### Déconnecter

Quand vous avez fini les actions, vous pouvez vous déconnecter en cliquant sur le petit symbole en haut à droite de l'écran

<img src="C:\Users\zhuyz\AppData\Roaming\Typora\typora-user-images\image-20240321171852478.png" alt="image-20240321171852478" style="zoom:40%;" />