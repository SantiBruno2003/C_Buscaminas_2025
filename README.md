ReadMe Nexo

INSTALACION Y CONFIGURACION DEL PROYECTO EN CODEBLOCKS:

1) Descargar SDL2 : https://github.com/libsdl-org/SDL/releases/download/release-2.0.22/SDL2-devel-2.0.22-mingw.zip

2) Extraerlo en la raíz del juego (debería dejar la carpeta con nombre SDL2-2.0.22 en la raíz (esta dentro de la extraída)).

3) Copiar y pegar el archivo SDL2.dll que esta en la ruta " TP_TOPICOS_2025_1C_JUEVES_NEXO\SDL2-2.0.22\x86_64-w64-mingw32\bin" en la raíz de la carpeta del juego

4) ENTRAR A LA CARPETA LIB DONDE ESTARA LA LIBRERIA TTF NECESARIA PARA LA FUENTE.

5) Copiar y pegar el archivo SDL2_ttf.dll que se encuentra en la ruta "TP_TOPICOS_2025_1C_JUEVES_NEXO\lib\SDL2_ttf-2.24.0\x86_64-w64-mingw32\bin" en la raíz de la carpeta del juego.

6) Configurar el proyecto dentro de codeblocks con los siguientes parámetros (en este orden, asegurarse que se copie todo en debug, release y en el proyecto):

Linker settings: 
SDL2main 
SDL2_ttf
SDL2

Search directories (agregar estas rutas de carpetas(puede tener alguna variacion)):

Compiler: 

SDL2-2.0.22\x86_64-w64-mingw32\include
SDL2-2.0.22\x86_64-w64-mingw32\include\SDL2
lib\SDL2_ttf-2.24.0\x86_64-w64-mingw32\include

Linker: 

SDL2-2.0.22\x86_64-w64-mingw32\lib
lib\SDL2_ttf-2.24.0\x86_64-w64-mingw32\lib


