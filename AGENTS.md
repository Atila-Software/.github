Quiero que mejores mi repositorio especial de GitHub Organization llamado `.github` para la organización `Atila-Software`.

Objetivo:
Convertir este repo en el centro de estándares de la organización para onboarding, pull requests, issues y documentación compartida.

Contexto:
- Organización: Atila Software
- Empresa de software con foco en Flutter, .NET, Node.js, SQL Server, Docker y soluciones ERP/mobile/web
- El repo `.github` debe servir para:
  1. mejorar la presentación pública de la organización,
  2. estandarizar contribuciones,
  3. ordenar PRs e issues,
  4. facilitar onboarding de nuevos desarrolladores,
  5. dejar una base profesional lista para crecer.

Quiero que generes una propuesta completa con archivos reales y contenido inicial listo para commitear.

Estructura esperada:
- `profile/README.md`
- `CONTRIBUTING.md`
- `SECURITY.md`
- `CODE_OF_CONDUCT.md`
- `.github/pull_request_template.md`
- `.github/ISSUE_TEMPLATE/bug_report.yml`
- `.github/ISSUE_TEMPLATE/feature_request.yml`
- `.github/ISSUE_TEMPLATE/config.yml`

Requisitos de contenido:

1) `profile/README.md`
- Debe presentar a Atila Software con tono profesional, claro y moderno.
- Debe explicar brevemente qué hace la empresa.
- Debe incluir una sección de tecnologías principales.
- Debe incluir una sección “How we work” o similar.
- Debe incluir una sección con tipos de repositorios o proyectos.
- Debe estar pensado para visitantes, candidatos y nuevos colaboradores.
- No inventes links que no existan. Si faltan links, deja placeholders claros tipo `TODO`.
- Escribirlo en inglés profesional.

2) `CONTRIBUTING.md`
- Debe explicar cómo contribuir a los repos.
- Debe incluir lineamientos de branches:
  - `main` protegida
  - `develop` opcional si aplica
  - `feature/...`
  - `fix/...`
  - `hotfix/...`
- Debe incluir lineamientos de commits claros.
- Debe incluir reglas para PR:
  - descripción obligatoria
  - pasos para probar
  - screenshots si aplica UI
  - revisión obligatoria
- Debe ser práctico, no demasiado largo.
- Escribirlo en inglés.

3) `SECURITY.md`
- Debe indicar cómo reportar vulnerabilidades.
- Debe sugerir no abrir issues públicos para fallas sensibles.
- Debe incluir placeholders para email o canal de contacto.
- Debe ser simple y profesional.
- Escribirlo en inglés.

4) `CODE_OF_CONDUCT.md`
- Crear una versión estándar y profesional, basada en buenas prácticas conocidas.
- No inventar políticas raras.
- Escribirlo en inglés.

5) `pull_request_template.md`
- Debe tener secciones concretas:
  - Summary
  - Why is this change needed?
  - How was this tested?
  - Screenshots / videos
  - Checklist
- El checklist debe incluir items útiles:
  - tested locally
  - no breaking changes
  - docs updated if needed
  - screenshots added if UI changed
- Debe ser corto pero exigente.

6) Issue templates YAML
- `bug_report.yml`
  - título, descripción, steps to reproduce, expected behavior, actual behavior, environment, screenshots, severity
- `feature_request.yml`
  - problema a resolver, solución propuesta, alternativas consideradas, contexto adicional, impacto
- `config.yml`
  - desactivar blank issues
  - agregar links de contacto si corresponde con placeholders

7) Estilo general
- Todo debe ser consistente en naming, tono y estructura.
- Tono profesional y limpio.
- No sobrecargar con demasiado texto.
- Priorizar utilidad real para un equipo de desarrollo.
- No agregar archivos innecesarios.

8) Salida esperada
- Quiero que generes directamente el contenido de cada archivo.
- Mostrá también un árbol final de carpetas.
- Si proponés mejoras opcionales, separalas en una sección final llamada `Optional next improvements`.

9) Importante
- No expliques teoría general de GitHub.
- No des una lista abstracta de ideas.
- Entregá archivos concretos listos para usar.
- Si asumís algo, hacelo de forma conservadora y marcá placeholders con `TODO`.