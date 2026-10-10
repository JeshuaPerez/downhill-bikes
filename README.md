# Downhill Bikes

Sitio multipágina sobre el downhill: las marcas que fabrican las bicicletas, los
atletas que compiten y un formulario para registrarse como rider. Está maquetado
a mano con HTML5 y CSS3, sin frameworks, sin plantillas y sin librerías.

Es un proyecto de práctica, hecho para dominar la maquetación y los elementos
nativos de HTML5 antes de pasar a JavaScript. El tema lo elegí yo: el downhill es
uno de los deportes que practico.

**Demo en vivo:** https://jeshuaperez.github.io/downhill-bikes/

## Qué contiene

| Página | Contenido |
|---|---|
| `index.html` | Qué es una bicicleta de downhill y cinco marcas (Specialized, Commencal, Canyon, Giant y Pivot), cada una con su ficha y enlace al sitio oficial |
| `pages/Atletas.html` | Cinco atletas (Loïc Bruni, Amaury Pierron, Fabio Wibmer, Luke Meier y Jenna Hastings), cada uno con video incrustado |
| `pages/Registro.html` | Formulario de inscripción de riders |

## Lo que practiqué aquí

- **HTML5 semántico**: `header`, `nav`, `main`, `section`, `article`, `footer`.
- **Video nativo** con la etiqueta `<video>`, sin reproductores externos.
- **Formularios con tipos de campo nativos**: `text`, `email`, `tel`, `url`,
  `time`, `range` y grupos de `radio`, aprovechando la validación que trae el
  navegador en lugar de escribirla a mano.
- **CSS por página**: una hoja global (`css/Estilos.css`) más una hoja propia
  para atletas y otra para el registro, en lugar de un solo archivo gigante.
- **Diseño adaptable** a pantallas de celular.

## Estructura

```
index.html           Página principal: marcas de downhill
pages/
├── Atletas.html     Atletas patrocinados, con video
└── Registro.html    Formulario de inscripción
css/
├── Estilos.css      Estilos globales
├── atletas.css      Estilos de la página de atletas
└── registro.css     Estilos del formulario
images/              Fotos de bicicletas y favicon
videos/              Clips de los atletas
```

## Cómo verlo

No necesita instalación ni servidor: clona el repositorio y abre `index.html` en
cualquier navegador.

```bash
git clone https://github.com/JeshuaPerez/downhill-bikes.git
cd downhill-bikes
```

## Nota sobre el contenido

Las imágenes de bicicletas, los videos y los nombres de marcas y atletas
pertenecen a sus respectivos dueños y se usan únicamente con fines educativos,
dentro de un ejercicio académico sin fin comercial.

---

Jeshua Pérez · [Portafolio](https://jeshuaperez.github.io/portafolio/) · [GitHub](https://github.com/JeshuaPerez)
