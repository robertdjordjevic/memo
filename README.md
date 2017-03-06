# memo
memo sur différentes technos


youtube-dl

Télécharger une playlist youtube en formatant les noms de fichiers sans l'ID youtube en fin de fichier
dans l'exemple ce sont les videos de Grafikart

youtube-dl -o "%(title)s.%(ext)s" https://www.youtube.com/user/grafikarttv/videos
