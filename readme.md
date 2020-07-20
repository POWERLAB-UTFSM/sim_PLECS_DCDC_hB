# sim_PLECS_DCDC_hB

## Resumen
Este repositorio corresponde a la simulación en PLECS de un convertidor DC-DC medio-puente con aislación galvánica para un driver LED de 600W.

## Pertenencia a proyecto
* **Código Proyecto**: FONDEF IT 18I0090
* **Título Proyecto**: 
* **Investigadores responsables**:
    * Ana Llor (Directora)
    * Freddy Flores
    * Marcelo Pérez
    * Samir Kouro
    * Alan Wilson
    * Sebastián Rivera
* **Estado**: En desarrollo
* **Inicio**: Junio 2019
* **Término**: -

## Autores del repositorio
* Sebastián Toro
* Alan Wilson 

## Ramas del repositorio
* master

## Sub-Carpetas
1. 

## Software para modificar repositorio
* PLECS

## Detalles técnicos del diseño
| **Descripción** | **Tipo** |
| - | - |
| Convertidor | DC-DC | 
| Topología | Medio puente | 
| Aislación Galvánica | Transformador de alta frecuencia (center-tap) | 
| Potencia nominal | 600 W | 
| Tensión de entrada nominal | 750 V DC | 
| Semiconductores de potencia | SiC MOSFET | 
| Control | Microcontrolador embebido (c2000 - Texas Instruments) | 

## Usar Git con este proyecto
Para descargar este proyecto al computador local:
1. Instalar Git: https://git-scm.com/downloads
1. Instalar Git LFS: https://git-lfs.github.com/
1. Inicializar Git LFS:<br />
`git lfs install`
1. Ir al directorio principal donde se quiere dejar el repositorio local, y clonar desde el repositorio remoto `https://remote.git`:<br />
`git clone https://remote.git` <br />
En este caso: <br />
`git clone https://github.com/POWERLAB-UTFSM/sim_PLECS_DCDC_hB.git`

### Usar Git desde la línea de comandos (manual)
1. **Abrir Bash:** <br /> Una vez que se hayan hecho las actualizaciones, ve al directorio del proyecto, abre la ventana de comandos de Git (Git Bash, u otro) y ejecuta:
1. `git status` <br /> Muestra los cambios hechos.
1. `git add [path/file]` <br /> Prepara los archivos/carpetas efectivos para consolidar (**Commit**). Para añadir todos los archivos a la vez, ejecutar `git add .`.
1. `git commit -m "description"` <br /> Consolida los cambios hechos con su respectiva descripción, y agrega el comentario `description`.
1. `git push origin master` <br /> Sube los cambios desde el repositorio local `origin` y la rama `master`, al repositorio remoto. Cambiar el nombre del repositorio local y rama, de ser necesario.
1. `git pull origin master` <br /> Descarga los últimos cambios desde el repositorio remoto hacia el repositorio local `origin` y la rama `master`.

Para más información: https://git-scm.com/doc

## Otros comentarios