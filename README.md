# Variables de Entorno configuradas para bat

[![N|Solid](https://i.imgur.com/r3lfak5.png)](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

Para poder las variables en una sesion debemos segir los siguientes pasos:

  - Crear un archivo de texto, con un editor
  - Cambiar las rutas correspondientes a los locales
  - Guardarlo con extención .bat
  - Ejecutar el script


```sh
@echo off
set CLASSPATH=
set ANT_HOME=C:\develop\ant\apache-ant-1.9.14
set PATH=%ANT_HOME%\bin;%PATH%
set JAVA_HOME=C:\develop\java\jdk1.8.0_221
set PATH=%JAVA_HOME%\bin;%PATH%
set M2_HOME=C:\develop\maven\apache-maven-3.2.1
set PATH=%M2_HOME%\bin;%PATH%
set M2=%M2_HOME%
set PATH=%M2%\bin;%PATH%
set GIT_HOME=C:\Users\maximiliano.soria\AppData\Local\Programs\Git
set PATH=%GIT_HOME%\bin;%PATH%
cls
echo Verifique la configuracion actual del entorno de compilacion:
echo .
echo CLASSPATH:     %CLASSPATH%         
echo ANT_HOME:      %ANT_HOME%
echo JAVA_HOME:     %JAVA_HOME%
echo M2_HOME:       %M2_HOME%
echo M2:            %M2%
echo GIT_HOME:		%GIT_HOME%
echo .
echo PATH:          %PATH%
echo .

```
