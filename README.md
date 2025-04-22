<p align="center">
  <img src="assets/img/logo.png" alt="Farmacia PHP Logo" width="120" />
  <h1>Sistema de Farmacia 🏥💊</h1>
  <p>Una solución completa para la gestión de farmacias, de código abierto y fácil de usar.</p>
  
  [![PHP](https://img.shields.io/badge/PHP-7.4%2B-%23946FC5.svg)](https://www.php.net/)
  [![MySQL](https://img.shields.io/badge/MySQL-8.0-%2300f.svg)](https://www.mysql.com/)
  [![FPDF](https://img.shields.io/badge/FPDF-1.8-orange.svg)](http://www.fpdf.org/)
  [![Bootstrap](https://img.shields.io/badge/Bootstrap-4.6-blue.svg)](https://getbootstrap.com/)
  [![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
</p>

---

## 📺 Demo en Vivo

<p align="center">
  <img src="docs/demo.gif" alt="Demostración GIF" />
</p>

---
## 🛠️ Tecnologías

- **PHP 7.4+**
- **MySQL 8.0+**
- **FPDF 1.8** para generación de PDFs
- **Bootstrap 4.6** para UI
- **jQuery** y **DataTables**
- **HTML5**, **CSS3**, **JavaScript**

---

## 📁 Estructura del Proyecto

```
Farmacia_php/
├── assets/
│   ├── css/        # Estilos personalizados
│   ├── img/        # Imágenes y logos
│   └── js/         # Scripts JS
├── src/
│   ├── includes/   # Header y footer comunes
│   ├── fpdf/       # Librería FPDF
│   ├── config.php  # Configuración de conexión
│   ├── index.php   # Panel principal
│   ├── clientes.php
│   ├── productos.php
│   ├── ventas.php
│   └── ...         # Más módulos (roles, tipos, laboratorios)
├── docs/           # Documentación y capturas
│   └── screenshot.png
├── .gitignore
├── LICENSE
└── README.md
```

---
## 🚀 Características Destacadas

| Funcionalidad           | Descripción rápida                                           |
|-------------------------|--------------------------------------------------------------|
| 🔐 **Usuarios & Roles** | Administración granular de permisos por rol.                 |
| 🛒 **Gestión de Ventas**| Proceso de venta intuitivo con cálculo automático de totales |
| 🗄️ **Inventario**       | Control de productos, laboratorios y tipos.                  |
| 📦 **Pedidos**          | Registro de compras y control de stock mínimo.               |
| 📋 **Reportes PDF**     | Exportación de ventas y existencias con FPDF.                |
| 🔍 **Búsqueda Avanzada**| Filtrado y paginación en tablas con DataTables.              |
| 📱 **Responsive UI**    | Compatible con dispositivos móviles y tablets.               |

---

## 🛠️ Stack Tecnológico

- **Backend:** PHP 7.4+ 
- **Base de datos:** MySQL 8.0+ 
- **Generación de PDF:** FPDF 1.8
- **Frontend:** Bootstrap 4.6, jQuery, DataTables
- **Servidor Local:** XAMPP, WAMP, MAMP o Docker

---

## ⚙️ Requisitos Previos

- PHP 7.4 o superior
- MySQL 8.0 o superior
- Extensiones PHP: `mysqli`, `gd`, `mbstring`
- Servidor web (Apache/Nginx)

---

## ⚙️ Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/DiegoCross7/Farmacia_php.git
   cd Farmacia_php
   ```
2. Configura la base de datos MySQL:
   - Crea una base de datos llamada `farmacia`.
   - Importa el script SQL: `v_farmacia.sql` en tu servidor.
3. Ajusta credenciales en `src/config.php`:
   ```php
   define('DB_HOST', 'localhost');
   define('DB_USER', 'tu_usuario');
   define('DB_PASS', 'tu_contraseña');
   define('DB_NAME', 'farmacia');
   ```
4. Copia `docs/screenshot.png` a `assets/img/` (opcional).
5. Levanta un servidor local (XAMPP, WAMP, MAMP) apuntando a la carpeta raíz.

---

## 🔧 Configuración

Renombra `src/.env.example` a `.env` y modifica:
```dotenv
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=farmacia
DB_USERNAME=tu_usuario
DB_PASSWORD=tu_contraseña
``` 

---

## 🎯 Uso

1. Accede a `http://localhost/Farmacia_php/src/index.php`.
2. Inicia sesión con credenciales por defecto:
   - **Usuario:** `admin`
   - **Contraseña:** `admin`
3. Explora el menú lateral para gestionar:
   - Usuarios, Roles, Permisos
   - Productos, Tipos, Laboratorios
   - Clientes, Ventas, Reportes
4. Genera reportes PDF desde **Presentación**.

---

## 🤝 Contribuir

¡Tu ayuda es bienvenida! Sigue estos pasos:
1. Haz **fork** del proyecto.
2. Crea una rama nueva: `git checkout -b mejora-mi-funcionalidad`.
3. Realiza tus cambios y haz **commit**: `git commit -m "Descripción de la mejora"`.
4. Sube la rama: `git push origin mejora-mi-funcionalidad`.
5. Abre un **Pull Request**.

Consulta [CONTRIBUTING.md](docs/CONTRIBUTING.md) para más detalles.

---

## 📄 Roadmap

- [ ] Autenticación OAuth
- [ ] Integración con pasarelas de pago
- [ ] Notificaciones por email
- [ ] Traducir interfaz a múltiples idiomas

---

## ⚖️ Licencia

Este proyecto está bajo la **Licencia MIT**. Consulta el archivo [LICENSE](LICENSE) para más información.

---

## 👤 Autor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/DiegoCross7">
        <img src="https://avatars.githubusercontent.com/DiegoCross7" width="80px" alt="" />
        <br />
        <sub><b>DiegoCross7</b></sub>
      </a>
    </td>
  </tr>
</table>

> ¡Gracias por visitar y aportar! 🌟

