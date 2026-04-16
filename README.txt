![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Analysis-blue)

# Serilog-UI Architecture Analysis & Contribution

Este repositorio contiene un análisis técnico profundo del sistema **Serilog-UI**, centrado en la observabilidad, extensibilidad y el desacoplamiento entre el núcleo del visor y los diferentes proveedores de datos.

## 🧠 Contenido del Análisis
- **Vistas de Arquitectura:** Contexto, Funcional y Despliegue (UML).
- **Atributos de Calidad:** Evaluación de escalabilidad y mantenibilidad.
- **Análisis de Diseño:** Estudio del desacoplamiento entre el Core y los Data Providers.

## 🚀 Contribución Técnica
Se realizó una refactorización crítica en el núcleo del sistema mediante el patrón **Template Method**. 

**Impacto:**
- **Eliminación de redundancia:** Se centralizó la lógica de construcción de consultas SQL.
- **Extensibilidad:** Se estandarizó la forma en que nuevos proveedores pueden integrarse en el sistema.
- **Mantenibilidad:** Desacoplamiento de la lógica de negocio del Core de las implementaciones específicas de los proveedores.

🔗 **Enlace al Commit:** [21fb7aa0](https://github.com/PGT5772/serilog-ui/commit/21fb7aa09cae7b878986ab46b5f32a756063a7a6)

## 🛠️ Tecnologías Analizadas
- **Backend:** .NET / ASP.NET Core
- **Frontend:** React / TypeScript
- **Persistencia:** Soporte para SQL (SQL Server, SQLite, MySQL) y NoSQL (MongoDB, Azure Cosmos DB).

## 📄 Documento Completo
Puedes consultar el informe técnico detallado en:  
👉 [PDF: Serilog-UI Full Report](./docs/serilog-ui-full-report.pdf)