# 🛍️ NexShop S.A. - Sistema de Gestión Comercial

## 📋 Descripción General

NexShop S.A. es una plataforma de gestión comercial diseñada para administrar de forma eficiente los procesos de venta, inventario y gestión de clientes de una empresa dedicada al comercio electrónico.

El objetivo principal del proyecto es proporcionar una solución centralizada que permita optimizar las operaciones comerciales, mejorar la trazabilidad de los productos y facilitar la toma de decisiones mediante una base de datos estructurada y escalable.

---

## 👨‍🎓 Información del Proyecto

| Campo       | Información                                 |
| ----------- | ------------------------------------------- |
| Proyecto    | NexShop S.A.                                |
| Tipo        | Base de Datos Relacional                    |
| Curso       | 2º SMR |
| Autor       | Miguel Martínez                             |
| Repositorio | https://github.com/Migueel9                 |
| Fecha       | 2026                                        |

---

## 🏢 Contexto Empresarial

NexShop S.A. opera dentro del sector del comercio electrónico y requiere una infraestructura de datos capaz de gestionar:

* Catálogo de productos
* Control de inventario
* Gestión de clientes
* Procesamiento de pedidos
* Métodos de pago
* Seguimiento de envíos
* Gestión de proveedores

La solución implementada busca garantizar la integridad de los datos y facilitar futuras ampliaciones del sistema.

---

## 🗄️ Modelo de Datos

### Diagrama Entidad-Relación (ER)

El modelo relacional ha sido diseñado siguiendo principios de normalización para minimizar redundancias y garantizar la consistencia de la información.

> <img width="6176" height="3336" alt="Diagrama_ER" src="https://github.com/user-attachments/assets/bd35a4ea-c074-424c-a25f-7a8a7de68de1" />
 

```markdown
![Diagrama ER](docs/diagrama-er.png)
```

---

## 📁 Estructura del Repositorio

```text
mi-proyecto-nexshop/
│
├── docs/
│   └── Capturas - Consultas.pdf
│   ├── Diagrama_ER.png
│   ├── Memoria de Análisis
│   └── Modelo Relacional
│
├── sql/
│   ├── consultas.sql
│   ├── datos.sql
│   └── schema.sql
│
├── README.md
```

---

## ⚙️ Instalación y Ejecución

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/Migueel9/mi-proyecto-nexshop.git
cd mi-proyecto-nexshop
```

### 2️⃣ Crear la base de datos

```sql
CREATE DATABASE nexshop;
```

### 3️⃣ Ejecutar el script principal

```bash
mysql -u root -p nexshop < sql/schema.sql
```

### 4️⃣ Cargar datos de ejemplo

```bash
mysql -u root -p nexshop < sql/inserts.sql
```

---

## 🔍 Funcionalidades Implementadas

### Gestión de Clientes

* Registro de clientes
* Actualización de información
* Historial de compras

### Gestión de Productos

* Alta y baja de productos
* Clasificación por categorías
* Control de stock

### Gestión de Pedidos

* Creación de pedidos
* Seguimiento de estados
* Historial de transacciones

### Gestión de Proveedores

* Registro de proveedores
* Relación producto-proveedor

### Facturación y Pagos

* Métodos de pago
* Control de facturación
* Registro de operaciones

---

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso                                |
| ---------- | ---------------------------------- |
| MySQL      | Sistema gestor de bases de datos   |
| SQL        | Definición y manipulación de datos |
| Git        | Control de versiones               |
| GitHub     | Gestión del repositorio            |
| Draw.io    | Diseño del modelo ER               |

---

## 📊 Principales Entidades

* Cliente
* Pedido
* Producto
* Categoría
* Inventario
* Proveedor
* Pago
* Envío

---

## 🎯 Objetivos Alcanzados

✅ Diseño de base de datos relacional

✅ Normalización de entidades

✅ Implementación de claves primarias y foráneas

✅ Integridad referencial

✅ Consultas SQL optimizadas

✅ Documentación técnica del proyecto

---

## 🚀 Posibles Mejoras Futuras

* Integración con aplicación web
* Implementación de procedimientos almacenados
* Creación de vistas avanzadas
* Automatización mediante triggers
* Panel de administración

---

## 👤 Autor

**Miguel Martínez**

GitHub: https://github.com/Migueel9

---
