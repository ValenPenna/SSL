# Variables
CC = gcc
CFLAGS = -std=c2x -Wall

# Regla por defecto: compilar el programa
hello: hello.c
	$(CC) $(CFLAGS) hello.c -o hello

# Regla para ejecutar el programa
run: hello
	./hello

# Regla para limpiar los archivos generados
clean:
	rm -f hello