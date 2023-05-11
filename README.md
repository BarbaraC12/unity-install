# Unity

Unity est un moteur de jeu multiplateforme développé par Unity Technologies. C'est l'un des plus répandus avec Unreal dans l'industrie du jeu vidéo, aussi bien pour les grands studios que pour les indépendants du fait de sa rapidité aux prototypages et qu'il permet de sortir les jeux sur tous les supports.  
|  Langues supporté  | Langages de programmation | Jeux connus |
| :--------: | :--------: | :--------: |
| Anglais | C#, C++ | Ori, Temple Run, Monument Valley, ... |

### Pour désinstaller sur Linux/Debian:  
```
$> sudo apt-get remove unityhub
```

### Pour installer depuis Linux/Debian:  
1. Ajouter la clé public:  
```
$> wget -qO - https://hub.unity3d.com/linux/keys/public | gpg --dearmor | sudo tee /usr/share/keyrings/Unity_Technologies_ApS.gpg > /dev/null
```
2. Ajouter Unity Hub repertoire au chemin /etc/apt/sources.list.d:  
```
$> sudo sh -c 'echo "deb [signedby=/usr/share/keyrings/Unity_Technologies_ApS.gpg] https://hub.unity3d.com/linux/repos/deb stable main" > /etc/apt/sources.list.d/unityhub.list'
```
3. Mise à jour et installation des paquets:  
```
$> sudo apt update
$> sudo apt-get install unityhub
```

### Manuel d'utilisation:
[![unity](https://dl.flathub.org/repo/appstream/x86_64/icons/128x128/com.unity.UnityHub.png)](https://docs.unity3d.com/Manual/UnityManual.html)
[![Csharp]()](https://docs.unity3d.com/Manual/UnityManual.html)
[![C++]()](https://docs.unity3d.com/Manual/UnityManual.html)
