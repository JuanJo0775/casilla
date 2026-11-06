# .edubot

Automatización para docentes: convierte las planillas de calificaciones escritas a mano en notas cargadas en el sistema de la institución.

> Este repositorio es una vitrina del proyecto. El código fuente es privado.

## El problema
Pasar las notas de una planilla de papel a la plataforma escolar es un trabajo manual, repetitivo y propenso a errores: una tarea de unas 2 horas por curso.

## La solución
Una foto de la planilla entra por un lado; por el otro, las notas quedan cargadas en la casilla correcta de cada estudiante. Un trabajo de 2 horas se resuelve fácilmente en unos 10 minutos.

## Cómo funciona
1. Foto de la planilla.
2. Reconocimiento con visión por IA de nombres, columnas y notas.
3. Revisión humana: el docente valida lo reconocido antes de guardar.
4. Emparejamiento por nombre con la lista real de estudiantes.
5. Recálculo de las notas derivadas.
6. Carga en la plataforma y verificación automática campo por campo.

## Estado
- Fase 1: prueba de concepto con automatización de procesos (RPA), completa y probada en vivo con un curso real.
- Fase 2: núcleo en Python, sin RPA, en curso (incluye cuentas de usuario y planes de uso).
- Fases 3 y 4: aplicación local y producto web, planeadas.
- Monetización en avance; aún sin pasarela de pagos.

## Principios
- Revisión humana obligatoria antes de guardar.
- Privacidad: el proyecto maneja calificaciones de menores; no se publican datos reales ni credenciales.

## Tecnologías
Python, UiPath, Google Gemini (visión con IA), Alembic (migraciones de base de datos) y GitHub Actions (pruebas automatizadas).

## Contacto
Juan José Naranjo Bocanegra · [LinkedIn](https://www.linkedin.com/in/juan-jose-naranjo-bocanegra-375673449/)

© 2026 Juan José Naranjo Bocanegra. Todos los derechos reservados.
