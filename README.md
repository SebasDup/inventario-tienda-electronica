# 🛒 Sistema de Punto de Venta (Simulación Empresarial en C)

## 📝 Descripción del Proyecto
Este proyecto es un sistema de Punto de Venta (POS) desarrollado íntegramente en C puro. Fue creado como una simulación empresarial para un cliente del sector de la electrónica (tipo Steren), con el objetivo de gestionar el inventario, procesar transacciones y modelar la lógica de negocio de una sucursal física. El sistema gestiona su propia base de datos a través de archivos de texto y cuenta con autenticación de usuarios.

## 🛠️ Tecnologías y Conceptos Aplicados
* **Lenguaje:** C estándar (C89/C99).
* **Gestión de Memoria:** Asignación dinámica de memoria utilizando `malloc` y `free`.
* **Estructuras de Datos:** Implementación de listas simplemente enlazadas mediante punteros para la gestión dinámica del carrito de compras.
* **Persistencia de Datos:** Manejo de archivos I/O (`.txt`) para almacenar persistencia de empleados, productos y registros de ventas.
* **Librerías Destacadas:** `<stdio.h>`, `<stdlib.h>`, `<string.h>`, `<time.h>`.

## 🎯 Competencias Desarrolladas
Como Ingeniero en TI, este proyecto me permitió consolidar:
* **Planeación y Diseño de Software:** Traducción de los requerimientos de un cliente simulado a una arquitectura de software funcional basada en consola.
* **Solución de Problemas de Bajo Nivel:** Manejo seguro de punteros, prevención de fugas de memoria y estructuración lógica algorítmica sin depender de frameworks modernos.
* **Lógica de Negocio y Seguridad:** Desarrollo de un sistema de roles (Administrador vs. Encargado) y control de flujo basado en credenciales.

## ⚙️ Características Principales (Features)
* **Sistema de Autenticación:** Login seguro basado en ID y contraseña con diferenciación de permisos.
* **Módulo de Ventas:** Generación de tickets, cálculo de totales, verificación de fondos y actualización de inventario en tiempo real.
* **Módulo de Inventario (CRUD):** Capacidad de dar de alta, modificar, consultar y dar de baja productos del catálogo.
* **Módulo de Recursos Humanos:** Gestión de empleados, roles, contraseñas y registro de fechas de ingreso automatizadas por el sistema operativo.

## 🚀 Cómo ejecutar el proyecto
1. Clona este repositorio: `git clone https://github.com/tu-usuario/tu-repo.git`
2. Compila el código fuente usando un compilador de C (ej. GCC): `gcc main.c -o pos_system`
3. Ejecuta el binario: 
   * En Linux/Mac: `./pos_system`
   * En Windows: `pos_system.exe`

## 📸 Capturas de Pantalla
1. Inicio de Sesión
<img width="548" height="282" alt="image" src="https://github.com/user-attachments/assets/dd02c960-3c07-4455-9d10-65002aed7d02" />


2. Menú del Sistema
<img width="640" height="263" alt="image" src="https://github.com/user-attachments/assets/a2298382-a03a-4948-bb10-e84a00ce6588" />


3. Gestión de Ventas
<img width="253" height="175" alt="image" src="https://github.com/user-attachments/assets/1d774432-bf17-493f-826d-a81585bf2767" />


4. Gestión de Productos
<img width="301" height="163" alt="image" src="https://github.com/user-attachments/assets/577396b2-defd-4881-b9ee-2415878c2bb0" />


5. Reporte de Inventario
<img width="750" height="237" alt="image" src="https://github.com/user-attachments/assets/24558f3c-0fb5-40a1-82f4-18df8658ff82" />


6. Reporte de Corte de Caja
<img width="845" height="262" alt="image" src="https://github.com/user-attachments/assets/aa4c6131-9720-4e0e-87ca-d16603a36d25" />
