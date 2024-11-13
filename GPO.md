##### Restriction d'un groupe d'utilisateur
##### Dans "Group Policy Management" => dérouler jusqu'au groupe souhaitez => Wilder_student => clic droit => Première option
![vm 1](https://github.com/user-attachments/assets/b2bdc3f9-2b41-4eba-b8c7-b79858f73818)
##### Donner un nom à ce nouveau GPO :arrow_up:
##### Dans wilder_students on vois maintenant le nouveau GPO à droite

![vm 1](https://github.com/user-attachments/assets/65fe4691-7d9b-49d9-810c-e73e5866eca5)
##### Editer
![vm 1](https://github.com/user-attachments/assets/f0d96297-e79e-4617-9492-8f2f5e2db38d)
##### Dérouler le menu corespondant pour trouver la politique de paneau de configuration :
##### Ici User Configuration => Policies => Administrative Templates => Control Panel => Toutes les régles relatives au Control Panel.
![vm 1](https://github.com/user-attachments/assets/eab7e2ff-7310-4ff9-93a5-c7bb008693fd)
##### Mettre disabled puis ok
![vm 1](https://github.com/user-attachments/assets/a837248b-1331-482c-a9db-7d42f6182997)
##### Résultat:
![vm 1](https://github.com/user-attachments/assets/f3145f00-ddc3-49ff-bd53-a51b993a027d)
##### Sur la machine client:
   * ##### Sur Powershell en Admistrator exécuter la commande : gpupdate /force
   * ##### faire windows+R => Ecrire : Control.exe
##### Résultat machine client :
![vm 1](https://github.com/user-attachments/assets/5accd1aa-8048-4c96-9526-538866c74e59)






