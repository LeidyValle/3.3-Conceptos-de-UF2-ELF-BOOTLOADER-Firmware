# 3.3-Conceptos-de-UF2-ELF-BOOTLOADER-Firmware

/*
 * Nombre del Archivo: main.c
 * Autor:   Valle Sanchez Leidy Lizeth
 * Correo:  l21210435@tectijuana.edu.mx
 * Fecha:   25/oct/2023
 * Curso:   Lenguajes de Interfaz
 * 
 * Objetivo:
 * Este programa está diseñado para [proporcionar una breve descripción del objetivo del programa].
 *
 */

#include <stdio.h>
#include "pico/stdlib.h"

int main() {
  stdio_init_all();

  int suma = 0;
  for (int i = 1; i <= 20; i++) {
    suma += i;
  }
  
  printf("La suma de los enteros del 1 al 20 es: %d\n", suma);

  while (true) {
    sleep_ms(250);
  }
}
