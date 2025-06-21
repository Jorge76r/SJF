# Simulador SJF – Despliegue con Docker y Render

Este proyecto implementa una aplicación web simple que representa el algoritmo de planificación **Shortest Job First (SJF)**. La aplicación fue contenerizada usando Docker y desplegada exitosamente en la plataforma Render.com como parte de una práctica de sistemas operativos.

---

## 🌐 Demo en línea

Accede al simulador aquí:  
🔗 [https://sjf-3h5h.onrender.com](https://sjf-3h5h.onrender.com)

---

## 📦 Tecnologías utilizadas

- **Docker**: Para contenerizar la aplicación y aislarla del sistema operativo anfitrión.
- **Render.com**: Para desplegar el contenedor en la nube.
- **Node.js + React (solo build estático)**: Para la construcción del frontend (aunque el foco está en la ejecución, no en el desarrollo).
- **Nginx**: Como servidor liviano en el contenedor final.
- **GitHub**: Como repositorio y control de versiones.

---

## ⚙️ Cómo ejecutar localmente

1. Clona el repositorio:

```bash
git clone https://github.com/Jorge76r/SJF.git
cd SJF