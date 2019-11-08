
#Instalación de Debian 8 paso a paso


Para navegar por las opciones usamos las tecla TAB y las flechas, para seleccionar una opcion usamos la tecla intro.

La instalación se crea en un disco duro vitual de 20GB utilizado Virtual Box.


0.Elegir Install.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/00.png" width="640" height="480" border="10"></a> </p>


1.Elegir idioma.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/01.png" width="640" height="480" border="10"></a> </p>


2.Elegir país.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/02.png" width="640" height="480" border="10"></a> </p>


3.Elegir tipo de teclado.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/03.png" width="640" height="480" border="10"></a> </p>

3.1.Esperar que terminen de aplicar las configuraciones seleccionadas y carga de componentes desde el dispositivo de instalación.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/03.1.png" width="640" height="480" border="10"></a> </p>


4.Escribir un nombre que deseen para el equipo. Es recomendable no poner un nombre que lxs relacione con ustedes.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/04.png" width="640" height="480" border="10"></a> </p>

5.Configurar nombre de dominio. Si no sabe que es esto lo puede omitir.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/05.png" width="640" height="480" border="10"></a> </p>

6.Elegir una contraseña segura para el usuario root todo poderoso.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/06.png" width="640" height="480" border="10"></a> </p>

6.1 Repetir la contraseña.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/06.1.png" width="640" height="480" border="10"></a> </p>

7.Ingresar el nombre completo del usuario que vamos a crear.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/07.png" width="640" height="480" border="10"></a> </p>

7.1 Nombre del usuario para la cuenta.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/07.1.png" width="640" height="480" border="10"></a> </p>

8.Elegir una contraseña segura para el usuario creado en el paso 7.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/08.png" width="640" height="480" border="10"></a> </p>

8.1.Repetir la contraseña.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/08.1.png" width="640" height="480" border="10"></a> </p>

8.2.Esperar que terminen de configurar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/08.2.png" width="640" height="480" border="10"></a> </p>

9.Elegir particionado manual.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/09.png" width="640" height="480" border="10"></a> </p>

9.1 Elegir la unidad en donde queremos instalar Debian.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/09.1.png" width="640" height="480" border="10"></a> </p>

9.2 Crear nueva tabla de particiones.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/09.2.png" width="640" height="480" border="10"></a> </p>

10.Crear partición /boot. Seleccionar Espacio Libre.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/10.png" width="640" height="480" border="10"></a> </p>

10.1.Crear una partición nueva.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/10.1.png" width="640" height="480" border="10"></a> </p>

10.2.Ingresar un tamaño de 250 MB

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/10.2.png" width="640" height="480" border="10"></a> </p>

10.3.Elegir Primaria.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/10.3.png" width="640" height="480" border="10"></a> </p>

10.4.Principio.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/10.4.png" width="640" height="480" border="10"></a> </p>

10.5. Utilizar como: Sistema de ficheros ext4 transaccional.

Punto de montaje: /boot. Dejar las demás opciones como están.

10.6.Elegir Se ha terminado de definir la partición.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/10.6.png" width="640" height="480" border="10"></a> </p>


11.Elegir Configurar los volúmenes cifrados.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/11.png" width="640" height="480" border="10"></a> </p>

11.1.Guardamos los cambios.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/11.1.png" width="640" height="480" border="10"></a> </p>

11.2.Crear volúmenes cifrados.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/11.2.png" width="640" height="480" border="10"></a> </p>

11.3.Con la tecla de espacio seleccionamos el ESPACIO LIBRE. En este caso /dev/sda. Nota: El primero es partición /boot creada en el paso 10. Damos en Continuar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/11.3.png" width="640" height="480" border="10"></a> </p>

11.4.Se han terminado de definir la partición.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/11.4.png" width="640" height="480" border="10"></a> </p>

11.5.Guardamos los cambios.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/11.5.png" width="640" height="480" border="10"></a> </p>

12.Crear volúmenes cifrados.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.png" width="640" height="480" border="10"></a> </p>

12.1.Con la tecla de espacio seleccionamos el dispositivo a cifrar. En este caso /dev/sda5. Damos en Continuar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.png" width="640" height="480" border="10"></a> </p>

12.2.Terminar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.2.png" width="640" height="480" border="10"></a> </p>

12.3.Confirmamos.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.3.png" width="640" height="480" border="10"></a> </p>

12.4.Es muy impórtate esperar que se sobre-escriba el disco con aleatoriedad. Esto puede tardar unos minutos dependiendo del equipo.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.4.png" width="640" height="480" border="10"></a> </p>


12.5.Elegir una contraseña segura para el cifrado. **Es importante que no olvide esta contraseña. Si la olvida no podrá recuperar su información. Se recomienda usar una frase facil de recordar.** Ejemplo: “Me gusta el helado 50 % caliente” podría escribirse como “M3 Gu$t4 3l H31ad0 50 % kali3n+3 :P”.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.5.png" width="640" height="480" border="10"></a> </p>

12.6.Repetimos la contraseña. ¡No olvidarla!

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/12.6.png" width="640" height="480" border="10"></a> </p>

Completamos el cifrado del disco. Ahora a crear el resto de particiones.


13.Elegir Configurar el Gestor de Volúmenes Lógicos (LVM).

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/13.png" width="640" height="480" border="10"></a> </p>

13.1.Guardar los cambios y configurar LVM.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/13.1.png" width="640" height="480" border="10"></a> </p>

