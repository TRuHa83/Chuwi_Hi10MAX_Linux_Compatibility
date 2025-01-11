# **Chuwi Hi10 Max: Instalación y Configuración de Linux**

Este proyecto documenta la experiencia de instalación y configuración de Linux en la tablet Chuwi Hi10 Max. El objetivo es proporcionar una guía detallada que sirva tanto como referencia personal para futuras reinstalaciones, como también para ayudar a otros usuarios interesados en utilizar Linux en este dispositivo.

---

## **Propósito del Proyecto**

- **Guía Personal:** Documentar los pasos necesarios para reinstalar y configurar Linux en la tablet Chuwi Hi10 Max, asegurando que en futuras ocasiones el proceso sea más rápido y sencillo.
- **Recurso Comunitario:** Compartir esta información públicamente para que otros usuarios puedan beneficiarse de la experiencia y resolver posibles problemas que puedan surgir durante la instalación.

---

## **Distribución utilizada en las pruebas**

El progreso y los resultados de cada prueba se detallarán en las siguientes tabla.

| Distribución         | Gráficos | Audio | WiFi | Bluetooth | Rotación | Táctil | Cámaras | HiPen H7 |
|----------------------|----------|-------|------|-----------|----------|--------|--------|----------|
| Manjaro KDE Plasma   |<div align="center">✅</div>|<div align="center">✅</div>|<div align="center">✅</div>|<div align="center">✅</div>|<div align="center">❌</div>|<div align="center">✅</div>|<div align="center">❌</div>|<div align="center">❌</div>|
| Ubuntu               |<div align="center">✅</div>|<div align="center">✅</div>|<div align="center">✅</div>|<div align="center">✅</div>|<div align="center">⚠️</div>|<div align="center">✅</div>|<div align="center">❌</div>|<div align="center">✅</div>|

---

### Manjaro KDE Plasma

La instalación con Manjaro KDE fue satisfactoria, aunque hubo algunos detalles por ajustar:

- **Escala de pantalla:** Es necesario configurar manualmente la escala para una correcta visualización, ya que no se establece automáticamente.

- **Funcionalidad táctil:** El táctil funciona, pero no de manera óptima. Al cambiar a Wayland, 

- **Cámara:** La cámara no funciona.

- **HiPen H7:** El lápiz HiPen H7 no es reconocido ni funcional.

- **Rotación:** La rotación de pantalla no funciona y no llegué a investigar una solución al respecto.

- **Teclado en pantalla:** Intenté encontrar un teclado en pantalla que fuera práctico y funcional, pero no encontré ninguna opción que me convenciera. Finalmente desistí y decidí probar con Manjaro GNOME.

Al cabo de un rato, después de probar e reinstalar componentes, la pantalla táctil empieza a fallar, haciendo que la experiencia sea horrible

### Manjaro Gnome
La instalación con Manjaro GNOME fue también satisfactoria, y presentó una mejora notable respecto a KDE Plasma en varios aspectos:
- Escala de pantalla: La escala se establece correctamente de forma automática, lo que mejora la experiencia visual sin necesidad de ajustes manuales.
- Gestos táctiles: Los gestos de 2 y 3 dedos funcionan correctamente, mostrando que GNOME está mejor optimizado para paneles táctiles que KDE Plasma.
- Teclado virtual: GNOME provee un teclado virtual integrado que resuelve el problema existente en KDE. Sin embargo, es importante mencionar que debe activarse manualmente desde las opciones de accesibilidad, y solo funciona en determinadas aplicaciones, por lo que la experiencia no es completamente óptima.
- Cámara y HiPen H7: La cámara sigue sin funcionar, al igual que el lápiz HiPen H7, que continúa sin ser reconocido ni funcional.

Al cabo de un rato, después de probar e reinstalar componentes, la pantalla táctil empieza a fallar, haciendo que la experiencia sea horrible.
Dado que se repite
