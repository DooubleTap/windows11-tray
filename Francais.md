## Afficher toutes les icônes dans la barre des tâches (Windows 11)

Pour Windows 11, Microsoft a décidé de supprimer l'option que vous cherchez ! Mais il existe un moyen de faire apparaître automatiquement toutes les icônes des applications dans votre barre des tâches sans avoir à les activer manuellement. Parfois, certaines applications mises à jour redeviennent cachées. Après avoir cherché sur internet, j'ai trouvé comment faire et j'ai décidé de partager les résultats ici.

Assurez-vous de suivre ces étapes uniquement si vous êtes à l'aise avec des instructions spécifiques.

1. Ouvrez regedit.exe (**WINKEY+R, write: regedit.exe, press enter**)
2. Ouvrez les dossiers et allez ici: **HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer**
3. Faites un clic droit sur le dossier Explorer dans l'arborescence et cliquez sur: **NEW** -> **DWORD (32-bit) Value**
4. Nommez le fichier exactement ainsi:  **EnableAutoTray**
5. Double-cliquez sur le fichier nouvellement créé et définissez sa valeur pour: 1
6. Ouvrez run.exe (WINKEY+R) et collez cette ligne entière: **explorer shell:::{05d7b0f4-2121-4eff-bf6b-ed3f69b894d9}**
7. La ligne ci-dessus ouvrira une fenêtre avec une case non cochée intitulée: **Always show all icons and notifications on the taskbar**. Cochez-la !

Vous pouvez maintenant fermer tout ce que vous avez ouvert dans les étapes ci-dessus.
