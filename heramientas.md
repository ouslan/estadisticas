# Instalacion Python 
Para comenzar a trabajar con Python, es necesario tener instalado Python en su ordenador. Para ello, puede seguir las instrucciones de instalación en el siguiente [enlace](https://www.python.org/downloads/).

# Instalacion de Anaconda
Anaconda es una distribución de Python que incluye muchas de las librerías que se utilizan en el análisis de datos. Para instalar Anaconda, puede seguir las instrucciones en el siguiente [enlace](https://www.anaconda.com/products/individual).

# Instalacion de un IDE
Un IDE es un entorno de desarrollo integrado que permite escribir código de manera más eficiente. Para instalar un IDE, puede seguir las instrucciones en el siguiente [enlace](https://code.visualstudio.com/download).

# Creacion de un ambiente virtual
Un ambiente virtual es un espacio de trabajo que permite instalar librerías de manera independiente a las que se encuentran instaladas en el sistema operativo. Para crear un ambiente virtual, puede seguir las siguientes intrucciones:
```bash
conda create -n clase anaconda
conda activate clase
pip install -r requirements.txt
```
## Descripción de los comandos
- `conda create -n clase anaconda -y`: Crea un ambiente virtual llamado `clase` con la distribución de Anaconda. Este comando puede tardar varios minutos ya que contriene mucchas de las librerías que se utilizan en el análisis de datos.
- `conda activate clase`: Activa el ambiente virtual `clase`.
- `pip install -r requirements.txt`: Instala las librerías adicionales que se utilizan en el análisis de datos. Este comando puede tardar varios minutos ya que contriene mucchas de las librerías que se utilizan en el análisis de datos.

# Instalacion de Git
Git es un sistema de control de versiones que permite trabajar en equipo de manera eficiente. Para instalar Git, puede seguir las instrucciones en el siguiente [enlace](https://git-scm.com/downloads).

# Instalacion de GitHub Desktop
GitHub Desktop es una interfaz gráfica que permite trabajar con Git de manera más interactiva. Para instalar GitHub Desktop, puede seguir las instrucciones en el siguiente [enlace](https://desktop.github.com/).

# Instalacion de este repositorio
Para instalar este repositorio, puede seguir las siguientes instrucciones:
```bash
git clone https://github.com/unclearcoder/estadisticas
cd estadisticas
```
## Descripción de los comandos
- `git clone https://github.com/unclearcoder/estadisticas': Crea una copia de este repositorio en su ordenador.
- `cd estadisticas`: Cambia el directorio de trabajo al repositorio que acaba de copiar.