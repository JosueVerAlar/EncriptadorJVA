# EncriptadorJVA

Te presento un breve ejercicio práctico donde construí un encriptador de texto, esto quiere decir que la entrada de información es tipo **string**, en minúsculas sin carácteres especiales o acentos. El texto que se añada es analizado y transformado según las siguientes reglas o "llaves de encriptación":

* La letra "e" es convertida para "enter"
* La letra "i" es convertida para "imes"
* La letra "a" es convertida para "ai"
* La letra "o" es convertida para "ober"
* La letra "u" es convertida para "ufat"

por ejemplo:

- "gato" => "gaitober"
- gaitober" => "gato"

La idea en términos generales es que se puedan intercambiar mensajes secretos con otras personas que sepan el secreto de la encriptación utilizada, por lo que también debe considerar una funcionalidad para desencriptar el texto. También se añadió el botón de copiado como un extra a los requisitos del reto. 

> #challengeonecodificador2

![Video tester informativo](https://github.com/JosueVerAlar/EncriptadorJVA/blob/main/imagenes/tester0.jpg)
![Video tester informativo](https://github.com/JosueVerAlar/EncriptadorJVA/blob/main/imagenes/tester1.jpg)
