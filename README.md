# 📅 Calendario Escolar 2025  

**Proyecto:** Calendario Escolar Interactivo y Responsivo  
**Institución:** Unidad Educativa *Juana Azurduy De Padilla*  
**Año:** 2025  

Este proyecto fue desarrollado como una herramienta digital para consultar de forma rápida y atractiva **todas las fechas, eventos y actividades importantes del año escolar**.  
El diseño está optimizado para distintos dispositivos y cuenta con un moderno **modo oscuro (Dark Mode)**.

---

## ✨ Características Destacadas  

- **📱 Diseño Responsivo (Mobile-First):**  
  Experiencia de usuario consistente en celulares, tablets y computadoras, usando *Media Queries* de CSS.  

- **🌙 Tema Oscuro Moderno:**  
  Uso de variables CSS personalizadas para un esquema visual atractivo (`--fondo`, `--primario`, `--secundario`).  

- **⏳ Contador Regresivo Dinámico:**  
  Muestra el número exacto de días restantes hasta el próximo evento importante.  

- **💬 Interactividad con Modal:**  
  Al hacer clic en una fecha, se despliega un modal con la descripción detallada del evento.  

- **🧩 Componentes Modulares:**  
  - Tabla de Fechas (`#tabla-fechas`)  
  - Tarjetas de Actividades (`#cards-actividades`)  
  - Sección de Creadores  

---

## 🛠️ Tecnologías Utilizadas  

| Tecnología | Propósito |
|-------------|------------|
| **HTML5** | Estructura semántica del contenido |
| **CSS3** | Estilos, animaciones y diseño responsivo (Flexbox y Media Queries) |
| **JavaScript (ES6)** | Lógica de la aplicación, contador y gestión del modal |
| **Google Fonts (Poppins)** | Tipografía moderna y legible |

---

## 🚀 Instalación y Ejecución  

1. **Clona o descarga** este repositorio:  
   ```bash
   git clone https://github.com/usuario/calendario-escolar-2025.git

    Abre el archivo index.html en tu navegador.

    Asegúrate de que las imágenes de los creadores estén en el mismo directorio o en la carpeta imagenes/ con rutas correctas, por ejemplo:

    <img src="imagenes/imagen-carlos.jpg" alt="Carlos Silva">

⚙️ Estructura del Proyecto

📦 calendario-escolar-2025/
├── index.html      # Estructura principal
├── style.css       # Estilos, variables y media queries
├── script.js       # Lógica del contador, modal y carga de datos
└── imagenes/       # Fotos o íconos de los creadores

📝 Edición y Personalización

Para añadir o modificar eventos, edita el array fechas en script.js:

// script.js
const fechas = [
  { 
    fecha: "2/3/2025", 
    evento: "Inicio de Clases", 
    tipo: "Escolar", 
    descripcion: "Inicio oficial del año lectivo." 
  },
  { 
    fecha: "3/19/2025", 
    evento: "Día del Padre", 
    tipo: "Conmemorativo", 
    descripcion: "Celebración institucional por el Día del Padre." 
  },
  // Agrega más eventos aquí...
];

👥 Equipo de Desarrollo
Rol	Nombre
🧭 Product Owner	Isaura Cárdenas
⚙️ Scrum Master	Antonio Saavedra
💻 Desarrollador Frontend	Carlos Silva
💻 Desarrollador Frontend	Isaac Rodríguez
💻 Desarrollador Frontend	Ricardo Gareca
📜 Créditos

© 2025 Unidad Educativa Juana Azurduy De Padilla
Proyecto: Taller Ágil - Scrum
Desarrollado con dedicación y trabajo en equipo por:
Isaac Rodríguez, Ricardo Gareca, Antonio Saavedra, Isaura Cárdenas y Carlos Silva.
