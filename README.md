# 🔵 Live Incident Response - 4Geeks Academy

## 📖 Descripción

Este repositorio contiene un ejercicio de **Respuesta a Incidentes en Vivo (Live Incident Response)** realizado sobre un servidor Linux comprometido en un entorno controlado. El objetivo fue identificar el vector de ataque, analizar la actividad maliciosa, contener la amenaza, erradicar los mecanismos de persistencia y restaurar la seguridad del sistema.

## 🎯 Objetivos

* 🔍 Investigar un incidente de seguridad en un sistema Linux comprometido.
* 🧩 Reconstruir la cadena de ataque a partir de evidencias forenses.
* 🛡️ Identificar vulnerabilidades explotadas y mecanismos de persistencia.
* 🚨 Aplicar acciones de contención, erradicación y recuperación.
* 📝 Documentar hallazgos y recomendaciones de seguridad.

## 🔬 Metodología

La investigación se realizó siguiendo principios de **Live Incident Response** y buenas prácticas de análisis forense digital, tomando como referencia la guía **NIST SP 800-61** para la gestión de incidentes de seguridad.

### Actividades realizadas

* 👥 Enumeración de usuarios y privilegios.
* ⚙️ Análisis de procesos y servicios activos.
* 📂 Revisión de archivos y directorios críticos.
* 📜 Análisis de logs y evidencias forenses.
* 🎣 Identificación del vector inicial de ataque.
* 🔗 Detección de mecanismos de persistencia.
* 🚫 Contención y erradicación de la amenaza.
* 🔒 Aplicación de medidas de hardening.

## 🚨 Principales Hallazgos

Durante la investigación se identificaron múltiples problemas de seguridad:

* 🔑 Credenciales almacenadas en texto plano.
* 👤 Creación de cuentas maliciosas para persistencia.
* 📩 Ejecución de scripts mediante ingeniería social.
* ⏰ Persistencia a través de cronjobs maliciosos.
* 📤 Exfiltración de información sensible hacia un servidor externo.
* 🌐 Servicios innecesarios expuestos.

## 🛠️ Herramientas Utilizadas

* 🐧 Linux Debian
* 💻 Bash
* 🔎 awk
* 🔍 grep
* ⚙️ systemctl
* ⏰ cron
* 📜 journalctl
* 🗂️ syslog
* 📦 tar

## ✅ Resultados

Al finalizar la respuesta al incidente se logró:

* ✔️ Reconstruir la cadena completa de compromiso.
* ✔️ Eliminar mecanismos de persistencia.
* ✔️ Revocar accesos maliciosos.
* ✔️ Renovar credenciales comprometidas.
* ✔️ Reducir la superficie de ataque del sistema.
* ✔️ Validar la integridad del servidor tras la recuperación.

## 📚 Referencias

* NIST SP 800-61 - Computer Security Incident Handling Guide
* MITRE ATT&CK Framework
* Common Weakness Enumeration (CWE)

## 👥 Equipo Blue Team

* Christopher García
* Alejandro Franco
* Adolfo Muñoz
* Néstor Cáceres
* Nataly Castañeda

---

> 🛡️ Proyecto académico orientado al aprendizaje de análisis forense digital, respuesta a incidentes y hardening de sistemas Linux.
