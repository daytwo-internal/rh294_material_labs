📘 RH294 – Material de Laboratorios (Complemento a Ansible Automation Platform)

Este repositorio contiene material de aprendizaje práctico diseñado como complemento al curso RH294 de Red Hat (Red Hat Ansible Automation Platform).
Incluye laboratorios guiados, ejemplos reales y ejercicios prácticos para reforzar los temas fundamentales de Ansible, orientados a estudiantes, administradores de sistemas y equipos de operaciones.

Los contenidos han sido elaborados por DayTwo – Soporte Libre, con el objetivo de proporcionar escenarios realistas que permitan comprender de forma práctica cómo funciona Ansible en entornos corporativos.

🎯 Objetivos del repositorio

Reforzar conocimientos del curso RH294 mediante práctica guiada.

Explicar conceptos complejos de Ansible mediante ejemplos simples y reproducibles.

Incluir labs que simulan situaciones reales de automatización en infraestructuras Linux/DevOps.

Servir como referencia didáctica para instructores y estudiantes de Ansible.

📚 Contenido del repositorio

Este repositorio incluye varios laboratorios organizados por temas clave:

🔹 1. Precedencia de variables

Cómo Ansible decide qué variable tiene prioridad.

Laboratorio con group_vars, host_vars, role defaults, role vars, vars_files, vars del play y extra_vars.

Ejemplos de override y comportamiento esperado.

🔹 2. Uso de Templates Jinja2 (*.j2)

Generación dinámica de archivos de configuración.

Plantillas con condicionales, loops y filtros.

Ejemplos reales (HAProxy, Nginx, systemd, JSON/YAML dinámicos).

🔹 3. Control de errores

ignore_errors

failed_when

block / rescue / always

Simulación de fallos y recuperación de errores en playbooks.

🔹 4. Import vs Include (Parse time vs Run time)

Diferencias entre:

import_playbook

import_tasks

import_role

include_tasks

include_role

include_vars

Laboratorios con lógica dinámica vs estática.

🔹 5. Facts y Gather Facts

Cómo obtener información del sistema.

Cómo usar ansible_facts en playbooks, lógica condicional y templates.

🗂 Estructura del repositorio