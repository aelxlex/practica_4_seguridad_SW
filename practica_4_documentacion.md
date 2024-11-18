# Práctica No. 4 - Seguridad de Software (INF 633)
---
### Univ. Alex Laime Quispe
---
## Herramientas y técnicas de seguridad para la web

### Introducción

Las herramientas de seguridad web son soluciones diseñadas para proteger aplicaciones web contra vulnerabilidades, ataques y accesos no autorizados. Estas herramientas son esenciales para garantizar la integridad, confidencialidad y disponibilidad de la información, especialmente en un entorno donde las amenazas cibernéticas son cada vez más sofisticadas.

---

### Descripción de las Herramientas

#### **1. ModSecurity**
- **Descripción:**  
  ModSecurity es un firewall de aplicaciones web (WAF) de código abierto que protege contra una amplia variedad de amenazas a través de reglas personalizadas.

- **Características principales:**  
  - Detección y prevención de ataques en tiempo real.  
  - Integración con servidores web como Apache, Nginx e IIS.  
  - Soporte para reglas predefinidas como OWASP Core Rule Set (CRS).  

- **Ventajas:**  
  - Gratuito y de código abierto.  
  - Altamente configurable.  
  - Compatible con múltiples plataformas.  

- **Limitaciones:**  
  - Configuración inicial compleja.  
  - Requiere experiencia técnica para crear y ajustar reglas.  

---

#### **2. OWASP ZAP (Zed Attack Proxy)**
- **Descripción:**  
  OWASP ZAP es una herramienta gratuita y de código abierto para realizar pruebas de penetración en aplicaciones web. Es parte del proyecto OWASP.

- **Características principales:**  
  - Escaneo de vulnerabilidades automatizado y manual.  
  - Proxy para monitorear y manipular tráfico HTTP/HTTPS.  
  - Extensible mediante scripts y complementos.  

- **Ventajas:**  
  - Interfaz intuitiva y fácil de usar.  
  - Ideal para desarrolladores y testers con poca experiencia.  
  - Comunidad activa y soporte continuo.  

- **Limitaciones:**  
  - Escaneos avanzados pueden ser lentos.  
  - No incluye soporte técnico oficial.  

---

#### **3. Acunetix**
- **Descripción:**  
  Acunetix es una herramienta comercial de análisis de vulnerabilidades web diseñada para identificar y mitigar riesgos en aplicaciones.

- **Características principales:**  
  - Escaneo de vulnerabilidades avanzadas como SQLi y XSS.  
  - Informes detallados y fáciles de entender.  
  - Integración con herramientas de desarrollo y CI/CD.  

- **Ventajas:**  
  - Altamente precisa y confiable.  
  - Interfaz profesional y fácil de usar.  
  - Soporte técnico disponible.  

- **Limitaciones:**  
  - Costo elevado para pequeñas empresas.  
  - No es de código abierto.  

---

### Comparación

| Herramienta     | Costo               | Facilidad de uso      | Capacidades de análisis       | Escenarios de uso recomendados              |
|------------------|---------------------|-----------------------|--------------------------------|---------------------------------------------|
| ModSecurity      | Gratuito           | Moderada              | Prevención de ataques básicos | Entornos con experiencia técnica avanzada.  |
| OWASP ZAP        | Gratuito           | Alta                  | Escaneo básico y avanzado     | Entornos académicos y pruebas iniciales.    |
| Acunetix         | Comercial (Trial)  | Muy alta              | Escaneo avanzado y preciso    | Aplicaciones empresariales o críticas.      |

---

### Conclusión

Para un entorno académico o una pequeña empresa con recursos limitados, usaría **OWASP ZAP** ya que es una elección adecuada por su facilidad de uso y capacidad para realizar pruebas básicas y avanzadas.

Pero si es para una aplicación empresarial donde la seguridad es crítica,escogería **Acunetix** porque es la mejor opción debido a su precisión y soporte técnico profesional.

En caso de necesitar una solución gratuita y altamente personalizable,elegiría **ModSecurity**, siempre que se tenga del conocimiento técnico necesario para configurarla de la mejor manera.