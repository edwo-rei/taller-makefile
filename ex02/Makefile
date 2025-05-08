# Define el nombre del ejecutable
NAME = complex

# Define el compilador a utilizar
CC = cc

# Define las flags del compilador
CFLAGS = -Wall -Wextra -Werror

# Define el comando para eliminar archivos
CLEAN = rm -rf

# Define la ubicación de las librerías
LIBDIR = ./inc

# Define la ubicación de la librería printf
PRINTLIB = ./$(LIBDIR)/printf

# Define el archivo de la librería printf
LIP_PRINTF = ./$(PRINTLIB)/libftprintf.a

# Define el comando para llamar al Makefile de printf
LIBFT_MAKEFILE = make -C $(PRINTLIB)

# Define los includes para la compilación
INCLUDE = -I$(PRINTLIB)

# Define la ruta a las librerías
LIBPATH = -L$(PRINTLIB)

# Define las librerías a enlazar
LIBS = -lftprintf

# Define la carpeta donde están los archivos fuente
SRC_FOLDER = src/
SRC_FILES = main.c \

# Lista los archivos fuente
SRCS = src/main.c

# Concatena la ruta con los nombres de archivos
# Genera los nombres de los archivos objeto

# -- RULES -- #
# Regla principal que compila el programa y la librería printf
# Regla patrón para compilar cada archivo .c a .o
%.o: %.c 
	 $(CC) $(CFLAGS) -c -o $@ $<

# Enlaza los objetos con la librería para crear el ejecutable
# Elimina los archivos objeto y limpia printf
# Limpieza completa: elimina objetos y ejecutable
# Recompila todo desde cero
# Declara reglas que no generan archivos

# -- UTILS -- #
# Ejecuta el programa

# -- LIBRARIES -- #

# Compila la librería printf
# Recompila la librería printf
# Limpia los objetos de printf
# Limpia completamente printf
