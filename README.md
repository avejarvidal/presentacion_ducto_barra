# Instalación Eléctrica del Edificio San Petersburgo
### Presentación Técnica e Interactiva: Sistema de Ducto de Barra Vertical

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Presentaci%C3%B3n%20en%20Vivo-success?style=for-the-badge&logo=github)](https://avejarvidal.github.io/presentacion_ducto_barra/)
[![Licencia](https://img.shields.io/badge/Uso-Pedag%C3%B3gico%20%2F%20T%C3%A9cnico-blue?style=for-the-badge)](#)

Presentación interactiva y material técnico de ingeniería eléctrica enfocado en alumnos de **3° y 4° Medio (Especialidad Electricidad / Electrotecnia)**, basada en el proyecto real de edificación en altura: **Edificio San Petersburgo** (Iquique, 22 pisos, 121 departamentos), ejecutado por **Constructora Guzmán y Larraín**.

---

## 🌐 Ver la Presentación en Vivo

La presentación puede verse directamente desde cualquier navegador web en:

👉 **[https://avejarvidal.github.io/presentacion_ducto_barra/](https://avejarvidal.github.io/presentacion_ducto_barra/)**

---

## 🎯 Contenido de la Presentación

La presentación cuenta con **9 diapositivas interactivas** estructuradas pedagógicamente:

1. **Portada y Alcance**: Contexto del edificio, objetivos del suministro y cadena de distribución (Empalme, Ducto de Barra, TDA y Malla de Tierra).
2. **Recorrido de la Energía en el Edificio**: Delimitación entre la red de la empresa distribuidora (suministro 380/220 V ±10%) y la instalación interior regulada por la SEC.
3. **El Desafío del Shaft en 22 Pisos**: Análisis de ingeniería de los problemas del cableado tradicional en altura (peso, volumen de bandejas, puntos calientes y efecto chimenea ante incendios).
4. **¿De qué está hecho el Ducto de Barra?**: Exploración interactiva de componentes del sistema prefabricado Legrand (barras de aluminio compacto IP-55, unión con perno de cabeza fusible por torque a 85 Nm, abrazaderas de suspensión elástica y cajas plug-in).
5. **Ventajas frente al Cableado Convencional**: Comparativa interactiva (ahorro de sección útil en el shaft, reducción de horas-hombre en montaje, materiales libres de halógenos y confinamiento de arco eléctrico).
6. **Montaje en el Shaft Piso a Piso**: Etapas constructivas (desde tablero general, transición horizontal a vertical mediante pieza T, cajas plug-in por nivel y protocolos de EPP en obra).
7. **Protección de las Personas (con Simulador)**:
   - **Simulación interactiva de ensayo de disparo de interruptor diferencial** (rampa de corriente $I\Delta \le 30\,\text{mA}$, tiempo de disparo $t \le 300\,\text{ms}$).
   - **Simulación interactiva de medición de resistencia de puesta a tierra** ($R_e \le 20\,\Omega$ según método de caída de potencial con telurómetro).
8. **Marco Normativo Chileno**: Explicación del marco legal SEC, Decreto Supremo N°8, transición desde NCh Elec. 4/2003 a los Pliegos Técnicos Normativos (RIC N°01 al N°19).
9. **Cierre y Declaración TE1**: Documentación requerida para recepción final (Formulario TE1 firmado por Instalador SEC Clase A, protocolos de verificación inicial RIC N°19 y planos as-built).

---

## 📂 Estructura del Repositorio

El repositorio está organizado de forma modular y estandarizada:

```
presentacion_ducto_barra/
├── index.html                                 # Punto de entrada web principal para GitHub Pages
├── Proyecto San Petersburgo.dc.html           # Copia original compatible con Design Canvas
├── deck-stage.js                             # Componente web de navegación y presentación
├── image-slot.js                             # Componente web para contenedores de imagen
├── support.js                                # Runtime reactivo de la presentación
├── .nojekyll                                 # Archivo de configuración para GitHub Pages
│
├── uploads/                                  # Imágenes y recursos gráficos de la presentación
│   ├── cropped-logo (1).png                  # Logo oficial Guzmán & Larraín Empresas
│   ├── pasted-1788476353225-0.png            # Render arquitectónico del Edificio San Petersburgo
│   ├── pasted-1788472594551-0.png            # Isométrico 3D AutoCAD del shaft y ducto de barra
│   └── pasted-1788472616138-0-mtm2f2si-2qhn.png # Detalle de ingreso horizontal y transición
│
├── documentos/                               # Planos de ingeniería e informes técnicos reales
│   ├── README.md                             # Índice detallado de la documentación técnica
│   ├── planos/                               # Planos en formato DWG (AutoCAD) y PDF
│   │   ├── Est_DB_ed_San_Petersburgo_rev_B.dwg         # Plano matriz CAD del ducto de barra
│   │   ├── Est_DB_ed_San_Petersburgo_rev_B_Lamina1.pdf # Lámina 1: Vista isométrica y elevación
│   │   ├── Est_DB_ed_San_Petersburgo_rev_B_Lamina2.pdf # Lámina 2: Detalles de soporte y montaje
│   │   └── Est_DB_ed_San_Petersburgo_rev_B_Lamina3.pdf # Lámina 3: Cajas plug-in y tableros
│   └── informes/                             # Informes técnicos y memorias de cálculo
│       ├── Informe_Puesta_a_Tierra_San_Petersburgo.pdf # Estudio y medición de malla de tierra
│       └── Informe_Verificacion_Inicial_PANQARA.pdf    # Informe de verificación inicial RIC N°19 SEC
│
└── .github/
    └── workflows/
        └── deploy.yml                        # Flujo automatizado de despliegue en GitHub Pages
```

---

## ⌨️ Controles de Navegación

Durante la presentación interactiva puedes utilizar:

| Acción | Control / Tecla |
| :--- | :--- |
| **Avanzar diapositiva** | `→` (Flecha derecha), `↓` (Flecha abajo), `Espacio` o `AvPág` |
| **Retroceder diapositiva** | `←` (Flecha izquierda), `↑` (Flecha arriba) o `RePág` |
| **Reiniciar al inicio** | Tecla `R` o `Inicio` |
| **Ir al final** | Tecla `Fin` |
| **Pantalla completa** | Botón **⛶ Ver en pantalla completa** o tecla `F11` |
| **Interacciones en pantalla** | Clic en botones, piezas del ducto, etapas y simuladores |
| **Dispositivos táctiles** | Toque en mitad derecha para avanzar, mitad izquierda para retroceder |

---

## 🚀 Cómo Activar GitHub Pages en el Repositorio

Si aún no has activado GitHub Pages en tu repositorio, sigue estos sencillos pasos:

1. Ingresa a tu repositorio en GitHub: `https://github.com/avejarvidal/presentacion_ducto_barra`.
2. Haz clic en **Settings** (Configuración) en la barra superior.
3. En el menú lateral izquierdo, selecciona **Pages**.
4. En **Build and deployment**:
   - **Source**: Selecciona `Deploy from a branch`.
   - **Branch**: Selecciona `main` y carpeta `/ (root)`.
   - Haz clic en **Save**.
5. ¡Listo! En unos instantes la presentación estará activa y accesible públicamente en `https://avejarvidal.github.io/presentacion_ducto_barra/`.
