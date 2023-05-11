# Unity

Unity est un moteur de jeu multiplateforme développé par Unity Technologies. C'est l'un des plus répandus avec Unreal dans l'industrie du jeu vidéo, aussi bien pour les grands studios que pour les indépendants du fait de sa rapidité aux prototypages et qu'il permet de sortir les jeux sur tous les supports.  
|  Langues supporté  | Langages de programmation | Jeux connus |
| :--------: | :--------: | :--------: |
| Anglais | C#, C++ | Ori, Temple Run, Monument Valley, ... |

## Manuels d'utilisation:
<div align="center">
 <a alt="unity" href="https://docs.unity3d.com/Manual/UnityManual.html" target="_blank" title="unity">
  <img width="10%" src="https://github.com/BarbaraC12/unity-install/blob/f849226015d732e85bab18fba06b7dc88f767672/img/apprendre-coder-unity.png" />
 </a>
  <a alt="C#" href="https://learn.microsoft.com/fr-fr/dotnet/csharp/methods" target="_blank" title="C Sharp">
  <img width="10%" src="https://github.com/BarbaraC12/unity-install/blob/f849226015d732e85bab18fba06b7dc88f767672/img/c-sharp.png" />
 </a>
  <a alt="C++" href="https://cplusplus.com/reference/" target="_blank" title="C++">
  <img width="10%" src="https://github.com/BarbaraC12/unity-install/blob/f849226015d732e85bab18fba06b7dc88f767672/img/c-plus-plus.png" />
 </a>
</div>

## Pour désinstaller sous Linux/Debian:  
```
$> sudo apt-get remove unityhub
```

## Pour installer depuis Linux/Debian:  
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
