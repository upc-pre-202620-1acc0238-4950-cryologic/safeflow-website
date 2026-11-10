# SafeFlow

Landing page de **SafeFlow**, una propuesta de plataforma para monitorear y controlar la cadena de frío. El sitio presenta cómo centralizar el seguimiento de temperatura y trazabilidad de productos sensibles durante su almacenamiento y transporte.

## ¿Qué busca resolver?

Una excursión de temperatura puede ocasionar pérdidas de productos y dificultar el cumplimiento de auditorías. SafeFlow propone ayudar a farmacias, laboratorios, empresas de alimentos, operadores logísticos y almacenes mediante monitoreo continuo y alertas oportunas.

## Contenido del sitio

- Presentación de la propuesta de valor y del producto.
- Características como monitoreo en tiempo real, alertas, inventario y reportes de trazabilidad.
- Explicación del flujo de uso y beneficios.
- Planes de referencia y sectores a los que se dirige.
- Sección del equipo, preguntas frecuentes y contacto.
- Selector de idioma español e inglés.

> **Nota:** Este repositorio contiene el sitio de presentación. Los enlaces a la demo llevan a una aplicación externa y la página de pago es referencial; la pasarela de pago aún no está integrada. El formulario de contacto prepara un correo para `contacto@safeflow.pe` mediante la aplicación de correo configurada en el dispositivo.

## Equipo

Somos estudiantes de Ingeniería de Software y desarrollamos esta propuesta como equipo:

- **Jefferson Bayron Morales Yapuchura** — Ingeniero de Software
- **Andy Alejandro Mio Mejía** — Ingeniero de Software
- **Sebastian Alonso Bustinza Muñoz** — Ingeniero de Software
- **Abraam Bernabe Acosta Elera** — Ingeniero de Software

## Tecnologías

- HTML5
- CSS3
- JavaScript

El proyecto es un sitio estático y no requiere instalar dependencias de Node.js.

## Cómo ejecutarlo

1. Clona el repositorio o descarga sus archivos.
2. Abre `index.html` en un navegador.

También puedes abrir la carpeta en Visual Studio Code y usar una extensión como **Live Server** para trabajar con recarga automática.

Se necesita conexión a internet para cargar las fuentes de Google Fonts, los videos de YouTube y los enlaces externos a la demo.

## Estructura del proyecto

```text
.
├── index.html           # Landing page principal
├── pago.html            # Página informativa del flujo de pago
├── css/
│   └── style.css        # Estilos y diseño adaptable
├── javascript/
│   ├── i18n.js          # Textos en español e inglés
│   └── script.js        # Interacciones de la página
├── img/                 # Logos, fotografías e ilustraciones
└── public/
    └── fonts/           # Archivos de fuentes e iconos
```

