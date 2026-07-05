---
layout: bare
title: "AuraEat — Privacy Policy / Política de Privacidad"
permalink: /auraeat/privacy-policy/
---

---

> 🇬🇧 **English version below** · 🇪🇸 [Versión en español más abajo](#política-de-privacidad-es)

---

# Privacy Policy

**AuraEat**  
_Effective Date: 21 May 2026_  
_Last Updated: 21 May 2026_

---

## 1. Introduction

AuraEat is a personal wellness app that aligns your eating window with your biological rhythms using biometric data from Apple HealthKit and AI-powered food analysis. The App is developed and operated by **Jan-Erik Sternberg**, an individual developer ("I", "me", or "my"). No company is registered in connection with this App.

This Privacy Policy describes how I collect, use, store, and protect your information when you use the AuraEat mobile application (the "App"). By using the App, you agree to the practices described in this policy.

---

## 2. Information I Collect

### 2.1 Apple HealthKit Data

With your explicit permission, the App reads the following data from Apple HealthKit:

- **Sleep Analysis** — sleep duration, sleep stages, and quality metrics to determine your actual wake-up and bedtime.
- **Heart Rate** — average beats per minute (BPM) to assess cardiovascular recovery.
- **Heart Rate Variability (HRV)** — millisecond-level variability data to compute metabolic readiness.
- **Resting Heart Rate** — daily resting heart rate to detect elevated stress or recovery states.

With your explicit permission, the App writes the following data to Apple HealthKit:

- **Water Intake** — hydration entries logged within the App, so your data stays consistent across Health-connected apps.

**I do not access any HealthKit data categories beyond those listed above.**

### 2.2 Data You Provide Directly

- **Food photos** — images you capture or select for AI-based nutritional grading.
- **Manual meal logs** — descriptions, grades, and timestamps for meals you log manually.
- **Hydration entries** — beverage type, volume, and timestamps.
- **Sleep questionnaire answers** (PSQI / ISI) — used solely to calibrate your eating window. These are wellness self-assessments, not clinical evaluations.
- **App settings** — language preference, wake/bedtime overrides, and hydration goals.

### 2.3 Data I Do NOT Collect

- I do **not** collect your name, email address, phone number, or other personal contact information through the App.
- I do **not** collect location data.
- I do **not** use advertising identifiers or tracking technologies.
- I do **not** collect device identifiers for the purpose of user tracking.

---

## 3. How I Use Your Information

All data collected is used exclusively to provide core App functionality:

| Data | Purpose |
|------|---------|
| Sleep Analysis | Calculate your personalised daily eating window |
| Heart Rate & HRV | Compute your Aura Score — a metabolic readiness metric that fine-tunes eating window timing |
| Resting Heart Rate | Detect recovery state and adjust eating window |
| Food Photos | AI-powered nutritional grading (glycemic load and circadian impact) |
| Meal Logs | Meal-sleep correlation analysis to discover your optimal last-meal-to-bedtime gap |
| Hydration Entries | Track daily water intake and sync to Apple Health |
| Sleep Questionnaire | Calibrate Aura Score baseline before HealthKit data accumulates |

**I do not use your health data for advertising, marketing, data mining, or any purpose other than providing the App's core wellness features.**

---

## 4. Third-Party Services

### 4.1 Groq AI

The App uses **Groq**, a third-party AI inference service, for two features:

1. **Food Photo Grading** — Your food photos are compressed and sent to Groq's API for nutritional analysis. No personally identifiable information is attached to these images.

2. **Daily Wellness Insights** — Aggregated, anonymised biometric values (sleep score, HRV, resting heart rate as numerical values only) are sent to generate personalised wellness suggestions.

**What is NOT sent to Groq:**
- Your name or any personal identifiers
- Raw HealthKit data or Apple Health records
- Your location, device identifiers, or contact information
- Historical health data — only the current day's aggregated metrics

Groq processes data pursuant to their own privacy policy. I configure prompts to minimise data exposure.

### 4.2 Apple HealthKit

HealthKit data is accessed through Apple's secure framework. In compliance with Apple's guidelines:

- **HealthKit data is never shared with third parties** for advertising or data-brokering purposes.
- **HealthKit data is never sold.**
- **HealthKit data is never used for purposes unrelated** to the App's health and fitness functionality.
- **HealthKit data is not stored in any cloud service** by the App.

### 4.3 No Other Third-Party Data Sharing

Beyond the limited data sent to Groq as described above, I do not share, sell, rent, or otherwise disclose your personal or health data to any third party.

---

## 5. Data Storage and Security

### 5.1 Local-First Architecture

All your data is stored **locally on your device**. This includes:

- Cached HealthKit snapshots (up to 60 days)
- Food scan history and grades
- Meal-sleep correlation history (up to 60 days)
- Streak and badge progress
- Hydration logs
- App settings and preferences

### 5.2 No Cloud Storage

The App does **not** upload your health data, food logs, or biometric information to any cloud server or remote database. Your data stays on your device.

### 5.3 Security Measures

- All data remains on-device within the App's sandboxed storage.
- HealthKit data is accessed through Apple's secure, permissioned framework.
- Food images sent to Groq are compressed and transmitted over encrypted HTTPS connections.
- The App does not implement user tracking.

---

## 6. Data Retention and Deletion

- **HealthKit cache**: Up to 60 days, automatically managed.
- **Meal-sleep correlation history**: Up to 60 days, automatically pruned.
- **Food scan logs**: Retained until you clear them.
- **All data can be deleted** at any time through Settings → "Clear Data", which permanently removes all locally stored data.
- **Uninstalling the App** removes all App data from your device.
- HealthKit data written by the App (water intake) can be managed through Apple's Health app.

---

## 7. Children's Privacy

AuraEat is not directed at children under the age of 16. I do not knowingly collect personal or health data from minors. If you believe a child has used the App, please contact me and I will take appropriate action.

---

## 8. Your Rights

You have full control over your data:

- **HealthKit Permissions** — Grant or revoke at any time via Settings → Health → AuraEat.
- **Data Deletion** — Delete all App data at any time from the Settings screen.
- **Opt Out of AI Features** — You may choose not to use the food scanner or AI insights; the core eating window functionality operates using only local HealthKit data.

### GDPR Rights (EEA / Spain)

If you are located in the European Economic Area — including Spain — you have the following rights under the **General Data Protection Regulation (GDPR, Regulation (EU) 2016/679)** and Spain's **Ley Orgánica 3/2018 de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD)**:

- **Right of access** — Request a copy of the data held about you.
- **Right to rectification** — Request correction of inaccurate data.
- **Right to erasure** — Request deletion of your data ("right to be forgotten").
- **Right to restriction of processing** — Request that processing be limited.
- **Right to data portability** — Receive your data in a machine-readable format.
- **Right to object** — Object to processing based on legitimate interests.

The **legal basis for processing** health data (a special category under Art. 9 GDPR) is your **explicit consent**, which you give during the onboarding process and can withdraw at any time.

To exercise any of these rights, contact me at the address below. You also have the right to lodge a complaint with the **Agencia Española de Protección de Datos (AEPD)** at [www.aepd.es](https://www.aepd.es).

---

## 9. Changes to This Privacy Policy

I may update this Privacy Policy from time to time. When I do, I will revise the "Last Updated" date at the top of this page. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 10. Contact

**Jan-Erik Sternberg**  
Email: [janerik.sternberg@alumni.esade.edu](mailto:janerik.sternberg@alumni.esade.edu)

---

_AuraEat is a wellness app, not a medical device. It does not diagnose, treat, or replace professional medical advice._

---
---

<a name="política-de-privacidad-es"></a>

> 🇪🇸 **Versión en español** · 🇬🇧 [English version above](#privacy-policy)

---

# Política de Privacidad

**AuraEat**  
_Fecha de entrada en vigor: 21 de mayo de 2026_  
_Última actualización: 21 de mayo de 2026_

---

## 1. Introducción

AuraEat es una aplicación personal de bienestar que alinea tu ventana de alimentación con tus ritmos biológicos, utilizando datos biométricos de Apple HealthKit y análisis de alimentos con inteligencia artificial. La aplicación ha sido desarrollada y es operada por **Jan-Erik Sternberg**, como desarrollador individual ("yo" o "mi"). No existe ninguna empresa registrada en relación con esta aplicación.

Esta Política de Privacidad describe cómo recopilo, utilizo, almaceno y protejo tu información cuando usas la aplicación móvil AuraEat (la "App"). Al utilizar la App, aceptas las prácticas descritas en esta política.

---

## 2. Información que recopilo

### 2.1 Datos de Apple HealthKit

Con tu permiso explícito, la App lee los siguientes datos de Apple HealthKit:

- **Análisis del sueño** — duración del sueño, fases y métricas de calidad para determinar tu hora real de despertar y de acostarte.
- **Frecuencia cardíaca** — pulsaciones por minuto (BPM) para evaluar la recuperación cardiovascular.
- **Variabilidad de la frecuencia cardíaca (VFC/HRV)** — variabilidad en milisegundos para calcular tu preparación metabólica.
- **Frecuencia cardíaca en reposo** — frecuencia diaria en reposo para detectar estados de estrés o recuperación.

Con tu permiso explícito, la App escribe los siguientes datos en Apple HealthKit:

- **Ingesta de agua** — entradas de hidratación registradas en la App, para que tus datos sean consistentes con otras apps conectadas a Salud.

**No accedo a ninguna categoría de datos de HealthKit más allá de las indicadas.**

### 2.2 Datos que tú proporcionas directamente

- **Fotos de alimentos** — imágenes que capturas o seleccionas para el análisis nutricional con IA.
- **Registros manuales de comidas** — descripciones, notas y horarios de comidas que introduces manualmente.
- **Registros de hidratación** — tipo de bebida, volumen y hora.
- **Respuestas al cuestionario de sueño** (PSQI / ISI) — utilizadas únicamente para calibrar tu ventana de alimentación. Son autoevaluaciones de bienestar, no evaluaciones clínicas.
- **Ajustes de la App** — preferencia de idioma, horas de despertar/acostarse, y objetivos de hidratación.

### 2.3 Datos que NO recopilo

- No recopilo tu nombre, dirección de correo electrónico, número de teléfono ni ninguna otra información de contacto personal a través de la App.
- No recopilo datos de ubicación.
- No utilizo identificadores publicitarios ni tecnologías de seguimiento.
- No recopilo identificadores de dispositivo con fines de seguimiento de usuarios.

---

## 3. Cómo utilizo tu información

Todos los datos recopilados se usan exclusivamente para proporcionar las funcionalidades principales de la App:

| Dato | Finalidad |
|------|-----------|
| Análisis del sueño | Calcular tu ventana de alimentación diaria personalizada |
| Frecuencia cardíaca y VFC | Calcular tu Puntuación Aura — métrica de preparación metabólica que ajusta el horario de tu ventana |
| Frecuencia cardíaca en reposo | Detectar el estado de recuperación y ajustar la ventana |
| Fotos de alimentos | Calificación nutricional con IA (carga glucémica e impacto circadiano) |
| Registros de comidas | Análisis de correlación comida-sueño para encontrar tu intervalo óptimo antes de acostarte |
| Registros de hidratación | Seguimiento de la ingesta diaria de agua y sincronización con Apple Salud |
| Cuestionario de sueño | Calibrar el Puntuación Aura inicial antes de que se acumulen datos de HealthKit |

**No utilizo tus datos de salud para publicidad, marketing, minería de datos ni ninguna finalidad ajena a las funcionalidades principales de la App.**

---

## 4. Servicios de terceros

### 4.1 Groq AI

La App utiliza **Groq**, un servicio de inferencia de inteligencia artificial de terceros, para dos funciones:

1. **Calificación de fotos de alimentos** — Las fotos de alimentos se comprimen y se envían a la API de Groq para su análisis nutricional. No se adjunta ninguna información de identificación personal a estas imágenes.

2. **Recomendaciones diarias de bienestar** — Se envían valores biométricos agregados y anonimizados (puntuación de sueño, VFC, frecuencia cardíaca en reposo como valores numéricos únicamente) para generar sugerencias personalizadas.

**Lo que NO se envía a Groq:**
- Tu nombre ni ningún identificador personal
- Datos brutos de HealthKit ni registros de Apple Salud
- Tu ubicación, identificadores de dispositivo ni información de contacto
- Datos históricos de salud — solo las métricas agregadas del día en curso

Groq trata los datos conforme a su propia política de privacidad. Configuro los prompts para minimizar la exposición de datos.

### 4.2 Apple HealthKit

El acceso a los datos de HealthKit se realiza a través del framework seguro de Apple. En cumplimiento de las directrices de Apple:

- **Los datos de HealthKit nunca se comparten con terceros** con fines publicitarios ni de intermediación de datos.
- **Los datos de HealthKit nunca se venden.**
- **Los datos de HealthKit nunca se utilizan para fines ajenos** a las funcionalidades de salud y bienestar de la App.
- **Los datos de HealthKit no se almacenan en ningún servicio en la nube** por parte de la App.

### 4.3 Sin otras transferencias a terceros

Más allá de los datos limitados enviados a Groq descritos anteriormente, no comparto, vendo, alquilo ni divulgo de ninguna otra forma tus datos personales o de salud a ningún tercero.

---

## 5. Almacenamiento y seguridad de datos

### 5.1 Arquitectura local

Todos tus datos se almacenan **localmente en tu dispositivo**. Esto incluye:

- Instantáneas de HealthKit en caché (hasta 60 días)
- Historial de escaneos de alimentos y calificaciones
- Historial de correlación comida-sueño (hasta 60 días)
- Progreso de rachas e insignias
- Registros de hidratación
- Ajustes y preferencias de la App

### 5.2 Sin almacenamiento en la nube

La App **no** sube tus datos de salud, registros de alimentos ni información biométrica a ningún servidor en la nube ni base de datos remota. Tus datos permanecen en tu dispositivo.

### 5.3 Medidas de seguridad

- Todos los datos permanecen en el almacenamiento protegido (sandbox) de la App en tu dispositivo.
- El acceso a los datos de HealthKit se realiza a través del framework seguro y con permisos de Apple.
- Las imágenes de alimentos enviadas a Groq se comprimen y transmiten mediante conexiones HTTPS cifradas.
- La App no implementa seguimiento de usuarios.

---

## 6. Conservación y eliminación de datos

- **Caché de HealthKit**: Hasta 60 días, gestionado automáticamente.
- **Historial de correlación comida-sueño**: Hasta 60 días, con eliminación automática.
- **Registros de escaneos de alimentos**: Conservados hasta que los elimines.
- **Todos los datos pueden eliminarse** en cualquier momento desde Ajustes → "Borrar datos", lo que elimina permanentemente todos los datos almacenados localmente.
- **Desinstalar la App** elimina todos los datos de la App de tu dispositivo.
- Los datos de HealthKit escritos por la App (ingesta de agua) pueden gestionarse directamente desde la app Salud de Apple.

---

## 7. Privacidad de menores

AuraEat no está dirigida a menores de 16 años. No recopilo conscientemente datos personales o de salud de menores. Si crees que un menor ha utilizado la App, contáctame y tomaré las medidas oportunas.

---

## 8. Tus derechos

Tienes control total sobre tus datos:

- **Permisos de HealthKit** — Concede o revoca el acceso en cualquier momento en Ajustes → Salud → AuraEat.
- **Eliminación de datos** — Elimina todos los datos de la App en cualquier momento desde la pantalla de Ajustes.
- **Exclusión de funciones de IA** — Puedes optar por no usar el escáner de alimentos ni las recomendaciones de IA; la funcionalidad principal de la ventana de alimentación opera únicamente con datos locales de HealthKit.

### Derechos según el RGPD y la LOPDGDD

Si te encuentras en el Espacio Económico Europeo — incluyendo España — tienes los siguientes derechos al amparo del **Reglamento General de Protección de Datos (RGPD, Reglamento (UE) 2016/679)** y la **Ley Orgánica 3/2018, de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD)**:

- **Derecho de acceso** — Solicitar una copia de los datos que conservo sobre ti.
- **Derecho de rectificación** — Solicitar la corrección de datos inexactos.
- **Derecho de supresión** — Solicitar la eliminación de tus datos ("derecho al olvido").
- **Derecho a la limitación del tratamiento** — Solicitar que el tratamiento sea restringido.
- **Derecho a la portabilidad** — Recibir tus datos en un formato legible por máquina.
- **Derecho de oposición** — Oponerte al tratamiento basado en intereses legítimos.

La **base jurídica para el tratamiento** de datos de salud (categoría especial conforme al Art. 9 RGPD) es tu **consentimiento explícito**, que otorgas durante el proceso de incorporación y puedes retirar en cualquier momento.

Para ejercer cualquiera de estos derechos, contáctame en la dirección indicada a continuación. Asimismo, tienes derecho a presentar una reclamación ante la **Agencia Española de Protección de Datos (AEPD)** en [www.aepd.es](https://www.aepd.es).

---

## 9. Cambios en esta Política de Privacidad

Puedo actualizar esta Política de Privacidad ocasionalmente. Cuando lo haga, actualizaré la fecha de "Última actualización" en la parte superior de esta página. El uso continuado de la App tras los cambios implica la aceptación de la política actualizada.

---

## 10. Contacto

**Jan-Erik Sternberg**  
Correo electrónico: [janerik.sternberg@alumni.esade.edu](mailto:janerik.sternberg@alumni.esade.edu)

---

_AuraEat es una aplicación de bienestar, no un producto sanitario. No diagnostica, trata ni sustituye el consejo médico profesional._
