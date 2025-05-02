# ArchitectureBench

**Comparativa estructurada entre MVVM, VIPER y Clean Architecture aplicada a un mismo flujo.**

`ArchitectureBench` permite visualizar, implementar y analizar tres arquitecturas móviles en un mismo caso de uso. Ideal para debates técnicos, capacitaciones y validaciones arquitectónicas.

---

## Propósito

- Evaluar ventajas y compromisos de distintas arquitecturas.
- Visualizar su impacto sobre testabilidad, legibilidad y escalabilidad.
- Fomentar análisis técnico sobre patrones de diseño.

---

## Contenido

- Implementaciones completas en MVVM, VIPER y Clean Architecture.
- Casos de uso idénticos con separación clara de capas.
- Utilización de dependencias comunes para comparación justa.
- Documentación con principios aplicados y decisiones técnicas.

---

## Pruebas

| Arquitectura   | Cobertura de prueba   |
|----------------|------------------------|
| MVVM           | Unitarias y de integración |
| VIPER          | Unitarias y mocks      |
| Clean Arch     | Unitarias + pruebas de capa |

---

## Integración

Se accede desde `ProductSuiteApp` como flujo seleccionable. Incluye navegación interna para elegir la arquitectura deseada.

---

## Requisitos

- iOS 15+
- Swift 6
- Swift Package Manager

---

## Licencia

MIT © Matías Adrián Molina
