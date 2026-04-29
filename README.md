# Acerca de mí

Especialista en Ciberseguridad y Hacker Ético con más de 15 años de experiencia en desarrollo de software, integración de sistemas y optimización de plataformas empresariales, participando en proyectos de alta criticidad tanto en el sector público como privado en Chile. Mi trayectoria abarca desde el desarrollo y mantención de soluciones basadas en IBM Lotus Domino, Java J2EE y PHP, hasta arquitecturas modernas con microservicios, Node.js, Spring Boot, Angular, Vue y contenedores Docker. He trabajado en organismos como la Contraloría General de la República, DGAC, Ministerio de Educación y diversas compañías del sector financiero, seguros y telecomunicaciones, aportando en la automatización de procesos, workflows, firma digital, autenticación, reportería y optimización de servicios, siempre con foco en la estabilidad, seguridad y eficiencia operativa.
[Más acerca de mí](https://www.vidycs.cl/experiencia-profesional)

# Proyecto Trascender

### Un estándar para construir software basado en capacidades universales

---

## ¿Qué es Trascender?

**Trascender es un estándar para construir software basado en capacidades universales, independiente del lenguaje o tecnología utilizada.**

Nace desde una realidad concreta:
Después de trabajar con múltiples instituciones y sistemas durante años, hay patrones que siempre se repiten.

* gestión de usuarios
* almacenamiento de archivos
* envío de correos
* manejo de contenido
* comunicación en tiempo real
* auditoría
* gestión de errores

Trascender propone algo simple:

> **No partir desde cero, sino desde lo que siempre existe.**

---

## Enfoque

En lugar de construir sistemas por capas técnicas, Trascender propone construirlos por **capacidades reales**.

Cada capacidad se representa como un módulo independiente:

Ejemplos:

* `cf.archivospublicos` → almacenamiento público
* `cf.account` → identidad y autenticación
* `cf.archivosprivados` → almacenamiento protegido
* `cf.database` → acceso y gestión de datos
* `cf.errores` → monitoreo y trazabilidad
* `cf.mailing` → envío de correos
* `cf.push` → notificaciones
* `cf.chat` → comunicación en tiempo real
* `cf.cms` → gestión de contenido
* `cf.blog` → publicación
* `cf.ecommerce` → lógica comercial

---

## Arquitectura

Cada código fuente es:

* ✅ Un sistema independiente
* ✅ Desplegable de forma autónoma
* ✅ Enfocado en una sola responsabilidad
* ✅ Diseñado para integrarse con otros módulos

En producción, estos módulos pueden vivir en subdominios:

```
www.tudominio.cl
account.tudominio.cl
archivospublicos.tudominio.cl
archivosprivados.tudominio.cl
...
```

---

## Integración

Los módulos están diseñados para comunicarse sin acoplamiento fuerte.

Principios:

* Comunicación vía API (HTTP/REST)
* Contratos claros entre servicios
* Posibilidad de eventos (según necesidad)
* Independencia tecnológica

---

## Independiente del lenguaje

Aunque la implementación actual está basada en **Node.js + Express**,
Trascender **no depende de un stack específico**.

Puede ser implementado en:

* Node.js (Express, NestJS, etc.)
* Java (Spring Boot)
* PHP (Laravel)
* u otros

> **No importa cómo lo programes, importa cómo lo piensas.**

---

## Objetivo

Trascender no busca ser:

* ❌ otro framework más
* ❌ una plataforma cerrada
* ❌ una solución única

Busca ser:

* ✅ una forma de pensar sistemas
* ✅ una base reutilizable
* ✅ un punto de partida sólido
* ✅ un estándar adaptable

---

## Estado del proyecto

Actualmente:

* Los módulos están desarrollados y en uso real
* Serán publicados progresivamente en GitHub
* No cuentan con soporte formal (por ahora)

---

## Sobre Vidycs

**Vidycs** es una consultora de software enfocada en:

* escalabilidad
* mantenibilidad
* seguridad
* simplificación de sistemas

Trascender nace como parte de esa experiencia práctica.

---

## Filosofía

> “El problema no es programar más, es decidir mejor qué construir.”

---

## Próximos pasos

* Definición formal de cada `cf.*`
* Estándares de integración
* Documentación por módulo
* Ejemplos en distintos lenguajes

---

## Siguiente paso para tí

[Partir con Archivos Públicos](https://github.com/jotacalderon90/cf.archivospublicos)
