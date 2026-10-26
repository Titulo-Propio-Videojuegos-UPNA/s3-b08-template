# B08 - Ingeniería XR Standalone e Interacción Espacial 6DoF con Unity 6, C# (.NET), OpenXR y Meta Quest 3

Portabilidad arquitectónica e ingeniería de Realidad Extendida (VR/MR) sobre los 25 visores Meta Quest 3 del laboratorio del campus: arranca en el minuto 1 con una tabla de traducción directa UE5 C++ ↔ Unity 6 C# (.NET) y una plantilla OpenXR preconfigurada (0 horas perdidas instalando SDKs), dedicando el bloque a programar C# (.NET) limpio y desacoplado (interfaces, async/await, consumo HTTP/JSON), interacción espacial 6DoF con XR Interaction Toolkit, Realidad Mixta (Passthrough) y optimización bajo el presupuesto móvil de 72/90 Hz.

---

## Cápsulas de Sesión y Etiquetas de Paracaídas (`s3-b08-template`)

- **Proyecto / Toybox:** Proyecto 8 (Pieza 5): «Estación Espacial / Gemelo XR 6DoF en Meta Quest 3» (aplicación VR/MR con manos y mandos 6DoF, agarre físico, paneles diegéticos y Passthrough en Unity 6 + C# a 72/90 Hz).
- **Capas 70 / 20 / 10:** • 70 % Base (en aula): App XR 6DoF en Unity 6 + C# (.NET) desplegada y corriendo en visor Meta Quest 3 con agarre físico, UI diegética y Passthrough. · • 20 % Reto autónomo: Consumo asíncrono (async/await) de datos externos en C# desacoplado por interfaces manteniendo 72/90 Hz estables. · • 10 % Extra Portfolio: Interacción bimanual avanzada en Realidad Mixta y captura de métricas OVR Metrics Tool.
- **Plataforma docente (vídeo indexado y entregas):** [https://ikasyn.com/titulo-videojuegos](https://ikasyn.com/titulo-videojuegos)

| Sesión | Subbloque | Horas | Título | Tag Inicio (`sync_checkpoint`) | Tag Fin |
|:---:|:---:|:---:|---|---|---|
| `S3-09` | `B08.1` | 2 h | Pieza 5 (XR con Unity 6, C# y Meta Quest 3) · Día 1: Traducción rápida UE5 C++ ↔ Unity 6 C# (.NET) | `scripts\sync_checkpoint.bat s3-09-start` | `s3-09-end` |
| `S3-10` | `B08.1` | 2 h | Pieza 5 · Arquitectura C# (.NET) desacoplada: interfaces, eventos C#, ScriptableObjects y async/await | `scripts\sync_checkpoint.bat s3-10-start` | `s3-10-end` |
| `S3-11` | `B08.2` | 2 h | Pieza 5 · Interacción espacial 6DoF I: XR Origin, seguimiento de manos/mandos y agarre físico directo | `scripts\sync_checkpoint.bat s3-11-start` | `s3-11-end` |
| `S3-12` | `B08.2` | 2 h | Pieza 5 · Interacción espacial 6DoF II: XRRayInteractor, sockets de encaje y locomoción sin cinetosis | `scripts\sync_checkpoint.bat s3-12-start` | `s3-12-end` |
| `S3-13` | `B08.2` | 2 h | Pieza 5 · Interfaces Espaciales Diegéticas (World-Space UI) y ergonomía visual en VR | `scripts\sync_checkpoint.bat s3-13-start` | `s3-13-end` |
| `S3-14` | `B08.3` | 2 h | Pieza 5 · Realidad Mixta (MR) en Meta Quest 3 I: Passthrough a color y anclajes al mundo físico | `scripts\sync_checkpoint.bat s3-14-start` | `s3-14-end` |
| `S3-15` | `B08.3` | 2 h | Pieza 5 · Realidad Mixta (MR) II: comprensión espacial, oclusión y planos del entorno | `scripts\sync_checkpoint.bat s3-15-start` | `s3-15-end` |
| `S3-16` | `B08.3` | 2 h | Pieza 5 · Conexión de telemetría en vivo a la experiencia XR/MR | `scripts\sync_checkpoint.bat s3-16-start` | `s3-16-end` |
| `S3-17` | `B08.4` | 2 h | Pieza 5 · Optimización móvil en Snapdragon XR2 (URP Forward, Single-Pass Instanced, 72/90 Hz) | `scripts\sync_checkpoint.bat s3-17-start` | `s3-17-end` |
| `S3-18` | `B08.4` | 2 h | Cierre B08 (Pieza 5): Empaquetado de APK autónomo y defensa en visor Meta Quest 3 | `scripts\sync_checkpoint.bat s3-18-end` | `s3-18-end` |
