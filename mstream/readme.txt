Para enviar el audio de tu maquina local a la maquina virtual "scp -r (ruta donde esta la cancion) (conexion a la maquina virtual:ubicacion donde va a parar la cancion)"
Ejemplo: scp -r /home/nahuel/Descargas/Child-Dreams.mp3   ubuntu@10.201.3.156:/home/ubuntu/final2/

Para enviar los audios al pod "kubectl cp (ruta donde se encuentra el audio) (pod:volumen)
Ejemplo: kubectl cp /home/ubuntu/final2/Brendan_Kinsella_-_02_-_Bach_-_Aria_Variata_BVW_989_-_Variation_No_2.mp3 mstream-0:/music

