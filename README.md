## Show all icons in the taskbar (Windows 11)

For windows 11, they decided to remove the option that you are looking for! But there is a way to have all icons of apps to appear automatically in your taskbar without having to activate it manually and sometimes, some apps that are updates will go back hidden. So after looking on the internet, i found how to do it and decided to share the results here. 

Make sure you follow those steps only if you are comfortable following specific instructions.

1. Open regedit.exe (**WINKEY+R, write: regedit.exe, press enter**)
2. Open folders and go there: **HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer**
3. Right click on the **Explorer** folder in the treebar and click **NEW** -> **DWORD (32-bit) Value**
4. Name the file exactly this: **EnableAutoTray**
5. Doouble click on the newly created file and set its value to: **1**
6. Open run.exe (WINKEY+R) Paste this whole line: **explorer shell:::{05d7b0f4-2121-4eff-bf6b-ed3f69b894d9}**
7. This line above will open a window with a unchecked box called: **Always show all icons and notifications on the taskbar**. Check it!


You can now close everything you opened in the steps above. 
