A collection of Discord UI tweaks I made for myself

# Bigger servers, smaller folders
The reverse of the default, basically. Looks neat with a "PlainFolderIcon" plugin from Vencord.

Default / tweaked / tweaked + PlainFolderIcon comparison:  
![image](https://github.com/user-attachments/assets/912f43d1-c50c-4c97-8f1f-7e2f379a82a9)
![image](https://github.com/user-attachments/assets/2613b330-7fed-4568-9e6d-b52a61ccc283)
![image](https://github.com/user-attachments/assets/9cd446c1-5f37-4d68-82e2-02c4164b1e34)

Add this to your QuickCSS to apply:
```
@import "https://raw.githubusercontent.com/WerDei/Discord-CSS-tweaks/refs/heads/main/bigger-servers.css";
```

Optional: add any of these options to tweak the look
```
:root {
  /* Don't shrink the folders */
  --bssf-folder-size: 48px;
  /* Make the "Add a Server" and "Explore" buttons just as big */
  --bssf-extras-size: 48px; 
}
```

# Selected server outline
An accessibility feature, basically. Makes it super obvious which server is currently selected  

![image](https://github.com/user-attachments/assets/349f39bc-2176-4436-b4c8-45b46bed1842)

```
@import "https://raw.githubusercontent.com/WerDei/Discord-CSS-tweaks/refs/heads/main/selected-server-outline.css";
```
Options:
```
:root {
  /* Set border thickness */
  --sso-selected-border: 3px;
  /* Change its color */
  --sso-selected-color: var(--header-primary);
}
```
