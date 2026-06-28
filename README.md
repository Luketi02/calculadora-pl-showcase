# 🚀 Calculadora PL: Optimización y Programación Lineal

Un sistema integral diseñado para la resolución, análisis y estudio pedagógico de problemas de Programación Lineal. Desarrollado con un enfoque estricto en la precisión matemática y la experiencia del usuario, evitando las limitaciones y los errores de redondeo de las calculadoras genéricas.

## 🛠️ Stack Tecnológico
* **Frontend / Framework:** Flutter (Dart).
* **Arquitectura:** Diseño reactivo basado en estado.
* **Lógica de Negocio:** Motor algorítmico propio desarrollado desde cero para el manejo de matrices Simplex y geometría analítica.
* **Persistencia:** Almacenamiento local optimizado mediante `SharedPreferences`, con control estricto de privacidad y gestión de historial por parte del usuario.

## ✨ Características Principales
* **Triple Motor de Resolución:** * Soporte completo para el **Método Gráfico** (renderizado de polígonos de áreas factibles).
  * **Método Analítico** (evaluación de vértices).
  * **Método Simplex** (incluyendo el manejo automatizado de la Gran M para minimización y maximización).
* **Precisión Absoluta (Zero-Decimal):** Motor matemático construido sobre una clase personalizada de fracciones exactas utilizando el algoritmo de Euclides para el Máximo Común Divisor (MCD). Garantiza cero errores de arrastre y una lectura matemática limpia.
* **Enfoque Pedagógico (Paso a Paso):** El sistema elimina el concepto de "caja negra". Documenta la estandarización del modelo inicial y detalla explícitamente las operaciones matriciales de Gauss-Jordan fila por fila.
* **Diagnósticos Académicos Avanzados:** Capacidad algorítmica para detectar, interceptar e informar anomalías matemáticas complejas:
  * Sistemas Infactibles (falsa optimalidad).
  * Soluciones No Acotadas (crecimiento infinito).
  * Soluciones Degeneradas.
  * Múltiples Soluciones Óptimas.
* **Calculadora Reactiva de Renglones Simplex:** Un submódulo dinámico de operaciones matriciales en tiempo real. Cuenta con manejo de excepciones silencioso para acompañar al estudiante en la práctica manual sin interrupciones.
* **Análisis de Sensibilidad (Post-Óptimo):** Interpretación económica de los recursos, traduciendo variables matemáticas en lógicas de negocio, como Precios Sombra y holguras.

## 📌 Estado del Proyecto
**Versión Actual:** 1.0.0 (Producción)
El motor algorítmico se encuentra 100% operativo y optimizado. Ha superado con éxito rigurosas pruebas de estrés académico, resolviendo correctamente escenarios de falsa optimalidad y degeneración.

## 📲 Instalación de la app
**Próximamente en AppsTore y PlayStore**
La app se subirá a las respectivas tiendas en su momento luego de finalizar algunos detalles.

---

## 👨‍💻 Autor

**Lucas Juan Miño**
* 🎓 **Perfil:** Profesor Universitario en Computación (POO) | Analista en Sistemas | Estudiante avanzado de la Licenciatura en Sistemas de Información.
* 📍 **Ubicación:** Posadas, Misiones, Argentina.
* 💼 **Contacto:** https://www.linkedin.com/in/lucas-juan-mi/ | lucas.mino1508@gmail.com

---

> **Aviso de Propiedad Intelectual 🔒**
> El código fuente de esta aplicación se mantiene en un repositorio privado por motivos académicos y profesionales. Este espacio funciona exclusivamente como documentación, portafolio y demostración arquitectónica del software.
