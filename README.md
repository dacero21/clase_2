![GitHub](https://img.shields.io/github/license/taller-R/clase_4) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/taller-R/clase_4/issues) ![](https://img.shields.io/github/followers/taller-R?style=social)

<img src="https://avatars0.githubusercontent.com/u/69440432?s=400&u=96b3e58c713578b563d5c3d3c259f34965ac8e33&v=4" align="right" width=120 height=120 alt="" />

# INSTRUCCIONES

## 1. Descargar la clase

Para descargar las clases debes seguir los siguientes pasos:

```{r}
# 1. Establecer el directorio de trabajo en el que quieres descargar la carpeta
setwd("~/Downloads")

# 2. Descargar el repositorio
download.file(url = "https://github.com/taller-R/clase_2/archive/master.zip", 
              destfile = "clase_2.zip")

# 3. Descomprimir las carpeta
unzip(zipfile = "clase_2.zip")

# 4. Cambiar nuevamente el directorio de trabajo
setwd("~/Downloads/clase_2-master")

# 5. Inspeccionar archivos en el directorio 
list.files()
```
O puedes seguir estas otras [instruciones](https://eduard-martinez.github.io/blog/github/clonar_github.html).  

## 2. Notas

* Los vídeos de la clase se encuentran [aquí](https://www.dropbox.com/sh/1s8odr6rrc64acl/AAAhWXHkq8w7_iMl3cW00kjfa?dl=0).Dropbox no deja reproducir los vídeos más de 1 hora en linea, debe descargarlos para que pueda verlos completos.

* Por favor hacer todas las correcciones ortográficas a este y los demas archivos .Rmd del repositorio.
