<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/117586521-891b8b00-b0cd-11eb-8a12-cf0b042755d5.png">
  <br />
 Guia Linux 
</h1>

<a href="https://github.com/VanitasuShieda?tab=followers">
         <img alt="followers" title="Follow for Updates" src="https://custom-icon-badges.demolab.com/github/followers/VanitasuShieda?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a> 


#### Una guía traducida sobre Linux que incluye sus múltiples entornos de escritorio, gestores de ventanas, herramientas y aplicaciones que te convertirán en un usuario de Linux mejor y más eficiente.

Fuente Original: https://github.com/mikeroyal/Linux-Guide-Spanish

 **Nota: Puedes convertir fácilmente este archivo tipo Markdown a PDF en [VSCode](https://code.visualstudio.com/) utilizando esta práctica extensión [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**
 
 
 # Tabla de Contenidos
 
- [Tabla de Contenidos](#tabla-de-contenidos)
  - [Recursos para aprender Linux](#recursos-para-aprender-linux)
    - [Repositorios de software y gestores de paquetes de Linux](#repositorios-de-software-y-gestores-de-paquetes-de-linux)
    - [Kernel de Linux](#kernel-de-linux)
    - [Systemd](#systemd)
    - [Canales de YouTube sobre Linux](#canales-de-youtube-sobre-linux)
    - [Linux Podcasts](#linux-podcasts)
- [Entornos de escritorio Linux](#entornos-de-escritorio-linux)
- [Gestores de ventanas de Linux](#gestores-de-ventanas-de-linux)
    - [Tiling (Gestores de ventanas en mosaico)](#tiling-gestores-de-ventanas-en-mosaico)
- [Empresas Linux](#empresas-linux)
- [Proveedores de hardware para Linux](#proveedores-de-hardware-para-linux)
- [Linux en la nube](#linux-en-la-nube)
- [Obtener software](#obtener-software)
  - [Gestores de paquetes (la forma principal)](#gestores-de-paquetes-la-forma-principal)
  - [Tiendas gráficas (para usuarios nuevos)](#tiendas-gráficas-para-usuarios-nuevos)
    - [GNOME Software Center](#gnome-software-center)
    - [KDE Plasma Discover Software Center](#kde-plasma-discover-software-center)
    - [App Outlet](#app-outlet)
  - [Formatos universales (multidistribución)](#formatos-universales-multidistribución)
    - [Flatpaks](#flatpaks)
    - [Snaps](#snaps)
    - [AppImages](#appimages)
  - [Compilar desde código fuente](#compilar-desde-código-fuente)
    - [¿Qué es el código fuente?](#qué-es-el-código-fuente)
    - [Requisitos previos](#requisitos-previos)
    - [Proceso típico de compilación](#proceso-típico-de-compilación)
      - [1 - Descargar el código fuente](#1---descargar-el-código-fuente)
      - [2 - Configurar la compilación](#2---configurar-la-compilación)
      - [3 - Compilar](#3---compilar)
      - [4 - Instalar](#4---instalar)
  - [Alternativas a Microsoft Office](#alternativas-a-microsoft-office)
  - [Secure \& Privacy Focused Web Browsers](#secure--privacy-focused-web-browsers)
    - [Privacy \& Security Focused Browser extensions](#privacy--security-focused-browser-extensions)
    - [Privacy-focused Search Engines](#privacy-focused-search-engines)
  - [Backups](#backups)
  - [Storage Disk Health](#storage-disk-health)
  - [Mejorar la duración de la batería](#mejorar-la-duración-de-la-batería)
  - [Herramientas para copiar/transferir archivos a tu sistema Linux](#herramientas-para-copiartransferir-archivos-a-tu-sistema-linux)
  - [Ejecutar aplicaciones Android en tu sistema Linux](#ejecutar-aplicaciones-android-en-tu-sistema-linux)
  - [Ejecutar aplicaciones de Windows en tu sistema Linux](#ejecutar-aplicaciones-de-windows-en-tu-sistema-linux)
  - [Edición profesional de audio y vídeo](#edición-profesional-de-audio-y-vídeo)
  - [Configuración de OBS Studio](#configuración-de-obs-studio)
    - [Complementos y temas útiles de terceros para OBS Studio.](#complementos-y-temas-útiles-de-terceros-para-obs-studio)
- [Gaming](#gaming)
    - [Linux Gaming Resources \& Tweak Tools](#linux-gaming-resources--tweak-tools)
    - [Game Controllers](#game-controllers)
  - [Steam](#steam)
  - [Enable Proton in Steam](#enable-proton-in-steam)
  - [ProtonDB](#protondb)
  - [Lutris](#lutris)
    - [Epic Games Store integration](#epic-games-store-integration)
    - [Blizzard Battle.net intgeration](#blizzard-battlenet-intgeration)
    - [EA Play integration](#ea-play-integration)
    - [Origin integration](#origin-integration)
    - [Ubisoft Connect integration](#ubisoft-connect-integration)
    - [GOG Galaxy integration](#gog-galaxy-integration)
    - [Playnite](#playnite)
  - [GameHub](#gamehub)
  - [Epic Games Store](#epic-games-store)
  - [Game Streaming](#game-streaming)
    - [Cloud Game Streaming](#cloud-game-streaming)
    - [Local Game Streaming](#local-game-streaming)
  - [Game Emulators](#game-emulators)
    - [Frontends](#frontends)
    - [Nintendo GameCube \& Wii](#nintendo-gamecube--wii)
    - [Nintendo Switch](#nintendo-switch)
    - [Nintendo 64](#nintendo-64)
    - [Nintendo DS](#nintendo-ds)
    - [Super Nintendo Entertainment System (SNES)](#super-nintendo-entertainment-system-snes)
    - [Nintendo Entertainment System](#nintendo-entertainment-system)
    - [Game Boy Advance](#game-boy-advance)
    - [DOS](#dos)
    - [Atari](#atari)
    - [Sega Dreamcast](#sega-dreamcast)
    - [PlayStation Portable](#playstationportable)
    - [PlayStation 1](#playstation-1)
    - [PlayStation 2](#playstation-2)
    - [PlayStation 3](#playstation-3)
    - [Xbox](#xbox)
    - [MAME](#mame)
  - [Hardware Performance(CPU, GPU, Gaming Peripherals)](#hardware-performancecpu-gpu-gaming-peripherals)
    - [NVIDIA](#nvidia)
    - [AMD](#amd)
    - [Intel ARC](#intel-arc)
    - [Gaming Peripherals](#gaming-peripherals)
  - [Performance Benchmarks](#performance-benchmarks)
  - [Wine](#wine)
    - [Winetricks](#winetricks)
- [WireGuard](#wireguard)
- [Linux Security Hardening](#linux-security-hardening)
    - [Security Standards, Frameworks and Benchmarks](#security-standards-frameworks-and-benchmarks)
    - [Security Tools](#security-tools)
  - [File systems](#file-systems)
- [Debian](#debian)
  - [Getting Started with Debian](#getting-started-with-debian)
- [Ubuntu](#ubuntu)
  - [Getting Started with Ubuntu](#getting-started-with-ubuntu)
  - [Additional Ubuntu Tools \& Resources for Enterprise \& Small Businesses](#additional-ubuntu-tools--resources-for-enterprise--small-businesses)
  - [Removing Snap and adding Flatpak support](#removing-snap-and-adding-flatpak-support)
  - [Setting up PipeWire for Ubuntu/Debian](#setting-up-pipewire-for-ubuntudebian)
    - [Reverting Changes](#reverting-changes)
- [Pop!\_OS](#pop_os)
  - [Getting Started with Pop!\_OS](#getting-started-with-pop_os)
  - [Pop Shop](#pop-shop)
- [Linux Mint](#linux-mint)
    - [Getting Started with Linux Mint](#getting-started-with-linux-mint)
    - [Installing KDE Plasma on Linux Mint](#installing-kde-plasma-on-linux-mint)
    - [Enable Firewall](#enable-firewall)
    - [Getting Software](#getting-software)
      - [Linux Mint Software Center](#linux-mint-software-center)
- [Fedora/CentOS Stream/RHEL](#fedoracentos-streamrhel)
  - [Getting Started with FedoraCentOS Stream/RHEL](#getting-started-with-fedoracentos-streamrhel)
  - [Fedora, Red Hat Enterprise Linux (RHEL) and CentOS Stream Development Cycle](#fedora-red-hat-enterprise-linux-rhel-and-centos-stream-development-cycle)
- [SUSE/openSUSE](#suseopensuse)
    - [Getting Started with SUSE/openSUSE](#getting-started-with-suseopensuse)
- [Arch Linux](#arch-linux)
  - [Getting Started Arch Linux](#getting-started-arch-linux)
    - [Arch Linux User Repository (AUR)](#arch-linux-user-repository-aur)
    - [Good Arch Linux Desktops for everyday use.](#good-arch-linux-desktops-for-everyday-use)
- [NixOS](#nixos)
  - [Getting Started NixOS](#getting-started-nixos)
  - [NixOS Developer Resources](#nixos-developer-resources)
  - [NixOS Tools and Modules](#nixos-tools-and-modules)
  - [NixOS Desktop](#nixos-desktop)
  - [Contribute](#contribute)
  - [License](#license)
 
1.  [File systems](https://github.com/VanitasuShieda/Linux-Guide-Spanish#file-systems) 

2.  [Debian](https://github.com/VanitasuShieda/Linux-Guide-Spanish#debian)

3.  [Ubuntu](https://github.com/VanitasuShieda/Linux-Guide-Spanish#ubuntu)

4.  [Pop!_OS](https://github.com/VanitasuShieda/Linux-Guide-Spanish#pop_os)

5.  [Linux Mint](https://github.com/VanitasuShieda/Linux-Guide-Spanish#linux-mint)

6.  [Fedora/CentOS Stream/Red Hat Enterprise Linux](https://github.com/VanitasuShieda/Linux-Guide-Spanish#fedoracentos-streamrhel)

7.  [SUSE/openSUSE](https://github.com/VanitasuShieda/Linux-Guide-Spanish#suseopensuse)

8.  [Arch Linux](https://github.com/VanitasuShieda/Linux-Guide-Spanish#arch-linux)

9.  [NixOS](https://github.com/VanitasuShieda/Linux-Guide-Spanish#nixos)

 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/117586523-8a4cb800-b0cd-11eb-95e7-68b97bd43c00.png">
  <br /> 
</p>

 
## Recursos para aprender Linux

[Volver al Inicio](#tabla-de-contenidos)

 * [A Brief History of Linux](https://www.digitalocean.com/community/tutorials/brief-history-of-linux)

 * [Contribute to FOSS](https://github.com/KillYourFM/contribute-foss) by Jason Evangelho, is an entensive Wiki page on how to contribute to the Linux and FOSS community.

 * [The Open Source Computer Science Degree by Forrest Knight](https://github.com/ForrestKnight/open-source-cs)

 * [MikeRoyal Windows Subsystem for Linux(WSL) Guide](https://github.com/mikeroyal/WSL-Guide)

 * [SUSE Training and Certification Program](https://training.suse.com/)
 
 * [Red Hat Training and Certification Program](https://www.redhat.com/en/services/training-and-certification)

 * [Linux Foundation Training and Certification Program](https://training.linuxfoundation.org/certification/)

NOTA: Link a sitio web oficial en ingles.

[Linux Professional Institute(LPI)](https://www.lpi.org) es una organización sin fines de lucro. Linux Professional Institute (LPI) es el estándar global de certificación y la organización de apoyo profesional para profesionales del código abierto. Con más de 175,000 personas certificadas, es el primer y mayor organismo de certificación neutro respecto a proveedores para Linux y software de código abierto en el mundo.

[Linux Foundation](https://www.linuxfoundation.org/)  alberga a Linux, Node.js y otros proyectos críticos que forman la columna vertebral de los servicios de internet modernos, incluido Pinterest. Unirse a The Linux Foundation es una excelente manera para que empresas consolidadas como la nuestra apoyen a esas comunidades.

[Cloud Native Computing Foundation (CNCF)](https://www.cncf.io/) alberga componentes críticos de la infraestructura tecnológica global. CNCF reúne a los principales desarrolladores, usuarios finales y proveedores del mundo y organiza las conferencias de desarrolladores de código abierto más grandes. CNCF forma parte de la organización sin fines de lucro Linux Foundation.

[RISC-V Foundation](https://riscv.org/) es una corporación sin fines de lucro controlada por sus miembros para promover la adopción e implementación de la arquitectura de conjunto de instrucciones (ISA) RISC-V, libre y abierta.

[Open Source Security Foundation (OpenSSF)](https://openssf.org/) es una colaboración intersectorial que reúne a líderes para mejorar la seguridad del software de código abierto mediante la construcción de una comunidad más amplia, iniciativas específicas y buenas prácticas. OpenSSF agrupa iniciativas de seguridad de código abierto bajo una misma fundación para acelerar el trabajo con el apoyo de múltiples industrias. Junto con la Core Infrastructure Initiative y la Open Source Security Coalition, incluirá nuevos grupos de trabajo que aborden la divulgación de vulnerabilidades, las herramientas de seguridad y más.

[Free Software Foundation (FSF)](https://www.fsf.org/) es una organización sin fines de lucro con la misión mundial de promover la libertad de los usuarios de computadoras.


### Repositorios de software y gestores de paquetes de Linux
[Volver al Inicio](#tabla-de-contenidos)



[dpkg(Debian Package)](https://www.digitalocean.com/community/tutorials/dpkg-command-in-linux) es el sistema de gestión de paquetes en Debian y sus derivados del sistema operativo.

[DEB](https://www.debian.org/distrib/packages) es un archivo de paquete de software de Debian usado en sistemas Linux Debian-base como Debian, Ubuntu, Linux Mint y Pop!_OS.

[APT (Advanced Package Tool)](https://en.wikipedia.org/wiki/APT_(software)) es un sistema de gestión de paquetes de nivel superior, que se utiliza más comúnmente que dpkg ya que puede obtener paquetes desde ubicaciones remotas.


[Nala](https://gitlab.com/volian/nala) es una interfaz de línea de comandos para el gestor de paquetes APT.

[Synaptic Package Manager](https://en.wikipedia.org/wiki/Synaptic_%28software%29) es una interfaz de línea de comandos para el gestor de paquetes APT.

[PPA(Personal Package Archive)](https://help.launchpad.net/Packaging/PPA) es un conjunto de repositorios de software que pueden distribuir software y actualizaciones directamente a los usuarios de Ubuntu. Crea tu paquete fuente, súbelo y Launchpad compilará los binarios y luego los alojará en tu propio repositorio apt.

[PackageKit](https://www.freedesktop.org/software/PackageKit/) es un conjunto de aplicaciones de software diseñado para proporcionar una interfaz coherente y de alto nivel para varios sistemas de gestión de paquetes en Linux.

[EPEL (Extra Packages for Enterprise Linux)](https://docs.fedoraproject.org/en-US/epel/) es un proyecto de repositorio de la comunidad, gratuito y de código abierto, del equipo de Fedora que proporciona paquetes adicionales de software de alta calidad para distribuciones Linux como RHEL (Red Hat Enterprise Linux) y CentOS Stream.

[DNF(Dandified Packaging Tool)](https://docs.fedoraproject.org/en-US/quick-docs/dnf/) es un gestor de paquetes que instala, actualiza y elimina paquetes en Fedora y es el sucesor de YUM (Yellow-Dog Updater Modified). DNF facilita el mantenimiento de paquetes comprobando automáticamente las dependencias y determinando las acciones necesarias para instalar paquetes.

[Micro DNF](https://fedoraproject.org/wiki/Changes/MajorUpgradeOfMicrodnf) es una implementación ligera en C de DNF, diseñada para realizar acciones de empaquetado simples cuando no necesitas DNF completo y deseas los entornos más pequeños posibles. Consulta [Micro DNF GitHub](https://github.com/rpm-software-management/microdnf).

[Fedora Updates System](https://bodhi.fedoraproject.org/) es un lugar para crear, probar y publicar actualizaciones de paquetes para Fedora.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168177134-85efb869-c2d5-4d7a-9a53-a3f61a2d74e2.png">
<br />
Fedora Updates System
</p>

[RPM Package Manager (RPM)](https://rpm.org/) es un potente sistema de gestión de paquetes capaz de compilar software desde el código fuente en paquetes fácilmente distribuibles, instalar, actualizar y desinstalar software empaquetado, y consultar información detallada sobre el software empaquetado, esté o no instalado.

[YUM (Yellowdog Updater, Modified)](https://www.digitalocean.com/community/tutorials/what-is-yum) es una utilidad de gestión de paquetes para sistemas Linux que utiliza el gestor de paquetes RPM.

[RPM Fusion](https://rpmfusion.org/) es un repositorio de software que proporciona software que el Proyecto Fedora o Red Hat no quieren incluir. Ese software se ofrece como RPMs precompilados para todas las versiones actuales de Fedora y versiones actuales de Red Hat Enterprise Linux o sus clones; puedes usar los repositorios de RPM Fusion con herramientas como yum y PackageKit.

[ROM OSTree](https://ostreedev.github.io/ostree/) es un sistema híbrido de imagen/paquete. Combina libostree como formato base de imagen y acepta RPM tanto en el lado cliente como en el servidor, compartiendo código con el proyecto dnf; específicamente libdnf. De este modo reúne muchos de los beneficios de ambos proyectos.

[YaST](https://yast.opensuse.org/) es una herramienta de instalación y configuración para openSUSE y las distribuciones SUSE Linux Enterprise. Presenta una interfaz fácil de usar y potentes capacidades de configuración.

[Zypper](https://software.opensuse.org/package/zypper) es un gestor de paquetes en línea de comandos que usa libzypp. Proporciona funciones como acceso a repositorios, resolución de dependencias, instalación de paquetes, etc. Los repositorios de Zypper son similares a los que utiliza YaST, que también hace uso de libzypp.

[Pacman](https://archlinux.org/pacman/) es una utilidad que gestiona paquetes de software en Arch Linux. Usa archivos comprimidos simples como formato de paquete y mantiene una base de datos de paquetes basada en texto (más bien una jerarquía), por si acaso es necesario realizar algún ajuste manual.

[Arch Linux User Repository (AUR)](https://aur.archlinux.org/) es un repositorio de software que contiene miles de scripts de compilación, para compilar casi 68,000 paquetes instalables desde el código fuente usando la aplicación makepkg de Arch Linux.

###  Kernel de Linux

[Volver al Inicio](#tabla-de-contenidos)

El núcleo (Kernel) Linux es el componente principal de un sistema operativo (SO) Linux y es la interfaz central entre el hardware de un ordenador y sus procesos. Se encarga de la comunicación entre ambos, gestionando los recursos de la forma más eficiente posible.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/219989150-5b6d5f1d-e7f8-4c5e-8fb9-5359f1acc54d.png">
  <br />
Linux kernel layout
</p>

**Categorías para las versiones del kernel de Linux:**

* **Prepatch:** **Pre parche:** Los kernels Prepatch o «RC (Realease Candidate)» son versiones preliminares del kernel principal destinadas principalmente a otros desarrolladores de kernels y entusiastas de Linux. Deben compilarse desde el código fuente y suelen contener nuevas características que deben probarse antes de poder incluirse en una versión estable. Los kernels Prepatch son mantenidos y publicados por Linus Torvalds.
    
* **Mainline:** **Línea principal:** El árbol de la línea principal es mantenido por  [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds). Es el árbol donde se introducen todas las nuevas características y donde se producen todos los nuevos y emocionantes desarrollos. Los nuevos núcleos de la línea principal se publican cada 9-10 semanas.
    
* **Stable:** **Estable:** Después de cada lanzamiento de un kernel mainline, se considera «estable». Cualquier corrección de errores para un kernel estable se retroporta desde el árbol mainline y la aplica un mantenedor de kernel estable designado. Por lo general, solo hay unos pocos lanzamientos de kernel con correcciones de errores hasta que el siguiente kernel mainline está disponible, a menos que se designe como «kernel de mantenimiento a largo plazo». Las actualizaciones del núcleo estable se lanzan según sea necesario, normalmente una vez a la semana.
    
* **Longterm:**  **A largo plazo:** Normalmente hay varios lanzamientos de núcleos de «mantenimiento a largo plazo» con el fin de retroportar correcciones de errores para árboles de núcleos más antiguos. Solo se aplican correcciones de errores importantes a estos núcleos y no suelen tener lanzamientos muy frecuentes, especialmente en el caso de los árboles más antiguos. 


**Núcleos actuales de versión a largo plazo**
 
|Versión |Responsable del mantenimiento |    Fecha de lanzamiento |Fecha prevista de fin de vida útil|
|------|------|-----|-----|
|6.18 |Greg Kroah-Hartman & Sasha Levin |2025-11-30 |Dec, 2026|
|6.12 |Greg Kroah-Hartman & Sasha Levin |2024-11-17 |Dec, 2026|
|6.6 |Greg Kroah-Hartman & Sasha Levin |2023-10-30 |Dec, 2026|
|6.1 |Greg Kroah-Hartman & Sasha Levin |2022-12-11 |Dec, 2027|
|5.15 |Greg Kroah-Hartman & Sasha Levin |2021-10-31 |Oct, 2026|
|5.10 |Greg Kroah-Hartman & Sasha Levin |2020-12-13 |Dec, 2026|
|5.4 |Greg Kroah-Hartman & Sasha Levin 	|2019-11-24 |Dec, 2025|
|4.19 |Greg Kroah-Hartman & Sasha Levin |2018-10-22 |Dec, 2024|
|4.14 |Greg Kroah-Hartman & Sasha Levin |2017-11-12 |Jan, 2024|

### Systemd
[Volver al Inicio](#tabla-de-contenidos)

[systemd](https://systemd.io/) Es un conjunto de componentes básicos para un sistema Linux. Proporciona un administrador de sistemas y servicios que se ejecuta como PID 1 e inicia el resto del sistema. Ofrece capacidades de paralelización agresivas, utiliza activación de socket y D-Bus para iniciar servicios, ofrece inicio bajo demanda de demonios, realiza un seguimiento de los procesos utilizando grupos de control de Linux, mantiene puntos de montaje y automontaje, e implementa una elaborada lógica de control de servicios basada en dependencias transaccionales. systemd es compatible con scripts de inicio SysV y LSB y funciona como sustituto de [SysVinit](https://wiki.archlinux.org/title/SysVinit).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/190265681-2266a967-096f-43be-a7ca-ae48815aa5e2.png">
  <br />
Systemd Overview
</p>

[init](https://en.wikipedia.org/wiki/Init) Es el padre de todos los procesos Linux con PID o ID de proceso 1. Es el primer proceso que se inicia cuando se arranca un ordenador y se ejecuta hasta que se apaga el sistema. **init significa inicialización**. 

<p align="center">
  <img
    src="./assets/images/linux-boot-process-es.png"
    alt="Diagrama del proceso de arranque de Linux">
  <br />
Proceso de Arranque de Linux
</p>

> Nota: Este diagrama representa el proceso de arranque clásico.
> En sistemas modernos, `systemd` reemplaza a `init` y los runlevels.


### Canales de YouTube sobre Linux

[Volver al Inicio](#tabla-de-contenidos)

// Spanish 


  * [Linux Inmutable](https://www.youtube.com/@linuxinmutable)

  * [Ezku](https://www.youtube.com/@ezku100)

  * [Kimu x64](https://www.youtube.com/@kimu_x64)

  * [xeyt](https://www.youtube.com/@xeyt3976)

Nota Personal: estos son algunos de los creadores de contenido que me gustan por su contenido y acostumbro ver.


// English 

 * [Jeff Geerling](https://www.youtube.com/c/JeffGeerling)

 * [DistroTube](https://www.youtube.com/c/DistroTube)
 
 * [Chris Titus Tech](https://www.youtube.com/c/ChrisTitusTech)
 
 * [Level1Techs](https://www.youtube.com/c/Level1Techs)
 
 * [Level1Linux](https://www.youtube.com/c/TekLinux)
 
 * [The Linux Experiment](https://www.youtube.com/c/TheLinuxExperiment)
 
 * [Learn Linux TV](https://www.youtube.com/c/LearnLinuxtv)
 
 * [TechHut](https://www.youtube.com/c/TechHutHD)
 
 * [Gardiner Bryant | TLG](https://www.youtube.com/c/GardinerBryant)
 
 * [LinuxScoop](https://www.youtube.com/c/LinuxScoop)
 
 * [Linux For Everyone](https://www.youtube.com/c/LinuxForEveryone)
 
 * [InfinitelyGalactic](https://www.youtube.com/c/InfinitelyGalactic)
 
 * [Diolinux(Brazil)](https://www.youtube.com/c/DiolinuxBr)
 
 * [Switched to linux](https://www.youtube.com/c/SwitchedtoLinux)
 
 * [DorianDotSlash](https://www.youtube.com/c/Doriandotslash)
 
 * [This Week in Linux](https://www.youtube.com/c/TunnellVision)
 
 * [The Linux Cast](https://www.youtube.com/c/TheLinuxCast)
 
 ### Linux Podcasts
 
 [Volver al Inicio](#tabla-de-contenidos)
 
// Spanish
  * [Podcast Linux](https://podcastlinux.com/)
  
  * [Reset](https://www.tupodcast.com/@reset)
  * [Reset (ApplePodcast)](https://podcasts.apple.com/us/podcast/reset/id1796972768)
  
  
  * [Linux Radio](https://open.spotify.com/show/38mWdd0CABMNaLYQe7RezU?si=818f8aa149394de5)

  * [Ubuntu y otras hierbas](https://www.youtube.com/playlist?list=PLrtOacI496LQE-2js3gwgv2upN72zJpO8)
  * [Ubuntu y otras hierbas (ApplePodcast)](https://podcasts.apple.com/es/podcast/ubuntu-y-otras-hierbas/id1239347221)
  
  * [Atareao con Linux](https://open.spotify.com/show/2v0fC8PyeeUTQDD67I0mKW?si=a35133aba8334ea2)
  * [Atareao con Linux (ApplePodcast)](https://podcasts.apple.com/ar/podcast/atareao-con-linux/id1437197202)
 
  * [Reca Linux](https://open.spotify.com/show/70Ld7IRVbFAZuMdd60BrLz?si=42b5b708345641f8)

  * [YT - KDE Express. Comunidad y Software Libre](https://www.youtube.com/playlist?list=PLnYTvqeUgaCFSbofkYgs0KyAVnU3BlqB7)
  * [Spotify - KDE Express. Comunidad y Software Libre](https://open.spotify.com/show/5sXfRJBfy8jiE5qXIkipjB?si=2896ec15202d4826)

//English

 * [Jupiter Broadcasting](https://www.youtube.com/c/JupiterBroadcasting)
 
 * [Destination Linux](https://www.youtube.com/channel/UC6vBLLp4V4cO6-58WBOIO2Q)
 
 * [Late Night Linux](https://www.youtube.com/c/LateNightLinux)
 
 * [Linux Game Cast](https://www.youtube.com/c/linuxgamecast)

# Entornos de escritorio Linux

 [Volver al Inicio](#tabla-de-contenidos)

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/189545533-4621b1a6-15c2-406a-9b89-b3ed43e47762.png">
  <br />
  KDE Plasma Desktop
</h1>

[KDE Plasma Desktop](https://kde.org), es un bonito escritorio similar al de Windows que se utiliza para navegar por Internet, mantenerse en contacto con compañeros de trabajo, amigos y familiares, gestionar archivos, disfrutar de música y vídeos, y ser creativo y productivo en el trabajo. La comunidad KDE desarrolla y mantiene más de 200 aplicaciones que se ejecutan en cualquier escritorio Linux y, a menudo, también en otras plataformas.

![image](https://user-images.githubusercontent.com/45159366/189545547-7e048fad-d7e5-41c3-aaf4-af08a60135e8.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/189545550-b510fb23-846c-4286-aeb2-6b0f658a8a5f.png">
  <br />
  GNOME Desktop
</h1>

[GNOME Desktop](https://www.gnome.org/), GNOME, una forma fácil y elegante de utilizar tu ordenador, está diseñado para que tú tengas el control y puedas hacer todo lo que necesites.

![image](https://user-images.githubusercontent.com/45159366/189545552-e83c423b-02a8-4604-b37b-5b93b814a354.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/52540606-4af15e80-2d40-11e9-8704-3308568fd105.png">
  <br />
  MATE Desktop
</h1>

[MATE Desktop](https://mate-desktop.org/), es la continuación del entorno de escritorio GNOME 2.  

![image](https://user-images.githubusercontent.com/45159366/54108470-4c429500-4399-11e9-8b8a-3ad0e831214b.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/52040486-66609c00-24ec-11e9-9f2d-468a387a9ce1.png">
  <br />
  Budgie Desktop
</h1>

[Budgie Desktop](https://getsol.us/solus/experiences/), Un escritorio moderno y con numerosas funciones, diseñado para no interferir en el trabajo del usuario. 

![budgie-desktop](https://user-images.githubusercontent.com/45159366/60866577-899b2000-a1dd-11e9-8d8f-48716ac14fba.png?raw=true "budgie-desktop")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/52910555-f3765580-324d-11e9-8597-99e6f3241701.png">
  <br />
  XFCE Desktop
</h1>

[XFCE Desktop](https://xfce.org/), Un entorno de escritorio ligero para sistemas operativos similares a UNIX. 


![image](https://user-images.githubusercontent.com/45159366/52910530-9a0e2680-324d-11e9-8e55-a7450c7fc316.png?raw=true "image")


<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/52699255-31136f80-2f2a-11e9-865c-75d7ee219cef.png">
  <br />
  Cinnamon Desktop
</h1>

[Cinnamon Desktop](https://cinnamon-spices.linuxmint.com/), Un escritorio Linux que ofrece funciones avanzadas e innovadoras y una experiencia de usuario tradicional.

![image](https://user-images.githubusercontent.com/45159366/54108466-4a78d180-4399-11e9-90aa-9340ca45ab1a.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/51798500-3782b700-21c8-11e9-83d6-9822ca172425.png">
  <br />
  LXQt Desktop
</h1>

[LXQt Desktop](https://lxqt.org/),El entorno de escritorio ligero Qt.

![image](https://user-images.githubusercontent.com/45159366/60866574-8869f300-a1dd-11e9-8c56-da585fe2d581.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/53791160-97623100-3edd-11e9-9015-9319a857e1b0.png">
  <br />
  Pantheon Desktop
</h1>

[Pantheon Desktop](https://elementary.io/), un escritorio GTK basado en el software GNOME mantenido por los desarrolladores de elementary OS.

![image](https://user-images.githubusercontent.com/45159366/53000646-ba6ceb00-33dd-11e9-93dd-fbd262cf1ce8.jpeg?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/63739716-1d36b780-c843-11e9-94f1-2085af4005a3.png">
  <br />
  Deepin Desktop
</h1>

[Deepin Desktop](https://www.deepin.org/en/dde/), Un entorno de escritorio doméstico elegante, fácil de usar y fiable.

![image](https://user-images.githubusercontent.com/45159366/57979064-21923f80-79cd-11e9-842a-55ab9ec73d41.jpeg?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/62761602-e8052980-ba3b-11e9-986d-4a2d801a83b1.png">
  <br />
  Unity Desktop
</h1>

[Unity Desktop](https://unity8.io/), Una interfaz gráfica para el entorno de escritorio GNOME desarrollada originalmente por Canonical Ltd.

![unity-desktop](https://user-images.githubusercontent.com/45159366/62761607-e9ceed00-ba3b-11e9-900a-591c53152e1f.png?raw=true "unity-desktop")

# Gestores de ventanas de Linux

 [Volver al Inicio](#tabla-de-contenidos)

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/189545533-4621b1a6-15c2-406a-9b89-b3ed43e47762.png">
  <br />
  KWin WM
</h1>

[KWin](https://invent.kde.org/plasma/kwin) Es el gestor de ventanas del escritorio KDE Plasma. Te ofrece un control total sobre tus ventanas, asegurándose de que no te estorben y te ayuden en tus tareas.  Dibuja la decoración de las ventanas, la barra situada en la parte superior de cada ventana con botones (configurables) como cerrar, maximizar y minimizar.

![image](https://user-images.githubusercontent.com/45159366/189545547-7e048fad-d7e5-41c3-aaf4-af08a60135e8.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/189545550-b510fb23-846c-4286-aeb2-6b0f658a8a5f.png">
  <br />
  Mutter WM
</h1>

[Mutter](https://gitlab.gnome.org/GNOME/mutter) es un servidor de pantalla Wayland y una biblioteca de gestión y composición de ventanas X11. Cuando se utiliza como servidor de pantalla Wayland, se ejecuta sobre KMS y libinput. Implementa el lado compositor del protocolo central Wayland, así como varias extensiones del protocolo. 

![image](https://user-images.githubusercontent.com/45159366/189545552-e83c423b-02a8-4604-b37b-5b93b814a354.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/189555888-7809aaca-e358-4a63-9a5b-c27337833cab.png">
  <br />
 FluxBox
</h1>

[Fluxbox](https://fluxbox.org/) Es un gestor de ventanas apilables para el sistema X Window, basado en Blackbox.

![fluxbox](https://user-images.githubusercontent.com/45159366/189555437-825c9bc9-5630-4985-bc84-b5a2d55b0865.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/189502362-0569c67b-34b0-43ae-8a54-01b3e00741e2.png">
  <br />
 OpenBox
</h1>

[Openbox](http://openbox.org/) Es un gestor de ventanas apilable ligero, potente y altamente configurable con amplia compatibilidad con los estándares.

![openbox](https://user-images.githubusercontent.com/45159366/189502364-368f1873-5d3e-4819-8dc6-0c14606d1d9a.png?raw=true "image")


### Tiling (Gestores de ventanas en mosaico)

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/58378567-d804a000-7f4a-11e9-9b60-db6a0136261f.png">
  <br />
  i3 wm
</h1>

[i3-wm](https://i3wm.org/), Un gestor de ventanas en mosaico para X11.


![i3-wm](https://user-images.githubusercontent.com/45159366/58378568-d935cd00-7f4a-11e9-8dd1-3c2a92986a68.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/58737339-f7218880-83b5-11e9-8315-69f1405b1719.png">
  <br />
 awesome wm
</h1>

[Awesome](https://awesomewm.org/), Un gestor de ventanas de marco de trabajo de última generación y altamente configurable para X. 

![awesome-wm](https://user-images.githubusercontent.com/45159366/58737340-f7ba1f00-83b5-11e9-98f2-d801ed881396.png?raw=true "image")

<h1 align="center">
  <img src="https://user-images.githubusercontent.com/45159366/60765336-04cdcc00-a04e-11e9-999a-3dd7547f9bb0.png">
  <br />
  Bspwm
</h1>

[Bspwm](https://github.com/baskerville/bspwm), Un gestor de ventanas basado en la partición binaria del espacio, centrado en la eficiencia de los recursos.

![bspwm](https://user-images.githubusercontent.com/45159366/60765269-d7cce980-a04c-11e9-9a69-3ee236c07a8f.png?raw=true "image")

<h1 align="center">
  <img src="https://raw.githubusercontent.com/hyprwm/Hyprland/main/assets/header.svg">
  <br />
  Hyprland
</h1>

[Hyprland](https://github.com/hyprwm/Hyprland), Hyprland es un compositor Wayland 100 % independiente y dinámico que no sacrifica su aspecto.

![Hyprland](https://camo.githubusercontent.com/14fcfb6512ea7aaa45f6381268e34802a234418664c4dfe7a86e1ab99a0f1ca7/68747470733a2f2f692e6962622e636f2f433179546230722f66616c662e706e67 "image")


# Empresas Linux

 [Volver al Inicio](#tabla-de-contenidos)

 * [Red Hat](https://www.redhat.com/en) creadores de Red Hat Enterprise Linux y patrocinadores de la empresa [Fedora Project](https://getfedora.org/).

 * [Canonical](https://canonical.com) creadores de Ubuntu Desktop y Server.

 * [SUSE](https://www.suse.com) creadores de SUSE Enterprise Linux.

 * [Manjaro](https://manjaro.org) creadores de Manjaro Linux.

 * [System76](https://system76.com) creadores de [Pop!_OS](https://pop.system76.com/)

# Proveedores de hardware para Linux

[Volver al Inicio](#tabla-de-contenidos)

 * [Valve](https://www.valvesoftware.com/) creadores de [Steam Deck](http://www.steamdeck.com/).

 * [System76](https://system76.com)

 * [Tuxedo Computers](https://www.tuxedocomputers.com/en)

 * [Entroware](https://www.entroware.com/store/)
 
 * [Pine64](https://pine64.com/)

 * [SlimBooks](https://slimbook.es/en/)

 * [Star Labs](https://starlabs.systems/)

 * [Lenovo](https://techtoday.lenovo.com/us/en/workstations/linux)

 * [HP](https://hpdevone.com/)

 * [Dell](https://www.dell.com/en-us/work/shop/overview/cp/linuxsystems) 
 
 * [Framework Laptop](https://frame.work/), Tenga en cuenta que deberá instalar Linux en su dispositivo, ya que no viene incluido con el portátil.

# Linux en la nube

 [Volver al Inicio](#tabla-de-contenidos)

[Amazon Linux 2](https://aws.amazon.com/amazon-linux-2/) Una nueva generación de Amazon Linux, un sistema operativo Linux para servidores de Amazon Web Services (AWS). Proporciona un entorno de ejecución seguro, estable y de alto rendimiento para desarrollar y ejecutar aplicaciones empresariales y en la nube. Con Amazon Linux 2, obtienes un entorno de aplicaciones que ofrece soporte a largo plazo con acceso a las últimas innovaciones del ecosistema Linux.

[Amazon Linux AMI](https://aws.amazon.com/amazon-linux-ami/) Es una imagen de Linux compatible y mantenida por Amazon Web Services para su uso en Amazon Elastic Compute Cloud (Amazon EC2). Está diseñada para proporcionar un entorno de ejecución estable, seguro y de alto rendimiento para las aplicaciones que se ejecutan en Amazon EC2.

[Bottlerocket](https://aws.amazon.com/bottlerocket/) es un sistema operativo de código abierto basado en Linux, diseñado específicamente por Amazon Web Services para ejecutar contenedores en máquinas virtuales o hosts bare metal. La mayoría de los clientes actuales ejecutan aplicaciones en contenedores en sistemas operativos de uso general que se actualizan paquete por paquete, lo que dificulta la automatización de las actualizaciones del sistema operativo.

 * [Getting Started with Bottlerocket and Certified AWS Partners](https://aws.amazon.com/blogs/apn/getting-started-with-bottlerocket-and-certified-aws-partners/)

 * [Using Bottlerocket with Amazon ECS](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-bottlerocket.html)

 * [Ubuntu on AWS](https://ubuntu.com/aws)

[CBL-Mariner](https://github.com/microsoft/CBL-Mariner) es una distribución interna de Linux para la infraestructura en la nube y los productos y servicios periféricos de Microsoft. CBL-Mariner está diseñado para proporcionar una plataforma coherente para estos dispositivos y servicios, y mejorará la capacidad de Microsoft para mantenerse al día con las actualizaciones de Linux. Esta iniciativa forma parte de la creciente inversión de Microsoft en una amplia gama de tecnologías Linux, tales como [SONiC](https://azure.microsoft.com/en-us/blog/sonic-the-networking-switch-software-that-powers-the-microsoft-global-cloud/), [Azure Sphere OS](https://docs.microsoft.com/en-us/azure-sphere/product-overview/what-is-azure-sphere) y [Windows Subsystem for Linux (WSL)](https://docs.microsoft.com/en-us/windows/wsl/about). 

[SONiC](https://azure.github.io/SONiC/) Es un sistema operativo de red de código abierto basado en Linux que se ejecuta en conmutadores de múltiples proveedores y ASIC. Ofrece un conjunto completo de funciones de red, como BGP y RDMA, que se han probado en entornos de producción en los centros de datos de algunos de los mayores proveedores de servicios en la nube.

[Azure Sphere](https://www.microsoft.com/en-us/azure-sphere/) es una plataforma de aplicaciones segura y de alto nivel con funciones de comunicación y seguridad integradas para dispositivos conectados a Internet. La plataforma consiste en la integración de hardware construido en torno a un chip de silicio seguro; el sistema operativo Azure Sphere, un sistema operativo personalizado de alto nivel basado en Linux; y el servicio de seguridad Azure Sphere, un servicio de seguridad basado en la nube que proporciona seguridad continua.

 * [Ubuntu on Azure](https://ubuntu.com/azure)

 * [Ubuntu Pro for Azure](https://ubuntu.com/azure/pro)

 * [Linux on Azure](https://azure.microsoft.com/en-us/overview/linux-on-azure/)

 * [Creating a Linux VM in the Azure portal](https://docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal)

 * [Creating a virtual Linux workstation in Google Cloud](https://cloud.google.com/solutions/creating-a-virtual-linux-workstation).

 * [Preparing Linux VMs migrating to Google Cloud with Migrate for Compute Engine](https://cloud.google.com/migrate/compute-engine/docs/4.5/how-to/prepare-vms-servers/preparing-linux-vms)

 * [Understanding OpenStack on Red Hat](https://www.redhat.com/en/topics/openstack)

 * [Understanding OpenStack on Ubuntu](https://ubuntu.com/openstack/what-is-openstack)

 * [Tutorials for Setting up Linux workspaces on DigitalOcean](https://www.digitalocean.com/community/tutorials?q=linux)

 * [DigitalOcean Marketplace](https://marketplace.digitalocean.com/)

 * [Linode](https://linode.com/)

# Obtener software

 [Volver al Inicio](#tabla-de-contenidos)

En Linux, el software se obtiene de manera diferente a otros sistemas operativos.
En lugar de descargar archivos ejecutables desde páginas web, la forma principal de instalar programas es a través de repositorios oficiales gestionados por el sistema.

Un repositorio es un servidor que contiene software verificado y compatible con tu distribución. El sistema utiliza un gestor de paquetes para descargar, instalar y actualizar automáticamente estos programas, manteniendo todo organizado y seguro.

Además de los repositorios tradicionales, existen otros métodos para obtener software, como formatos universales (Flatpak, Snap, AppImage) o la compilación manual desde el código fuente.


## Gestores de paquetes (la forma principal)
En Linux, el software se instala mediante gestores de paquetes que descargan programas desde repositorios oficiales.

Ejemplos según distribución:

Debian / Ubuntu
`sudo apt install nombre-paquete`


Arch Linux
`sudo pacman -S nombre-paquete`


Fedora
`sudo dnf install nombre-paquete`

## Tiendas gráficas (para usuarios nuevos)

Muchos entornos tienen tiendas, funcionan como una tienda de apps, pero usan el gestor de paquetes del sistema por debajo:

* GNOME Software
* KDE Discover
* Ubuntu Software

### GNOME Software Center

<img src="https://user-images.githubusercontent.com/45159366/145691816-6445caec-5608-4022-bff2-353cfb728c66.png">

### KDE Plasma Discover Software Center

<img src="https://user-images.githubusercontent.com/45159366/145691934-52154d53-2457-4226-be11-ee23d4520c74.png">

**Note: Todo este software también está disponible en otras distribuciones populares de Linux, como [Debian](https://www.debian.org/), [Linux Mint](https://linuxmint.com/), [elementary OS](https://elementary.io/), [Pop!_OS](https://pop.system76.com/), [Fedora](https://getfedora.org), [Manjaro Linux](https://manjaro.org/), [EndeavourOS](https://endeavouros.com/) y [Arch Linux](https://archlinux.org/).
** Además, si sigues desplazándote hacia abajo, verás otras formas sencillas de obtener aplicaciones de software a través de Flathub, Snap Store y AppImages.**

### App Outlet

[App Outlet](https://app-outlet.github.io/) es una tienda de aplicaciones universal (Flatpaks, Snaps y AppImages) inspirada en el servicio en línea Linux App Store.

 <img src="https://user-images.githubusercontent.com/45159366/106686354-0095c780-657f-11eb-892b-659d3252d6e7.png">

## Formatos universales (multidistribución)
Además de los repositorios tradicionales, existen formatos universales que permiten instalar aplicaciones de forma independiente a la distribución.

### Flatpaks

Flatpak es un sistema de paquetes universal enfocado en aplicaciones de escritorio. Es común en distribuciones modernas y se integra bien con entornos como GNOME y KDE.

Ventajas:
- Funciona en múltiples distribuciones.
- Aísla las aplicaciones mediante sandboxing.
- Permite instalar versiones más recientes que las disponibles en los repositorios oficiales.

Desventajas:
- Puede ocupar más espacio en disco debido a dependencias incluidas.
- Requiere configuración inicial (por ejemplo, añadir Flathub).

Ejemplo:

`flatpak install flathub org.mozilla.firefox`

[FlatHub](https://flathub.org/) es un servicio de compilación y distribución para aplicaciones Flatpak.

[Flatseal](https://github.com/tchx84/flatseal) es una utilidad gráfica para revisar y modificar los permisos desde tu [Flatpak](https://flatpak.org/). [Get it on Flathub store](https://flathub.org/apps/details/com.github.tchx84.Flatseal).

[FlatHub Forum](https://discourse.flathub.org/)

 <img src="https://github.com/mikeroyal/Linux-Guide/assets/45159366/e19925b2-4fcf-406d-81eb-85b8dcd84889">
 
### Snaps

Snap es un formato desarrollado por Canonical (empresa detrás de Ubuntu). Es más común en Ubuntu y sus derivadas.

Ventajas:
- Instalación sencilla.
- Actualizaciones automáticas.
- Buen aislamiento de aplicaciones.

Desventajas:
- Puede tener tiempos de arranque más lentos.
- Mayor consumo de espacio.
- Menor integración en distribuciones que no son Ubuntu.

Ejemplo:

`sudo snap install vlc`


[Snap Store](https://snapcraft.io/store) es un servicio de compilación y distribución para aplicaciones Snap.

[Snapcraft Forum](https://forum.snapcraft.io/)

 <img src="https://user-images.githubusercontent.com/45159366/106686375-08ee0280-657f-11eb-9918-5385d8c09148.png">
 <img src="https://user-images.githubusercontent.com/45159366/106686378-0a1f2f80-657f-11eb-83aa-37ac96c7b032.png">

### AppImages

AppImage es un formato portable que no requiere instalación. El programa se descarga como un único archivo ejecutable.

Ventajas:
- No necesita instalación.
- No modifica el sistema.
- Ideal para probar aplicaciones rápidamente.

Desventajas:
- No se actualiza automáticamente.
- Mo se integra completamente con el gestor de paquetes.
- El usuario debe gestionar los permisos manualmente.

Uso típico:
```
chmod +x programa.AppImage
./programa.AppImage
```

[AppImageHub](https://www.appimagehub.com) es un servicio de compilación y distribución para aplicaciones AppImage.

[AppImage Manager](https://github.com/AppImageCrafters/appimage-manager) es un gestor de paquetes para AppImages.

[AppImage Forum](https://discourse.appimage.org/)

 <img src="https://user-images.githubusercontent.com/45159366/106686382-0b505c80-657f-11eb-9d74-9a94ec0d0693.png">

## Compilar desde código fuente

Compilar desde código fuente significa descargar el código original de un programa y construirlo manualmente en tu sistema.

Este método es más avanzado y normalmente se utiliza cuando:

- El programa no está disponible en los repositorios oficiales.
- Se necesita una versión más reciente.
- Se desea personalizar la compilación.
- Se quiere entender mejor cómo funciona el software internamente.

Para usuarios principiantes, generalmente no es el método recomendado, pero es importante conocerlo.

---

### ¿Qué es el código fuente?

El código fuente es el conjunto de archivos escritos en un lenguaje de programación (como C, C++ o Rust) que describen cómo funciona un programa.

Para poder ejecutarlo, ese código debe convertirse en binarios mediante un proceso llamado **compilación**.

---

### Requisitos previos

Antes de compilar, necesitas herramientas de desarrollo instaladas.

- Debian / Ubuntu
  
`sudo apt install build-essential`


 - Arch Linux
  
`sudo pacman -S base-devel`

### Proceso típico de compilación

Muchos proyectos siguen este flujo clásico:

#### 1 - Descargar el código fuente

El código puede obtenerse desde:
* El sitio oficial del proyecto
* GitHub o GitLab
* Un archivo comprimido (.tar.gz, .tar.xz)

Ejemplo:
```
tar -xvf programa.tar.gz
cd programa
```
####  2 - Configurar la compilación

Algunos proyectos usan el sistema tradicional configure:

`./configure`


Este paso:
* Verifica dependencias
* Prepara el entorno
* Genera archivos necesarios para compilar

Si falta alguna dependencia, el proceso mostrará un error.

#### 3 - Compilar

`make`

Aquí el compilador transforma el código fuente en archivos ejecutables.

Este proceso puede tardar desde segundos hasta varios minutos, dependiendo del tamaño del proyecto.

#### 4 - Instalar
  
`sudo make install`

Este paso copia los archivos compilados al sistema (normalmente en /usr/local/).

---

Otros sistemas de compilación modernos

No todos los proyectos usan configure y make. Algunos sistemas modernos incluyen:

* CMake
* Meson
* Cargo (Rust)
* Go build (Go)
* npm / yarn (JavaScript)

Cada proyecto suele incluir instrucciones específicas en un archivo README.md o INSTALL.


## Alternativas a Microsoft Office
[Volver al Inicio](#tabla-de-contenidos)

[OnlyOffice](https://www.onlyoffice.com/) es una suite ofimática segura, tanto offline como online, altamente compatible con los formatos de MS Office  para Windows, Mac y Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158472597-9ca73786-4e28-497f-9c6d-0a0040e8c3da.png">
  <br />
  OnlyOffice
</p>

[FreeOffice](https://www.freeoffice.com/) Es una suite ofimática segura y altamente compatible con los formatos de MS Office para Windows, Mac y Linux.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266331-321a1004-14cb-473f-a01f-9a9a6e67623a.png">
  <br />
  FreeOffice
</p>

[LibreOffice](https://www.libreoffice.org/) es una suite de software de productividad ofimática gratuita y de código abierto similar a Microsoft Office.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158470268-2834d32d-72ef-4e5e-8cd6-02db51a5dcfa.png">
  <br />
  LibreOffice
</p>

[WPS Office](https://www.wps.com/office/linux/) es una suite ofimática gratuita desarrollada por Kingsoft. Ofrece procesador de textos, hojas de cálculo y presentaciones con una interfaz y compatibilidad muy similares a Microsoft Office, lo que la convierte en una alternativa popular para usuarios que migran desde Windows.

Aunque es gratuita, WPS Office no es completamente de código abierto.
 
<p align="center">
 <img src="./assets/images/wps-2019.png">
  <br />
  WPS Office
</p>


         
         
## Secure & Privacy Focused Web Browsers
[Volver al Inicio](#tabla-de-contenidos)

[Mozilla Firefox](https://www.mozilla.org/firefox/) is a free and open-source web browser developed by the Mozilla Foundation.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266387-04609c3f-1324-4c21-9186-5ed338835260.png">
  <br />
  Firefox
</p>

[LibreWolf](https://librewolf.net/) Está diseñado para aumentar la protección contra las técnicas de rastreo y huellas digitales, al tiempo que incluye algunas mejoras de seguridad. Elimina toda la telemetría, la recopilación de datos y las molestias, además de desactivar funciones que restringen la libertad, como el DRM.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189506043-3e2c44b9-9809-469f-a41e-8f6e6fad5c04.png">
  <br />
  LibreWolf
</p>

[Brave](https://brave.com/) Es un navegador web rápido, privado y seguro para PC, Mac y dispositivos móviles. Incluye [Brave Search](https://brave.com/search/), un motor de búsqueda privado que te da prioridad a ti, y no a las grandes tecnológicas, para aquellos que no quieren utilizar Google Search.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266393-8891913c-5acd-4a3a-98cf-ce214282126d.png">
  <br />
  Brave
</p>

[Ungoogled-Chromium](https://github.com/ungoogled-software/ungoogled-chromium) Es un enfoque sencillo para eliminar la dependencia del servicio web de Google.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/173683899-a91b5b02-533f-4ad2-ba84-c3a70108e0dd.png">
  <br />
 Ungoogled-Chromium
</p>

[Vivaldi](https://vivaldi.com/) Es un navegador web rápido, privado y seguro para PC, Mac y dispositivos móviles. Incluye funciones integradas como Notas, Captura de pantalla, Propiedades de imagen y (muchas) más. Tenga en cuenta que Vivaldi es un software propietario y no de código abierto.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/158266396-25f48ceb-9868-4d8f-80a3-30bbd0bbf092.png">
  <br />
  Vivaldi
</p>

[Ghostery Dawn](https://www.ghostery.com/dawn) Es un navegador web rápido, privado y seguro para PC, Mac y dispositivos móviles. Incluye el paquete completo Ghostery Privacy Suite, que contiene [Ghostery Glow](https://www.ghostery.com/glow), un motor de búsqueda privado que no registra tu historial de búsqueda, lo que significa que obtienes resultados objetivos, no resultados filtrados según la probabilidad de que hagas clic en ellos.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/169711128-745e445d-0c1e-46d8-a7cf-12b0d6fcbda5.png">
  <br />
  Ghostery Dawn
</p>

### Privacy & Security Focused Browser extensions

[Volver al Inicio](#tabla-de-contenidos)

[UBlock Origin](https://ublockorigin.com/) es una extensión de navegador gratuita y de código abierto, multiplataforma, destinada al filtrado de contenidos y cuyo objetivo principal es neutralizar la invasión de la privacidad de una forma eficaz y fácil de usar.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)

[Privacy Badger](https://privacybadger.org/) es una extensión del navegador que aprende automáticamente a bloquear rastreadores invisibles.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp)

[DuckDuckGo Privacy Essentials](https://duckduckgo.com/app) It is a browser extension that automatically learns to block invisible trackers.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-for-firefox/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg?hl=fr)

[Ghostery](https://www.ghostery.com/ghostery-browser-extension) es una extensión de navegador Ad Blocker que ofrece una protección integral de la privacidad.

 * [Firefox extension](https://www.ghostery.com/ghostery-ad-blocker-firefox)
 * [Chrome extension](https://www.ghostery.com/ghostery-ad-blocker-chrome)

[HTTPS Everywhere](https://www.eff.org/https-everywhere)  es una extensión creada por EFF y el Proyecto Tor que cambia automáticamente miles de sitios web de «http» (no seguro) a «https» (seguro).

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en)

[CleanURLs](https://gitlab.com/KevinRoebert/ClearUrls) es una extensión que elimina automáticamente los elementos de seguimiento de las URL para ayudar a proteger tu privacidad cuando navegas por Internet.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk/)

**PixelBlock** es una extensión de Gmail que bloquea los intentos de rastreo de correos electrónicos utilizados para detectar cuándo abres y lees los correos electrónicos. 

 * [Chrome extension](https://chrome.google.com/webstore/detail/pixelblock/jmpmfcjnflbcoidlgapblgpgbilinlem/)

[Sitejabber](https://www.sitejabber.com/) es una extensión para que los consumidores encuentren negocios online fiables y eviten estafas.

[Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/sitejabber/)

[Chrome extension](https://chrome.google.com/webstore/detail/sitejabber-ratings-review/ckiddbafgcfifpioacgfijgicacanflo)

[1Password](https://1password.com/) Es un gestor de contraseñas que proporciona a los usuarios un lugar donde almacenar diversas contraseñas, licencias de software y otra información confidencial en una caja fuerte virtual protegida con una contraseña maestra protegida por PBKDF2.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/1password-x-password-manager/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/1password-%E2%80%93-password-mana/aeblfdkhhhdcdjpifhhbdiojplfjncoa?hl=en)

[Bitwarden](https://bitwarden.com/) Es un servicio gratuito y de código abierto para la gestión de contraseñas que almacena información confidencial, como credenciales de sitios web, en una bóveda cifrada.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb)

[Guardio](https://guard.io/) es una extensión ligera diseñada para ayudarte a navegar de forma rápida y segura. Limpiará tu navegador, lo acelerará y protegerá tu información privada.

 * [Chrome extension](https://chrome.google.com/webstore/detail/guardio-protection-for-ch/gjfpmkejnolcfklaaddjnckanhhgegla)

[OneTab](https://www.one-tab.com/) Es una extensión que convierte tus pestañas en una lista y acelera tu navegador.

 * [Firefox extension](https://addons.mozilla.org/en-US/firefox/addon/onetab/)
 * [Chrome extension](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall)

### Privacy-focused Search Engines

[Volver al Inicio](#tabla-de-contenidos)

 * [Brave Search](https://brave.com/search/)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009061-21142683-0943-4ef2-9ca1-a66831410ae4.png">
  <br />

</p>

 * [Ghostery Glow](https://www.ghostery.com/glow)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009065-2d360d4f-9712-4f80-9da2-e8808773ba7f.png">
  <br />

</p>

 * [DuckDuckGo](https://duckduckgo.com/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009064-2d753a92-6e80-48a5-9e88-deb9d886162e.png">
  <br />

</p>

 * [Startpage](https://www.startpage.com/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009074-7e0ae42e-84b2-4815-9280-d56ff289462b.png">
  <br />

</p>

 * [Qwant](https://www.qwant.com/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009070-b652dab1-0f4a-4020-b231-bc7da3897c04.png">
  <br />

</p>

 * [Ecosia](https://www.ecosia.org/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009066-d81594fe-873f-4aed-ac0f-2f9f6673ebc9.png">
  <br />

</p>

 * [Swisscows](https://swisscows.com/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009076-74c38325-077d-4511-be75-981646dd11c8.png">
  <br />

</p>

 * [searX](https://searx.info/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009072-54539257-92f9-4f7e-9515-3cb14a2e8695.png">
  <br />

</p>

 * [Mojeek](https://www.mojeek.com/)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/187009069-afd5a4e2-aea5-4143-87ba-8882c31476a8.png">
  <br />

</p>

## Backups

[Volver al Inicio](#tabla-de-contenidos)

[TimeShift](https://github.com/linuxmint/timeshift) Es una herramienta de restauración del sistema para Linux. Crea instantáneas del sistema de archivos utilizando rsync+hardlinks o instantáneas BTRFS. Admite instantáneas programadas, múltiples niveles de copia de seguridad y filtros de exclusión. 

[Vorta](https://vorta.borgbase.com/) Es un cliente de copia de seguridad para equipos de escritorio macOS y Linux. Integra el potente Borg Backup con tu entorno de escritorio favorito para proteger tus datos contra fallos del disco, ransomware y robos. [Disponible como Flatpak en Flathub](https://flathub.org/apps/details/com.borgbase.Vorta)

[Pika Backup](https://apps.gnome.org/app/org.gnome.World.PikaBackup/) es una herramienta de copia de seguridad diseñada para guardar tus datos personales y no admite la recuperación completa del sistema. Pika Backup funciona con el software BorgBackup, que ha sido probado exhaustivamente. [Disponible como Flatpak en Flathub](https://flathub.org/apps/details/org.gnome.World.PikaBackup)

## Storage Disk Health 

[Volver al Inicio](#tabla-de-contenidos)

[Dirstat-rs](https://github.com/scullionw/dirstat-rs) Es una interfaz de línea de comandos rápida y multiplataforma para el uso del disco, similar a [Windirstat](https://windirstat.net/). 

[Dutree](https://github.com/nachoparker/dutree) es una herramienta para analizar el uso del sistema de archivos escrita en Rust.

[Scrutiny](https://github.com/AnalogJ/scrutiny) Es una herramienta WebUI para smartd [monitorización S.M.A.R.T](https://www.crucial.com/articles/about-ssd/smart-and-ssds), tendencias históricas y umbrales de fallo en el mundo real.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/183272245-468ac924-ebd6-475d-94af-6dfa7b97e7cb.png">
<br />
Scrutiny UI
</p>

## Mejorar la duración de la batería
[Volver al Inicio](#tabla-de-contenidos)

* [Laptop Power Management tutorial by Chris Titus Tech](https://christitus.com/laptop-power-management/)

[auto-cpufreq](https://github.com/AdnanHodzic/auto-cpufreq) es un optimizador automático de la velocidad y el consumo de la CPU para Linux basado en la supervisión activa del estado de la batería del portátil, el uso de la CPU, la temperatura de la CPU y la carga del sistema. En definitiva, le permite mejorar la duración de la batería sin renunciar a nada. 

[TLP](https://linrunner.de/tlp/index.html) es una herramienta gratuita de código abierto, con numerosas funciones y línea de comandos para la gestión avanzada de la energía, que ayuda a optimizar la duración de la batería en ordenadores portátiles con sistema operativo Linux. 

[TLPUI](https://github.com/d4nj1/TLPUI) es una interfaz de usuario GTK para TLP escrita en Python.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/189506040-bad9ef24-1a43-442e-a9b1-844e0e463490.png">
<br />
TLPUI
</p>    

[Asus linux drivers](https://github.com/asus-linux-drivers) Controladores Linux no oficiales para portátiles y accesorios Asus. Mantenido por el fundador de la organización y la comunidad. Cualquier contribución es bienvenida (incidencias, debates, relaciones públicas).

 
## Herramientas para copiar/transferir archivos a tu sistema Linux
 [Volver al Inicio](#tabla-de-contenidos)
 
[KDE Connect](https://kdeconnect.kde.org/) es una herramienta que te permite conectar fácilmente tu teléfono a tu ordenador, tu ordenador a tu tableta o tu ordenador a tu dispositivo Steam Deck. Se puede utilizar para compartir archivos entre dispositivos, leer y enviar SMS directamente desde tu ordenador portátil y bloquear tu ordenador de forma remota.

[Warpinator](https://github.com/linuxmint/warpinator) Es una herramienta gratuita y de código abierto para enviar y recibir archivos entre ordenadores que se encuentran en la misma red. [Warpinator Flatpak](https://flathub.org/apps/details/org.x.Warpinator)

[FileZilla Client](https://filezilla-project.org/) Es un cliente FTP, FTPS y SFTP multiplataforma rápido y fiable con muchas funciones útiles y una interfaz gráfica de usuario intuitiva. [FileZilla Flatpak](https://flathub.org/apps/details/org.filezillaproject.Filezilla)

[Dragit](https://github.com/sireliah/dragit) es una aplicación para compartir archivos de forma intuitiva entre dispositivos. Es útil cuando se desea enviar archivos de un ordenador a otro con el mínimo esfuerzo. Dragit detecta automáticamente los dispositivos de la red local con la ayuda del protocolo mDNS y permite enviar archivos de forma inmediata. [Dragit Flatpak](https://flathub.org/apps/details/com.sireliah.Dragit)

[WinFsp](https://github.com/winfsp/winfsp) Es un conjunto de componentes de software para ordenadores con Windows que permite la creación de sistemas de archivos en modo usuario. En este sentido, es similar a FUSE (Filesystem in Userspace), que proporciona la misma funcionalidad en ordenadores similares a UNIX.

[SSHFS-Win](https://github.com/winfsp/sshfs-win) Es una adaptación mínima de SSHFS a Windows. Si nos fijamos en su funcionamiento interno, utiliza Cygwin para el entorno POSIX y WinFsp para la funcionalidad FUSE (Filesystem in Userspace).

[RiftShare](https://riftshare.app) es una herramienta multiplataforma (Windows, MacOS, Linux) para compartir archivos que admite transferencias totalmente cifradas tanto en la red local como fuera de ella mediante una sencilla contraseña. RiftShare utiliza [magic-wormhole](https://github.com/magic-wormhole/magic-wormhole) y es compatible con otros clientes magic-wormhole. Además, es totalmente de código abierto y tiene licencia GPLv3. [RiftShare Flatpak](https://flathub.org/apps/details/app.riftshare.RiftShare)

[SyncThing](https://syncthing.net/) Es un programa de sincronización continua de archivos. Sincroniza archivos entre dos o más ordenadores en tiempo real, protegidos de forma segura contra miradas indiscretas. Funciona con Mac OS X, Windows, Linux, FreeBSD, Solaris, OpenBSD, Android y muchos otros. Se puede descargar en Discover. También es de código abierto y tiene licencia MPL-2.0.

[Usermode FTP Server](https://gitlab.com/ergoithz/umftpd) es una herramienta que te permite iniciar un servidor FTP como usuario y transferir archivos con cualquier cliente FTP. Te permite acceder a tus archivos directamente con el soporte FTP integrado en muchos exploradores de archivos: Explorador de archivos de Windows, Thunar, Gnome Files, Dolphin y muchos más. [Usermode FTP Server on FlatHub](https://flathub.org/apps/details/eu.ithz.umftpd)

## Ejecutar aplicaciones Android en tu sistema Linux
[Volver al Inicio](#tabla-de-contenidos)

[Waydroid](https://github.com/waydroid/waydroid) es un enfoque basado en contenedores para arrancar un sistema Android completo en un sistema Linux normal. Asegúrate de consultar el [Waydroid Arch wiki page](https://wiki.archlinux.org/title/Waydroid). 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189516892-24454312-836a-4a88-a6b8-a3e9aaa8612c.png">
  <br />
</p>

[Anbox](https://github.com/anbox) es un software basado en contenedores para ejecutar un sistema Android completo en distribuciones Linux. Asegúrate de consultar [Anbox Arch wiki page](https://wiki.archlinux.org/title/Anbox).


## Ejecutar aplicaciones de Windows en tu sistema Linux
[Volver al Inicio](#tabla-de-contenidos)

[Bottles](https://usebottles.com/) Es una herramienta de software que te permite ejecutar software de Windows en Linux. Su sistema de instalación de dependencias integrado garantiza el acceso automático a la compatibilidad del software. El gestor de descargas puede descargar los componentes oficiales, tales como: el ejecutor (Wine, Proton), DXVK, dependencias, etc. Disponible en [FlatHub](https://flathub.org/apps/details/com.usebottles.bottles) o a través de la tienda [KDE Discover](https://apps.kde.org/discover/).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/182049940-ccba08e7-b05d-4991-b36f-1e2596c390da.png">
 </p>
 
## Edición profesional de audio y vídeo

[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108773208-dba7cb00-7512-11eb-8fd0-2d009dbfc729.png">
</p>


[H.264(AVC)](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC) Es un estándar de compresión de vídeo basado en la codificación DCT entera orientada a bloques y con compensación de movimiento que define múltiples perfiles (herramientas) y niveles (velocidades de bits y resoluciones máximas) con soporte hasta 8K.

[H.265(HEVC)](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding) Es un estándar de compresión de vídeo sucesor del H.264 (AVC). Ofrece una compresión de datos entre un 25 % y un 50 % mejor con el mismo nivel de calidad de vídeo, o una calidad de vídeo mejorada con la misma velocidad de bits.

[FFmpeg](https://ffmpeg.org) es un marco multimedia líder que puede decodificar, codificar, transcodificar, multiplexar, demultiplexar, transmitir, filtrar y reproducir prácticamente cualquier cosa que hayan creado los seres humanos y las máquinas. Es compatible con los formatos antiguos más desconocidos y con los más avanzados en múltiples plataformas, como Windows, macOS y Linux.

[HandBrake](https://handbrake.fr/) Es una herramienta para transcodificar vídeo desde casi cualquier formato con una selección de códecs ampliamente compatibles. Es compatible con Windows, macOS y Linux.
 
[Dynamic Adaptive Streaming over HTTP (DASH)](https://developer.mozilla.org/en-US/docs/Web/HTML/DASH_Adaptive_Streaming_for_HTML_5_Video) Es un protocolo de transmisión adaptativa que permite que una transmisión de vídeo cambie entre velocidades de bits en función del rendimiento de la red, con el fin de mantener la reproducción del vídeo.

[OpenMAX™](https://www.khronos.org/openmax/) es una API multiplataforma que proporciona una amplia compatibilidad con códecs y aplicaciones de streaming multimedia, ya que permite desarrollar, integrar y programar componentes multimedia acelerados en múltiples sistemas operativos y plataformas de silicio.

[DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/) es la única solución del mundo que combina edición profesional 8K, corrección de color, efectos visuales y posproducción de audio, todo en una sola herramienta de software. Puede pasar instantáneamente de la edición al color, los efectos y el audio con un solo clic. DaVinci Resolve Studio es también la única solución diseñada para la colaboración entre múltiples usuarios, de modo que editores, asistentes, coloristas, artistas de efectos visuales y diseñadores de sonido pueden trabajar en directo en el mismo proyecto al mismo tiempo.

[Blender](https://www.blender.org/features/video-editing/) Incluye un editor de secuencias de vídeo integrado que le permite realizar acciones básicas como cortes y empalmes de vídeo, así como tareas más complejas como el enmascaramiento de vídeo o la gradación de color. El editor de vídeo incluye: vista previa en directo, forma de onda de luminancia, vectorscopio de crominancia y visualización de histogramas. Mezcla de audio, sincronización, desplazamiento y visualización de formas de onda.

[Kdenlive](https://kdenlive.org/en/) es una herramienta de edición de vídeo de código abierto que admite archivos multimedia ilimitados. Se basa en MLT Framework, KDE y Qt. Es ideal para quienes buscan una herramienta de edición de vídeo muy versátil y repleta de funciones. La última versión 25.12 incluye funciones muy interesantes, como diseños de interfaz, compatibilidad con múltiples flujos de audio, gestión de datos en caché y barras de zoom en el monitor de clips y el panel de efectos, pero se podría decir que lo más destacado de esta versión son las mejoras en la estabilidad y la interfaz.

[OpenShot](https://www.openshot.org/) es una herramienta de edición de vídeo de código abierto diseñada para usuarios nuevos en el entorno de edición. Cuenta con funciones sencillas, como la función de arrastrar y soltar, y ofrece una interfaz de usuario fácil de usar y rápida de aprender. Este potente editor de vídeo ofrece un montón de formas eficientes de cortar y recortar tus vídeos. Puedes utilizar libremente las pistas ilimitadas, el motor de efectos de vídeo, el editor de títulos, las animaciones 3D, la cámara lenta y los efectos de tiempo. Es compatible con los códecs de vídeo más utilizados que son compatibles con FFmpeg, como WebM (VP9), AVCHD (libx264), HEVC (libx265) y códecs de audio como mp3 (libmp3lame) y aac (libfaac). El programa puede renderizar vídeos MPEG4, ogv, Blu-ray y DVD, así como vídeos Full HD para subirlos a sitios web de vídeos en Internet como YouTube.

[Lightworks](https://www.lwks.com/) Es una aplicación de edición de vídeo no lineal para editar y masterizar vídeo digital utilizada por la industria cinematográfica. Su edición profesional se ha utilizado para éxitos de taquilla como Shutter Island, Pulp Fiction y Misión imposible. Interfaz de usuario intimidante. Al igual que los editores de vídeo profesionales, como Adobe Premiere Pro, Lightworks es bastante complicado de usar para los nuevos usuarios.

[Shotcut](https://www.shotcut.org/) es un editor de vídeo multiplataforma de código abierto. Permite realizar diversas acciones, como editar vídeos (incluida la calidad de vídeo 4K), añadir efectos, crear nuevas películas, importar la mayoría de formatos de archivos de imagen, exportar a casi cualquier formato de archivo y mucho más.

[Olive](https://www.olivevideoeditor.org) Es un editor de vídeo no lineal gratuito cuyo objetivo es ofrecer una alternativa completa al software profesional de edición de vídeo de alta gama.

[Natron](https://natrongithub.github.io/) es un potente compositor digital capaz de satisfacer todas tus necesidades en 2D/2.5D. Sus robustos formatos de archivo OIIO y su arquitectura OpenFX hacen de Natron el compositor de código abierto más flexible para la comunidad de efectos visuales. Su interfaz y funcionalidad son las mismas en todas las plataformas, como MacOS, Linux y Windows.

[OBS (Open Broadcaster Software)](https://obsproject.com/) es un software gratuito y de código abierto para la grabación de vídeo y la transmisión en directo. Transmite a Twitch, YouTube y muchos otros proveedores o graba tus propios vídeos con codificación H264 / AAC de alta calidad.

[REAPER](https://www.reaper.fm/) Es una aplicación completa de producción de audio digital para ordenadores que ofrece un conjunto completo de herramientas para la grabación, edición, procesamiento, mezcla y masterización multipista de audio y MIDI. REAPER es compatible con una amplia gama de hardware, formatos digitales y complementos, y se puede ampliar, programar y modificar de forma integral. 

[JACK Audio Connection Kit AKA JACK](https://jackaudio.org/) es un demonio de servidor de sonido profesional que proporciona conexiones en tiempo real y de baja latencia para datos de audio y MIDI entre aplicaciones que implementan su API. JACK se puede configurar para enviar datos de audio a través de una red a una máquina «maestra», que luego envía el audio a un dispositivo físico. Esto puede ser útil para mezclar audio de varios ordenadores «esclavos» sin necesidad de cables adicionales o mezcladores de hardware, y manteniendo la ruta de audio digital durante el mayor tiempo posible.

[Bitwig Studio](https://www.bitwig.com) Es una estación de trabajo de audio digital que cuenta con flujos de trabajo lineales y no lineales para el diseño de sonido, la grabación, las actuaciones en directo y mucho más. Incluye más de 90 instrumentos, efectos y otras herramientas creativas. Es compatible con Windows, macOS y Linux.

[PipeWire](https://pipewire.org) es una API de servidor y espacio de usuario para gestionar canalizaciones multimedia. Proporciona un motor de procesamiento basado en gráficos y de baja latencia sobre dispositivos de audio y vídeo que se puede utilizar para dar soporte a los casos de uso que actualmente gestionan tanto pulseaudio como JACK. PipeWire se diseñó con un potente modelo de seguridad que facilita la interacción con dispositivos de audio y vídeo desde aplicaciones en contenedores. Los nodos del gráfico se pueden implementar como procesos independientes, que se comunican con sockets e intercambian contenido multimedia mediante el paso de fd.

[Yabridge](https://github.com/robbert-vdh/yabridge) es una forma moderna y transparente de utilizar los plugins VST2 y VST3 de Windows en Linux. Yabridge es compatible con el uso de plugins VST2 y VST3 de Windows de 32 y 64 bits en un host VST de Linux de 64 bits, como si fueran plugins VST2 y VST3 nativos, con compatibilidad opcional con [grupos de complementos](https://github.com/robbert-vdh/yabridge#plugin-groups) para permitir la comunicación entre complementos VST2 y tiempos de inicio rápidos. 

[Sonobus](https://sonobus.net) Es una aplicación fácil de usar para transmitir audio peer-to-peer de alta calidad y baja latencia entre dispositivos a través de Internet o una red local.

[Avid Pro Tools](https://www.avid.com/pro-tools) Es un software de producción de audio estándar en la industria para compositores, músicos, productores e ingenieros.

[LMMS](https://lmms.io/) es un programa de aplicación de estación de trabajo de audio digital de código abierto. Cuando LMMS se combina con el hardware informático adecuado, permite producir música mediante la organización de muestras, la síntesis de sonidos, la reproducción en un teclado MIDI y la combinación de las funciones de rastreadores y secuenciadores. Desarrollado por Paul Giblock y Tobias Junghans, este programa significa «Linux MultiMedia Studio» y es compatible con prácticos complementos que le permiten funcionar en diferentes sistemas operativos.

[Ardour](http://ardour.org/) es un proyecto colaborativo de código abierto en el que participa un equipo internacional formado por músicos, programadores e ingenieros de sonido profesionales. El desarrollo es transparente: cualquiera puede ver nuestro trabajo a medida que se realiza. Al igual que con un buen equipo vintage, puedes abrir la caja y mirar dentro.

[Audacity](https://www.audacityteam.org/) Es un editor y grabador de audio multipista fácil de usar para Windows, Mac OS X, GNU/Linux y otros sistemas operativos. Desarrollado por un grupo de voluntarios como código abierto y ofrecido de forma gratuita. Increíble comunidad de soporte.

[Glimpse](https://glimpse-editor.github.io/) Es un editor de gráficos rasterizados multiplataforma basado en el Programa de Manipulación de Imágenes GNU, disponible para Linux, MacOS y Windows. Una herramienta excelente para crear miniaturas de vídeos de YouTube.
 
 ## Configuración de OBS Studio

[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185703842-0926e10a-467a-471c-b5f6-b74df4e460d9.png">
  <br />
</p>

[OBS (Open Broadcaster Software)](https://obsproject.com/) es un software gratuito y de código abierto para la grabación de vídeo y la transmisión en directo. Transmite a Twitch, YouTube y muchos otros proveedores o graba tus propios vídeos con codificación H264 / AAC de alta calidad. OBS Studio añadió **compatibilidad nativa con PipeWire y Wayland en la versión 27**. 

 [![OBS Studio Flatpak on Flathub](https://user-images.githubusercontent.com/45159366/185704745-32111c92-2687-49f6-9247-6e925f6a41a6.png)](https://flathub.org/apps/details/com.obsproject.Studio)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/185704748-217443ac-57e3-4ab3-ba74-6d09c2fe62fb.png">
  <br />
  OBS Studio
</p>

 * [OBS PipeWire Audio Capture](https://github.com/dimtpap/obs-pipewire-audio-capture) Es un complemento que añade tres fuentes para OBS Studio con el fin de capturar salidas de audio, entradas y aplicaciones utilizando PipeWire.
 
 * [OBS Scale To Sound](https://github.com/dimtpap/obs-scale-to-sound) Es un complemento para OBS Studio que añade un filtro que escala una fuente en función de los niveles de audio de cualquier fuente de audio que elijas.
 
  * [OBS Studio Fully-loaded](https://github.com/wimpysworld/obs-fully-loaded) es un script para sistemas basados en Ubuntu/Debian que instala OBS Studio junto con funciones y complementos adicionales preinstalados. Este proyecto ha sido desarrollado y es mantenido por [Martin Wimpress](https://github.com/wimpysworld/).
 
 ### Complementos y temas útiles de terceros para OBS Studio.

|  Tipo  | Nombre  | Descripcion |
| Complemento  |**[Advanced Scene Switcher](https://github.com/WarmUpTill/SceneSwitcher)** |  un cambiador de escenas automatizado. | 
  | Complemento |**[Audio Pan](https://github.com/norihiro/obs-audio-pan-filter) **| controla la panoramización estéreo de la fuente de audio. |
  | Complemento |**[Browser](https://github.com/obsproject/obs-browser) **| complemento del navegador OBS Studio basado en CEF.|
  | Complemento |**[Directory Watch Media](https://github.com/exeldro/obs-dir-watch-media) **| filtro que se puede añadir a la fuente multimedia para cargar el archivo más antiguo o más reciente de un directorio.|
  | Complemento |**[Downstream Keyer](https://github.com/exeldro/obs-downstream-keyer) **| añade un muelle Downstream Keyer.|
  | Complemento |**[Dynamic Delay](https://github.com/exeldro/obs-dynamic-delay) **| filtro para retrasar dinámicamente una fuente de vídeo.|
  | Complemento |**[Freeze Filter](https://github.com/exeldro/obs-freeze-filter) **| congela una fuente utilizando un filtro.|
  | Complemento |**[Gradient Source](https://github.com/exeldro/obs-gradient-source) **| añade degradados como fuente.|
  | Complementos |**[GStreamer](https://github.com/fzwoch/obs-gstreamer) **| alimenta los canales de lanzamiento de GStreamer en OBS Studio y utiliza elementos codificadores de GStreamer.|
  | Complemento |**[Move Transition](https://github.com/exeldro/obs-move-transition) **| mueve la fuente a una nueva posición durante la transición de escena.|
  | Complemento |**[Multi Source Effect](https://github.com/norihiro/obs-multisource-effect) **| proporciona un efecto personalizado para renderizar múltiples fuentes.|
  | Complemento |**[NDI](https://github.com/Palakis/obs-ndi) **| red A/V a través de NDI de NewTek.|
  | Complemento |**[NvFBC](https://gitlab.com/fzwoch/obs-nvfbc) **| captura de pantalla a través de la API FBC de NVIDIA. Requiere [parches NvFBC para controladores Nvidia](https://github.com/keylase/nvidia-patch) para GPU de consumo.|
  | Complemento |**[Pulse App Capture](https://github.com/jbwong05/obs-pulseaudio-app-capture) **| captura el audio de la aplicación desde PulseAudio.|
  | Complemento |**[Soundboard](https://github.com/cg2121/obs-soundboard) **| añade un panel de sonido.|
  | Complemento |**[Source Copy](https://github.com/exeldro/obs-source-copy) **| añade opciones de copiar y pegar al menú de herramientas.|
  | Complemento |**[Source Dock](https://github.com/exeldro/obs-source-dock) **| crea un Dock para una fuente, que te permite ver los niveles de audio, cambiar el volumen y controlar los medios. |
  | Complemento |**[Recursion Effect](https://github.com/exeldro/obs-recursion-effect) **| filtro de efecto de recursividad.|
  | Complemento |**[Replay Source](https://github.com/exeldro/obs-replay-source) **| reproducción a cámara lenta de fuentes asíncronas desde la memoria.|
  | Complemento |**[RGB Levels](https://github.com/petrifiedpenguin/obs-rgb-levels-filter) **| filtro sencillo para ajustar los niveles RGB.|
  | Complemento |**[RTSPServer](https://github.com/iamscottxu/obs-rtspserver/) **| codifica y publica en una transmisión RTSP.|
  | Complemento |**[Scale to Sound](https://github.com/Qufyy/obs-scale-to-sound) **| añade un filtro que escala una fuente en función de los niveles de audio de cualquier fuente de audio que elijas.|
  | Complemento |**[Scene Collection Manager](https://github.com/exeldro/obs-scene-collection-manager) **| filtra, realiza copias de seguridad y restaura colecciones de escenas.|
  | Complemento |**[Scene Notes Dock](https://github.com/exeldro/obs-scene-notes-dock) **| crea un Dock para mostrar y editar notas de la escena activa actual.|
  | Complemento |**[Source Record](https://github.com/exeldro/obs-source-record) **| permite grabar fuentes a través de un filtro.|
  | Complemento |**[Source Switcher](https://github.com/exeldro/obs-source-switcher) **| para cambiar entre una lista de fuentes.|
  | Complemento |**[Spectralizer](https://github.com/univrsal/spectralizer) **| visualización de audio mediante fftw.|
  | Complemento |**[StreamFX](https://github.com/Xaymar/obs-StreamFX) **| colección de filtros y transiciones de efectos modernos.|
  | Complemento |**[Teleport](https://github.com/fzwoch/obs-teleport) **| sustituto abierto similar a NDI.|
  | Complemento |**[Text Pango](https://github.com/kkartaltepe/obs-text-pango) **| proporciona una fuente de texto renderizada con Pango con soporte multilingüe, soporte para emojis, renderización vertical y soporte RTL.|
  | Complemento |**[Text PThread](https://github.com/norihiro/obs-text-pthread) **| complemento de fuente de texto enriquecido con muchas funciones avanzadas.|
  | Complemento |**[Time Warp Scan](https://github.com/exeldro/obs-time-warp-scan) **| filtro de escaneo con distorsión temporal.|
  | Complemento |**[Transition Table](https://github.com/exeldro/obs-transition-table) **| personaliza las transiciones entre escenas.|
  | Complemento |**[Virtual Cam Filter](https://github.com/exeldro/obs-virtual-cam-filter) **| permite que las fuentes estén disponibles para la cámara virtual a través de un filtro.|
  | Complemento |**[VNC Source](https://github.com/norihiro/obs-vnc) **| visor VNC que funciona como fuente.|
  | Complemento |**[Websockets](https://github.com/Palakis/obs-websocket) **| controla OBS Studio de forma remota a través de WebSockets, compatible con [StreamControl](https://play.google.com/store/apps/details?id=dev.t4ils.obs_remote&hl=en).|
  
# Gaming
[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189517086-1d91abff-4a1b-4f7f-bd02-ffaf09178f5c.gif">
  <br />
</p>

### Linux Gaming Resources & Tweak Tools
 
 * [GamingOnLinux](https://www.gamingonlinux.com/)
 * [BoilinSteam](https://boilingsteam.com/)
 * [PCGamingWiki](https://www.pcgamingwiki.com/wiki/Home)
 * [Rootgamer](https://rootgamer.com/about-us/)
 * [Linux Gaming Central](https://linuxgamingcentral.com/)
 * [Linux Game Cast](https://www.youtube.com/c/linuxgamecast)
 * [r/linux_gaming subreddit](https://www.reddit.com/r/linux_gaming)
 
### Game Controllers

[Back to Top](#table-of-contents)

[Steam Contoller](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=steam+controller&_sacat=0)

 * **Note:** Steam Controllers were discontinued on November 26, 2019, though, you can still buy them on ebay.

 * [Steam Controller Setup](https://help.steampowered.com/en/faqs/view/41C5-7D8C-1671-411E)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/211141385-fe44e2a3-ebc2-41d7-acc1-4d14957ef9aa.png">
 
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/211141386-8054ef27-e7de-4ecc-96e9-b8a46e45a9ea.png">
 
</p>


[Xbox Wireless Controller + USB-C® Cable](https://www.xbox.com/en-us/accessories/controllers/xbox-wireless-controller-usb-c)

 * [XONE](https://github.com/medusalix/xone) is a Linux kernel driver for Xbox One and Xbox Series X|S accessories. It serves as a modern replacement for xpad, aiming to be compatible with Microsoft's Game Input Protocol (GIP).
 * [XPAD neo](https://github.com/atar-axis/xpadneo) is an Advanced Linux Driver for Xbox One Wireless Controller (shipped with Xbox One S).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/187094245-3c406751-4e4b-42fd-bd2c-a72181722fad.png">
  <br />
    Xbox Controller
</p>

[PlayStation 5 DualSense™ Wireless Controller](https://www.playstation.com/en-us/accessories/dualsense-wireless-controller/)

* [Update the wireless controller firmware](https://controller.dl.playstation.net/controller/lang/gb/fwupdater.html)

* [DS4Windows](https://ds4-windows.com/) is an open-source gamepad input mapper and virtual emulator designed to use and connect your PlayStation controller (DualShock 3/4 and DualSense 5) to a Windows 10 & 11 PC. It also comes handy with emulating a Xbox controller and tricks the computer into thinking the DS4, is in fact, an Xbox game pad (virtual emulation occurs).

**Note:** make sure to use [Bottles](https://usebottles.com/) to run this firmware update and DS4Windows.
 
<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/187094347-109c80cd-5cc3-4a97-8a8f-0181687ab0d4.png">
  <br />
    PS 5  DualSense™ Controller
</p>

[Nintendo Switch Pro Controller](https://www.amazon.com/Nintendo-Switch-Pro-Controller/dp/B01NAWKYZ0)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/194023448-09e74efa-67f8-4503-87f5-5b7e59289608.png">
  <br />
    Nintendo Switch Pro Controller
</p>

[8Bitdo Ultimate Bluetooth Controller](https://www.8bitdo.com/ultimate-bluetooth-controller/) with Charging Dock, Wireless Pro Controller for Switch, Windows and Steam Deck.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/212845008-8d95f23a-a391-4370-9a93-e033ce5491c8.png">
</p>

[GuliKit KingKong 2 Pro Wireless Controller](https://www.amazon.com/KingKong-Wireless-Controller-Nintendo-Switch-Bluetooth/dp/B09QJN8ZD9)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/212845013-9ab88231-3185-4c27-a28f-825aee3fec5e.png">
</p>

[Amazon Luna Controller](https://www.amazon.com/luna/getting-started)

* **The Luna Controller** is made for Amazon's cloud gaming service. Powered by Cloud Direct technology Connect directly to Amazon's custom game servers when playing on Luna, reducing roundtrip latency by 17 to 30 milliseconds vs. a local Bluetooth connection among Windows PC, Mac, and Fire TV. 

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/218290132-7a548dea-8c9b-4c96-8efb-24b9d8c7f74c.png">
</p>
  
## Steam
[Volver al Inicio](#tabla-de-contenidos)

[Steam Flatpak](https://flathub.org/apps/details/com.valvesoftware.Steam) available on FlatHub.

[Steam Remote Play Together](https://store.steampowered.com/remoteplay/#together) is a steam service that let's you share your Steam local multi-player games with friends over the internet, for free. Using Remote Play Together, one player owns and runs the game, then up to four players can join.

[Proton](https://github.com/ValveSoftware/Proton/) is a tool for use with the Steam client which allows games which are exclusive to Windows to run on the Linux operating system. It uses Wine to facilitate this.

[Proton Next](https://github.com/ValveSoftware/Proton/wiki/Changelog) is an easier way to check out and test the upcoming stable releases of new Proton versions for Linux desktop and Steam Deck.

  **The following games are now playable:**
       - Rift
       - Unravel 2
       - Airborne Kingdom
       - Nancy Drew: Legend of the Crystal Skull
       - Re-Volt
       - Aspire: Ina's Tale
       - Battle Realms: Zen Edition
       - Deathsmiles II
       - Primal Carnage: Extinction
       - Pico Park Classic Edition
       - Six Ages: Ride Like the Wind
       - Darkstar One
       - Indiana Jones and the Emperor Tomb
       - Bulletstorm: Full Clip Edition
   * Fix Batman: Arkham City GOTY launching in the background on Steam Deck when set to fullscreen.
   * Fix Marvel's Spider-Man Remastered displaying dialog about outdated drivers on AMD systems.
   * Fix Final Fantasy IV (3D Remake) having no audio.
   * Fix Return to Monkey Island not reacting to mouse clicks after a recent game update.
   * Fix upsidedown videos in VRChat and many other games.
   * Fix Call of Duty Black Ops II Zombies and Multiplayer hanging on exit.
   * Fix Bail or Jail crashing when opening the Terms of Serivce.
   * Improve GTA V situation with not loading textures.
   * Fix Red Dead Redemption 2 crashing after a recent game update.
   * Fix Final Fantasy XIV Online launcher functionality after game update.
   * Fix cutscene stutter in Disgaea 5.
   * Fix Thrustmaster HOTAS having non-functional dial in Elite Dangerous.
   * Fix Planet Zoo randomly crashing.
   * Fix SCP: Secret Labratory not being playable after a recent game update (again).
   * Fix Tekken 7 crashing at launch.
   * Fix Armello hanging on exit.
   * Fix Sword Art Online: Hollow Realization freezing after the tutorial.
   * Fix Space Engineers intro video not playing correctly.
   * Fix Dragon's Dogma: Dark Arisen videos not playing correctly.
   * Implement network video support for VRChat.
   * Update dxvk to v1.10.3-28-ge3daa699.

[ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt) is a tool to install and manage [Proton-GE](https://github.com/GloriousEggroll/proton-ge-custom) and [Luxtorpeda](https://github.com/luxtorpeda-dev/luxtorpeda) for Steam and [Wine-GE](https://github.com/GloriousEggroll/wine-ge-custom) for Lutris with this graphical user interface. Based on AUNaseef's [ProtonUp](https://github.com/AUNaseef/protonup), made with Python 3 and Qt 6.

## Enable Proton in Steam

 - Click on “Steam” then “Settings” to open the Settings window at the far-left corner.
 - On the “Settings” window, click on “Steam Play.” Ensure you check the “Enable Steam Play for supported files” and “Enable Steam Play for   all other titles” checkboxes. Lastly, select the Proton version you wish to use from the drop-down menu.

 <img src="https://user-images.githubusercontent.com/45159366/106686402-13100100-657f-11eb-9012-6bdac264a808.png">

## ProtonDB
[Volver al Inicio](#tabla-de-contenidos)

[ProtonDB](https://www.protondb.com) is a collection of over 100,000 gaming reports from other gamers as they test games with Proton on Linux and provide aggregate scores of how well games perform. A growing pool of suggestions provides tweaks that you can try to get games working while Proton continues development. In addition to this, you may explore the Steam game catalog on this site to browse and discover a wide range of titles that were previously unavailable for use on Linux.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108773213-dcd8f800-7512-11eb-8775-19b0c8924d55.png">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/108773214-dd718e80-7512-11eb-983b-ce192e5b30f2.png">
</p>

## Lutris
[Volver al Inicio](#tabla-de-contenidos)

[Lutris](https://lutris.net)is a gaming client for Linux. It gives you access to all your video games with the exception of the current console generation. Also, integrates nicely with other stores like GOG, Steam, Battle.net, Origin, Uplay and many other sources that allow you to import your existing game library and community maintained install scripts give you a completely automated setup.

### Epic Games Store integration

[Volver al Inicio](#tabla-de-contenidos)

[Add Epic Games Store](https://lutris.net/games/epic-games-store/)

 <img src="https://user-images.githubusercontent.com/45159366/106686406-14412e00-657f-11eb-97c4-c80c6e25a374.png">
 
 ### Blizzard Battle.net intgeration
[Volver al Inicio](#tabla-de-contenidos)

[Blizzard Battle.net](https://lutris.net/games/battlenet/) is an internet-based online gaming, digital distribution, and digital rights management platform developed by Activision and Blizzard Entertainment. Battle.net is the launcher for World of Warcraft, Diablo III, StarCraft II, Hearthstone, Heroes of the Storm, Overwatch and Call of Duty.

<img src="https://user-images.githubusercontent.com/45159366/189614458-d51a15cb-d02d-4b1f-9e77-e712dcdb1d73.png">

### EA Play integration
[Volver al Inicio](#tabla-de-contenidos)

[EA Play](https://lutris.net/games/ea-desktop/) is a subscription-based video game service from Electronic Arts for the Xbox One, Xbox Series X/S, PlayStation 4, PlayStation 5 and Microsoft Windows platforms, offering access to selected games published by Electronic Arts along with additional incentives.

<img src="https://user-images.githubusercontent.com/45159366/189614466-476e0c4e-bab9-44bd-86c4-8aeadd739b63.png">

### Origin integration
[Volver al Inicio](#tabla-de-contenidos)
 
[Origin](https://lutris.net/games/origin/) is an online gaming, digital distribution and digital rights management (DRM) platform developed by Electronic Arts that allows users to purchase games on the internet for PC and mobile platforms, and download them with the Origin client (formerly EA Download Manager, EA Downloader and EA Link).

<img src="https://user-images.githubusercontent.com/45159366/189614468-49c4a05c-d6ca-4988-b3e6-10f0c71463d6.png">

### Ubisoft Connect integration
[Volver al Inicio](#tabla-de-contenidos)

[Ubisoft Connect](https://lutris.net/games/ubisoft-connect/) is a digital distribution, digital rights management, multiplayer and communications service created by Ubisoft to provide an experience similar to the achievements/trophies offered by various other game companies.

<img src="https://user-images.githubusercontent.com/45159366/189614471-422cbad8-1ae7-4f06-ad81-7f3b68550569.png">

### GOG Galaxy integration
[Volver al Inicio](#tabla-de-contenidos)

[GOG GALAXY](https://lutris.net/games/gog-galaxy/) is a fully optional client to install, play and update your games.

<img src="https://user-images.githubusercontent.com/45159366/189615528-385c01a8-f780-49e0-9502-db00d8082d9d.png">

### Playnite

[Volver al Inicio](#tabla-de-contenidos)

[Playnite](https://playnite.link/) is an open source video game library manager and launcher with support for 3rd party libraries like Steam, GOG, Origin, Battle.net and Ubisoft Connect. Includes game emulation support, providing one unified interface for your games.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/208235743-4521f909-f26c-4eb1-b259-0b06e9e1d380.png">
</p>

## GameHub
[Volver al Inicio](#tabla-de-contenidos)

[GameHub](https://github.com/tkashkin/GameHub) is a unified library for all your games. It allows you to store your games from different platforms into one program to make it easier for you to manage your games.

<img src="https://user-images.githubusercontent.com/45159366/107862734-96451880-6e03-11eb-9b92-9d355b890083.png">

**GameHub supports:**

 - native games for Linux
 - **multiple compatibility layers:**
   - Wine
   - Proton
   - [DOSBox](https://www.dosbox.com/)
   - [RetroArch](https://store.steampowered.com/app/1118310/RetroArch/)
   - [ScummVM](https://www.scummvm.org/)
   - [WineWrap](https://www.gog.com/forum/general/adamhms_linux_wine_wrappers_news_faq_discussion/post1) — a set of preconfigured wrappers for [supported games](https://www.gog.com/forum/general/adamhms_linux_wine_wrappers_news_faq_discussion/post3);
   - custom emulators

 - **multiple game platforms:**
   - [Steam](https://store.steampowered.com/)
   - [GOG](https://www.gog.com/)
   - [Humble Bundle (including Humble Trove)](https://www.humblebundle.com/)
   - [itch.io](https://itch.io/)


## Epic Games Store
[Volver al Inicio](#tabla-de-contenidos)

[Heroic](https://heroicgameslauncher.com/) is an Open Source Game Launcher for Linux, Windows and macOS (for both Native and Windows Games using Crossover). It supports launching games from the Epic Games Store using Legendary, a CLI alternative to the Epic Games Launcher. [Flatpak for Heroic Games Launcher](https://flathub.org/apps/details/com.heroicgameslauncher.hgl)

[Epic Games Store](https://www.epicgames.com/store/) is a digital video game storefront for Microsoft Windows and macOS, operated by Epic Games.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/111918016-3fed7a00-8a40-11eb-964e-930c801c1c72.png">
</p>

## Game Streaming
[Volver al Inicio](#tabla-de-contenidos)

### Cloud Game Streaming

[Volver al Inicio](#tabla-de-contenidos)

[Xbox Cloud Gaming](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming) is Microsoft's cloud-based Xbox game-streaming technology **(currently in Beta)**. **Play games like Forza Horizon 4, Halo 5: Guardians, Gears of War 4, Sea of Thieves, Cuphead, Red Dead Redemption 2, and 100+ other games on your mobile device or Chrome web browser**. Xbox Cloud Gaming does require an **[Xbox Game Pass Ultimate](https://www.xbox.com/en-US/xbox-game-pass/cloud-gaming)** subscription.

<img src="https://user-images.githubusercontent.com/45159366/108111388-74d56e00-7049-11eb-8aeb-3e5d65f9e832.png">

[Geforce NOW](https://www.nvidia.com/en-us/geforce-now/download/) is NVIDIA's Cloud Gaming Service.

<img src="https://user-images.githubusercontent.com/45159366/106686391-0f7c7a00-657f-11eb-9d0b-1ebb4d385883.jpeg">

[Amazon Luna](https://www.amazon.com/luna/landing-page) is Amazon's Cloud Gaming Service. Amazon Luna is Compatible/Supported on a vartiey of [Devices and Browsers](https://www.amazon.com/gp/help/customer/display.html?nodeId=GUFHUSX8X324T4XE).

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/112693072-364b8400-8e3d-11eb-9df0-d58af7ac9c9c.png">
</p>

[Shadow](https://shadow.tech/) is a fully-featured, cloud-based, high-end computer. It is the only remote service that offers performance capable of competing with a local PC. Available on Windows, macOS, Linux, Android/AndroidTV, and iOS/tvOS.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/200110962-dd631248-7a13-48bb-9b5a-acbbf8550e16.png">
</p>

### Local Game Streaming

[Volver al Inicio](#tabla-de-contenidos)

[Steam Remote Play Together](https://store.steampowered.com/remoteplay/#together) is a steam service that let's you share your Steam local multi-player games with friends over the internet, for free. Using Remote Play Together, one player owns and runs the game, then up to four players can join.

[Steam Link app](https://store.steampowered.com/steamlink/about) is available free of charge, streaming your Steam PC games to phones, tablets, and TV.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/112692999-14ea9800-8e3d-11eb-964a-6bee4e665900.png">
</p>

[Chiaki](https://git.sr.ht/~thestr4ng3r/chiaki) is a Free and Open Source Software Client for **PlayStation 4 and PlayStation 5 Remote Play** for Linux, FreeBSD, OpenBSD, Android, macOS, Windows, Nintendo Switch and potentially even more platforms. [Chiaki Flatpak](https://flathub.org/apps/details/re.chiaki.Chiaki)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/208854787-3442b9df-60bc-4ed2-87e3-efaa159a6b7f.png">
</p>

[Parsec](https://parsec.app/cloud-gaming) is a video game streaming platform, which offers a wide variety of games and genres to choose from and provides a high-quality and smooth gameplay. SParsec is developed in order to provide a high-quality smooth gameplay, same time to be free of all ads and in-game purchases.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/166166858-e70ca081-8931-46f3-9dc3-fe9c719d76f8.png">
</p>

[Moonlight Game Streaming](https://moonlight-stream.org/) is a program that let you stream from your PC games over the Internet with no configuration required. Stream from almost any device, whether you're in another room or miles away from your gaming rig. [Sunshine](https://github.com/LizardByte/Sunshine) is a **Game stream host for Moonlight** that is a self-hosted, low latency, cloud gaming solution with support for AMD, Intel, and NVIDIA GPUs.

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/106686398-11463d80-657f-11eb-841a-d534829ccc3d.png">
</p>

## Game Emulators
[Volver al Inicio](#tabla-de-contenidos)

**Also checkout these subreddits for more great Game Emulators recommendations**
  
   - [r/emulation](https://www.reddit.com/r/emulation/)
   - [r/emulations](https://www.reddit.com/r/emulators/)
   - [r/RetroArch](https://www.reddit.com/r/RetroArch/)
   - [r/DolphinEmulator](https://www.reddit.com/r/DolphinEmulator/)
   - [r/Citra](https://www.reddit.com/r/Citra/)
   - [r/cemu](https://www.reddit.com/r/cemu/)
   - [r/yuzu](https://www.reddit.com/r/yuzu/)
   - [r/OpenEmu](https://www.reddit.com/r/OpenEmu/)
   - [r/MAME](https://www.reddit.com/r/MAME/)
   - [r/EmuDev](https://www.reddit.com/r/EmuDev/)
   - [r/Roms](https://www.reddit.com/r/Roms/)

### Frontends

[EmulationStation Desktop Edition (ES-DE)](https://www.es-de.org/) is a frontend application for browsing and launching games from your multi-platform game collection. It's  available for Unix/Linux, macOS(M1 & Intel) and Windows. 

[RetroArch](https://www.retroarch.com/) is a frontend for emulators, game engines and media players. It enables you to run classic games on a wide range of computers and consoles through its slick graphical interface. Settings are also unified so configuration is done once and for all. [RetroArch Flatpak](https://flathub.org/apps/details/org.libretro.RetroArch)

[RetroPie](https://retropie.org.uk/) is a frontend for emulators that allows you to turn your Raspberry Pi, ODroid C1/C2, or PC into a retro-gaming machine. It builds upon Raspbian, [EmulationStation](https://github.com/Aloshi/EmulationStation), RetroArch and many other projects to enable you to play your favourite Arcade, home-console, and classic PC games with the minimum set-up.

[Pegasus](https://pegasus-frontend.org/) is a cross platform, customizable graphical frontend for launching emulators and managing your game library (especially retro games) and launching them from one place. It's focused on customizability, cross platform support (including embedded devices) and high performance. [Pegasus Flatpak](https://flathub.org/apps/details/org.pegasus_frontend.Pegasus)

[Mednaffe](https://github.com/AmatCoder/mednaffe) is a front-end (GUI) for mednafen emulator which is a portable argument(command-line)-driven multi-system emulator. [Mednaffe Flatpak](https://flathub.org/apps/details/com.github.AmatCoder.mednaffe)

**The following systems are supported:**

  * Atari Lynx
  * Neo Geo Pocket (Color)
  * WonderSwan
  * GameBoy (Color)
  * GameBoy Advance
  * Nintendo Entertainment System
  * Super Nintendo Entertainment System/Super Famicom
  * Virtual Boy
  * PC Engine/TurboGrafx 16 (CD)
  * SuperGrafx
  * PC-FX
  * Sega Game Gear
  * Sega Genesis/Megadrive
  * Sega Master System
  * Sega Saturn (experimental, x86_64 only)
  * Sony PlayStation

[Cartridge](https://github.com/unclebacon-live/cartridge) is a self-hosted game library made with Laravel + Vue.js.

Cartridge Features

- Scan for ROM files and match with IGDB game information
- Serve ROM download links alongside game details
- Manage access to library with user creation and permissions (WIP)
- Allow users to request games (Planned)
- Play select ROMs in-browser using JS emulators (Planned)
- Track played and favorite games (even ones that aren't available for download) (Planned)

<p align="center">
  <img src="https://user-images.githubusercontent.com/45159366/172274231-d691a850-1879-44fb-8fa0-08e549d7bb29.png">
    <br />
      Cartridge UI
</p>

### Nintendo GameCube & Wii

[Dolphin](https://dolphin-emu.org) is an emulator for two recent Nintendo video game consoles: the GameCube and the Wii. It allows PC gamers to enjoy games for these two consoles in full HD (1080p) with several enhancements: compatibility with all PC controllers, turbo speed, networked multiplayer, and even more. [Dolphin Flatpak](https://flathub.org/apps/details/org.DolphinEmu.dolphin-emu)

### Nintendo Switch 

[Ryujinx](https://ryujinx.org/) is an open-source Nintendo Switch emulator created by gdkchan and written in C#. This emulator aims at providing excellent accuracy and performance, a user-friendly interface, and consistent builds. [Ryujinx Flatpak](https://flathub.org/apps/details/org.ryujinx.Ryujinx)

[yuzu](https://yuzu-emu.org) is an experimental open-source emulator for the Nintendo Switch from the creators of Citra. [yuzu](https://yuzu-emu.org) is an experimental open-source emulator for the Nintendo Switch from the creators of Citra.[Yuzu Flatpak](https://flathub.org/apps/details/org.yuzu_emu.yuzu)

### Nintendo 64

[m64p](https://m64p.github.io/) is a Nintendo 64 Emulator. It uses mupen64plus-gui, a brand new mupen64plus frontend written in Qt5. It supports all of the things you’d expect from a frontend (savestate management, pausing, screenshots). [m64p Flatpak](https://flathub.org/apps/details/io.github.m64p.m64p)

[simple64](https://github.com/simple64/simple64) is an emulator based on a heavily modified version of mupen64plus-core, and ParaLLEl RSP/RDP. It includes a GUI, netplay, controller configuration, and  more. [simple64 Flatpak](https://flathub.org/apps/details/io.github.simple64.simple64)

Nintendo 3DS

[Citra](https://citra-emu.org/) is an open-source emulator for the Nintendo 3DS capable of playing many of your favorite games.[Citra Flatpak](https://flathub.org/apps/details/org.citra_emu.citra)

### Nintendo DS

[DeSmuME](https://desmume.org/) is a Nintendo DS emulator. [DeSmuME Flatpak](https://flathub.org/apps/details/org.desmume.DeSmuME)

[melonDS](https://github.com/melonDS-emu/melonDS) is a tool that aims at providing fast and accurate Nintendo DS emulation. While it is still a work in progress, it has a pretty solid set of features. [melonDS Flatpak](https://flathub.org/apps/details/net.kuribo64.melonDS)

**Features:**

   * Nearly complete core (CPU, video, audio, etc...)
   * OpenGL renderer, 3D upscaling
   * RTC, microphone, lid close/open
   * Joystick support
   * Savestates
   * Various display position/sizing/rotations modes
   * Work-in-progress Wi-Fi emulation for online connectivity and local multiplayer
   * Experimental emulation of the Nintendo DSi

### Super Nintendo Entertainment System (SNES)

[Snes9x](https://www.snes9x.com/) is a portable, freeware Super Nintendo Entertainment System (SNES) emulator. [Snes9x Flatpak](https://flathub.org/apps/details/com.snes9x.Snes9x) 

[bsnes](https://github.com/bsnes-emu/bsnes) is a Super Nintendo (SNES) emulator focused on performance, features, and ease of use. [bsnes flatpak](https://flathub.org/apps/details/dev.bsnes.bsnes)

### Nintendo Entertainment System  

[Nestopia](https://github.com/0ldsk00l/nestopia) is a portable NES/Famicom emulator written in C++. [Nestopia Flatpak](https://flathub.org/apps/details/ca._0ldsk00l.Nestopia)

### Game Boy Advance

[mGBA](https://mgba.io/) is a new emulator for running Game Boy Advance games. It aims to be faster and more accurate than many existing Game Boy Advance emulators, as well as adding features that other emulators lack. [mGBA Flatpak](https://flathub.org/apps/details/io.mgba.mGBA)

[SameBoy](https://github.com/LIJI32/SameBoy) is an open source Game Boy (DMG) and Game Boy Color (CGB) emulator, written in portable C. It has an SDL frontend and a libretro core. [SameBoy Flatpak](https://flathub.org/apps/details/io.github.sameboy.SameBoy)

[GB Enhanced+](https://github.com/shonumi/gbe-plus) is an original Game Boy, Game Boy Color and Game Boy Advance emulator. Its focus is on completeness of emulation, including peripherals. [GB Enhanced+ Flatpak](https://flathub.org/apps/details/com.github.shonumi.gbe-plus)

### DOS 

[DOSBox](https://www.dosbox.com/) is an open-source DOS emulator which primarily focuses on running DOS Games.

[DOSBox Staging](https://github.com/dosbox-staging/dosbox-staging) is a full x86 CPU emulator (independent of host architecture), capable of running DOS programs that require real or protected mode. [DOSBox Staging Flatpak](https://flathub.org/apps/details/io.github.dosbox-staging)

### Atari

[Stella](https://stella-emu.github.io/) is a multi-platform Atari 2600 VCS emulator released under the GNU General Public License (GPL). Stella is available on Windows MacOS, Linux, and FreeBSD. [Stella Flatpak](https://flathub.org/apps/details/io.github.stella_emu.Stella)

[Hatari](https://hatari.tuxfamily.org/) is an Atari ST/STE/TT/Falcon emulator for Linux, BSD, MacOS, Windows and other systems which are supported by the SDL library. The Atari ST was a 16/32 bit computer system which was first released by Atari in 1985. [Hatrai Flatpak](https://flathub.org/apps/details/org.tuxfamily.hatari)

### Sega Dreamcast

[Flycast](https://github.com/flyinghead/flycast) is a multi-platform Sega Dreamcast, Naomi and Atomiswave emulator derived from reicast. [Flycast Flatpak](https://flathub.org/apps/details/org.flycast.Flycast)

### PlayStation Portable

[PPSSPP](https://www.ppsspp.org/) is a PSP emulator that can run games in full HD resolution. It can even upscale textures that would otherwise be too blurry as they were made for the small screen of the original PSP. [PPSSPP Flatpak](https://flathub.org/apps/details/org.ppsspp.PPSSPP)

### PlayStation 1

[DuckStation](https://www.duckstation.org/) is an simulator/emulator of the Sony PlayStation 1 console, focusing on playability, speed, and long-term maintainability. [DuckStation Flatpak](https://flathub.org/apps/details/org.duckstation.DuckStation).

[Avocado](https://github.com/JaCzekanski/Avocado) is a Modern PlayStation 1 emulator.

### PlayStation 2

[PCSX2](https://pcsx2.net/) is a Playstation 2 'emulator', a free program that tries to replicate the Playstation 2 console to enable you to play PS2 games on your PC. [PCSX2 Flatpak](https://flathub.org/apps/details/net.pcsx2.PCSX2)

[Play!](https://github.com/jpd002/Play-) is a PlayStation2 emulator for Windows, macOS, Linux, Android, iOS and web browser platforms. [Play! Flatpak](https://flathub.org/apps/details/org.purei.Play)

### PlayStation 3

[RPCS3](https://rpcs3.net/) is an experimental open-source Sony PlayStation 3 emulator and debugger written in C++ for Windows and Linux. RPCS3 started development in May of 2011 by its founders DH and Hykem. The emulator is currently capable of running over 1800 commercial titles powered by Vulkan and OpenGL. [RPCS3 Flatpak](https://flathub.org/apps/details/net.rpcs3.RPCS3)

### Xbox

[xemu](https://xemu.app/) is an original Xbox emulator. [xemu Flatpak](https://flathub.org/apps/details/app.xemu.xemu)

[Xenia](https://github.com/xenia-project/xenia) is an Xbox 360 Emulator. 

### MAME

[MAME](https://www.mamedev.org/) is a Arcade Machine Emulator. [MAME Flatpak](https://flathub.org/apps/details/org.mamedev.MAME)


## Hardware Performance(CPU, GPU, Gaming Peripherals)
[Volver al Inicio](#tabla-de-contenidos)

### NVIDIA
[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189858113-0d681062-8bd5-4db9-b92b-71bec318f2f5.png">
  <br />
</p>

 * [NVIDIA Linux Open GPU Kernel Module Source](https://github.com/NVIDIA/open-gpu-kernel-modules)

[GreenWithEnvy (GWE)](https://gitlab.com/leinardi/gwe) is a GTK system utility designed by Roberto Leinardi to provide information, control the fans and overclock your NVIDIA video card for better performance. Available as a [Flatpak on FlatHub](https://flathub.org/apps/details/com.leinardi.gwe).

 <img src="https://user-images.githubusercontent.com/45159366/107091994-89974380-67b7-11eb-85ed-eedec7e3dfbf.png">
 
 ### AMD 
 [Volver al Inicio](#tabla-de-contenidos)
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190588167-4fd0bd50-cd43-47f1-b28f-16f70a243549.png">
  <br />
</p>
 
* **[AMD FidelityFX Super Resolution (FSR)](https://www.amd.com/en/technologies/radeon-software-fidelityfx)** is an open source, high-quality solution for producing high resolution frames from lower resolution inputs. FSR enables “practical performance” for costly render operations, such as hardware ray tracing for the AMD RDNA™ and AMD RDNA™ 2 architectures.

* **[AMD FidelityFX Super Resolution (FSR) 2.0](https://github.com/GPUOpen-Effects/FidelityFX-FSR2)** is an open source, high-quality solution for producing high resolution frames from lower resolution inputs. It uses temporal data and optimized anti-aliasing to boost framerates in supported games while delivering similar or better image quality than native resolution.

* **[AMD Open Source Driver for Vulkan®](https://github.com/GPUOpen-Drivers/AMDVLK)** is an open-source Vulkan driver for Radeon™ graphics adapters on Linux®. It is built on top of AMD's Platform Abstraction Library (PAL), a shared component that is designed to encapsulate certain hardware and OS-specific programming details for many of AMD's 3D and compute drivers. 

* **[Vulkan® Memory Allocator (VMA)](https://gpuopen.com/vulkan-memory-allocator/)** is a library provides a simple and easy to integrate API to help you allocate memory for Vulkan® buffer and image storage. 

* **[Radeon™ Raytracing Analyzer (RRA)](https://gpuopen.com/radeon-raytracing-analyzer/)** is a tool that investigates the performance of your raytracing applications and highlight potential bottlenecks.

* **[Radeon™ GPU Profiler](https://gpuopen.com/rgp/)** is a low-level optimization tool that provides detailed information on Radeon™ GPUs.

* **[Radeon™ GPU Analyzer](https://gpuopen.com/rga/)** is an offline compiler and performance analysis tool for DirectX®, Vulkan®, SPIR-V™, OpenGL®, and OpenCL™. It can be used together with [RGP](https://gpuopen.com/rgp/), [RMV](https://gpuopen.com/rmv/), and [RDP](https://gpuopen.com/rdp/).

 * **[Radeon™ Developer Panel (RDP)](https://gpuopen.com/rdp/)** is an essential part of the Radeon™ Developer Tool Suite. It provides the communication channel that delivers requests to, and receives data from, the AMD Radeon™ driver.

* **[Radeon™ Memory Visualizer (RMV)](https://gpuopen.com/learn/radeon-memory-visualizer-on-linux/)** is a powerful tool that allows users to analyze video memory usage on AMD Radeon GPUs.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190555167-e1293b98-eaf1-4df0-815c-88569b8dfe23.png">
  <br />
  Radeon™ Memory Visualizer (RMV)
</p>


* **[CoreCtrl](https://gitlab.com/corectrl/corectrl)** is a free and open source Linux application that allows you to control your computer hardware with ease using application profiles for native and Windows applications, along with basic CPU controls and full AMD GPUs controls (for both old and new models). 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190553872-1111d52c-dc73-4868-8e27-60a8d0f57937.png">
  <br />
  CoreCtrl
</p>

### Intel ARC
[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190093904-20680f0b-a387-4a48-9c43-de8d5f0b5d2e.png">
  <br />
</p>

**Version requirements for DG2/Alchemist hardware on Linux:**

* **[Linux Kernel 6.0 or newer](https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git)**
* **[Mesa 22.2 or newer](https://gitlab.freedesktop.org/mesa/mesa/-/tree/22.2)** for ANV Vulkan and Iris OpenGL will in turn work out-of-the-box with current cards when booting with the necessary kernel support in place.
* **[Latest linux-firmware.git](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git)** for the very latest GuC firmware support.

**Note:** With Linux 6.0 the DG2 class support is not exposed by default but requires setting the **i915.force_probe=[PCI-ID] module option** to force the driver to initialize the graphics card. 

**On Debian-based systems:**

```sudo dmesg | grep -i i915```

**On Arch Linux-based systems:**

```su dmesg | grep -i i915```

[Intel Xe Super Sampling (XeSS)](https://www.intel.com/content/www/us/en/products/docs/arc-discrete-graphics/xess.html) is a temporal image upscaling AI rendering technology that increases graphics performance similar to [NVIDIA's DLSS (Deep Learning Super Sampling)](https://developer.nvidia.com/dlss). Intel's Arc GPU architecture (Fall 2022) will have GPUs that feature dedicated Xe-cores to run XeSS. The GPUs will have Xe Matrix eXtenstions matrix (XMX) engines for hardware-accelerated AI processing. XeSS will be able to run on devices without XMX, including integrated graphics, though, the performance of XeSS will be lower on non-Intel graphics cards because it will be powered by [DP4a instruction](https://www.intel.com/content/dam/www/public/us/en/documents/reference-guides/11th-gen-quick-reference-guide.pdf).


* [ Intel XeSS ML Upscaling | The Digital Foundry Tech Review | XeSS vs DLSS vs Native](https://www.youtube.com/watch?v=rfLwZy650s0)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190093928-ca15e58b-f830-47f5-b66b-19219d160178.png">
  <br />
</p>

Intel ARC GPUs Overview. Credit: [Intel](https://www.intel.com/content/www/us/en/products/details/discrete-gpus/arc.html)

### Gaming Peripherals
[Volver al Inicio](#tabla-de-contenidos)

[OpenRazer](https://openrazer.github.io/) is a collection of Linux drivers for Razer devices - providing kernel drivers, DBus services and Python bindings to interact with the DBus interface.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189784910-8704a50d-0a9b-454c-8a49-9f87127062b1.png">
  <br />
</p>

[OpenRGB](https://gitlab.com/CalcProgrammer1/OpenRGB) is a network-based Software Development Kit, which allows third-party software to control all of your RGB. This allows for game integrations, music visualization, ambient lighting, and anything else you can imagine. It supports ASUS, ASRock, Corsair, G.Skill, Gigabyte, HyperX, MSI, Razer, ThermalTake, and more.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189850391-73936b95-8996-44f3-8d81-bd0938a379fd.png">
  <br />
</p>

[GX52](https://gitlab.com/leinardi/gx52) is a GTK application designed to provide control for the LEDs and MFD of Logitech X52 and X52 Pro H.O.T.A.S.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189784925-ebe6c07f-bfe4-441d-b705-1dc737fbacdf.png">
  <br />
</p>

[Coolero](https://gitlab.com/coolero/coolero) is a program to monitor and control your cooling devices. It offers an easy-to-use user interface with various control features and also provides live thermal performance details.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189784926-67102123-7bb4-4ccd-9fde-c499780c45e5.gif">
  <br />
</p>
 
[Piper](https://github.com/libratbag/piper/) is a frontend GTK application to configure gaming devices(mainly Gaming Mice).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189784915-770052d0-7764-41d8-8501-1b4404e716a3.png">
  <br />
</p>
 
[StreamDeck-UI](https://timothycrosley.github.io/streamdeck-ui/) is a Linux compatible UI for the [Elgato Stream Deck](https://www.elgato.com/en/stream-deck).

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189784917-512c6757-4cc5-41bb-b9bb-9b1cd3500255.gif">
  <br />
</p>
 
[Asusctl](https://asus-linux.org/) is a control daemon, CLI tools, and a collection of crates for interacting with ASUS ROG laptops.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189784927-21208072-450e-4018-a613-3e3156535cc4.png">
  <br />
</p>

[MangoHud](https://github.com/flightlessmango/MangoHud) is a Vulkan and OpenGL overlay for monitoring FPS, temperatures, CPU/GPU load and more.

[GOverlay](https://github.com/benjamimgois/goverlay) is an open source project aimed to create a Graphical UI to manage Vulkan/OpenGL overlays. It is still in early development.

## Performance Benchmarks
[Volver al Inicio](#tabla-de-contenidos)

[Geekbench 5](https://www.geekbench.com/download/) is a cross-platform benchmark that measures your system's performance with the press of a button.

[Phoronix Test Suite](https://www.phoronix-test-suite.com/)

[UNIGINE Superposition](https://benchmark.unigine.com/superposition) is an extreme performance and stability test for PC hardware: video card, power supply, cooling system.

<img src="https://user-images.githubusercontent.com/45159366/107092007-8f8d2480-67b7-11eb-9c3f-a0cb02e6dfcd.png">

## Wine
[Volver al Inicio](#tabla-de-contenidos)

[WINE(Wine Is Not an Emulator)](https://www.winehq.org) is a compatibility layer capable of running Windows applications on several POSIX-compliant operating systems, such as Linux, macOS, & BSD. Instead of simulating internal Windows logic like a virtual machine or emulator, Wine translates Windows API calls into POSIX calls on-the-fly, eliminating the performance and memory penalties of other methods and allowing you to cleanly integrate Windows applications into your desktop.

### Winetricks

[Winetricks](https://github.com/Winetricks/winetricks) is an easy way to work around problems in Wine. 
  
# WireGuard
[Back to the Top](https://github.com/VanitasuShieda/Self-Hosting-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147891038-00f57362-e843-4bfb-be31-606c954d4e6c.png">
  <br />
</p>


[WireGuard®](https://www.wireguard.com/) is a straight-forward, fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec while avoiding the massive headache. It intends to be considerably more performant than OpenVPN. WireGuard is designed as a general-purpose VPN for running on embedded interfaces and super computers alike, fit for many circumstances. Initially released for the Linux kernel, it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely deployable. It is currently under a massive development, but it already might be regarded as the most secure, most comfortable to use, and the simplest VPN solution in the industry.

[Wiretrustee](https://wiretrustee.com/) is a WireGuard®-based mesh network that connects your devices into a single private network.

[Wireguard Manager](https://github.com/complexorganizations/wireguard-manager) is a tool that enables you to build your own vpn under a minute.

[Tailscale](https://github.com/tailscale) is a WireGuard-based app that makes secure, private networks easy for teams of any scale. It works like an [overlay network](https://tailscale.com/blog/how-tailscale-works/) between the computers of your networks using all kinds of [NAT traversal sorcery](https://tailscale.com/blog/how-nat-traversal-works/).

[Headscale](https://github.com/juanfont/headscale) is an open source, self-hosted implementation of the Tailscale coordination server.

[Firezone](https://firezone.dev/) is a self-hosted WireGuard®-based VPN server and Linux firewall.

[Mistborn](https://gitlab.com/cyber5k/mistborn) is a secure platform for easily standing up and managing your own cloud services: including firewall, ad-blocking, and multi-factor WireGuard VPN access.

[Mistborn CLI](https://gitlab.com/cyber5k/mistborn-cli) is a Command-line interface for [Mistborn](https://gitlab.com/cyber5k/mistborn).

[BoringTun](https://github.com/cloudflare/boringtun) is an implementation of the WireGuard® protocol designed for portability and speed. It's successfully deployed on millions of [iOS](https://apps.apple.com/us/app/1-1-1-1-faster-internet/id1423538627) and [Android](https://play.google.com/store/apps/details?id=com.cloudflare.onedotonedotonedotone&hl=en_US) consumer devices as well as thousands of Cloudflare Linux servers.

[PiVPN](https://pivpn.io/) is the simplest VPN installer, designed for [Raspberry Pi](https://www.raspberrypi.com).

[Algo VPN](https://github.com/trailofbits/algo) is a set of Ansible scripts that simplify the setup of a personal WireGuard and IPsec VPN. It uses the most secure defaults available and works with common cloud providers.

[Pro Custodibus](https://www.procustodibus.com/features/) is a tool for managing WireGuard with a variety of business VPN (Virtual Private Network) use cases, such as site-to-site connectivity, secure remote access from anywhere, secure access to the cloud (Amazon Web Services, Google Cloud Platform, Microsoft Azure, etc), and more.

[Drago](https://seashell.github.io/drago) is a flexible configuration manager for WireGuard designed to make it simple to configure secure network overlays spanning heterogeneous nodes distributed across different clouds and physical locations. Drago is in active development, and we welcome contributions from the open-source community.

[Netmaker](https://netmaker.org/) is a tool that helps connect any computers together over a secure, fast, private network, and manage multiple networks from a central server.

[Kilo](https://github.com/squat/kilo) is a multi-cloud network overlay built on WireGuard and designed for Kubernetes. Kilo connects nodes in a cluster by providing an encrypted layer 3 network that can span across data centers and public clouds. The Pod network created by Kilo is always fully connected, even when the nodes are in different networks or behind NAT. By allowing pools of nodes in different locations to communicate securely, Kilo enables the operation of multi-cloud clusters. Kilo's design allows clients to VPN to a cluster in order to securely access services running on the cluster.

[Subspace](https://github.com/subspacecloud/subspace) is a simple WireGuard VPN server GUI.

[WG UI](https://github.com/EmbarkStudios/wg-ui) is a basic, self-contained management service for WireGuard with a self-serve web UI.

[WireHole](https://github.com/IAmStoxe/wirehole) is a combination of WireGuard, PiHole, and Unbound in a docker-compose project with the intent of enabling users to quickly and easily create and deploy a personally managed full or split-tunnel WireGuard VPN with ad blocking capabilities (via Pihole), and DNS caching with additional privacy options (via Unbound).

[Gluetun](https://github.com/qdm12/gluetun) is a lightwieght VPN client in a thin Docker container for multiple VPN providers, written in Go, and uses OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in.

[Ethr](https://github.com/microsoft/ethr) is a cross platform network performance measurement tool written in golang. The goal of this project is to provide a native tool for comprehensive network performance measurements of bandwidth, connections/s, packets/s, latency, loss & jitter, across multiple protocols such as TCP, UDP, HTTP, HTTPS, and across multiple platforms such as Windows, Linux and other Unix systems.

# Linux Security Hardening
[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/189516372-57bd1f95-6fde-448f-98bb-45e116338b4a.png">
  <br />
</p>

### Security Standards, Frameworks and Benchmarks 

 * [Personal Security Checklist](https://github.com/Lissy93/personal-security-checklist) is a curated checklist of 300+ tips for protecting digital security and privacy in 2022.

 * [Awesome Privacy](https://github.com/Lissy93/awesome-privacy) is acurated list of privacy & security-focused software and services. 

 * [STIGs Benchmarks - Security Technical Implementation Guides](https://public.cyber.mil/stigs/)

 * [CIS Benchmarks - CIS Center for Internet Security](https://www.cisecurity.org/cis-benchmarks/)

 * [CIS Top 18 Critical Security Controls](https://www.cisecurity.org/controls/cis-controls-list)

 * [OSSTMM (Open Source Security Testing Methodology Manual) PDF](https://github.com/VanitasuShieda/Open-Source-Security-Guide/files/8834704/osstmm.en.2.1.pdf)

 * [NIST Technical Guide to Information Security Testing and Assessment (PDF)](https://github.com/VanitasuShieda/Open-Source-Security-Guide/files/8834705/nistspecialpublication800-115.pdf)

 * [NIST - Current FIPS](https://www.nist.gov/itl/current-fips)

 * [ISO Standards Catalogue](https://www.iso.org/standards.html)

 * [Common Criteria for Information Technology Security Evaluation (CC)](https://www.commoncriteriaportal.org/cc/) is an international standard (ISO / IEC 15408) for computer security. It allows an objective evaluation to validate that a particular product satisfies a defined set of security requirements. 

 * [ISO 22301](https://www.iso.org/en/contents/data/standard/07/51/75106.html) is the international standard that provides a best-practice framework for implementing an optimised BCMS (business continuity management system).

 * [ISO27001](https://www.iso.org/isoiec-27001-information-security.html) is the international standard that describes the requirements for an ISMS (information security management system). The framework is designed to help organizations manage their security practices in one place, consistently and cost-effectively.

 * [ISO 27701](https://www.iso.org/en/contents/data/standard/07/16/71670.html) specifies the requirements for a PIMS (privacy information management system) based on the requirements of ISO 27001. It is extended by a set of privacy-specific requirements, control objectives and controls. Companies that have implemented ISO 27001 will be able to use ISO 27701 to extend their security efforts to cover privacy management.
 
 * [SOC 2](https://www.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpasoc2report.html) is an auditing procedure that ensures your service providers securely manage your data to protect the interests of your company/organization and the privacy of their clients. 

 * [NIST CSF](https://www.nist.gov/national-security-standards) is a voluntary framework primarily intended for critical infrastructure organizations to manage and mitigate cybersecurity risk based on existing best practice.

 * [Landlock LSM(Linux Security Module)](https://www.kernel.org/doc/html/latest/security/landlock.html) is a framework to create scoped access-control (sandboxing). Landlock is designed to be usable by unprivileged processes while following the system security policy enforced by other access control mechanisms (DAC, LSM, etc.).
 
### Security Tools

[OpenSCAP](https://www.open-scap.org/) is U.S. standard maintained by [National Institute of Standards and Technology (NIST)](https://www.nist.gov/). It provides multiple tools to assist administrators and auditors with assessment, measurement, and enforcement of security baselines. OpenSCAP maintains great flexibility and interoperability by reducing the costs of performing security audits. Whether you want to evaluate DISA STIGs, NIST‘s USGCB, or Red Hat’s Security Response Team’s content, all are supported by OpenSCAP.

[Open Vulnerability and Assessment Language](https://oval.mitre.org/) is a community effort to standardize how to assess and report upon the machine state of computer systems. OVAL includes a language to encode system details, and community repositories of content. Tools and services that use OVAL provide enterprises with accurate, consistent, and actionable information to improve their security.

[OWASP](https://www.owasp.org/index.php/Main_Page) is an online community, produces freely-available articles, methodologies, documentation, tools, and technologies in the field of web application security.

[OWASP Nettacker](https://github.com/OWASP/Nettacker) is a project created to automate information gathering, vulnerability scanning and eventually generating a report for networks, including services, bugs, vulnerabilities, misconfigurations, and other information. This software will utilize TCP SYN, ACK, ICMP, and many other protocols in order to detect and bypass Firewall/IDS/IPS devices. 

[OWASP Zed Attack Proxy (ZAP)](https://owasp.org/www-project-zap/) is a free, open-source penetration testing tool being maintained under the umbrella of the Open Web Application Security Project (OWASP). ZAP is designed specifically for testing web applications and is both flexible and extensible. Great for pentesters, devs, QA, and CI/CD integration. At its core, ZAP is what is known as a "man-in-the-middle proxy."

[SELinux](https://github.com/SELinuxProject/selinux) is a security enhancement to Linux which allows users and administrators more control over access control. Access can be constrained on such variables as which users and applications can access which resources. These resources may take the form of files. Standard Linux access controls, such as file modes (-rwxr-xr-x) are modifiable by the user and the applications which the user runs. Conversely, SELinux access controls are determined by a policy loaded on the system which may not be changed by careless users or misbehaving applications.

[AppArmor](https://www.apparmor.net/) is an effective and easy-to-use Linux application security system. AppArmor proactively protects the operating system and applications from external or internal threats, even zero-day attacks, by enforcing good behavior and preventing both known and unknown application flaws from being exploited. AppArmor supplements the traditional Unix discretionary access control (DAC) model by providing mandatory access control (MAC). It has been included in the mainline Linux kernel since version 2.6.36 and its development has been supported by Canonical since 2009.

[Control Groups(Cgroups)](https://www.redhat.com/sysadmin/cgroups-part-one) is a Linux kernel feature that allows you to allocate resources such as CPU time, system memory, network bandwidth, or any combination of these resources for user-defined groups of tasks (processes) running on a system.

[SpiderFoot](https://github.com/smicallef/spiderfoot) is an open source intelligence (OSINT) automation tool. It integrates with just about every data source available and utilises a range of methods for data analysis, making that data easy to navigate.

[Lynis](https://cisofy.com/lynis/) is a security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening. Agentless, and installation is optional.

[Fail2Ban](http://www.fail2ban.org/) is an open source intrusion prevention software framework that scans log files like /var/log/auth.log and bans IP addresses conducting too many failed login attempts. It does this by updating system firewall rules to reject new connections from those IP addresses, for a configurable amount of time. 

[Aircrack-ng](https://www.aircrack-ng.org/) is a network software suite consisting of a detector, packet sniffer, WEP and WPA/WPA2-PSK cracker and analysis tool for 802.11 wireless LANs. It works with any wireless network interface controller whose driver supports raw monitoring mode and can sniff 802.11a, 802.11b and 802.11g traffic.

[Burp Suite](https://portswigger.net/burp) is a leading range of cybersecurity tools.

[KernelCI](https://foundation.kernelci.org/) is a community-based open source distributed test automation system focused on upstream kernel development. The primary goal of KernelCI is to use an open testing philosophy to ensure the quality, stability and long-term maintenance of the Linux kernel.

[Continuous Kernel Integration project](https://github.com/cki-project) helps find bugs in kernel patches before they are commited to an upstram kernel tree. We are team of kernel developers, kernel testers, and automation engineers.

[Snowpatch](https://github.com/ruscur/snowpatch) is a continuous integration tool for projects using a patch-based, mailing-list-centric git workflow. This workflow is used by a number of well-known open source projects such as the Linux kernel.

[Snort](https://www.snort.org/) is an open-source, free and lightweight network intrusion detection system (NIDS) software for Linux and Windows to detect emerging threats.

[Wireshark](https://www.wireshark.org/) is a free and open-source packet analyzer. It is used for network troubleshooting, analysis, software and communications protocol development, and education. 

[Tink](https://github.com/google/tink) is a multi-language, cross-platform, open source library that provides cryptographic APIs that are secure, easy to use correctly, and harder to misuse. 

[OSSEC HIDS(Host Intrusion Detection System)](https://www.ossec.net/) is an open source security tool that performs log analysis, integrity checking, rootkit detection, time-based alerting and active response. In addition to its IDS functionality, it is commonly used as a SEM/SIM solution.

[Scapy](https://scapy.net/) is a powerful interactive packet manipulation tool, packet generator, network scanner, network discovery tool, and packet sniffer.

[Certgen](https://github.com/cilium/certgen) is a convenience tool to generate and store certificates for Hubble Relay mTLS.

[syzkaller](https://github.com/google/syzkaller) is an unsupervised, coverage-guided kernel fuzzer.

[SchedViz](https://github.com/google/schedviz) is a tool for gathering and visualizing kernel scheduling traces on Linux machines.

[oss-fuzz](https://google.github.io/oss-fuzz/) aims to make common open source software more secure and stable by combining modern fuzzing techniques with scalable, distributed execution.

[Wfuzz](https://github.com/xmendez/wfuzz) was created to facilitate the task in web applications assessments and it is based on a simple concept: it replaces any reference to the FUZZ keyword by the value of a given payload.

[Nmap](https://nmap.org/) is a security scanner used to discover hosts and services on a computer network, thus building a "map" of the network. 

[Acra](https://cossacklabs.com/acra) is a single database security suite with 9 strong security controls: application level encryption, searchable encryption, data masking, data tokenization, secure authentication, data leakage prevention, database request firewall, cryptographically signed audit logging, security events automation. It is designed to cover the most important data security requirements with SQL and NoSQL databases and distributed apps in a fast, convenient, and reliable way.

[Netdata](https://github.com/netdata/netdata) is high-fidelity infrastructure monitoring and troubleshooting, real-time monitoring Agent collects thousands of metrics from systems, hardware, containers, and applications with zero configuration. It runs permanently on all your physical/virtual servers, containers, cloud deployments, and edge/IoT devices, and is perfectly safe to install on your systems mid-incident without any preparation.

[Themis](https://cossacklabs.com/themis) is a free open-source high-level cryptographic library for mobile and backend platforms. Recommended by OWASP for application security, it allows protecting sensitive data (PII, locations, messages, etc.). While giving easy-to-use and hard-to-misuse API, Themis works to provide secure data storage, message exchange, socket connections, and authentication in apps across 15 platforms and languages.

[Trivy](https://aquasecurity.github.io/trivy/) is a comprehensive security scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues and hard-coded secrets.

[Lynis](https://cisofy.com/lynis/) is a security auditing tool for Linux, macOS, and UNIX-based systems. Assists with compliance testing (HIPAA/ISO27001/PCI DSS) and system hardening. Agentless, and installation optional. 

[RustScan](https://github.com/RustScan/RustScan) is a Modern Port Scanner.

[gosec](https://github.com/securego/gosec) is a Golang Security Checker that inspects source code for security problems by scanning the Go AST.

[Prowler](https://github.com/prowler-cloud/prowler) is an Open Source security tool to perform AWS security best practices assessments, audits, incident response, continuous monitoring, hardening and forensics readiness. It contains more than 240 controls covering CIS, PCI-DSS, ISO27001, GDPR, HIPAA, FFIEC, SOC2, AWS FTR, ENS and custom security frameworks. 

[eNgine](https://github.com/yogeshojha/rengine) is an automated reconnaissance framework for web applications with a focus on highly configurable streamlined recon process via Engines, recon data correlation and organization, continuous monitoring, backed by a database, and simple yet intuitive UI. 

[Osmedeus](https://github.com/j3ssie/osmedeus) is a Workflow Engine for Offensive Security. It was designed to build a foundation with the capability and flexibility that allows you to build your own reconnaissance system and run it on a large number of targets.

[Terrascan](https://runterrascan.io/) is a static code analyzer for Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure. 

[Sliver](https://github.com/BishopFox/sliver) is an open source cross-platform adversary emulation/red team framework, it can be used by organizations of all sizes to perform security testing. Sliver's implants support C2 over Mutual TLS (mTLS), WireGuard, HTTP(S), and DNS and are dynamically compiled with per-binary asymmetric encryption keys.

[Payloads All The Things](https://github.com/swisskyrepo/PayloadsAllTheThings) is a list of useful payloads and bypass for Web Application Security and Pentest/CTF. 

[TheHive](https://thehive-project.org/) is a scalable 3-in-1 open source and free Security Incident Response Platform designed to make life easier for SOCs, CSIRTs, CERTs and any information security practitioner dealing with security incidents that need to be investigated and acted upon swiftly. It is the perfect companion to [MISP](http://www.misp-project.org/). 

[MITRE ATT&CK®](https://attack.mitre.org/) is a global knowledge base of adversary tactics and techniques based on real-world security observations. It is used as a foundation for the development of specific threat models and methodologies in the private sector, in government, and in the cybersecurity product and service community.

[CALDERA™](https://caldera.mitre.org/) is a cyber security platform designed to easily automate adversary emulation, assist manual red-teams, and automate incident response.

[Atomic Red Team™](https://github.com/redcanaryco/atomic-red-team) is a library of tests mapped to the [MITRE ATT&CK®](https://attack.mitre.org/) framework. Security teams can use Atomic Red Team to quickly, portably, and reproducibly test their environments.

[OpenCTI](https://www.opencti.io/) is an open source platform allowing organizations to manage their cyber threat intelligence knowledge and observables. It has been created in order to structure, store, organize and visualize technical and non-technical information about cyber threats.

[Amass](https://owasp.org/www-project-amass/) is an OWASP Project that performs network mapping of attack surfaces and external asset discovery using open source information gathering and active reconnaissance techniques.

[IVRE](https://ivre.rocks/) is a network recon framework. That let's you build your own, self-hosted and fully-controlled alternatives to Shodan, ZoomEye, Censys, and GreyNoise. IVRE can run your Passive DNS service, collect and analyse network intelligence from your sensors, and much more.

[MISP](https://www.misp-project.org/) is an open source software solution for collecting, storing, distributing and sharing cyber security indicators and threats about cyber security incidents analysis and malware analysis. MISP is designed by and for incident analysts, security and ICT professionals or malware reversers to support their day-to-day operations to share structured information efficiently.

[Nikto](https://github.com/sullo/nikto) is an Open Source web server scanner which performs comprehensive tests against web servers for multiple items, including over 6400 potentially dangerous files/CGIs, checks for outdated versions of over 1200 servers, and version specific problems on over 270 servers.

[eBPF](https://ebpf.io/) is a technology that can run sandboxed programs in the Linux kernel without changing kernel source code or loading kernel modules. By making the Linux kernel programmable, infrastructure software can leverage existing layers, making them more intelligent and feature-rich without continuing to add additional layers of complexity to the system.

[Cilium](https://cilium.io/) uses eBPF to accelerate getting data in and out of L7 proxies such as Envoy, enabling efficient visibility into API protocols like HTTP, gRPC, and Kafka. 

[Hubble](https://github.com/cilium/hubble) is a Network, Service & Security Observability for Kubernetes using eBPF.

[Patchwork](https://github.com/getpatchwork/patchwork) is a web-based patch tracking system designed to facilitate the contribution and management of contributions to an open-source project. 

[pfSense](https://www.pfsense.org/) is a free and open source firewall and router that also features unified threat management, load balancing, multi WAN, and more.

[Emissary](https://github.com/NationalSecurityAgency/emissary) is a P2P based data-driven workflow engine that runs in a heterogeneous possibly widely dispersed, multi-tiered P2P network of compute resources. Workflow itineraries are not pre-planned as in conventional workflow engines, but are discovered as more information is discovered about the data.

[MADCert](https://github.com/NationalSecurityAgency/MADCert) is a cross-platform tool that consists of a certificate generator, a file system certificate manager, and a command line interface for the purposes of testing.

[Priam](https://github.com/Netflix/Priam) is a tool/process for backup/recovery, Token Management, and Centralized Configuration management for Cassandra.


## File systems

[Volver al Inicio](#tabla-de-contenidos)

[GlusterFS](https://www.gluster.org/) is a free and open source scalable network filesystem. Gluster is a scalable network filesystem. Using common off-the-shelf hardware, you can create large, distributed storage solutions for media streaming, data analysis, and other data- and bandwidth-intensive tasks.

[Ceph](https://ceph.io/) is a software-defined storage solution designed to address the object, block, and file storage needs of data centers adopting open source as the new norm for high-growth block storage, object stores and data lakes. Ceph provides enterprise scalable storage while keeping [CAPEX](https://corporatefinanceinstitute.com/resources/knowledge/modeling/how-to-calculate-capex-formula/) and [OPEX](https://www.investopedia.com/terms/o/operating_expense.asp) costs in line with underlying bulk commodity disk prices.

[Hadoop Distributed File System (HDFS)](https://www.ibm.com/analytics/hadoop/hdfs) is a distributed file system that handles large data sets running on commodity hardware. It is used to scale a single Apache Hadoop cluster to hundreds (and even thousands) of nodes. HDFS is one of the major components of Apache Hadoop, the others being [MapReduce](https://www.ibm.com/analytics/hadoop/mapreduce) and [YARN](https://hadoop.apache.org/docs/current/hadoop-yarn/hadoop-yarn-site/YARN.html).

[ZFS](https://docs.oracle.com/cd/E19253-01/819-5461/zfsover-2/) is an enterprise-ready open source file system and volume manager with unprecedented flexibility and an uncompromising commitment to data integrity.

[OpenZFS](https://openzfs.org/wiki/Main_Page ) is an open-source storage platform. It includes the functionality of both traditional file systems and volume manager. It has many advanced features including:

  - Protection against data corruption.
  - Integrity checking for both data and metadata.
  - Continuous integrity verification and automatic "self-healing" repair.

[Btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) is a modern copy on write (CoW) filesystem for Linux aimed at implementing advanced features while also focusing on fault tolerance, repair and easy administration. Its main features and benefits are:

  - Snapshots which do not make the full copy of files
  - RAID - support for software-based RAID 0, RAID 1, RAID 10
  - Self-healing - checksums for data and metadata, automatic detection of silent data corruptions
  
[MergerFS](https://github.com/trapexit/mergerfs) is a union filesystem geared towards simplifying storage and management of files across numerous commodity storage devices. It is similar to mhddfs, unionfs, and aufs.

**MergerFS Features**

  - Configurable behaviors / file placement
  - Ability to add or remove filesystems at will
  - Resistance to individual filesystem failure
  - Support for extended attributes (xattrs)
  - Support for file attributes (chattr)
  - Runtime configurable (via xattrs)
  - Works with heterogeneous filesystem types
  - Moving of file when filesystem runs out of space while writing
  - Ignore read-only filesystems when creating files
  - Turn read-only files into symlinks to underlying file
  - Hard link copy-on-write / CoW
  - Support for POSIX ACLs
  
[Bcachefs](https://bcachefs.org/) is an advanced new filesystem for Linux, with an emphasis on reliability and robustness and the complete set of features one would expect from a modern filesystem. Scalability has been tested to 50+ TB, will eventually scale far higher. 

[Squashfs](https://www.kernel.org/doc/html/latest/filesystems/squashfs.html) is a compressed read-only filesystem for Linux. It uses zlib, lz4, lzo, or xz compression to compress files, inodes and directories. Inodes in the system are very small and all blocks are packed to minimize data overhead.

#  Debian
 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439772-7225c680-6ae7-11eb-90ae-05908496c8d1.png">
  <br /> 
</p>

## Getting Started with Debian

[Debian](https://www.debian.org/) is an operating system and a distribution of Free Software. It is maintained and updated through the work of many users who volunteer their time and effort.

[Debian GitLab](https://salsa.debian.org/explore/projects)

[Install Docker Engine on Debian](https://docs.docker.com/engine/install/debian/)

[Installing Debian on WSL (Windows Subsystem for Linux)](https://wiki.debian.org/InstallingDebianOn/Microsoft/Windows/SubsystemForLinux)

[Debian for WSL GitLab](https://salsa.debian.org/debian/WSL)

[Debian Wiki](https://wiki.debian.org/NetworkConfiguration)

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.
 
<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/129622953-4b379400-9145-4d5b-9572-bcda571894f4.png">
  <br />
  Debian 11 Desktop
</h2>

# Ubuntu

 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/106686312-ef4cbb00-657e-11eb-92d5-93d7d39b4cf6.png">
  <br />
 
</p>

## Getting Started with Ubuntu

[Ubuntu](https://ubuntu.com/) is a modern open source operating system on Linux for the enterprise Server, Desktop, Cloud, and IoT developed by Canonical. Also, checkout the new [Ubuntu Desktop Installer](https://discourse.ubuntu.com/t/refreshing-the-ubuntu-desktop-installer/20659), which will be available to test in the 21.10 release (October 2021).

[Ubuntu Flavours](https://www.ubuntu.com/download/flavours) is for those that prefer an alternative desktop environment such as [KDE Plasma Desktop](https://kubuntu.org/), [MATE](https://ubuntu-mate.org/), [Xfce](https://xubuntu.org/), [LXQt](https://lubuntu.me/), [Budgie](https://ubuntubudgie.org/), and [UKUI](https://www.ubuntukylin.com/) you can download a Flavour for your preferred desktop environment and use that to install Ubuntu, pre-configured for the desktop environment of your choice.
 
<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/164793005-67371e3c-d74d-4b40-9fd1-b9a71bd4172a.png">
  <br />
  Ubuntu Desktop
</h3>

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350348-e43ea5a2-2346-4b0b-acc0-fc3352c3d820.png">
  <br />
  Etcher UI
</h2>

## Additional Ubuntu Tools & Resources for Enterprise & Small Businesses

[Ubuntu Community Hub](https://discourse.ubuntu.com/)

[Ubuntu Tutorials](https://ubuntu.com/tutorials)

[FreeRDP](https://github.com/FreeRDP/FreeRDP) is a free remote desktop protocol library and clients.

[apt-get](https://github.com/wimpysworld/deb-get) is a tool that provides functionality for .debs published in 3rd party repositories or via direct download. It works on Ubuntu and derivative distributions. 

[ZFS](https://docs.oracle.com/cd/E19253-01/819-5461/zfsover-2/) is an enterprise-ready open source file system and volume manager with unprecedented flexibility and an uncompromising commitment to data integrity.

[OpenZFS](https://openzfs.org/wiki/Main_Page ) is an open-source storage platform. It includes the functionality of both traditional file systems and volume manager. It has many advanced features including:

  - Protection against data corruption.
  - Integrity checking for both data and metadata.
  - Continuous integrity verification and automatic "self-healing" repair.

[Multipass](https://multipass.run/) is a command line interface to launch, manage and generally test with instances of Linux(Ubuntu) in  a VM. It works on Linux, Windows and macOS.

[LXD](https://linuxcontainers.org/lxd/) is a next generation system container manager. It offers a user experience similar to virtual machines but using Linux containers instead. It's image based with pre-made images available for a wide number of Linux distributions and is built around a very powerful, yet pretty simple, REST API.

[MAAS](https://maas.io/) is an open source SDDC solution used by telcos, financial institutions, media companies and supercomputer admins to take care of all the low-level details. PXE, IPMI, ILO and all the custom protocols needed for diverse vendor hardware support come together in one clean REST API with Python bindings for easy integration and automation.

[JuJu](https://juju.is/) is an open source application modeling tool for public and private clouds. It forms part of Ubuntu's cloud portfolio, together with Ubuntu Server, Ubuntu OpenStack, MAAS for bare-metal provisioning, and Landscape for systems management and monitoring.

[JAAS (Juju as a Service)](https://jaas.ai/)  is a service that makes it easy to deploy [OpenStack](https://www.openstack.org/) at scale. Where you quickly and reliably build an enterprise-scale cloud running on Ubuntu.

[Ubuntu OpenStack](https://ubuntu.com/openstack)is the #1 platform for [OpenStack](https://www.openstack.org/) and the #1 platform for public cloud operations on [AWS](https://aws.amazon.com/), [Microsoft Azure](https://azure.microsoft.com/) and [Google Cloud](https://cloud.google.com/).

[Ubuntu is the reference platform for Kubernetes](https://ubuntu.com/kubernetes) on all major public clouds, including official support in Google's GKE, Microsoft's AKS and Amazon's EKS CAAS offerings. 

[Ubuntu on WSL](https://wiki.ubuntu.com/WSL) is a wiki guide on getting started with the latest version of Ubuntu installed and setup on WSL for Windows 10.

[Ubuntu Pro for Azure](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/canonical.0001-com-ubuntu-pro-focal?tab=Overview) is a premium image designed by Canonical optimized for production environments running on Azure. It includes security and compliance services, enabled by default, in a form suitable for small to large-scale Linux enterprise operations with no contract needed. 

[Ubuntu on AWS](https://ubuntu.com/aws)

[Ubuntu on Azure](https://ubuntu.com/azure)

[Active Directory Integration on Ubuntu](https://github.com/VanitasuShieda/Perfect-Ubuntu-Guide/files/6064814/Active_Directory_Integration_Ubuntu_Desktop_Final.pdf)

## Removing Snap and adding Flatpak support

[Unsnap](https://github.com/popey/unsnap) is a tool to quickly migrate from using snap packages to flatpaks.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/167506753-17c62a29-ce7e-4556-a90f-9996aa73a92e.png">
  <br />
</p>

Unsnap running in the terminal. Credit: [Alan Pope](https://github.com/popey/)

## Setting up PipeWire for Ubuntu/Debian

**Note:** For those using Pop!_OS 22.04 or later PipeWire is already setup by default.

**Add PipeWire PPA**

```$ sudo add-apt-repository ppa:pipewire-debian/pipewire-upstream```

**Install the pipewire-audio-client-libraries and additional libraries to use Bluetooth, GStreamer, or JACK devices with your Ubuntu/Debian system.**
 
 ```$ sudo apt update```
  ```  $ sudo apt install pipewire pipewire-audio-client-libraries gstreamer1.0-pipewire libpipewire-0.3-{0,dev,modules} libspa-0.2-{bluetooth,dev,jack,modules} pipewire{,-{audio-client-libraries,pulse,media-session,bin,locales,tests}}```

**After installation has completed, run the following command to reload the daemon in systemd.**

```$ systemctl --user daemon-reload```

**Disable PulseAudio in Ubuntu. It will no longer be needed, since we are using PipeWire.**

```$ systemctl --user --now disable pulseaudio.service pulseaudio.socket```

**PulseAudio is disabled, we can start PipeWire and enable it to run automatically upon system boot.**

```$ systemctl --user --now enable pipewire pipewire-pulse```

**Run the following command to ensure that PipeWire is running.**

```$ pactl info```

### Reverting Changes

```$ sudo apt remove pipewire pipewire-audio-client-libraries gstreamer1.0-pipewire libpipewire-0.3-{0,dev,modules} libspa-0.2-{bluetooth,dev,jack,modules} pipewire{,-{audio-client-libraries,pulse,media-session,bin,locales,tests}}```

**Reload the daemon in systemd.**

```$ systemctl --user daemon-reload```

**Re-enables the PulseAudio service after you do a system reboot.**

```$ systemctl --user --now enable pulseaudio.service pulseaudio.socket```

**Ensure that PulseAudio has been completely restored.**
 
```$ pactl info```

# Pop!_OS

 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107091607-eb0ae280-67b6-11eb-91af-c052daa76876.png">
  <br />
  
</p>

## Getting Started with Pop!_OS

[Pop!_OS](https://pop.system76.com/) is an operating system(based on [Ubuntu](https://ubuntu.com/)) for STEM and creative professionals who use their computer as a tool to discover and create developed by [System76](https://system76.com/).

[Pop!_OS COSMIC (Computer Operating System Main Interface Components)](https://blog.system76.com/post/655369428109869056/popos-2104-a-release-of-cosmic-proportions) is a custom desktop environment developed by [System76](https://system76.com/). This makes navigating your desktop workflow via your mouse, keyboard, and/or trackpad much simpler and more efficient. 

[PipeWire](https://pipewire.org) is a server and user space API to deal with multimedia pipelines. It provides a low-latency, graph based processing engine on top of audio and video devices that can be used to support the use cases currently handled by both pulseaudio and JACK. PipeWire was designed with a powerful security model that makes interacting with audio and video devices from containerized applications easy. Nodes in the graph can be implemented as separate processes, communicating with sockets and exchanging multimedia content using fd passing.

- [Differences between Pop!_OS and Ubuntu](https://support.system76.com/articles/difference-between-pop-ubuntu/)

- [System76 Support (Ask a question/submit a ticket)](https://support.system76.com/)

- [System76 Laptops](https://system76.com/laptops)

- [System76 Desktops](https://system76.com/desktops)

- [HP Dev One laptop with Pop!_OS](https://hpdevone.com/)

- [Pop!_OS GitHub](https://github.com/pop-os)

- [Pop!_OS reddit](https://www.reddit.com/r/pop_os/)

[Popsicle](https://github.com/pop-os/popsicle) is a Linux utility for flashing multiple USB devices in parallel, written in Rust.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/172025606-a1b6638d-34b0-44a0-ae3f-97cd70446521.png">
  <br />
  Popsicle UI
</p>

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350348-e43ea5a2-2346-4b0b-acc0-fc3352c3d820.png">
  <br />
  Etcher UI
</p>
 
<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/142935333-7cc708ee-cadf-4700-bfa4-fecdd29baaa4.png">
  <br />
  Pop!_OS Desktop
</h1>

## Pop Shop

<img src="https://user-images.githubusercontent.com/45159366/107091582-e21a1100-67b6-11eb-9043-1385d2d8afd9.png">

# Linux Mint

[Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107585812-b8485c00-6bb3-11eb-9007-c99eb2c8aa8e.png">
  <br />
 
</p>

### Getting Started with Linux Mint
[Back to the Top](https://github.com/VanitasuShieda/Linux-Mint-Guide#table-of-contents)

[Linux Mint](https://linuxmint.com/) is a modern, elegant, and comfortable open source operating system(based on Debian and Ubuntu), which is both powerful and easy to use for both new and advanced users. The flagsip version of Linux Mint uses the [Cinnamon desktop environment](https://cinnamon-spices.linuxmint.com/) similiar to Windows 7.

<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350295-4c6b8ab5-17d2-4e2f-91ca-a111bcdb2a34.png">
  <br />
  Linux Mint Desktop 
</h2>

[Linux Mint MATE](https://linuxmint.com/edition.php?id=285) uses the [MATE Desktop environment](https://mate-desktop.org/).

<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350307-4683a0f4-2731-45c0-bda5-d50bac1c7153.png">
  <br />
  Linux Mint Desktop with MATE
</h2>

[Linux Mint Xfce](https://linuxmint.com/edition.php?id=286) uses the [Xfce Desktop environment](https://xfce.org/).

<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350301-1bba5a9f-f404-40c1-b4fe-66f67a0b4268.png">
  <br />
  Linux Mint Desktop with Xfce
</h2>

[Linux Mint Debian Edition (LMDE)](https://www.linuxmint.com/download_lmde.php) uses [Debian Bullseye](https://www.debian.org/) as the base for a very stable and rock solid user experience with the Cinnamon desktop.

<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350295-4c6b8ab5-17d2-4e2f-91ca-a111bcdb2a34.png">
  <br />
  Linux Mint Debian Edition (LMDE)
</h2>

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

<h2 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157350348-e43ea5a2-2346-4b0b-acc0-fc3352c3d820.png">
  <br />
  Etcher UI
</h2>

### Installing KDE Plasma on Linux Mint

```sh
sudo apt install kde-plasma-desktop
```
OR

```sh
sudo apt install kde-standard
```
<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157352628-34ee2dfc-dc4b-489e-a70e-4f58b0fa1f79.png">
  <br />
  KDE Plasma Desktop on Linux Mint
</h1>

### Enable Firewall

```sh
sudo systemctl enable ufw
sudo systemctl start ufw
```
### Getting Software


#### Linux Mint Software Center

<img src="https://user-images.githubusercontent.com/45159366/157350978-ecce979a-7a59-43e2-a014-4ff8bd02d1b2.png">

**Note 1: All this software is also available in other popular Linux distributions such as [Debian](https://www.debian.org/), [elementary OS](https://elementary.io/), [Pop!_OS](https://pop.system76.com/), [Fedora](https://getfedora.org), [Manjaro Linux](https://manjaro.org/), [EndeavourOS](https://endeavouros.com/) and [Arch Linux](https://archlinux.org/).**

**Note 2: For new users not comfortable with using the command-line checkout the Essential Apps section to get started. Also, if you scroll down further you'll see other easy ways to get software applications through Flathub, Snap Store, and AppImages.**


# Fedora/CentOS Stream/RHEL

 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145488517-79284af2-ec1d-40a5-a7b8-ddb2cb343da2.png">
  <br />
</p>

## Getting Started with FedoraCentOS Stream/RHEL

[Fedora](https://getfedora.org/) is a polished, easy to use operating system for laptop & desktop computers, with a complete set of tools for developers and makers of all kinds. The Fedora OS base is used to build/develop new versions of [Red Hat® Enterprise Linux® (RHEL)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux) the world's leading enterprise Linux platform. The OS serves as the foundation for which you can scale existing apps and roll out emerging technologies across bare-metal, virtual, container, and all types of cloud environments.

[Fedora Server](https://getfedora.org/) is a powerful, flexible operating system that includes the best and latest datacenter technologies. It puts you in control of all your infrastructure and services.

[Fedora ARM](https://arm.fedoraproject.org/) is an initiative to bring versions of Fedora tailored for running on ARM-based systems.

[Fedora Silverblue](https://silverblue.fedoraproject.org/) is a variant of the Fedora Workstation that uses rpm-ostree to provide an immutable OS image with reliable updates and easy rollbacks.

[Fedora Kinoite](https://kinoite.fedoraproject.org/) is an immutable desktop operating system. It aims to be extremely stable and reliable. It also aims to be an excellent platform for developers and for those using container-focused workflows. Kinoite is a variant of the Fedora KDE Spin.

[Fedora CoreOS](https://getfedora.org/coreos?stream=stable) is an automatically-updating, minimal operating system for running containerized workloads securely and at scale.

[Fedora Spins](https://spins.fedoraproject.org/) is for those that prefer an alternative desktop environment such as KDE Plasma Desktop, MATE; or Xfce, you can download a spin for your preferred desktop environment and use that to install Fedora, pre-configured for the desktop environment of your choice.

[CentOS Stream](https://www.centos.org/centos-stream/) is a continuously delivered distro(uses the Fedora OS base) that tracks just ahead of Red Hat Enterprise Linux (RHEL) development, positioned as a midstream between Fedora Linux and RHEL.

[Red Hat Enterprise Linux CoreOS](https://ostreedev.github.io/ostree/#operating-systems-and-distributions-using-ostree) is a derivative of Fedora CoreOS, used in [OpenShift 4](https://try.openshift.com/). The [machine-config-operator](https://github.com/openshift/machine-config-operator/blob/master/docs/OSUpgrades.md) manages upgrades. RHEL CoreOS is also the successor to RHEL Atomic Host, which uses rpm-ostree as well.

[EPEL (Extra Packages for Enterprise Linux)](https://docs.fedoraproject.org/en-US/epel/) is an free and open source community-based repository project from the Fedora team which provides 100% high-quality add-on software packages for Linux distribution including RHEL (Red Hat Enterprise Linux) and CentOS Stream.

[DNF(Dandified Packaging Tool)](https://docs.fedoraproject.org/en-US/quick-docs/dnf/) is a software package manager that installs, updates, and removes packages on Fedora and is the successor to YUM (Yellow-Dog Updater Modified). DNF makes it easy to maintain packages by automatically checking for dependencies and determines the actions required to install packages.

[Micro DNF](https://fedoraproject.org/wiki/Changes/MajorUpgradeOfMicrodnf) is a lightweight C implementation of DNF, designed to be used for doing simple packaging actions when you don't need full-blown DNF and you want the tiniest useful environments possible. Checkout the [Micro DNF GitHub](https://github.com/rpm-software-management/microdnf).

[Fedora Updates System](https://bodhi.fedoraproject.org/) is a place to create, test, and publish package updates for Fedora.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/168177134-85efb869-c2d5-4d7a-9a53-a3f61a2d74e2.png">
<br />
</p>

[BuildStream](https://gitlab.com/BuildStream/buildstream) is a flexible and extensible framework for the modelling of build pipelines in a declarative YAML format, written in python.

[CoreOS Assembler (COSA)](https://github.com/coreos/coreos-assembler) is a collection of various tools used to build Fedora CoreOS style systems, including RHEL CoreOS. The goal is that everything needed to build and test the OS comes encapsulated in one (admittedly large) container.

[OSTree](https://ostreedev.github.io/ostree/) is an upgrade system for Linux-based operating systems that performs atomic upgrades of complete filesystem trees. It is not a package system; rather, it is intended to complement them. Checkout the [OSTree GitHub](https://github.com/ostreedev/ostree). 

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/167503492-1d768b22-4044-4093-a8ee-61a5df9613b8.png">
<br />
OSTree
</p>

[rpm-ostree](https://coreos.github.io/rpm-ostree/) is a hybrid image/package system. It combines [libostree](https://ostreedev.github.io/ostree/) as a base image format, and accepts RPM on both the client and server side, sharing code with the [dnf](https://en.wikipedia.org/wiki/DNF_(software)) project; specifically [libdnf](https://github.com/rpm-software-management/libdnf). Thus bringing many of the benefits of both projects together.

[Pulp](https://pulpproject.org/) is a software repository platform for Fetching, Uploading, Organizing, and Distributing Software Packages.

<p align="center">
<img src="https://user-images.githubusercontent.com/45159366/167503480-792b4842-1371-4c4e-b8ea-5e135292663c.png">
<br />
Pulp Platform
</p>

[Pulp OSTree Plugin](https://github.com/pulp/pulp_ostree) is a Pulp plugin to support hosting your own OSTree content.

[RPM Package Manager (RPM)](https://rpm.org/) is a powerful package management system capable of building computer software from source into easily distributable packages installing, updating and uninstalling packaged software querying detailed information about the packaged software, whether installed or not.

[RPM Fusion](https://rpmfusion.org) is a software repository provides software that the Fedora Project or Red Hat doesn't want to ship. That software is provided as precompiled RPMs for all current Fedora versions and current Red Hat Enterprise Linux or clones versions; you can use the RPM Fusion repositories with tools like yum and PackageKit.

[PipeWire](https://pipewire.org) is a server and user space API to deal with multimedia pipelines.It provides a low-latency, graph based processing engine on top of audio and video devices that can be used to support the use cases currently handled by both pulseaudio and JACK. PipeWire was designed with a powerful security model that makes interacting with audio and video devices from containerized applications easy. Nodes in the graph can be implemented as separate processes, communicating with sockets and exchanging multimedia content using fd passing.

[WirePlumber](https://pipewire.pages.freedesktop.org/wireplumber/) is a modular session / policy manager for [PipeWire](https://pipewire.org/) and a GObject-based high-level library that wraps PipeWire’s API, providing convenience for writing the daemon’s modules as well as external tools for managing PipeWire. The WirePlumber daemon implements the session & policy management service. It follows a modular design, having plugins that implement the actual management functionality.

[Btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) is a modern copy on write (CoW) filesystem for Linux aimed at implementing advanced features while also focusing on fault tolerance, repair and easy administration. Its main features and benefits are:

  - Snapshots which do not make the full copy of files.
  - RAID - support for software-based RAID 0, RAID 1, RAID 10.
  - Self-healing - checksums for data and metadata, automatic detection of silent data corruptions.

[Anaconda](http://fedoraproject.org/wiki/Anaconda) is an OS installer used by Fedora, Red Hat Enterprise Linux (RHEL), CentOS Stream and other Linux distributions.

[Fedora Labs](https://labs.fedoraproject.org/) is a selection of curated bundles of purpose-driven software and content as curated and maintained by members of the Fedora Community. These may be installed as standalone full versions of Fedora or as add-ons to existing Fedora installations. 

[Fedora Special Interest Groups (SIGs)](https://fedoraproject.org/wiki/Category:SIGs?rd=SIGs) are teams within the Fedora Project that are less formal than official subprojects. The SIGs are sometimes a first stage in the development of new projects within the Fedora Project.  

[Fedora Media Writer](https://fedoramagazine.org/make-fedora-usb-stick/) is a tool in Fedora that will set up your flash drive to run a "Live" version of Fedora Workstation, meaning that you can boot it from your flash drive and try it out right away without making any permanent changes to your computer.

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

[Using Fedora with Microsoft’s WSL2](https://fedoramagazine.org/wsl-fedora-33/)

[Fedora Project Wiki](http://fedoraproject.org/wiki/Fedora_Project_Wiki)

[Fedora Developer Portal](https://developer.fedoraproject.org/start.html)

[Fedora Project Forum](https://discussion.fedoraproject.org/)

 <h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/233298608-216b9cea-a15f-4fc1-afe7-8b37c93ebdf1.png">
  <br />
  Fedora Linux Desktop
</h1>

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145488524-ebfd666a-bf90-43d8-bc41-8c363e4e233a.png">
  <br />
 CentOS Stream Desktop
</h1>

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110252965-b9fc0a00-7f3c-11eb-969c-ea210badfd50.png">
  <br />
Red Hat Enterprise Linux Desktop
</h1>
 
 ## Fedora, Red Hat Enterprise Linux (RHEL) and CentOS Stream Development Cycle
 
 <img src="https://user-images.githubusercontent.com/45159366/107158836-7ca65b80-6941-11eb-95dd-5166023597a7.png">
 
# SUSE/openSUSE
 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439812-836ed300-6ae7-11eb-9c6c-2f8b2cbaab86.png">
  <br />
</p>

### Getting Started with SUSE/openSUSE

[SUSE](https://www.suse.com/) is a leading Linux OS most adaptable Linux operating system and the only open Kubernetes management platform thanks to their acquistion of [Rancher](https://rancher.com/). They also developer of [SUSE Linux Enterprise](https://www.suse.com/download/) and the primary sponsor of the community-supported [openSUSE Project](https://software.opensuse.org/), which develops the openSUSE Linux distribution.

[openSUSE Leap](https://en.opensuse.org/Portal:Leap) is a brand new way of building openSUSE and is new type of a hybrid Linux distribution. Leap uses source from SUSE Linux Enterprise (SLE), which gives Leap a level of stability unmatched by other Linux distributions, and combines that with community developments to give users, developers and sysadmins the best stable Linux experience available. 

[openSUSE Tumbleweed](https://en.opensuse.org/Portal:Tumbleweed) is a pure rolling release version of openSUSE containing the latest "stable" versions of all software instead of relying on rigid periodic release cycles. The project does this for users that want the newest stable software. 

[openSUSE Kubic](https://get.opensuse.org/kubic/) is a multi-purpose Standalone & Kubernetes Container Operating System based on openSUSE MicroOS. Kubic uses kubeadm to provide an easy way of configuring a Kubernetes cluster across multiple machines, while our MicroOS base keeps your operating system updated automatically, with fully atomic rollbacks if required.

[openSUSE MicroOS](https://get.opensuse.org/microos/) is a M icro Service OS providing Transactional (Atomic) Updates upon a read-only btrfs root filesystem. It's designed to host container workloads with automated administration & patching.

[openSUSE Build Service](https://build.opensuse.org/) is the public instance of the Open Build Service (OBS) used for development of the openSUSE distribution and to offer packages from same source for Fedora, Debian, Ubuntu, SUSE Linux Enterprise and other distributions.

[YaST](https://yast.opensuse.org/) is a installation and configuration tool for openSUSE and the SUSE Linux Enterprise distributions. It features an easy-to-use interface and powerful configuration capabilities.

[Zypper](https://software.opensuse.org/package/zypper) is a command line package manager which makes use of libzypp. It provides functions like repository access, dependency solving, package installation, etc. Zypper repositories are similar to the ones used in YaST, which also makes use of libzypp.

[Btrfs](https://btrfs.wiki.kernel.org/index.php/Main_Page) is a modern copy on write (CoW) filesystem for Linux aimed at implementing advanced features while also focusing on fault tolerance, repair and easy administration. Its main features and benefits are:

  - Snapshots which do not make the full copy of files.
  - RAID - support for software-based RAID 0, RAID 1, RAID 10.
  - Self-healing - checksums for data and metadata, automatic detection of silent data corruptions.

[KIWI Next Generation (KIWI NG)](https://osinside.github.io/kiwi/) is a command line utility to build Linux system appliances.

[openSUSE for WSL (Windows Subsystem for Linux)](https://en.opensuse.org/openSUSE:WSL)

[SUSE Linux Enterprise Server for WSL (Windows Subsystem for Linux)](https://www.microsoft.com/en-us/p/suse-linux-enterprise-server-15-sp1/9pn498vpmf3z?activetab=pivot:overviewtab)

[Rancher](https://rancher.com) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads. They were [acquired by SUSE in July 2020](https://rancher.com/blog/2020/suse-to-acquire-rancher/).

[openSUSE Wiki](https://en.opensuse.org/Main_Page)  is the source of information about the openSUSE project and distribution. The goal is to provide high quality documentation and a place for collaboration on all parts of the project.

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.


 <h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110253144-9f766080-7f3d-11eb-9a01-2ac6738637e9.png">
  <br />
  SUSE Linux Enterprise 12 Desktop
</h1>

<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/110253145-a00ef700-7f3d-11eb-9b5c-d3cee3cbce84.png">
  <br />
  openSUSE Deskop
</h1>
 
 
# Arch Linux
 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439842-91bcef00-6ae7-11eb-9e8b-bafe48a25bd7.png">
  <br />
</p>

## Getting Started Arch Linux

[Arch Linux](https://archlinux.org/) is an independently developed, x86-64 general purpose GNU/Linux distribution versatile enough to suit any role. Development focuses on simplicity, minimalism, and code elegance. Arch is installed as a minimal base system, configured by the user upon which their own ideal environment is assembled by installing only what is required or desired for their unique purposes.

[ArchWiki](https://wiki.archlinux.org) is the best source for Arch Linux documentation on the web.

[Arch Linux on WSL(Windows Subsystem for Linux)](https://github.com/yuk7/ArchWSL)

[Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

### Arch Linux User Repository (AUR)

[Arch Linux User Repository (AUR)](https://aur.archlinux.org/) contains thousands build scripts, for compiling nearly 68,000 installable packages from source using the Arch Linux makepkg application.

### Good Arch Linux Desktops for everyday use.

**[Manjaro Linux](https://manjaro.org/)**


 <h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/145650520-6f0233c8-3f0f-434c-a85d-e713fb7624e9.png">
  <br />
  Manjaro Linux Desktop
</h3>

**[EndeavourOS](https://endeavouros.com/)**

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/107439882-9e414780-6ae7-11eb-819e-e87e7bcc7a97.png">
  <br />
  EndeavourOS Desktop
</h3>

**[Gauruda Linux](https://garudalinux.org/)**

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/127042105-f6a6d97e-77bd-402e-af4f-df7af588eb08.png">
  <br />
 Gauruda Linux Desktop
</h3>

**[ArcoLinux](https://arcolinux.com/)**

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128940632-9e2a198f-f84d-490b-b4a2-22f6217ee574.png">
  <br />
ArcoLinux Desktop
</h3>

[Steam OS 3.0](https://store.steampowered.com/steamdeck) is an [immutable](https://en.wikipedia.org/wiki/Immutable_object) Operating System(OS) using the [KDE Plasma](https://kde.org/plasma-desktop) desktop. This allows you to install applications in containers using [Flatpak](https://flatpak.org/), rather than onto the root filesystem. This means not only that the installation of applications is isolated from the core filesystem, but also that the ability for malicious applications to compromise/break your system is significantly reduced.

<h3 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/157353163-6f5c4c1a-a89f-4ee5-9ffe-1d9f991c773c.png">
  <br />
  SteamOS 3.0 with KDE Plasma Deskop
</h3>

# NixOS
 [Volver al Inicio](#tabla-de-contenidos)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128645103-795eebbd-f853-47cc-8087-916dfd98347b.png">
  <br />
</p>


## Getting Started NixOS

[NixOS](https://nixos.org/) is a Linux distribution built on top of the [Nix package manager](https://nixos.wiki/wiki/Nix). It has tools dedicated to DevOps and deployment tasks.

[Nix Tour](https://nixcloud.io/tour/) is an interactive tour that uses the actual package manager to learn you the language by example, in the browser.

[Nix](https://nixos.wiki/wiki/Nix) is a package manager and build system that parses reproducible build instructions specified in the [Nix Expression Language](https://nixos.wiki/wiki/Nix_Expression_Language), is a pure functional language with lazy evaluation. Nix expressions are pure functions taking dependencies as arguments and producing derivation specifying a reproducible build environment for the package. Nix stores the results of the build in unique addresses specified by a hash of the complete dependency tree, creating an immutable package store that allows for atomic upgrades, rollbacks and concurrent installation of different versions of a package, essentially eliminating [dependency hell](https://en.wikipedia.org/wiki/Dependency_hell).

[Nix Expression Language](https://nixos.wiki/wiki/Nix_Expression_Language) is a pure, lazy, functional language. Purity means that operations in the language don't have side-effects (for instance, there is no variable assignment). The language is not a full-featured, general purpose language. Its main job is to describe packages, compositions of packages, and the variability within packages.

[Nixpkgs](https://nixos.wiki/wiki/Nixpkgs) is the largest repository of [Nix](https://nixos.wiki/wiki/Nix) packages(over 80,000 packages) and [NixOS](https://nixos.wiki/wiki/NixOS) modules. The repository is [hosted on GitHub](https://github.com/nixos/nixpkgs) and maintained by the community, with official backing from the [NixOS Foundation](https://nixos.org/). Additionally, checkout [Language-specific package helpers](https://nixos.wiki/wiki/Language-specific_package_helpers) and [Alternative Package Sets](https://nixos.wiki/wiki/Alternative_Package_Sets).

[NixOS Packages Search](https://search.nixos.org/packages) is a tool for searching through NixOS packages.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/173939766-8972583c-855e-4a9b-b9f1-761b60ea255e.png">
  <br />
  NixOS Packages Search
</p>

## NixOS Developer Resources
[Back to the Top](https://github.com/VanitasuShieda/NixOS-Guide#table-of-contents)

 - [NixOS Wiki](https://nixos.wiki/)

 - [NixOS Pills - Developer Guides](https://nixos.org/guides/nix-pills/)
 
 - [NixOS Learn](https://nixos.org/learn.html)

 - [Nix Package Manager Manual](https://nixos.org/manual/nix/stable/#chap-installation)

 - [Home Manager - NixOS Wiki](https://nixos.wiki/wiki/Home_Manager)
 
 - [What Is Nix — Developer Tooling | Shopify Engineering](https://shopify.engineering/what-is-nix)

 - [Cheatsheet - NixOS Wiki](https://nixos.wiki/index.php?title=Cheatsheet&useskin=vector)
 
 - [nix.dev guide for developers](https://nix.dev/)
 
 - [Hound - search across all/selected Nix-related repositories.](https://search.nix.gsc.io) 
 
 - [Nix(A One Pager) - A one page introduction to Nix, the language](https://github.com/tazjin/nix-1p) 
 
 - [Nix Shorts](https://github.com/justinwoo/nix-shorts/)

 - [Getting started with Home Manager for Nix](https://ghedam.at/24353/tutorial-getting-started-with-home-manager-for-nix)

 - [NixOS Wiki - Raspberry Pi 4](https://nixos.wiki/wiki/NixOS_on_ARM/Raspberry_Pi_4)

 - [NixOS aarm64 SD image](https://hydra.nixos.org/job/nixos/trunk-combined/nixos.sd_image.aarch64-linux)

 - [nixery.dev](https://nixery.dev/)
 
 - [NixOS Discourse Forum](https://discourse.nixos.org/)
 
 - [NixCon- annual community conference](https://nixcon.org/)

 - [NixOS Community](https://nixos.org/community.html)

 - [NixOS Governance](https://nixos.org/governance.html)

 - [Consider Donating to the NixoS Project](https://nixos.org/donate.html)

## NixOS Tools and Modules
[Back to the Top](https://github.com/VanitasuShieda/NixOS-Guide#table-of-contents)

 - [Hydra](https://github.com/nixos/hydra) is Nix's official continuous integration and build system.

 - [Kubenix](https://github.com/xtruder/kubenix) is a Kubernetes resource builder written in Nix.

 - [Nix-kubernetes](https://github.com/xtruder/nix-kubernetes) is a Kubernetes deployment manager written in nix.

 - [Disnix](https://github.com/svanderburg/disnix) is a microservice architecture built with Nix.

 - [Hail](https://github.com/TaktInc/hail) is a service for pull-based continuous deployment.

 - [Morph](https://github.com/DBCDK/morph) is a NixOS deployment tool.

 - [Nixery](https://nixery.dev/) is a ad-hoc container images from Nix.

 - [Home Manager](https://github.com/nix-community/home-manager) is a tool to manage your user configuration just like NixOS.s.

 - [NixVim](https://github.com/pta2002/nixvim) is a NeoVim distribution built with Nix modules and Nixpkgs.

 - [Simple Nixos Mailserver](https://gitlab.com/simple-nixos-mailserver/nixos-mailserver) is a complete mailserver, managed with NixOS modules.

 - [Stylix](https://github.com/danth/stylix) is a system-wide colorscheming and typography for NixOS.

 - [Awesome-Nix-HPC](https://github.com/freuk/awesome-nix-hpc) is a High Performance Computing package sets.

 - [Nix-darwin](https://github.com/LnL7/nix-darwin) is a tool to manage macOS configuration just like on NixOS.

 - [Nixpkgs-firefox-darwin](https://github.com/bandithedoge/nixpkgs-firefox-darwin) is a nikpkg to automatically updated Firefox binary packages for macOS.

 - [Nixpkgs-wayland](https://github.com/nix-community/nixpkgs-wayland) is a bleeding-edge Wayland packages.

 - [NUR(Nix User Repositories)](https://github.com/nix-community/NUR/) is the mother of all overlays, allowing access to user repositories and installing packages via attributes.

 - [Alejandra](https://github.com/kamadorueda/alejandra) is a opinionated Nix code formatter optimized for speed and consistency.

 - [Comma](https://github.com/Shopify/comma) is a tool that quickly runs any binary; wraps together `nix run` and `nix-index`

 - [Colmena](https://github.com/zhaofengli/colmena) is a simple, stateless NixOS deployment tool modeled after NixOps and morph.

 - [Krops](https://cgit.krebsco.de/krops/about/) is a lightweight toolkit to deploy NixOS systems, remotely or locally.

 - [KuberNix](https://github.com/saschagrunert/kubernix) is a single-dependency Kubernetes clusters via Nix packages.

 - [Terraform-nixos](https://github.com/tweag/terraform-nixos) is a set of Terraform modules designed to deploy NixOS.

 - [Terranix](https://terranix.org) is a tool to use Nix and the NixOS module system to write your Terraform code.

 - [Arion](https://github.com/hercules-ci/arion#readme) is a configure Docker Compose with Nix modules.

 - [Deploy-rs](https://github.com/serokell/deploy-rs) is a simple multi-profile Nix-flake deploy tool.

 - [Fractalide](https://github.com/fractalide/fractalide) is a reusable Reproducible Composable Software.

 - [Nixos-shell](https://github.com/Mic92/nixos-shell) is a simple headless VM configuration using Nix (similar to Vagrant).

 - [Pushnix](https://github.com/arnarg/pushnix) is a simple cli utility that pushes NixOS configuration and triggers a rebuild using ssh.

 - [Musnix](https://github.com/musnix/musnix) is a real-time audio modules for NixOS.

 - [Nix-bundle](https://github.com/matthewbauer/nix-bundle) is a package Nix attributes into single-file executables.

 - [Extra-container](https://github.com/erikarvstedt/extra-container) is a run declarative NixOS containers from the command line. Similar to nixos-shell (chrisfarms).

 - [Nixcloud-webservices](https://github.com/nixcloud/nixcloud-webservices) is a set of nixpkgs extension for web-related technologies.

 - [Krops](https://cgit.krebsco.de/krops/about/) is a stateless alternative to nixops with improved secret management.

 - [Mach-nix](https://github.com/DavHau/mach-nix) is a tool that makes it easy to create and share reproducible python environments or packages. Existing tools for python package management often suffer from reproducibility and complexity issues, requiring a multitude of tools and additional virtualization layers to work sufficiently. 
 
  - [Digga](https://github.com/divnix/digga) is a flake utility library that helps you declaratively craft and manage all three layers of your system environment within a single nix flakes repository:

    * Development shells (via numtide/devshell).
    * Home environments (via nix-community/home-manager).
    * Host configurations (via NixOS/nixpkgs/nixos).

 - [Impermanence](https://github.com/nix-community/impermanence) is a set of modules to help you handle persistent state on systems with ephemeral root storage.
 
 - [NixOS Vagrant Plugin](https://github.com/nix-community/vagrant-nixos-plugin) is a plugin that adds nix provisioning for [NixOS](https://nixos.org/) guests to [Vagrant](https://www.vagrantup.com/).
 
 - [Fenix](https://github.com/nix-community/fenix) is a Rust toolchains and Rust analyzer nightly for nix.

 - [NixOS-WSL](https://github.com/nix-community/NixOS-WSL) is a minimal root filesystem for running NixOS on WSL. It can be used with DistroLauncher as ```install.tar.gz``` or as input to ```wsl --import --version 2```.

 - [Nix-bitcoin](https://github.com/nixbitcoin/nix-bitcoin/) is a set of NixOS modules to install a bitcoin node with emphasis on security.

 - [Nixpkgs-review](https://github.com/Mic92/nixpkgs-review) is a review nixpkgs pull requests.

 - [Nix-update](https://github.com/Mic92/nix-update) is a swiss army knife for updating nix packages.

 - [Nox](https://github.com/madjar/nox) is a set of tools to make Nix easier to use.

 - [Nix-diff](https://github.com/Gabriel439/nix-diff) is a tool to compare Nix derivations.

 - [Niff](https://github.com/FRidh/niff) is a tool to compare two Nix expressions to determine what attributes changes.

 - [Nix-upgrade-scripts](https://github.com/peterhoeg/nix-upgrade-scripts)  is a set of tools for Nixpkgs maintainers to upgrade packages.

 - [Nixops-manager](https://github.com/grafted-in/nixops-manager) is a NixOps wrapper for Git repositories.

 - [Narfuse](https://github.com/taktoa/narfuse) is a FUSE filesystem for mounting Nix archive (NAR) files as a virtual Nix store.

 - [Nix-visualize](https://github.com/craigmbooth/nix-visualize) is a tool to visualize the dependencies of a given package.

 - [Home-manager](https://github.com/rycee/home-manager) is a system for managing a user environment using Nix.

 - [NixGl](https://github.com/guibou/nixGL) is a wrapper to run OpenGL applications outside of NixOS.

 - [Nixfmt](https://github.com/serokell/nixfmt) is a formatter for Nix code.

 - [Nix-index](https://github.com/bennofs/nix-index) is a tool that quickly locate Nix packages with specific files.

 - [Nix-prefetch](https://github.com/msteen/nix-prefetch) is a universal tool for updating source checksums.

 - [Nix-tree](https://github.com/utdemir/nix-tree) is a tool that let's you interactively browse the dependency graph of Nix derivations.

 - [Statix](https://github.com/nerdypepper/statix) is a linter/fixer to check for and fix antipatterns in Nix code.

 - [Cached-nix-shell](https://github.com/xzfc/cached-nix-shell) is a `nix-shell` replacement that uses caching to open subsequent shells quickly.

 - [Cachix](https://cachix.org/) is a hosted binary cache service; free for open-source projects.

 - [Devshell](https://github.com/numtide/devshell) is a `mkShell` with extra bits and a toml config option to be able to onboard non-nix users.

 - [Flake-utils](https://github.com/numtide/flake-utils) - Pure Nix flake utility functions to help with writing flakes.

 - [Gitignore.nix](https://github.com/hercules-ci/gitignore.nix) - The most feature-complete and easy-to-use `.gitignore` integration.

 - [Lorri](https://github.com/target/lorri/) is a much better `nix-shell` for development that augments direnv.

 - [Makes](https://github.com/fluidattacks/makes) is a Nix-based CI/CD pipeline framework for building, testing, and releasing projects in any language, from anywhere. 

 - [Niv](https://github.com/nmattia/niv/) is a easy dependency management for Nix projects with package pinning.

 - [Nix-direnv](https://github.com/nix-community/nix-direnv) is a fast loader and flake-compliant configuration for the direnv environment auto-loader.

 - [Nixpkgs-review](https://github.com/Mic92/nixpkgs-review) is the best tool to verify that a pull-request in Nixpkgs is building properly.

 - [Pre-commit-hooks.nix](https://github.com/cachix/pre-commit-hooks.nix) is a tool to run linters/formatters at commit time and on your CI.

 - [Robotnix](https://github.com/danielfullmer/robotnix) is a declarative and reproducible build system for Android (AOSP) images.

 - [Nixpkgs-hammering](https://github.com/jtojnar/nixpkgs-hammering) is a nixpkg to beat your package expressions into a shape.

 - [Nix-alien](https://github.com/thiagokokada/nix-alien) is a tool to run unpatched binaries on Nix/NixOS easily.

## NixOS Desktop
[Back to the Top](https://github.com/VanitasuShieda/NixOS-Guide#table-of-contents)

 - [Etcher](https://www.balena.io/etcher/) is an open source, cross-platform software that makes it easy to flash operating system images to a microSD card or USB device.

 - [nixos-generators](https://github.com/nix-community/nixos-generators) is a NixOS config and build multiple different images types including VirtualBox VMs, Azure images, and installation ISOs.
 
 - [nixos-up](https://github.com/samuela/nixos-up) is a super easy NixOS installer that can be used from the installation ISO.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/173939768-31847173-88ab-45f0-8501-0980d1a2a29e.png">
  <br />
  NixOS Desktop with the new Calamares Installer
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/128645111-b2a92dd2-f246-4df0-b05c-5b0ffce05448.png">
  <br />
  NixOS with the Plasma Desktop
</p>


## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/VanitasuShieda/Linux-Guide-Spanish/pulls).


## License

 [Volver al Inicio](#tabla-de-contenidos)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).

Post Original: mikeroyal - [Linux Guide](https://github.com/mikeroyal/Linux-Guide)





████████████████████████████████████████████████████████████▓█████████████████████████████████████████████████████████████
███████████████████████████████████████████████████████████▓ ▒▓███████████████████████████████████████████████████████████
██████████████████████████████████████████████████████████▓▒  ▓███████████████████████████████████████████████████████████
██████████████████████████████████████████████████████████▓▒  ▓▓██████████████████████████████████████████████████████████
██████████████████████████████████████████████████████████▓   ▒▓██████████████████████████████████████████████████████████
██████████████████████████████████████████████████████████▒   ░▓██████████████████████████████████████████████████████████
█████████████████████████████████████████████████████████▓▒    ▓██████████████████████████████████████████████████████████
█████████████████████████████████████████████████████████▓     ▒██████████████████████████████████████████████████████████
█████████████████████████████████████████████▓▓ █████████▓     ▒▓████████▓▓▓██████████████████████████████████████████████
███████████████████████████████████████████▓░ ▒▓████████▓▒      ▓█████████▓  ▒▓███████████████████████████████████████████
█████████████████████████████████████████▓░  ▒██████▓▓▓▒░        ▒▓▓▓██████▓░  ▒▓█████████████████████████████████████████
██████████████████████████████████████▓▓░  ░▓████▓▒                   ▒▓▓████▓   ▒▓███████████████████████████████████████
█████████████████████████████████████▓▒   ▒▓██▓▒░        ░               ▒▓███▓   ░▓██████████████████████████████████████
████████████████████████████████████▓    ▓███▓      ▒▓▓█▓▒      ▓▓▓▓▒      ▒███▓░   ▓▓████████████████████████████████████
██████████████████████████████████▓▒    ▓██▓▒       ▒▓███▓      ▓██▓▒░      ░▓██▓▒   ░▓███████████████████████████████████
█████████████████████████████████▓▒    ▒██▓░   ░  ████ ░░       ░░ ▒███  █    ▓██▓░   ░▓██████████████████████████████████
█████████████████████████████████▒    ▒▓█▓░    █     ███████████████     █     ▓██▓    ░▓█████████████████████████████████
███████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓██████▓     ▓█▓▒    ░░   ▒██████████████████   █ ░    ▓██▒    ▒██████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓████████████
██████████▒               ░▓███▓▒    ▒██▓    ▓▒ █ █████████████████████▒▓ ▒▓░   ▓██▓     ▓███▓▒               ░▓██████████
████████▓▒   ░▒▒▒▒▒▒▒▒▒▒   ▒███▓     ▓██▒   ▒▓▓ ████     ███████      ███ ▓█▓   ░▓█▓▒    ▒███▓   ▒▒▒▒▒▒▒▒▒▒▒░  ▒▓█████████
██▓               ░▓███▓▒  ░▓██▓    ░▓█▓▒   ▓█▓ ███  ████ █████ █▓██  ███ ▓█▓    ▓██▒    ▒▓██▒  ▒▓███▓▒               ▓███
██▓                 ▓███▓   ▓█▓▒    ▒▓█▓░   ▓█▓ ███   ██████████▒██░  ███ ▒█▓░   ▓██▓     ▓█▓░  ▓███▓                 ▓███
████████████████▓▒   ▒▓█▓▒  ▒▓▓▒    ▒▓█▓░   ▓▓░ ██████▒████▓ ▒████▒██████  ▓▓░   ▓██▓     ▓▓▓   ▓██▓   ▒▓█████████████████
██████████████████▓   ▒▓▓▓   ▓▓▒     ▓██▒   ▒▒  █████████████████████████   ▒    ▓██▒     ▓▓▒  ░▓▓▒   ▒███████████████████
███████████████████▓   ▒▓▓   ▒▓▒     ▓██▓   ▒▓  ▒████████████████████████  ▒▓   ▒▓█▓     ░▓▒   ▒▓▒   ▓████████████████████
████████████████████▓░   ▒░          ▒██▓▒   ▓▓▒ ███████████████████████ ░▒▓▒   ▓██▓           ▒░   ▒█████████████████████
█████████████████████▓▒   ▒░  ░░      ▓██▓   ▒███▒  ▓████████████████  ▒▓██▓   ▓██▓░     ░   ░▒░   ▓██████████████████████
██████████████████████▓▒              ░▓██▓   ▒████▓▒ █████████████ ▒▓████▓   ▓███▒               ▓███████████████████████
████████████████████████▓▓▒▒▒▒▒▒▒      ░▓██▓░  ▓███▓░███████  ██████ ▓███▓▒  ▓███▒      ░▒▒▒▒▒▒▓▓█████████████████████████
█████████████████████████████████▓      ░▓███▓  ▓██▒ ██████   ███████░██▓░ ▒▓███▓      ▒██████████████████████████████████
██████████████████████████████████▓       ▓███▓▓ ▓▓ █████ ██ ██ █████ ▓▓ ▒▓███▓▒      ▒███████████████████████████████████
███████████████████████████████████▓       ▒▓████▓░███████████████████ ▓████▓▒       ▒████████████████████████████████████
████████████████████████████████████▓▒       ▒▓██▒ ███████████████████▓░▓█▓▒        ▓█████████████████████████████████████
██████████████████████████████████████▓         ░ █████████████████████ ░░        ▒▓██████████████████████████████████████
███████████████████████████████████████▓▒          ███████████████████          ▒▓████████████████████████████████████████
█████████████████████████████████████████▓▓░               ░▒▒                ▒▓██████████████████████████████████████████
████████████████████████████████████████████▓▓░                            ▒▓█████████████████████████████████████████████
████████████████████████████████████████████████▓▒░                    ▒▓▓████████████████████████████████████████████████
████████████████████████████████████████████████████▓▓▓▒▒▒░░░░▒░▒▒▓▓▓█████████████████████████████████████████████████████
█████████████████████████▓▓▓▓▓▓█████▒  ▓██████████████████████▓▒ ▓████████████████████████████████████████████████████████
██████████████████████▓▒      ▒▓███▓░  ▓██████████████████████▓  ▓██▓▓▓▓██████████████████████████████████████████████████
████████████████████▓▒  ▓▓▒  ▒▓███▓░  ▓███████████████████████▓████▓  ▒▓██████████████████████████████████████████████████
████████████████████▓  ▒▓▓  ▒▓███▓  ▓▓▓▓▒    ░█▓▓   ▓▒   ▓█▓▒  ▓█▓     ░███▓▒     ▓█▓▒    ▓▓▓   ██▓  ▓████████████████████
████████████████████▓  ▓▓░  ▓██▓  ▒▓▓▓  ▓▒   ▓▓ ░    ░   ▓░ ░  ▓█▓░  ▒▓▓█▓  ▓▒░  ▓█▓  ▒▓  ▒ ░  ░▓▓  ░▓████████████████████
████████████████████████▓   ▓▓▒ ░▓█▓░ ▓▓▓▒  ▓██▓▒  ▒▒▒  ▓▓▓▒  ▒██▓  ▒▓██▒  ▓▓▓  ▒███   ▒▓██▓▒  ▓▓▒  ▓█████████████████████
████████████████████████▓  ▒░ ░▓██▓░ ░▓▓▒  ▓▓██▓  ▓▓▓  ▒▓█▓  ░▓█▓   ▓▓▓▒  ▓▓▓  ░▓█▓▓▓▓   ▓█▓  ▓▓▒  ▒▓█████████████████████
████████████████████████▓   ▒▓████▓   ▒      ▓▓  ░▓▓     ▓▒  ▒ ▓▒  ░  ▒   ▒    ▒ ▒  ▓▓▒  ▓▓  ░▒      ▓████████████████████
████████████████████████▓ ▒▓███████▓  ▓▓░ ▒▓██▓  ▓█▓  ▒▓█▓▒ ░▓██▓  ▒▓██▓  ░▓▒  ▓██▓   ▓▓███░  ▓▓▒ ▒▓██████████████████████

