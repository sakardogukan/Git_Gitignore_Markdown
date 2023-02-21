# Gitignore

.gitignore dosyası bir projenin kök dizininde oluşturulan düz bir metin dosyasıdır. Yüklenmek istenmeyen, gözardı edilmek istenilen, local çalışma alanında takip edilmesini istemediğimiz, ekip arkadaşları için gerekmeyen dosyaların repoya gitmesini engellemek için kullanılır.

```https://github.com/github/gitignore/tree/main/Global``` sayfasından IDE’ler için ignore yapıları incelenebilir. VsCode içinde ```.gitignore``` dosyası oluşturulur. 

#### ```.gitignore``` dosyası içerisinde yer alabilecek örnek içerik:

.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
!.vscode/*.code-snippets
#### Local History for Visual Studio Code
.history/
#### Built Visual Studio Code Extensions
*.vsix
#### images
*.png
img/
*.jpeg
#### videos
*.mp4
#### log
*.log
Password.txt
