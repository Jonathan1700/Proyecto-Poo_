# 📋 Sistema de Gestión de Permisos

Sistema de consola en Python para administrar empleados, tipos de permiso y ausencias laborales con cálculo automático de descuentos..

---

## ▶️ Ejecución

```bash
python sistema_permisos.py
```
> Requiere Python 3.8+. No necesita librerías externas.

---

## 🗂️ Funcionalidades

| Opción | Descripción |
|--------|-------------|
| 1 | Registrar Empleado |
| 2 | Registrar Tipo de Permiso |
| 3 | Registrar Permiso |
| 4 | Consultar Registros |
| 5 | Consultar Permisos |
| 6 | Eliminar Registro |
| 7 | Estadísticas |

---

## 📐 Lógica de Negocio

- **Valor hora:** `sueldo / 240`
- **Descuento por horas:** `tiempo × valor_hora`
- **Descuento por días:** `tiempo × 8 × valor_hora`
- Permisos **remunerados** no generan descuento.

---

## 🛠️ Conceptos Aplicados

- Clases abstractas (ABC), Mixins y Decoradores
- Funciones de orden superior: `map`, `filter`, `reduce`
- Validación de fechas con `datetime`

---

## 👥 Integrantes

- Jonathan Castro Belfor
- Jhoan Cevallos
- Elian Galeas
- Jose Torres
- Jean Jimenez
