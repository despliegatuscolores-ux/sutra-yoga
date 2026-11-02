# SŪTRA · La Práctica Viva

> *Aforismos milenarios convertidos en micro-prácticas cotidianas de desidentificación, presencia y libertad interior.*

[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-blue.svg)](index.html)
[![Offline First](https://img.shields.io/badge/Architecture-Offline--First-orange.svg)](#arquitectura-técnica)
[![Deploy with GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-violet.svg)](#despliegue-en-github-pages)

---

## 🪔 Visión del Proyecto

El estudio tradicional de los textos sapienciales corre con frecuencia el riesgo de convertirse en mera acumulación intelectual. **SŪTRA** nace con el propósito inverso: **no coleccionar conceptos, sino encarnarlos**.

Inspirada en el Raja Yoga de Patañjali (y con una arquitectura diseñada para expandirse hacia la tradición budista), esta aplicación web actúa como un santuario digital minimalista para:
1. **Aquietar las fluctuaciones mentales** (*citta-vṛtti-nirodha*).
2. **Desidentificarse del ruido psicológico** para descansar en la consciencia testigo (*Sākṣin*).
3. **Vaciar la mente de reactividad** para permitir que la serenidad esencial se manifieste en la conducta diaria.

Desarrollada bajo una filosofía de **cero dependencias externas**, funciona íntegramente en el navegador del usuario con total privacidad.

---

## ✨ Módulos Principales

### 1. El Sūtra Vivo (Integración Diaria)
* **Texto fuente y fonética:** Transliteración IAST rigurosa del aforismo sánscrito.
* **Traducción esencial:** Interpretación psicológica directa, desprovista de dogmatismos.
* **Micro-práctica conductual:** Una acción concreta, observable y medible para aplicar durante el día (en el trabajo, relaciones o momentos de fricción).
* **Racha de presencia continua:** Registro simbólico del hábito cotidiano de auto-observación (*Svādhyāya*).

### 2. Laboratorio Pratipakṣa Bhāvanā (Sūtra 2.33)
Espacio interactivo para aplicar el principio de **alquimia mental** cuando surge un pensamiento hostil, ansioso o reactivo:
* **Fase 1 (Reconocer):** Nombrar la turbulencia interna sin culpa ni represión.
* **Fase 2 (Desidentificar):** Tomar distancia situándose en la perspectiva del Testigo (*"Esto es un objeto mental observado, no quien soy"*).
* **Fase 3 (Invocar lo Opuesto):** Cultivar activamente la cualidad complementaria (*Maitrī* / bondad amorosa, *Karuṇā* / compasión, *Īśvara Praṇidhāna* / entrega confiada).

### 3. Respirador Armónico (Prāṇāyāma)
* Guía visual continua con expansión armónica geométrica.
* Patrones de respiración integrados:
  * **Sama Vṛtti** (Caja 4-4-4-4): Estabilización del sistema nervioso central.
  * **Serenidad** (4-7-8): Relajación profunda e inducción al reposo.
* **Síntesis Sonora Nativa:** Tonos de cuenco tibetano modelados matemáticamente en tiempo real con la **Web Audio API** (sin librerías de terceros ni archivos de audio externos pesados).

### 4. Diario del Testigo (*Sākṣin*)
* Bitácora contemplativa para registrar *vṛttis* (agitaciones) y actos de entrega/vaciamiento.
* Clasificación interna de obstáculos psicológicos (*Kleśas*): ignorancia básica (*Avidyā*), ego (*Asmitā*), apego (*Rāga*), aversión (*Dveṣa*) y miedo existencial (*Abhiniveśa*).
* Exportación y copia de seguridad en un clic: formatos **JSON** (datos estructurados) y **TXT** (lectura en prosa).

### 5. Compendio Filosófico
* Archivo temático estructurado por dimensiones vitales:
  * *Relaciones y conducta externa* (Yama)
  * *Alquimia interior y purificación* (Niyama)
  * *Postura, cuerpo y energía* (Āsana y Prāṇāyāma)
  * *Desidentificación y quietud profunda* (Samādhi Pāda)
* Búsqueda en tiempo real por término, concepto o término en sánscrito.

---

## 🏛️ Arquitectura Técnica

El proyecto sigue una arquitectura estricta de **cero dependencias** (*Vanilla Stack*), garantizando portabilidad absoluta, longevidad del código y rendimiento instantáneo:

| Capa | Implementación | Propósito |
|---|---|---|
| **Estructura** | HTML5 Semántico | Accesibilidad, indexación limpia y legibilidad estructural. |
| **Diseño y Estética** | CSS3 nativo (Variables CSS) | Tipografía clásica (*Cormorant Garamond* / *Inter*), temas claro/oscuro y diseño responsivo fluido sin frameworks pesados. |
| **Lógica** | JavaScript ES6+ (Modular) | Gestión reactiva de estado sin Virtual DOM. |
| **Audio** | Web Audio API | Síntesis acústica procedural mediante osciladores senoidales (`sine`) y envolventes de ganancia exponenciales. |
| **Persistencia** | `localStorage` API | Almacenamiento 100% del lado del cliente. Privacidad absoluta: ningún dato sale del dispositivo. |

---

## 🚀 Puesta en Marcha

### Uso local inmediato
No requiere Node.js, gestores de paquetes ni proceso de compilación:

```bash
# 1. Clonar el repositorio
git clone [https://github.com/](https://github.com/)<tu-usuario>/sutra-viva.git

# 2. Entrar en la carpeta
cd sutra-viva

# 3. Abrir en cualquier navegador moderno
open index.html        # En macOS
xdg-open index.html    # En Linux
start index.html       # En Windows
