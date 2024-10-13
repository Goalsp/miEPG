# miEPG   v1.3

Utilizando Github Actions para generar un xml a partir de otro, pudiendo modificar el nombre y el logo de cada canal

El script se ejecuta todos los días a las 13:30

***
- Modifica el fichero epgs.txt con la url de la EPG de origen

- Modifica el fichero canales.txt con los canales que desees y sus nombres

Los nombres de los canales tienen que ir separados por comas (sin espacios), el primer campo es el nombre del canal de la EPG de origen, el segundo campo es el nuevo nombre que le quieres dar al canal (por ejemplo el de tu lista), y el tercer campo es la url del logo (déjalo en blanco si quieres mantener el logo de la EPG de origen)

· Ejemplo: NombreEPG,NombreLISTA,hffp://raw.githubusercontent.com/Images/logo_dobleM.png

***
Cuando se ejecute el script obtendremos una url con la EGP creada con tus canales y sus nombres

(Cambia el [Username] por el de tu cuenta de GitHub)
```
https://raw.githubusercontent.com/[Username]/miEPG/master/miEPG.xml
```
