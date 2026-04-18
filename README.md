# S03--26-Equipo-29-Product-Design
Creación de un MVP Multibrand con un Design System para el area de EdTech
# 🚀 Multibrand Design System: EdTech Platform 

## 📌 Visión General
Este proyecto presenta la arquitectura y desarrollo de un **Sistema de Diseño Escalable** para una plataforma educativa. El objetivo principal fue crear una base técnica sólida que permita la convivencia de dos marcas con públicos objetivos opuestos bajo una misma estructura de componentes.

---

## 🏗️ 1. Arquitectura del Sistema
El sistema utiliza una metodología de **Tokens de Diseño**, separando la estructura lógica de la capa visual. 
- **Estructura Unificada:** Las dimensiones, jerarquías y disposición de elementos permanecen constantes.
- **Capa Visual Dinámica:** El sistema permite la inyección de estilos (color y radio de bordes) para transformar la identidad de la interfaz sin alterar el código base o la arquitectura del diseño.

## 📚 2. Biblioteca de Componentes (Figma)
La biblioteca fue construida bajo los principios de **Atomic Design**, garantizando consistencia y eficiencia:
- **Átomos:** Paletas cromáticas, tipografía (Nunito) y escalas de espaciado.
- **Moléculas:** Botones con estados (default, hover, focus), campos de entrada y etiquetas.
- **Organismos:** Tarjetas de cursos (Cards) y menús de navegación que se adaptan dinámicamente según la marca activa.

## 🎨 3. Guía de Diseño Multibrand
El sistema soporta actualmente dos marcas diferenciadas:
1. **Modern Academy (Adultos):** - *Identidad:* Profesional y sobria.
   - *Estilo:* Tonos azules y esquinas rectas ($4px$) para transmitir confianza y seriedad.
2. **Creative Kids (Niños):** - *Identidad:* Lúdica y amigable.
   - *Estilo:* Tonos naranja/coral y esquinas redondeadas ($20px$) para un entorno orgánico y cercano.

## ⚖️ 4. Gobernanza y Documentación
Para asegurar la evolución saludable del sistema, se establecieron los siguientes protocolos:
- **Centralización:** Los componentes maestros residen en una biblioteca núcleo (Componentes); cualquier cambio se replica globalmente.
- **Documentación de Uso:** Cada componente cuenta con reglas de aplicación para evitar la fragmentación visual.
- **Handoff Eficiente:** Uso de nomenclatura estandarizada en capas para facilitar la implementación por el equipo de desarrollo.

## ♿ 5. Accesibilidad e Inclusión
- **Contraste:** Selección de colores verificada bajo estándares **WCAG 2.1** para garantizar legibilidad.
- **Interacción:** La versión infantil utiliza áreas de clic más amplias y elementos visuales simplificados, facilitando la navegación para usuarios con habilidades motrices en desarrollo.

---

## 📽️ Demostración del Sistema
*(Aquí puedes insertar el enlace a tu video de Loom o un GIF del cambio de azul a naranja)*
https://www.figma.com/proto/IKvJUjYL35EWrkDUXtxsFq/WEBSITE-Modern-Academy?node-id=32-23&t=X3zNcgspz3u0TGnn-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1

## 🛠️ Herramientas Utilizadas
- **Figma:** Diseño de interfaz y prototipado avanzado (Smart Animate).
- **GitHub:** Documentación y control de versiones del sistema.
