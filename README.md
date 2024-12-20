# ft\_printf

ft\_printf es un proyecto de la escuela 42 que consiste en recrear la funcionalidad de la función `printf` de la biblioteca estándar de C. Este proyecto permite comprender mejor los conceptos de formateo de cadenas, manejo de argumentos variables y manejo de memoria.

---

## Características

ft\_printf incluye soporte para los siguientes especificadores de formato:

- **%c**: Carácter
- **%s**: Cadena de caracteres (string)
- **%p**: Puntero en formato hexadecimal
- **%d**: Entero con signo en base 10
- **%i**: Entero con signo en base 10
- **%u**: Entero sin signo en base 10
- **%x**: Entero sin signo en base 16 (minúsculas)
- **%X**: Entero sin signo en base 16 (mayúsculas)
- **%%**: Porcentaje literal

---

## Requisitos del sistema

- Sistema operativo: Linux o macOS
- Compilador: gcc

---

## Instalación

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tuusuario/ft_printf.git
   cd ft_printf
   ```

2. Compila la biblioteca:

   ```bash
   make
   ```

3. Incluye el archivo `libftprintf.a` en tu proyecto:

   ```c
   #include "ft_printf.h"
   ```

---

## Uso

1. En tu programa principal, incluye el header:

   ```c
   #include "ft_printf.h"
   ```

2. Usa `ft_printf` como lo harías con `printf`:

   ```c
   #include "ft_printf.h"

   int main(void) {
       ft_printf("Hola, mundo!\n");
       ft_printf("Valor: %d\n", 42);
       ft_printf("Hexadecimal: %x\n", 255);
       return 0;
   }
   ```

3. Compila tu programa junto con la biblioteca:

   ```bash
   gcc -Wall -Wextra -Werror main.c -L. -lftprintf -o programa
   ```

---

## Estructura del proyecto

- **ft\_printf.c**: Implementación principal de la función `ft_printf`.
- **ft\_printf.h**: Archivo de cabecera con las definiciones necesarias.
- **utils/**: Contiene funciones auxiliares utilizadas por `ft_printf`.
- **Makefile**: Automiza la compilación del proyecto.

---

## Testing

Incluye pruebas unitarias para verificar que `ft_printf` funcione correctamente:

1. Compila el proyecto:

   ```bash
   make
   ```

2. Ejecuta un archivo de pruebas:

   ```bash
   ./test_printf
   ```

---

## Contribuciones

Si deseas contribuir al proyecto, por favor abre un **pull request** o crea un **issue** en este repositorio.

---

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

---

## Contacto

Marco Fernández Callejón
- https://www.linkedin.com/in/marco-fernandez-12b061343/?trk=opento_sprofile_details
- marco.fernandezcallejon@hotmail.com



