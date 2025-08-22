[Link](https://japago25andes.github.io/Prototipo-Uber-EventConnect/)

# Uber EventConnect - Prototipo Interactivo

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🚀 Resumen del Proyecto

**Uber EventConnect** es una nueva funcionalidad propuesta dentro de la aplicación de Uber, diseñada para resolver la caótica y estresante experiencia de conseguir transporte después de eventos a gran escala como conciertos o partidos deportivos. Este repositorio aloja un prototipo interactivo del concepto central: la **"Fila Virtual"**.

El objetivo del proyecto era validar una solución para alcanzar el objetivo SMART de **incrementar en un 25% los viajes** en la categoría EventConnect y **reducir en un 30% las quejas** por transporte post-evento en Bogotá en un plazo de 12 meses.

---

## 🤯 El Problema: El Caos Post-Evento

La investigación de usuarios identificó un arquetipo clave, "Camila Hernández, la Asistente Frustrada del Evento". Sus principales frustraciones al salir de un evento masivo son:
* **Caos y Desorganización**: El punto de dolor más grande, incluso por encima del precio.
* **Esperas Largas e Inciertas**: Una cita de un usuario que cambió la perspectiva del proyecto fue: "Esperé 1 hora un transporte sin éxito; al final caminé 15 cuadras para encontrar un taxi". Esto demostró que la incertidumbre y la espera pesan más que el costo.
* **Tarifas Dinámicas Elevadas**: La ansiedad causada por la imprevisibilidad de los precios dinámicos.
* **Dificultad para Encontrar un Carro**: Más del 70% de los usuarios entrevistados mencionaron la dificultad para encontrar un viaje disponible como su principal molestia.

---

## ✨ La Solución: Fila Virtual

Para abordar estos puntos de dolor, la idea central seleccionada para el desarrollo fue la **"Fila Virtual por Lotes con Geolocalización"**.

Este sistema permite a los asistentes unirse a una fila digital desde sus teléfonos antes de que termine el evento. Luego, la aplicación agrupa a los usuarios en lotes, asignándoles una hora específica y un punto claramente marcado para encontrarse con su conductor. Esto transforma la experiencia de un "sálvese quien pueda" estresante a un proceso ordenado, predecible y justo. La **"Fila Virtual con Cronómetro"** fue identificada como un atributo **"Delighter" (Espectacular)** en el análisis del Modelo Kano, ya que convierte un punto de dolor masivo en un momento "mágico" y memorable.

---

## 📱 Prototipo Interactivo

Este prototipo interactivo simula el recorrido del usuario a través de la funcionalidad "Fila Virtual". Fue construido para probar y validar supuestos críticos sobre el comportamiento del usuario y para comunicar el valor de la solución.

### Funcionalidades Clave del Prototipo:
* **Incorporación Sencilla**: Se invita a los usuarios a unirse a la Fila Virtual con una propuesta de valor clara: una tarifa fija y una salida ordenada.
* **Estado de la Fila en Tiempo Real**: Una vez en la fila, el usuario puede ver su posición, el número de personas delante y una cuenta regresiva en vivo con su tiempo de espera estimado. Este fue un elemento clave para generar confianza.
* **Mensajes de Confianza**: La interfaz incluye mensajes para asegurar al usuario que su lugar está guardado, incluso si cierra la aplicación o pierde su conexión a internet, una duda que surgió durante las pruebas.
* **Notificación "¡Es tu turno!"**: Una alerta clara le dice al usuario cuándo debe dirigirse al punto de recogida designado.
* **Información Clara del Conductor y Recogida**: La aplicación proporciona el carril de recogida exacto y los detalles del conductor asignado para eliminar la confusión.

---

## 🕹️ Cómo Usar el Prototipo

El prototipo consta de cuatro pantallas principales que guían al usuario a través de la experiencia EventConnect:

1.  **Pantalla de Invitación**: La pantalla inicial presenta la oferta para unirse a la Fila Virtual. Haz clic en **"Entrar a la Fila Virtual"** para continuar.
2.  **Pantalla de Espera**: Esta pantalla muestra tu posición en tiempo real en la fila y una cuenta regresiva del tiempo de espera estimado. La simulación avanzará automáticamente.
3.  **Pantalla de Tu Turno**: Cuando el contador llega a cero, aparece esta pantalla, indicándote que vayas a un carril de recogida específico y mostrando los detalles de tu conductor.
4.  **Pantalla de Éxito**: Después de confirmar la recogida, una pantalla final resume los beneficios del viaje, como el tiempo y el dinero ahorrados.

---

## 📈 Validación y Aprendizajes del Proyecto

El proyecto siguió un proceso de validación sistemático, lo que condujo a conocimientos clave que dieron forma al prototipo y la estrategia final.

### Hitos de Validación:
* **Supuesto Crítico Validado**: Una prueba mini-piloto validó el supuesto más crítico (A2): que los usuarios estarían dispuestos a unirse a la fila antes de que terminara el evento. La prueba alcanzó una **tasa de adopción del 50%**, superando con creces el umbral de éxito del 30%.
* **Éxito en la Prueba de Marketing**: Una prueba cuantitativa utilizando una campaña de anuncios en Instagram Stories y una página de destino resultó en una **tasa de conversión del 11.03%** (registros de correo electrónico), superando el objetivo del 8%. Esto confirmó un interés de mercado significativo en la solución.
* **Retroalimentación Cualitativa**: Las pruebas con usuarios de la página de marketing revelaron que el titular inicial era demasiado genérico. Cambiarlo por uno más directo y añadir una sección de Preguntas Frecuentes (FAQ) para abordar el escepticismo de los usuarios mejoró significativamente la comprensión y la confianza.

### Aprendizajes Clave:
* **La Certeza es el Verdadero Valor**: La característica más valorada es la sensación de orden y certeza que proporcionan el cronómetro y la posición en la fila.
* **La Comunicación Proactiva es Crucial**: Los usuarios necesitan una confirmación explícita de que no perderán su lugar en la fila si cierran la aplicación o pierden la señal.
* **El "Delighter" es el Diferenciador**: La "Fila Virtual" es la funcionalidad principal que eleva la experiencia de funcional a espectacular y es la ventaja competitiva clave.

---

## 🛠️ Stack Tecnológico

Este prototipo fue construido utilizando tecnologías front-end estándar:

* **HTML5**: Para la estructura y el contenido de la aplicación web.
* **CSS3**: Para los estilos, el diseño y las animaciones.
* **JavaScript**: Para la lógica interactiva, los temporizadores y las transiciones de página.

---

## ➡️ Próximos Pasos

Basado en la exitosa validación, los siguientes pasos estratégicos son:
1.  **Asegurar Alianzas con Recintos (Supuesto A7)**: Forjar acuerdos con los lugares de eventos para establecer carriles de recogida exclusivos y apoyo logístico.
2.  **Garantizar la Adopción de los Conductores (Supuesto A13)**: Diseñar y probar incentivos para asegurar que los conductores sigan el sistema de asignación por lotes sin rechazar viajes.
3.  **Escalar un Piloto en el Mundo Real**: Implementar la funcionalidad en un evento en vivo con una base de usuarios más grande para confirmar las tasas de adopción y la viabilidad operativa a escala.
