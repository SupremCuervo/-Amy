# 🙌 Contribuir a Amy — Guía para colaboradores

Gracias por tu interés en contribuir a **Amy**.  
Este documento explica cómo colaborar de forma eficaz y amable con el proyecto.

---

## 🙏 Valores de la contribución

- Respeto: tratamos las contribuciones con consideración y gratitud.  
- Claridad: busca claridad en código y documentación.  
- Educación: enseñamos mientras recibimos contribuciones.  
- Pequeños pasos: PRs pequeños y bien explicados se aceptan más rápido.

---

## 🧭 ¿Cómo empezar?

1. **Fork** este repositorio y clona tu fork localmente:
   ```bash
   git clone https://github.com/SupremCuervo/-Amy.git
   
2. **Crea una rama con una breve descripción:**

```bash
Copiar código
git checkout -b feat/mi-cambio
```
**3. Implementa tu cambio, añade tests y documentación.
4. Haz commit y push a tu fork:**
```bash
Copiar código
git add .
git commit -m "Descripción corta del cambio"
git push origin feat/mi-cambio
```
**5. Abre un Pull Request (PR) desde tu fork hacia main explicando:**
Qué problema resuelve.
Cómo probarlo.
Impactos conocidos.

**🧪 Tests y calidad**
Añade tests automáticos para cambios lógicos (unitarios o de integración).
Sigue las reglas de estilo del proyecto (se incluirá un formatter y linter pronto).
Los PRs deberán pasar CI antes de fusionarse.

**📚 Tipos de contribuciones bienvenidas**
Corrección de bugs y mejoras pequeñas.
Nuevas características en el compilador o herramientas.

Ejemplos y documentación (muy importantes).

Tests, scripts de build y configuración de CI/CD.
Diseño, iconografía, y assets (logos, etc.).
Traducciones y ejemplos en otros idiomas.

**🧾 Issues y solicitudes**
Antes de trabajar en algo grande, abre un Issue describiendo la idea.
Para features grandes, preferimos un RFC (documento corto con propósito, diseño y ejemplo).

**🧑‍⚖️ Revisión de PRs**
Los mantenedores revisarán PRs en orden y con cortesía.
Pueden pedir cambios; responde puntualmente en el PR.
Aceptamos PRs pequeños más rápido; los cambios grandes pueden requerir discusión.

**🛡️ Seguridad y divulgación responsable**
No publiques vulnerabilidades en Issues públicos. Usa SECURITY.md para reportes privados.

Si encuentras un fallo de seguridad, contacta a amy.languagecontact@gmail.com.

**🏷️ Contribución de código: licencia y autoría**
Al contribuir aceptas que tu contribución se publique bajo la Licencia MIT con atribución extendida del proyecto.
Si deseas ser reconocido explícitamente, indícalo en el PR (aparecerá en el historial del commit).

**🧩 Comunicación**
Usa Issues para problemas técnicos.

Para discusiones generales, usa la sección Discussions o el canal oficial (si existe).

Respeta el CODE_OF_CONDUCT.md en todo momento.

⚙️ Entorno de desarrollo recomendado (breve)
Git >= 2.x
Node / Python / Rust (según módulo) — las instrucciones de setup aparecerán en docs/DEV_SETUP.md.
Editor: VS Code con extensiones recomendadas (linter, formatter).
<div align="center">
Gracias por querer colaborar. ¡Amy florece con la comunidad! 🌸
</div>
