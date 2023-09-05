# Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle

### Création d'une Unité d'Organisation (OU), d'un groupe d'utilisateurs et d'un utilisateur dans Active Directory

#### Étape 1 : Création de l'Unité d'Organisation (OU) Wilders_students

1. Se connecter au serveur Active Directory en tant qu'administrateur.

2. allez dans l'outil "Utilisateurs et ordinateurs Active Directory"

3. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/c1466e68-6e59-4a0d-8985-354b16b47f2a)

4. Dans l'arborescence de l'Active Directory, faites un clic droit sur le nom de domaine "wilders.lan" et sélectionnez "Nouveau" -> "Unité d'Organisation".

5. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/b5f0e9aa-db9a-40e8-b1af-b370add43c17)


6. Nommez l'Unité d'Organisation "Wilders_students" et cliquez sur "OK" pour la créer.

#### Étape 2 : Création du groupe d'utilisateurs Students

1. Dans l'outil "Utilisateurs et ordinateurs Active Directory", faites un clic droit sur l'Unité d'Organisation "Wilders_students".

2. Sélectionnez "Nouveau" -> "Groupe".

3. Nommez le groupe "Students" et cliquez sur "OK" pour le créer.

4. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/f3ff8e24-20fb-44d0-b263-7ec6e2fb7732)
![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/0d459d36-476a-44ad-b779-a76875f339e6)


#### Étape 3 : Création d'un utilisateur et ajout au groupe Students

1. Toujours dans l'outil "Utilisateurs et ordinateurs Active Directory", faites un clic droit sur l'Unité d'Organisation "Wilders_students".

3. Sélectionnez "Nouveau" -> "Utilisateur".

4. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/d1859fb0-9c92-4835-a457-e1df61929508)


5. Suivez l'Assistant de création d'utilisateur pour définir les détails de l'utilisateur. et définir le mot de passe.

6. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/3de943e2-3192-4e43-9fea-c8dc947d8008)


7. Une fois l'utilisateur créé, faites un clic droit sur l'utilisateur nouvellement créé, sélectionnez "Propriétés", puis allez dans l'onglet "Membre de". Cliquez sur "Ajouter" et saisissez "Students" (le nom du groupe créé à l'étape précédente) pour ajouter l'utilisateur à ce groupe.

8. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/fe69ceea-5533-43a7-a062-b149398a6f52)
9. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/d1bb2c2b-f480-4f80-bc6a-b88090180ed8)
10. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/9c8d7f46-0574-496c-874d-4284d1327077)


11. Cliquez sur "OK" pour confirmer et fermez la boîte de dialogue des propriétés de l'utilisateur.

12. ![image](https://github.com/manmaryem/Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle/assets/137881827/420c6bf8-2a3f-45f8-8621-fbd9e404b2a6)


