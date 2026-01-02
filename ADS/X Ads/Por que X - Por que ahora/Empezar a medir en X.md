## Medición en X: Cómo funciona y qué opciones ofrece

### 1. **Soluciones de medición de X**

- X utiliza tanto soluciones propias como de terceros para ofrecer múltiples opciones de medición de alta calidad.
    
- Esto permite medir con precisión y transparencia el rendimiento de campañas publicitarias, ayudando a los anunciantes a entender cómo contribuyen a sus objetivos de marketing y negocio.
    

---

### 2. **Píxel de Twitter (X)**

- Es un código que se coloca en el sitio web para enviar datos a X.
    
- **Dos tipos de etiquetas:**
    
    - **Etiqueta universal:** Un código único para todo el sitio, que mide múltiples acciones y simplifica el seguimiento del recorrido del usuario.
        
    - **Etiqueta única (evento):** Para medir una única conversión específica (ejemplo: descarga de un libro o envío de formulario).
        
- Se recomienda usar la etiqueta universal para la mayoría de los casos.
    
- El píxel se encuentra en el administrador de X Ads en Herramientas > Seguimiento de conversiones.
    
- Si está bien implementado, el estado aparecerá como "seguimiento".
    

---

### 3. **Integración Servidor a Servidor con DoubleClick Campaign Manager (DCM)**

- X tiene integración directa solo con Google DCM.
    
- Cuando un usuario ve una impresión, se envía un enlace URL a Google para rastrear impresiones.
    
- No hay integración directa con otros socios de medición externos, pero sí se puede medir clics con soluciones de terceros.
    

---

### 4. **Proveedores de Medición Móviles (MMP)**

- Soluciones externas que recopilan y estandarizan datos de apps para medir campañas.
    
- X no ofrece SDK propio para apps, por lo que se debe usar el SDK de un proveedor MMP.
    
- Algunos MMP compatibles con X: Adjust, Appsflyer, Branch, Kochava, Singular.
    
- Se conecta el MMP con X para medir instalaciones y eventos dentro de la app.
    
- Eventos visibles en Ads Manager tras recibir datos.
    

---

### 5. **Cambios con iOS 14 y AppTrackingTransparency (ATT)**

- Apple exige permiso explícito del usuario para acceder al IDFA, afectando la precisión de medición y atribución.
    
- **Impactos:**
    
    - Disminución de usuarios identificables y dificultar la atribución.
        
    - Cambios en campañas de instalación y re-engagement de apps.
        
- **Soluciones:**
    
    - Uso de SKAdNetwork para usuarios que no autorizan seguimiento, a través de MMP integrados con X.
        
    - Límites en campañas iOS (máximo 70 grupos de anuncios simultáneos).
        
    - Audiencias que sí autorizan seguimiento siguen siendo medibles con IDFA.
        
- En campañas web, afectación a mediciones basadas en terceros, recomendación de usar rastreadores basados en redirección y verificar etiquetas JavaScript.
    

---

### 6. **Métodos de medición alternativos**

- **Atribución multitáctil (MTA):** Depende de socios externos como Neustar o VisualIQ para medir la contribución de múltiples puntos de contacto publicitarios.
    
- **Modelización de mezcla de marketing (MMM):**
    
    - Análisis estadístico que estima la influencia de cada canal publicitario en ventas.
        
    - Se realiza periódicamente para ajustar objetivos y presupuestos.
        
    - Puede hacerse internamente o con apoyo de terceros como Neustar, Kantar, Analytic Partners.
        

---

### 7. **Cómo funciona la medición por socios en X**

- X permite conectar con proveedores externos para obtener datos de medición integrados y análisis detallados.
    
- Se busca proveer transparencia y soporte para la evaluación efectiva del rendimiento publicitario.