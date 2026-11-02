#### 1. ¿Qué diferencia existe entre git add y git commit?
git add prepara los archivos para el cambio y git commit los guarda en el historial

#### 2. ¿Qué hace git push y por qué puede ser rechazado?
git push sube los commits al repositorio remoto. Se rechaza si el remoto tiene cambios que tú no

#### 3. ¿En qué se diferencian git fetch y git pull?
git fetch solo descarga los cambios remotos y git pull los descarga y los fusiona 

#### 4. ¿Qué significa origin/main?
ES la copia que está en GitHub

#### 5. ¿Qué muestra git status antes y después de git add?
Antes de git add muestra los cambios no preparados en rojo y después los cambios preparados los muestra en verde

#### 6. ¿Para qué sirve git diff --cached?
Muestra las diferencias entre los archivos y el último commit

#### 7. ¿Qué indica git log --oneline HEAD..origin/main?
Muestra los cambios que están en GitHub y que todavía no has descargado

#### 8. ¿Por qué conviene realizar commits pequeños y descriptivos?
Para entender fácilmente qué se cambió y poder deshacer errores sin perder todo el trabajo

#### 9. ¿Cómo resolviste el push rechazado y por qué no utilizaste --force?
Se resolvió usando git fetch y git pull --no-rebase y los demás comandos para integrar los cambios del repositorio. 
No se usó --force para evitar sobrescribir los cambios

#### 10. ¿Qué diferencia hay entre un diagrama de clases y un diagrama de secuencia?
El diagrama de clases muestra cómo está construido el programa y sus partes, y los diagramas de secuencia muestra los 
pasos y el orden en que eas partes interactúan

#### 11. ¿Qué utilidad tienen los breakpoints durante una depuración?
Sirven para pausar el programa en una línea específica y revisar qué valores tienen las variables en ese momento

#### 12. ¿Por qué son importantes las pruebas antes y después de refactorizar?
Las de antes aseguran que el programa funcionaba, y las de después confirman que al limpiar el código no rompiste nada

#### 13. ¿En qué carpeta y ventana de IntelliJ estabas cuando se rechazó el push?
Estaba en la carpeta de unidad-03/README.md y en la ventana de la terminal
