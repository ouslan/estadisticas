# Instalación de Python

Para comenzar a trabajar con Python, es necesario tenerlo instalado en tu ordenador. Sigue las instrucciones de instalación en el siguiente [enlace](https://www.python.org/downloads/) para instalar Python en tu sistema.

# Instalación de Anaconda

Anaconda es una distribución de Python que incluye muchas de las bibliotecas utilizadas en el análisis de datos. Para instalar Anaconda, sigue las instrucciones en el siguiente [enlace](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Windows-x86_64.exe).

# Instalación de un IDE

Un IDE (Entorno de Desarrollo Integrado) te permite escribir código de manera más eficiente. Para instalar un IDE, sigue las instrucciones en el siguiente [enlace](https://code.visualstudio.com/download).

# Creación de un ambiente virtual

Un ambiente virtual es un espacio de trabajo que te permite instalar bibliotecas de manera independiente a las que están instaladas en tu sistema operativo. Sigue las siguientes instrucciones para crear un ambiente virtual:

```bash
conda create -n clase anaconda
conda activate clase
pip install -r requirements.txt
```

## Descripción de los comandos

- `conda create -n clase anaconda -y`: Crea un ambiente virtual llamado `clase` con la distribución de Anaconda. Este comando puede tardar varios minutos, ya que incluye muchas de las bibliotecas utilizadas en el análisis de datos.
- `conda activate clase`: Activa el ambiente virtual `clase`.
- `pip install -r requirements.txt`: Instala las bibliotecas adicionales utilizadas en el análisis de datos. Este comando puede tardar varios minutos, ya que incluye muchas de las bibliotecas utilizadas en el análisis de datos.

# Instalación de Git

Git es un sistema de control de versiones que permite trabajar en equipo de manera eficiente. Para instalar Git, sigue las instrucciones en el siguiente [enlace](https://git-scm.com/downloads).

# Instalación de GitHub Desktop

GitHub Desktop es una interfaz gráfica que facilita el trabajo con Git de manera más interactiva. Para instalar GitHub Desktop, sigue las instrucciones en el siguiente [enlace](https://desktop.github.com/).

# Instalación de este repositorio

Para instalar este repositorio, sigue las siguientes instrucciones:

```bash
git clone https://github.com/unclearcoder/estadisticas
cd estadisticas
```

## Descripción de los comandos

- `git clone https://github.com/unclearcoder/estadisticas`: Crea una copia de este repositorio en tu ordenador.
- `cd estadisticas`: Cambia al directorio de trabajo del repositorio que acabas de clonar.