# Frontend Team Cards

Proyecto web colaborativo desarrollado como ejercicio académico de Git, flujo de ramas y diseño responsivo con Bootstrap 5.

## Objetivo del Proyecto

Crear una plataforma web sencilla y organizada que presente las tarjetas de perfil del equipo de desarrollo, permitiendo visualizar un resumen en la página principal y acceder a la información completa de cada integrante en su página individual.

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica de las páginas.
- **CSS3 / Bootstrap 5.3**: Diseño visual moderno, sistema de grid responsivo y componentes de interfaz.
- **Git & GitHub**: Control de versiones, trabajo colaborativo en equipo y flujo de ramas.

## Integrantes del Equipo

1. **Edison Andrés Chacua** (Capitán)
   - GitHub: [@Andresittow](https://github.com/Andresittow)
   - Correo: `edison.chacuaq@campusucc.edu.co`
   - Rol: Coordinación, estructura base y perfil individual.

2. **Valeria Estefanía Góngora**
   - GitHub: [@valeriagongorator](https://github.com/valeriagongorator)
   - Correo: `luzvaleria3026@hotmail.com`
   - Rol: Perfil individual y card de presentación.

3. **Julieth Vanessa Mena**
   - GitHub: [@vanessaucc](https://github.com/vanessaucc)
   - Correo: `julieth.mena@campusucc.edu.co`
   - Rol: Perfil individual y card de presentación.

## Estructura del Proyecto

```text
/
├── index.html
├── README.md
├── profiles/
│   ├── card-andres.html
│   ├── card-valeria.html
│   └── card-vanessa.html
└── assets/
    ├── andres.jpg
    ├── valeria.jpg
    └── vanessa.jpg
```

## Flujo de Ramas (Git Flow)

El proyecto sigue un flujo de trabajo colaborativo estricto:

```text
feature/card-andres ───┐
feature/card-valeria ──┼──> developer ──> main
feature/card-vanessa ──┘
```

- `main`: Rama de producción final con versiones estables y verificadas.
- `developer`: Rama de integración y revisión colaborativa.
- `feature/card-andres`: Desarrollo del perfil y card de Andrés.
- `feature/card-valeria`: Desarrollo del perfil y card de Valeria.
- `feature/card-vanessa`: Desarrollo del perfil y card de Vanessa.
