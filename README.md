# 🧾 C# Desktop Sales System (Proyecto Taller 2024)

## 📌 Descripción
Sistema de ventas e inventario desarrollado como parte del Taller de Programación 2024.  
La aplicación permite gestionar productos, usuarios, ventas y reportes utilizando una interfaz de escritorio en C# con una base de datos SQL local.

Este proyecto fue desarrollado aplicando principios básicos de arquitectura, separación de capas y control de datos, y se utilizó Git/GitHub para control de versiones entre diferentes entornos (PC y notebook).

---

## 🚀 Funcionalidades principales

- 📦 **Gestión de productos**  
  - Alta, baja, modificación  
  - Control de stock  
  - Búsqueda y filtrado  

- 🛒 **Gestión de ventas**  
  - Selección de productos  
  - Cálculo automático de totales  
  - Actualización automática del inventario  

- 👤 **Autenticación de usuarios**  
  - Login  
  - Validación básica de permisos  

- 📊 **Reportes**  
  - Ventas del día  
  - Listado de productos  

---

## 🛠️ Tecnologías utilizadas

| Área | Tecnologías |
|------|-------------|
| Lenguaje | C# (.NET) |
| Entorno | Windows Forms / .NET Framework |
| Base de datos | SQL local (SQLite / SQLServer LocalDB, según setup) |
| Gestión de código | Git + GitHub |
| Arquitectura | Organización por capas y módulos funcionales |

---

## 🗂️ Estructura del proyecto

/ProyectoVentas/
├─ /Forms/ # Ventanas principales de la aplicación
├─ /Models/ # Entidades (Producto, Usuario, Venta)
├─ /Controllers/ # Lógica de negocio
├─ /Data/ # Acceso a la base de datos
├─ /bin/ # Archivos de compilación (ignorar en Git)
├─ /obj/ # Archivos temporales (ignorar en Git)
├─ README.md # Documentación del proyecto
└─ .gitignore # Exclusiones de Git

---

## ▶️ Cómo ejecutar el proyecto

### **Requisitos previos**
- Visual Studio 2022 o superior  
- .NET Framework correspondiente al proyecto  
- Motor SQL local (SQLite o LocalDB, según versión)  

### **Pasos**
1. Clonar el repositorio:
   git clone https://github.com/tomascollar/proyecto_taller2024_
2. Abrir el .sln en Visual Studio
3. Restaurar dependencias automáticamente
4. Ejecutar la aplicación con F5
5. La base de datos se genera automáticamente si la app lo implementa. Si no, usar el archivo .sql incluido (si aplicara)
