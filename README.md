# 📊 Sistema de Facturación AS

### *Sistema de Facturación y Control Comercial de Escritorio*

[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/UI-PyQt%20/%20PySide-green.svg)](https://doc.qt.io/qtforpython/)
[![Tests](https://img.shields.io/badge/tests-pytest-yellow.svg)](https://docs.pytest.org/)

**El sistema de Facturación AS** es una solución ligera y eficiente para la gestión de ventas, control de inventario y facturación, desarrollada íntegramente en Python con un enfoque en la simplicidad y el rendimiento local.

---

## ✨ Características Principales

* **Interfaz Gráfica (GUI):** Experiencia de usuario fluida y moderna desarrollada con PyQt/PySide.
* **Gestión de Usuarios:** Módulo de registro y autenticación segura de usuarios.
* **Control Comercial:** Gestión centralizada de procesos de facturación.
* **Almacenamiento Híbrido:** Soporte para persistencia de datos mediante `billing_data.json` y bases de datos locales (`db.py`).
* **Arquitectura Robusta:** Código estructurado con enfoque en escalabilidad.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python 3.x
* **UI Framework:** PyQt5 / PySide6
* **Base de Datos:** JSON / SQLite (db.py)
* **Testing:** Pytest

---

## 📂 Estructura del Proyecto

```text
├── .venv/               # Entorno virtual
├── img/                 # Recursos visuales y activos
├── tests/               # Pruebas automatizadas
│   ├── test_create_user.py
│   └── test_login_ui.py
├── db.py                # Lógica de base de datos
├── billing_data.json    # Almacenamiento local
└── main.py              # Punto de entrada de la aplicación
