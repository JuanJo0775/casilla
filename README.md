# Casilla

Del papel al sistema, sin teclear casilla por casilla.

Casilla es una aplicación para docentes que convierte la foto de una planilla de notas escrita a mano en notas cargadas en el sistema de gestión escolar de la institución. Un trabajo de 2 horas se resuelve fácilmente en unos 10 minutos.

*Este repositorio es una vitrina del proyecto. El código fuente es privado.*

## El problema

Pasar las notas de una planilla de papel al sistema es un trabajo manual, repetitivo y propenso a errores. Una planilla de 22 estudiantes son 86 casillas para teclear una por una.

## La solución

El docente sube la foto de la planilla y una IA de visión reconoce nombres, columnas y notas. Luego revisa lo reconocido en una tabla editable y confirma. Casilla empareja cada nota con el estudiante correcto por nombre, recalcula las notas derivadas, las carga en el sistema y verifica, campo por campo, que lo guardado coincida. También incluye un generador de planillas en blanco para cerrar el circuito completo.

## Estado

El motor de reconocimiento y carga está completo y probado en vivo con un curso real. La aplicación local (FastAPI y Next.js) está completa. El producto web está en desarrollo: las cuentas de usuario y los planes de uso ya están construidos; faltan la pasarela de pago, el despliegue y HTTPS.

## Principios

La revisión humana es obligatoria antes de guardar: nunca se guarda a ciegas. Casilla no conserva notas ni nombres de estudiantes; el historial registra qué se cargó y cuándo. Este proyecto maneja calificaciones de menores, por eso no se publican datos reales ni credenciales.

## Tecnologías

Python, FastAPI, Next.js, TypeScript, PostgreSQL, Alembic, Google Gemini (visión con IA), GitHub Actions (integración continua y pruebas) y un sistema de diseño propio. La prueba de concepto inicial se hizo con UiPath.

## Contacto

Juan José Naranjo Bocanegra · LinkedIn: https://www.linkedin.com/in/juan-jose-naranjo-bocanegra-375673449/

© 2026 Juan José Naranjo Bocanegra. Todos los derechos reservados.
