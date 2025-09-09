# Sobre mi

Soy desarrollador especializado en desarrollo móvil, creando
aplicaciones nativas y multiplataforma con un enfoque en rendimiento
y experiencia de usuario. Además, cuento con habilidades full stack
que me permiten trabajar tanto en el frontend como en el backend

# Detalles usados para accesibilidad

1.- Skip link: Se añadió un enlace Saltar al contenido al inicio de la página. Permite a usuarios de teclado o lectores de pantalla ir directo al <main id="contenido">. Validado con tecla Tab.

2.- Foco visible: Se definieron estilos :focus (borde naranja) en enlaces y botones para indicar visualmente dónde está el foco. Probado navegando con Tab y Shift+Tab.

3.- Navegación por teclado: Todos los elementos interactivos son nativos (<a> y <button>). No hay necesidad de div con eventos onclick, por lo que la navegación es natural con teclado (Tab, Enter, Espacio).

4.- Alt descriptivos en imágenes: Cada producto tiene un alt que describe el tipo de calzado y el modelo. Así los usuarios con lector de pantalla entienden el contenido visual.

5.- Uso prudente de aria-\*: Se usó solo cuando agrega valor:

aria-label="Menú principal" en <nav>.

aria-label="Comprar Producto X" en botones para dar contexto.

aria-labelledby en cada article para asociarlo con su título.

6.- Contraste y legibilidad: Texto negro (#222) sobre fondo blanco (#fff) con contraste de 15:1, superando el estándar WCAG AA. Se probó con WebAIM Contrast Checker y cumple con nivel AAA.
