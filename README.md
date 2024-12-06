# AI Profile Questionnaire

Una aplicación interactiva que ayuda a los usuarios a descubrir su perfil de uso de Inteligencia Artificial y obtener recomendaciones personalizadas para herramientas y proyectos.

## 🎯 Objetivo

Ayudar a los participantes a:
- Identificar qué herramientas de IA se adaptan mejor a su perfil
- Descubrir proyectos potenciales que pueden desarrollar
- Mejorar su capacidad para estructurar prompts efectivos
- Encontrar su camino en diferentes campos profesionales:
  - Artes visuales y diseño
  - Tecnología y ciencia
  - Negocios y gestión
  - Ciencias sociales
  - Contenido multimedia

## 🏗 Estructura del Proyecto

### Componentes
```
src/
  ├── components/
  │   ├── forms/         # Componentes de formulario reutilizables
  │   │   └── specialized/ # Formularios específicos por área
  │   ├── sections/      # Secciones principales del cuestionario
  │   │   ├── prompts/   # Componentes de evaluación de prompts por área
  │   │   └── areas/     # Componentes de áreas de aplicación por especialidad
  │   └── layout/        # Componentes de estructura y navegación
  ├── utils/             # Utilidades y funciones auxiliares
  ├── types/             # Definiciones de tipos TypeScript
  ├── store/             # Estado global con Zustand
  └── constants/         # Constantes y configuraciones
```

### Secciones del Cuestionario

#### 1. Perfil Básico
- Nivel educativo
- Área principal de interés
- Conocimiento previo sobre IA
- Formularios especializados por área:
  - Artes Visuales: estilos, herramientas, portfolio
  - Tecnología: lenguajes, frameworks, experiencia
  - Negocios: industria, automatización, análisis
  - Ciencias Sociales: métodos, herramientas, ética
  - Multimedia: tipos de contenido, plataformas

#### 2. Capacidad de Prompts
- Ejercicios específicos por área
- Evaluación contextualizada
- Feedback personalizado
- Métricas de evaluación adaptadas

#### 3. Áreas de Aplicación
- Proyectos específicos por especialidad
- Herramientas recomendadas por área
- Recursos de aprendizaje focalizados
- Guías de implementación

#### 4. Resultados y Recomendaciones
- Perfil detallado por especialidad
- Recomendaciones específicas de herramientas
- Plan de desarrollo personalizado
- Recursos adicionales por área

## 💻 Tecnologías Utilizadas

- React + TypeScript
- Tailwind CSS para estilos
- Zustand para gestión de estado
- Vite como bundler

## 🚀 Características

- Interfaz intuitiva y responsiva
- Navegación fluida entre secciones
- Evaluación especializada por área
- Recomendaciones contextualizadas
- Diseño moderno y accesible
- Formularios dinámicos especializados
- Sistema de tipos robusto
- Arquitectura modular y mantenible

## 📋 Perfiles de Usuario

### Perfil Artístico Visual
- Enfoque en artes visuales y diseño
- Herramientas: DALL-E, Midjourney, Stable Diffusion
- Evaluación de capacidades creativas
- Recomendaciones de proyectos artísticos

### Perfil Técnico/Científico
- Enfoque en desarrollo y ciencia
- Herramientas: TensorFlow, PyTorch, Scikit-learn
- Evaluación de capacidades técnicas
- Proyectos de machine learning y análisis

### Perfil Empresarial
- Enfoque en negocios y gestión
- Herramientas: Tableau, Power BI, Salesforce Einstein
- Evaluación de necesidades comerciales
- Proyectos de optimización y análisis

### Perfil Científico Social
- Enfoque en investigación social
- Herramientas: SPSS, NVivo, ATLAS.ti
- Evaluación de metodologías
- Proyectos de investigación social

### Perfil Multimedia
- Enfoque en contenido digital
- Herramientas: Runway ML, Soundraw, Synthesia
- Evaluación de producción multimedia
- Proyectos de contenido digital

## 🌟 Beneficios

- Orientación especializada por área
- Desarrollo de habilidades específicas
- Descubrimiento de herramientas relevantes
- Plan de desarrollo personalizado
- Recursos focalizados por especialidad

## 🛠 Desarrollo Local

1. Clonar el repositorio
2. Instalar dependencias:
```bash
npm install
```
3. Iniciar el servidor de desarrollo:
```bash
npm run dev
```

## 📚 Recursos Adicionales

El cuestionario incluye por área:
- Ejemplos prácticos especializados
- Ejercicios interactivos adaptados
- Guías de mejora específicas
- Recursos de aprendizaje personalizados
- Comunidad de práctica

## 🤝 Contribución

Las contribuciones son bienvenidas. Por favor:
1. Haz fork del repositorio
2. Crea una rama para tu feature
3. Envía un pull request con tus cambios

## 📝 Licencia

MIT License - siéntete libre de usar y modificar este proyecto para tus necesidades.