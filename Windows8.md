# Informe sobre la instalación del sistema operativo Windows 8 en una maquina virtual
**Curso:** Sistemas operativos I
**Estudiante:** Harold Sneider pulido Rios

---

## Tabla de Contenido

  - [Informe Sobre la Instalación del Sistema Operativo Windows 8 en una Máquina Virtual](#informe-sobre-la-instalación-del-sistema-operativo-Windows-8-en-una-máquina-virtual)
  - [Tabla de Contenido](#tabla-de-contenido)
    - [1. Introducción](#1-introducción)
      - [Propósito](#propósito)
      - [Alcance](#alcance)
    - [2. Requisitos Previos a la Instalación](#2-requisitos-previos-a-la-instalación)
      - [Requisitos de hardware](#requisitos-de-hardware)
      - [Requisitos de software](#requisitos-de-software)
    - [3. Configuración de la Máquina Virtual (MV)](#3-configuración-de-la-máquina-virtual-mv)
      - [Elección del software de virtualización](#elección-del-software-de-virtualización)
      - [Creación de la máquina virtual](#creación-de-la-máquina-virtual)
    - [4. Proceso de Instalación de Windows 8](#4-proceso-de-instalación-de-Windows-8)
      - [Descarga de la ISO de Windows 8](#descarga-de-la-iso-de-Windows-8)
      - [Configuración de la máquina virtual](#configuración-de-la-máquina-virtual)
      - [Pasos de la instalación](#pasos-de-la-instalación)
    - [5. Configuración Posterior a la Instalación](#5-configuración-posterior-a-la-instalación)
      - [Actualizaciones del Sistema](#actualizaciones-del-sistema)
      - [Instalar software esencial](#instalar-software-esencial)
      - [Configuración de los ajustes del sistema](#configuración-de-los-ajustes-del-sistema)
      - [Instalación software adicional](#instalación-software-adicional)
    - [6. Pruebas y verificación](#6-pruebas-y-verificación)
      - [Rendimiento del sistema](#rendimiento-del-sistema)
      - [Pruebas de funcionalidad](#pruebas-de-funcionalidad)
    - [7. Conclusión](#7-conclusión)
      - [Resumen del proceso](#resumen-del-proceso)
      - [Observaciones y desafíos](#observaciones-y-desafíos)
      - [Comentarios Sobre Windows 8](#comentarios-sobre-Windows-8)
    - [8. Referencias](#8-referencias)
      - [Sitios Web](#sitios-web)
      - [Documentos](#documentos)
      - [Tutoriales](#tutoriales)


     ---

    ### 1. Introducción

#### Propósito
El proposito de este informe es llevar un registro y una guia de la instalación de Windows 8, desde la configuración en la maquina virtual, los requistos necesarios para correrlos y unas pruebas para ver que cosas puede hacer este sistema operativo.
#### Alcance
Su alcance va hasta que se le logre la correcta instalación y configuración de Windows 8 desde Virtual Box.

### 2. Requisitos Previos a la Instalación

#### Requisitos de hardware
- Procesador: Procesador de dos núcleos o superior (se recomiendan 2 GHz)
- MEMORIA RAM: Mínimo 2 GB (se recomiendan 4 GB)
- Espacio en disco: Al menos 20 GB de almacenamiento libre (se recomiendan el doble o triple)
- Conexión a Internet: Para descargar software y actualizaciones.
- Arquitectura: 64-bits.

#### Requisitos de software
- Software de virtualización: Oracle VirtualBox (versión 6.1 o posterior)
- Archivo ISO de Windows 8: Windows 8.1

### 3. Configuración de la Máquina Virtual (MV)

#### Elección del software de virtualización
Para esta instalación, se elige Oracle VirtualBox debido a su amplio soporte y facilidad de uso.

#### Creación de la máquina virtual
1. **Abre VirtualBox** y haz clic en «Nuevo» para crear una nueva máquina virtual.
2. **Nombra la VM** (Windows 8.1), establece el tipo en «Microsoft Windows» y la versión en «Windowws 8 (64 bits)».
3. **Asigne memoria**: Asigna al menos 4 GB de memoria RAM.
4. **Crear un disco duro virtual**: Seleccione «Crear un disco duro virtual ahora» y siga las instrucciones para asignar al menos 25 GB de almacenamiento.
   
<p float="left" style="text-align:center">
  <img src="Imágenes/Windows8-Instalación.png" width="800" />
</p>

