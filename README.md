# DB-Coursework-2026-2

Repositorio de entrega para la asignatura de Bases de Datos (semestre 2026-2).

## Instrucciones de entrega — Fork y Pull Request

Cada estudiante debe integrar su proyecto a este repositorio mediante un Pull Request (PR) desde su fork. Sigue este procedimiento y el formato de ejemplo: https://github.com/gabrielhuav/DB-Coursework-2026-1

Pasos rápidos para enviar tu PR:

1. Haz fork de este repositorio a tu cuenta de GitHub.
2. Clona tu fork localmente:

```bash
git clone https://github.com/<tu-usuario>/DB-Coursework-2026-2.git
cd DB-Coursework-2026-2
```

3. Modifica el `README.md` y


4. Haz commit y push a tu fork (usa `main` o una rama propia):

```bash
git add <tu-usuario>
git commit -m "Add project for <tu-usuario>"
git push origin main
```

6. Abre un Pull Request desde tu fork hacia `gabrielhuav/DB-Coursework-2026-2` (base: `main`).

# 🥩 Proyecto: Carnicería Camacho (Sistema de Gestión de Carnicería)

Sistema web desarrollado para modernizar y optimizar la administración de una carnicería mediante una página web conectada a una base de datos en Supabase. El sistema permite gestionar productos, clientes, proveedores y ventas en tiempo real mediante operaciones CRUD.

##  Tecnologías

* **Base de Datos:** PostgreSQL (Supabase)
* **Frontend:** HTML y JavaScript
* **Backend:** Supabase API REST y funciones SQL
* **Despliegue:** GitHub Pages

##  Funcionalidades principales

* Gestión de productos
* Gestión de clientes
* Gestión de proveedores
* Registro de ventas
* Operaciones CRUD completas
* Cálculo automático de impuesto y total
* Conexión en tiempo real con Supabase
* Seguridad mediante RLS y Policies

##  Seguridad

* Uso de anon public key
* Protección mediante Row Level Security (RLS)
* Policies para controlar lectura, inserción, actualización y eliminación de datos

## 🔗 Conexión de la aplicación

Página web : https://ivanrvillegas10-dev.github.io/carniceria/

Repositorio : https://github.com/ivanrvillegas10-dev/carniceria
