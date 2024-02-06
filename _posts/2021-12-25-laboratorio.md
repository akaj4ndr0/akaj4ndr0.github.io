---
layout: splash
title: "Cómo crear un laboratorio para hacking"
excerpt: "Laboratorio para hacking. Instalación y configuración Virtual Box. Instalación Kali Linux." 
date: 2021-12-25
classes: wide
tags:
  - Laboratorios
---

<br/>
# Cómo crear  un laboratorio para hacking

## Instalación de Virtual Box

El primer paso para crear nuestro laboratorio es descargarnos [Virtual Box](https://www.virtualbox.org/wiki/Downloads), un software de virtualización para crear máquinas virtuales
con instalaciones de sistemas operativos. Esto quiere decir que si tienes un ordenador con Windows, por ejemplo, puedes crear una máquina virtual con cualquier otro sistema operativo
sin necesidad de crear particiones en tu propio equipo.

Una vez instalado, sigues estos pasos para configurar una red NAT, que usaremos en las máquinas virtuales que instalaremos más adelante. En el menú archivo de Virtual Box, elige Preferencias, y en la opción Red crear una nueva red NAT.

<p><center><img src="../assets/images/laboratorio/preferencias.png" alt="preferencias red Virtual Box"></center></p>
<p><center><img src="../assets/images/laboratorio/crear-red.png" alt="crear red Virtual Box"></center></p>


## Descarga la imagen Kali

Kali Linux es una distribución basada en Debian GNU/Linux diseñada especialmente para la auditoría y seguridad informática. Desde la página oficial de [Kali-Linux](https://www.kali.org/get-kali/#kali-bare-metal) descarga el instalador de kali eligiendo la opción Bare Metal.

<img src="../assets/images/laboratorio/instalador-kali.png" alt="instalador">

<img src="../assets/images/laboratorio/instalador-kali2.png" alt="instalador">

## Instalación de la máquina virtual Kali

Una vez instalado Virtual Box y descargada la imagen de Kali, vamos a instalar Kali en nuestro equipo.
Ejecuta el software de virtualización Virtual Box y elige la pestaña <strong><i>Nueva</i></strong>.

<img src="../assets/images/laboratorio/maquinakali1.png" alt="Instalando Kali 1">

A continuación da un nombre a tu máquina virtual, escribe Linux en la opción Tipo, y elige la versión de Debian (64-bit).

<p><center><img src="../assets/images/laboratorio/maquinakali2.png" alt="Instalando Kali 2"></center></p>

Elige la cantidad de memoria RAM reservada para la máquina virtual según las características de tu equipo anfitrión.

<p><center><img src="../assets/images/laboratorio/maquinakali3.png" alt="Instalando Kali 3"></center></p>

Deja las siguientes opciones por defecto.

<p><center><img src="../assets/images/laboratorio/maquinakali4.png" alt="Instalando Kali 4"></center></p>

<p><center><img src="../assets/images/laboratorio/maquinakali5.png" alt="Instalando Kali 5"></center></p>

<p><center><img src="../assets/images/laboratorio/maquinakali6.png" alt="Instalando Kali 6"></center></p>

A continuación asigna el espacio del disco duro virtual que tendrá la máquina. 

<p><center><img src="../assets/images/laboratorio/maquinakali7.png" alt="Instalando Kali 7"></center></p>

Ahora vamos a configurar algunos aspectos de la máquina virtual.

En la pestaña <strong><i> Configuración </i></strong> haz click sobre <strong><i> Sistema </i></strong> y desmarca la casilla <strong><i>Disquete</i></strong>.

<p><center><img src="../assets/images/laboratorio/maquinakali8.png" alt="Instalando Kali 8"></center></p>

En la pestaña <strong><i> Procesador </i></strong> elige el número de procesadores según las características de tu equipo anfitrión.

<p><center><img src="../assets/images/laboratorio/maquinakali9.png" alt="Instalando Kali 9"></center></p>

A continuación en la opción <strong><i> Almacenamiento </i></strong> haz click sobre el icono del CD y selecciona el disco virtual óptico en la ruta de descarga de la imagen iso de Kali.

<p><center><img src="../assets/images/laboratorio/maquinakali10.png" alt="Instalando Kali 10"></center></p>

Una vez configurada la máquina haz click sobre la pestaña <strong><i> Iniciar </i></strong> y comenzará la instalación de Kali.

<p><center><img src="../assets/images/laboratorio/maquinakali11.png" alt="Instalando Kali 11"></center></p>

<p><center><img src="../assets/images/laboratorio/maquinakali12.png" alt="Instalando Kali 12"></center></p>

Selecciona el idioma y la ubicación.

<p><center><img src="../assets/images/laboratorio/maquinakali13.png" alt="Instalando Kali 13"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali14.png" alt="Instalando Kali 14"></center></p>

Asigna un nombre a la máquina.

<p><center><img src="../assets/images/laboratorio/maquinakali15.png" alt="Instalando Kali15"></center></p>

Deja la siguiente casilla en blanco.

<p><center><img src="../assets/images/laboratorio/maquinakali16.png" alt="Instalando Kali 16"></center></p>

Escribe el nombre completo del usuario.

<p><center><img src="../assets/images/laboratorio/maquinakali17.png" alt="Instalando Kali 17"></center></p>

Y escribe el nombre del usuario para la nueva cuenta y asignale una contraseña.

<p><center><img src="../assets/images/laboratorio/maquinakali18.png" alt="Instalando Kali 18"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali19.png" alt="Instalando Kali 19"></center></p>

Las siguiente opciones déjalas por defecto.

<p><center><img src="../assets/images/laboratorio/maquinakali20.png" alt="Instalando Kali 20"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali21.png" alt="Instalando Kali 21"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali22.png" alt="Instalando Kali 22"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali23.png" alt="Instalando Kali 23"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali24.png" alt="Instalando Kali 24"></center></p>

Marca la opción <strong><i>Sí</i></strong> y dale a continuar.

<p><center><img src="../assets/images/laboratorio/maquinakali25.png" alt="Instalando Kali 25"></center></p>

En la siguiene panatalla deja todas las opciones por defecto y dale a continuar.

<p><center><img src="../assets/images/laboratorio/maquinakali26.png" alt="Instalando Kali 26"></center></p>

Ahora marca la opción <strong><i>Sí</i></strong> y continúa con la instalación.

<p><center><img src="../assets/images/laboratorio/maquinakali27.png" alt="Instalando Kali 27"></center></p>

A continuación marca la segunda opción.

<p><center><img src="../assets/images/laboratorio/maquinakali28.png" alt="Instalando Kali 28"></center></p>

Dale a continuar y la instalación se habrá completado.

Inicia sesión con el usuario de la nueva cuenta y la contraseña asignada.

<p><center><img src="../assets/images/laboratorio/maquinakali30.png" alt="Instalando Kali 30"></center></p>

¡¡¡Ya tienes Kali Linux instalado en tu equipo!!!

<p><center><img src="../assets/images/laboratorio/maquinakali31.png" alt="Instalando Kali 31"></center></p>

Para poder compartir el portapapeles y poder arrastrar y soltar entre el equipo anfitrión y la máquina virtualizada haz lo siguiente.

<p><center><img src="../assets/images/laboratorio/maquinakali32.png" alt="Instalando Kali 32"></center></p>
<p><center><img src="../assets/images/laboratorio/maquinakali33.png" alt="Instalando Kali 33"></center></p>

No te olvides de configurar el adaptador de red de la máquina. Para ello apaga la máquina y desde el menú configuración, en red selecciona la opción red NAT y como nombre la que creamos en el paso
de instalación de Virtuabl Box.

<p><center><img src="../assets/images/laboratorio/asignar-red.png" alt="Configurando el adaptador de red en Virtual Box"></center></p>

## Instalación de la máquina Metasploitable

Metasploitable es una máquina virtual Linux creada intencionalmente vulnerable. Esta máquina virtual se puede utilizar para probar herramientas
de seguridad y practicar hacking de modo seguro. Puedes descargar la máquina desde este [enlace](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/).

Una vez descargado, descomprime el archivo y abre el software de virtualización Virtual Box. Haz click sobre la pestaña <strong><i>Nueva</i></strong> y asígnale un nombre
a la máquina virtual. Elige Linux en la opción Tipo y como versión elige Other Linux (64-bit).

<p><center><img src="../assets/images/laboratorio/metasploitable1.png" alt="Creando máquina virtual metasploitable"></center></p>

Asigna la memoria RAM según las características de tu equipo anfitrión.

<p><center><img src="../assets/images/laboratorio/metasploitable2.png" alt="Asignando memoria RAM a metasploitable"></center></p>

Ahora selecciona la opción "Usar un archivo de disco duro virtual existente" y haz click sobre el icono carpeta.

<p><center><img src="../assets/images/laboratorio/metasploitable3.png" alt="Creando máquina virtual metasploitable 2"></center></p>

Añade el archivo con extensión .vmdk que encontrarás en la ruta donde descomprimistes el archivo .zip de metasploitable2.

<p><center><img src="../assets/images/laboratorio/metasploitable4.png" alt="Creando máquina virtual metasploitable 3"></center></p>

Ahora ya puedes iniciar la máquina, el usuario y contraseña para acceder es <strong><i>msfadmin</i></strong>.

<p><center><img src="../assets/images/laboratorio/metasploitable6.png" alt="Iniciando metasploitable"></center></p>

¡¡¡ Hemos acabado !!! Ya tienes un laboratorio para realizar pruebas de seguridad y hacer Hacking de forma segura.

Configura el adaptador de red como hicimos en la máquina Kali.
