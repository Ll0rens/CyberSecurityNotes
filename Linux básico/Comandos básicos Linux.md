-----
- Tags: #Linux
-----
- `awk '{print $2}' FS=":"` : Quédate con el segundo argumento, utilizando ":" como delimitador
- `tr 'a' 'b'`: Transforma las 'a' en 'b' (utilizar solo para caracteres, para sustituir palabras utilizar `sed`)
- `rev`: Da la vuelta a la cadena abc -> cba
- `grep -vE "hola|adios"`: quita las palabras hola y adiós
- `find . -type f`: busca los archivos de tipo file solamente
- `find . -type f -user OWNER -group GROUP_OWNER -size 33c`: busca por usuario y por grupo y por tamaño del archivo 33 bytes
- `sed 's/prueba/probando/g'`: Cambia la palabra 'prueba' por 'probando' (la g del final es para que lo sustituya en todos los lados)
- `uniq -u`: lista lineas únicas
- `strings file.txt`: Lista solo las cadenas legibles
- `base64 "cadena"`: Encodea la cadena en base64
- `base 64 "cadena" -d`: Hace un Decode de la cadena en base 64 y nos la muestra normal


ssh bandit11@bandit.labs.overthewire.org -p 2220
6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM