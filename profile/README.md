<div align="center">

# 👋 NineTF (NTF)

*Sistemas, scripts y bots hechos a mano, sin salir de la terminal.*

</div>

---

## 📌 ¿Qué es esto?

NineTF es donde monto y mantengo mis proyectos: optimización de Windows, laboratorios en Linux, bots de Discord y herramientas para servidores de juego. No hay equipo de marketing detrás ni roadmap corporativo — es trabajo de taller, hecho porque me gusta que las cosas funcionen bien y sin grasa de más.

---

## 🛠️ En qué ando metido

<details>
<summary><b>🚀 Optimización de Windows</b></summary>
<br>

Scripts y configuraciones a medida con **NTLite** y rutinas en **PowerShell** para quitar telemetría, procesos de fondo que no aportan nada, y dejar el sistema respirando.

</details>

<details>
<summary><b>🐳 Laboratorios y contenedores</b></summary>
<br>

Máquinas Linux headless (Debian) donde pruebo cosas, automatizo servicios con **Docker** y gestiono dominios sin depender de paneles de terceros.

</details>

<details>
<summary><b>🤖 Bots para comunidades</b></summary>
<br>

Bots en **JavaScript**/**Node.js** con **SQLite** de base, pensados para moderar, registrar y llevar el control de servidores de Discord sin volverme loco revisando logs a mano.

</details>

<details>
<summary><b>🎮 Servidores de juego</b></summary>
<br>

Configuración de puertos, tunelización y ajustes finos para servidores dedicados de supervivencia — la prioridad siempre es que no lagee y que no se caiga a las 3 de la mañana.

</details>

---

## 🗂️ Proyectos

| Proyecto | Estado | Stack | Qué hace |
| :--- | :---: | :--- | :--- |
| **codeOS** | 💿 Estable | `NTLite` `Scripts` | Imagen de Windows optimizada para rendimiento. |
| **codeUtils** | 🛠️ En desarrollo | `PowerShell` `Registry` | Scripts de tweaking y mantenimiento del sistema. |
| **PZManager** | 🛠️ En desarrollo | `HTML` `JS` `Docker` | Panel web para gestionar servidores de Project Zomboid sin tocar consola. |
| **Vigil** | 🛡️ Activo | `Node.js` `SQLite` | Bot de moderación y logs para servidores de Discord. |
| **Overwatch** | 🖥️ En desarrollo | `Bash` `Docker` | Bot para monitorizar servicios y dominios. |

---

## 🦁 PZManager, más de cerca

<div align="center">

![Status](https://img.shields.io/badge/estado-en%20desarrollo-f1c40f?style=for-the-badge)
![Stack](https://img.shields.io/badge/HTML-e34c26?style=for-the-badge&logo=html5&logoColor=white)
![Stack](https://img.shields.io/badge/JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)
![Stack](https://img.shields.io/badge/Docker-2496ed?style=for-the-badge&logo=docker&logoColor=white)

</div>

Es el proyecto en el que más tiempo estoy metiendo ahora mismo. La idea es simple: un panel local para no tener que estar entrando por SSH o editando el `.ini` a mano cada vez que quiero cambiar algo del servidor de PZ.

<details>
<summary><b>🗺️ Roadmap</b></summary>
<br>

- [x] Panel de configuración del servidor
- [x] Gestión de mods y Workshop IDs
- [x] Ver jugadores conectados en vivo
- [x] Todo dockerizado para no complicarme el despliegue
- [ ] Editor de sandbox-vars con validación en vivo
- [ ] Consola remota integrada
- [ ] Backups automáticos desde el propio panel
- [ ] Soporte para varios servidores a la vez

</details>

<details>
<summary><b>⚙️ Por dentro</b></summary>
<br>

| Parte | Con qué está hecho |
| :--- | :--- |
| Interfaz | HTML + JS, sin frameworks de por medio |
| Backend | Node.js sirviendo la API del panel |
| Despliegue | Docker, corre junto al servidor dedicado |
| Alcance | Pensado para uso local/LAN, no para exponerlo a internet |

</details>

---

## 🧪 Con lo que trabajo

```yaml
Sistemas: [Debian GNU/Linux, Windows Core, Docker, Proxmox]
Backend:  [Node.js, JavaScript, PowerShell, Bash]
Datos:    [SQLite, JSON Datastores]
Redes:    [IONOS DNS, Certbot SSL, Port Forwarding, Pterodactyl]
```

---

<div align="center">

Todo lo de aquí es código abierto bajo Apache 2.0. Échale un vistazo a los repos si te pica la curiosidad.

</div>
