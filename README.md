# 📊 Control de Nóminas y Cuadrantes de Turnos (Enterprise Edition)

> **🔒 Nota sobre Privacidad y Protección de Datos (RGPD / GDPR):**  
> El código fuente completo, la base de datos de producción y los binarios operativos de este software se encuentran alojados en un **repositorio privado**. Esta aplicación fue desarrollada para un caso de uso real de gestión laboral y salarial; por estrictos motivos de cumplimiento del Reglamento General de Protección de Datos (RGPD) y confidencialidad, los archivos fuente reales no se exponen públicamente.

---

## 🛠️ Arquitectura y Stack Tecnológico

Aunque el código fuente operativo está protegido en entorno privado, la solución técnica se compone de los siguientes módulos y tecnologías desarrolladas íntegramente en Python:

- **Interfaz Gráfica (GUI):** Desarrollada con **CustomTkinter** para un diseño moderno (Dark/Light mode).
- **Gestión de Sesión:** Módulo de autenticación de usuarios (`auth.py`) con control de accesos.
- **Control de Jornadas:** Calendario interactivo (`calendario.py`) para el registro de turnos, horas extra y incidencias.
- **Cálculo Salarial:** Panel de métricas (`dashboard.py`) para estimación de retribuciones y conceptos de nómina.
- **Generación de Informes:** Exportación automatizada de datos a hojas de cálculo mediante **Pandas** y **OpenPyXL** (`excel_exporter.py`).
- **Empaquetado:** Compilación a ejecutable independiente (`.exe`) mediante **PyInstaller**.

---

## 📐 Esquema Modular del Proyecto (Privado)

```text
control_nominas/
├── modules/
│   ├── auth.py             # Control de accesos y seguridad
│   ├── calendario.py       # Registro y cuadrante de turnos
│   ├── dashboard.py        # Métricas y cálculo de nómina
│   ├── excel_exporter.py   # Automatización de reportes (.xlsx)
│   └── login_view.py       # Interfaz gráfica de autenticación
├── main.py                 # Orquestador principal de la aplicación
└── main.spec               # Configuración de compilación PyInstaller



Propósito y Capacidades
Esta herramienta fue diseñada para resolver una necesidad del mundo real: automatizar el control de horas de trabajo, turnos rotativos y el cálculo de percepciones salariales de forma rápida, evitando errores manuales en hojas de cálculo tradicionales y generando reportes listos para administración.
Si eres reclutador o estás interesado en evaluar mis habilidades de desarrollo en Python, arquitectura modular o automatización de procesos, puedes contactar conmigo para solicitar una demostración controlada o ver capturas de pantalla anonimizadas.


```