13.2.Crear un grupo de volúmenes, para el resto de particiones.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/13.2.png" width="640" height="480" border="10"></a> </p>

13.3.Escribir el nombre que deseen para el nuevo grupo. Continuar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/13.3.png" width="640" height="480" border="10"></a> </p>

14.Seleccionamos la unidad cifrada. En este caso /dev/mapper/sda5_crypt. Continuar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/14.png" width="640" height="480" border="10"></a> </p>

14.1.Crear un volumen lógico.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/14.1.png" width="640" height="480" border="10"></a> </p>

14.2.Seleccionar el grupo. En este caso solo hay el creado en el paso 13.2.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/14.2.png" width="640" height="480" border="10"></a> </p>

14.3.Escribir el nombre que deseen para el nuevo volumen lógico, se siguiere un nombre descriptivo. Este será la partición /, por lo que le pondré de nombre raiz para . Continuar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/14.3.png" width="640" height="480" border="10"></a> </p>

14.4.Introducir el tamaño deseado para la partición. Los tamaños elegidos dependerán de sus necesidades y tamaño del disco.


<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/14.4.png" width="640" height="480" border="10"></a> </p>

15.Repetimos los pasos 14.1 al 14.3 para los demás volúmenes lógicos. Crearé: raiz con 1.5GB ( creada en los pasos 14.1 a 14.3), usr con 6GB, var con 2GB, tmp con 3GB, swap con 1GB (generalmente se usa la cantidad de memoria RAM por 1.5. Ejemplo: 2GB RAM x 1.5 = usamos de swap 3GB) y el resto del disco para home.
Puede crear unicamente los volúmenes: raiz, home y swap y Debian trabajará correctamente.

15.1.Creados los volúmenes lógicos damos en terminar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/15.1.png" width="640" height="480" border="10"></a> </p>

16.Ahora elegimos cada uno de los volúmenes. Empezando por el primero de la lista: LV home.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/16.png" width="640" height="480" border="10"></a> </p>

16.1.Utilizar como.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/16.1.png" width="640" height="480" border="10"></a> </p>

16.2.Sistema de ficheros ext4 transaccional.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/16.2.png" width="640" height="480" border="10"></a> </p>

16.3.Punto de montaje: /home – directorios personales de los usuarios.

16.4.Se ha terminado de definir la partición.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/16.4.png" width="640" height="480" border="10"></a> </p>

17.Elegimos las partición siguiente: LV raiz.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/17.png" width="640" height="480" border="10"></a> </p>

17.1.Utilizar como.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/17.1.png" width="640" height="480" border="10"></a> </p>

17.2.Sistema de ficheros ext4 transaccional.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/17.2.png" width="640" height="480" border="10"></a> </p>

17.3.Punto de montaje: / - sistema de ficheros raíz.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/17.3.png" width="640" height="480" border="10"></a> </p>

17.4.Se ha terminado de definir la partición.

18.Elegimos las partición siguiente: LV swap.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/18.png" width="640" height="480" border="10"></a> </p>

18.1.Utilizar como. Área de intercambio.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/18.1.png" width="640" height="480" border="10"></a> </p>

18.3.Punto de montaje: / - sistema de ficheros raíz.

18.4.Se ha terminado de definir la partición.

19.Si creamos mas volúmenes lógico repetimos el paso 16 seleccionando los respectivos puntos de montaje. Solo la volumen swap se usa como Área de intercambio. /usr, /var, /opt, /tmp, /srv, /home pueden ser EXT4

20.Finalizar el particionado y escribir los cambios en el diso.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/20.png" width="640" height="480" border="10"></a> </p>

20.1.Confirmamos los cambios.

20.2.Esperamos.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/20.2.png" width="640" height="480" border="10"></a> </p>

21.Usar una réplica de red. Esto son los repositorios de donde queremos instalar programas y actualizar nuestro Debian.

21.1.Elegir el país de la réplica de red.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/21.1.png" width="640" height="480" border="10"></a> </p>

21.2.mirrors.ucr.ac.cr/debian/.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/21.2.png" width="640" height="480" border="10"></a> </p>

21.3.Si utiliza un proxy ingrese la información. Continuar.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/21.3.png" width="640" height="480" border="10"></a> </p>

21.4.Esperamos. Este proceso dependerá de nuestra conexión a internet.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/21.4.png" width="640" height="480" border="10"></a> </p>

22.Instalar el cargador de arranque GRUB.

22.1.Elegir el dispositivo donde instalar el cargador de arranque.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/22.1.png" width="640" height="480" border="10"></a> </p>

23.Esperar mientras finaliza la instalación. Retirar el medio de instalación y Continuar. El equipo se reiniciara. Nos pedirá la contraseña para descifrar el disco duro.

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/23.0.png" width="640" height="480" border="10"></a> </p>

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/23.1.png" width="640" height="480" border="10"></a> </p>

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/23.2.png" width="640" height="480" border="10"></a> </p>

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/23.3.png" width="640" height="480" border="10"></a> </p>

<p><img src="https://raw.githubusercontent.com/fmonge/fmonge.github.io/imagenes/Debian/Install/23.4.png" width="640" height="480" border="10"></a> </p>

# ¡A disfrutar Debian GNU/Linux y el Software Libre!

El contenido de este documento es Creative Commons [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

<p><img src="https://static.fsf.org/fsforg/graphics/infographics/windows8_infographic_es.png" width="700" height="1200" border="10"></a> </p>
