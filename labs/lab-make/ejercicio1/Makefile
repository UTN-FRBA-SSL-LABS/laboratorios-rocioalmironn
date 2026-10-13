# Nombre del programa final
PROGRAMA := suma

# TODO 1: Definí el compilador a usar
CC := gcc

# TODO 2: Definí las flags de compilación
CFLAGS := -Wall

# Regla principal: indica qué construir al ejecutar `make`
all: $(PROGRAMA)

# Regla para generar el ejecutable a partir de suma.c
$(PROGRAMA): suma.c
	$(CC) $(CFLAGS) suma.c -o $(PROGRAMA)

# Regla para limpiar los archivos generados
clean:
	rm -f $(PROGRAMA)

.PHONY: all clean
