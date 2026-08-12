# <img width="40" height="40" alt="icon" src="https://github.com/user-attachments/assets/acc52db9-2c44-471b-8319-47567eb1156c" /> Temporizador Eclipse: Cuenta atrás y alarmas (12/08/2026)

<div align="center">
  <img width="150" alt="icon" src="https://github.com/user-attachments/assets/acc52db9-2c44-471b-8319-47567eb1156c" />
</div>

<br>

Aplicación nativa para Android diseñada para el seguimiento en tiempo real y la monitorización de los eventos del eclipse solar total del 12 de agosto de 2026. Esta nueva versión universal es capaz de funcionar en cualquier punto del mundo de forma totalmente *offline*.

## 🚀 Características principales

- **Cálculo Astronómico Universal:** Integración de GPS y entrada manual de coordenadas para calcular las circunstancias locales (C1, C2, Máximo, C3, C4) desde cualquier lugar de observación utilizando algoritmos precisos.
- **Soporte para Zonas de Penumbra:** Adaptación inteligente del motor de alertas para observadores fuera de la franja de totalidad, calculando y notificando automáticamente el inicio de la parcialidad (C1), el máximo del eclipse parcial y el fin del evento (C4).
- **Visor de Oscurecimiento en Tiempo Real:** Barra de progreso dinámica que calcula y visualiza el porcentaje exacto del disco solar que está siendo cubierto por la Luna en cada instante.
- **Ajuste Fino de Tiempos (Anulación Manual):** Panel de configuración que permite sobrescribir los cálculos matemáticos para introducir manualmente (HH:mm:ss) las horas de contacto si se dispone de datos de alta precisión para el punto de observación.
- **Memoria Persistente Anti-Cierres:** Guardado automático de todos los ajustes, coordenadas y estado de las alarmas. Si el sistema operativo cierra la aplicación por optimización de batería, todo se restaura de inmediato al volver a abrirla.
- **Bloqueo de Pantalla Activa (*Wake Lock*):** La aplicación mantiene la pantalla encendida de forma permanente mientras está en primer plano, permitiendo una monitorización continua sin necesidad de tocar el dispositivo.
- **Sistema Avanzado de Alertas Híbridas:** Completo asistente automatizado diseñado para no tener que mirar la pantalla durante el evento. Combina locuciones de voz, tonos de alta frecuencia y vibración:
  - Cuenta atrás por voz a los -10, -5 y -1 minutos de los eventos principales.
  - Recordatorios de seguridad para el uso de gafas y filtros solares.
  - Inyección de señal acústica exacta combinada con voz en los milisegundos críticos (Contactos y Máximo).
- **Ejecución de Alta Prioridad en Segundo Plano:** El motor de audio inyecta los avisos a través del **canal de alarmas del sistema**. Las notificaciones operan con total normalidad y al máximo volumen incluso con la pantalla apagada, el terminal bloqueado o el modo "No Molestar" activado. Ideal para concentrarse en la astrofotografía.
- **Modo de Ensayo Inteligente:** Función de test por fases con saltos temporales calculados para verificar de forma continua la secuencia completa de alertas antes del día del evento.

## 📥 Descarga e Instalación

La aplicación se distribuye de manera directa mediante APK para garantizar su disponibilidad inmediata para la observación. Puedes instalarla siguiendo estos pasos:

1. Dirígete a la sección de **[Releases](https://github.com/mpizarrotig/alarmas-eclipse/releases/latest)** de este repositorio.
2. En la última versión publicada, despliega "Assets" y descarga el archivo **`alarmas-eclipse.apk`** directamente en tu dispositivo móvil.
3. Abre el archivo descargado para iniciar la instalación.

> **⚠️ Nota sobre la instalación:**
> * Al ser un archivo descargado directamente de internet, Android solicitará permiso para **"instalar aplicaciones de orígenes desconocidos"**. Concede este permiso a tu navegador web o explorador de archivos.
> * El archivo APK ha sido firmado criptográficamente por el autor. Si **Google Play Protect** muestra una pantalla de advertencia por ser una aplicación distribuida fuera de su tienda oficial, simplemente selecciona **"Más detalles"** y a continuación **"Instalar de todas formas"**.

---

## 🛠️ Tecnologías utilizadas
- Desarrollada de forma nativa para el ecosistema Android.
- Código optimizado para un mínimo consumo de recursos y almacenamiento.

---
**Autor:** Manuel Pizarro, 2026
