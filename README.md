# 🛒 Urban Grocers — API Testing

Pruebas funcionales a la API REST de **Urban Grocers** tras la actualización de sus módulos de kits y servicios de entrega.

[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)](https://www.postman.com/)
[![JIRA](https://img.shields.io/badge/JIRA-0052CC?style=for-the-badge&logo=jira&logoColor=white)](https://www.atlassian.com/software/jira)
[![API REST](https://img.shields.io/badge/API%20REST-6E4AFF?style=for-the-badge)]()

---

## 📋 Descripción del proyecto

Urban Grocers lanzó nuevas actualizaciones sobre cómo la plataforma maneja los **kits de productos** y los **servicios de entrega**. El objetivo fue analizar los nuevos requisitos y verificar que la API los admitiera correctamente mediante pruebas funcionales exhaustivas.

---

## 🎯 Objetivos

- Validar que los endpoints de kits y delivery funcionaran correctamente tras la actualización
- Diseñar y ejecutar casos de prueba positivos y negativos
- Documentar y reportar los bugs encontrados con evidencia de respaldo

---

## 🛠️ Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| **Postman** | Ejecución de solicitudes HTTP y validación de respuestas |
| **Jira** | Reporte y seguimiento de bugs |
| **ApiDoc** | Consulta de documentación técnica de la API |
| **Google Sheets** | Registro de casos de prueba y resultados |

---

## 🔍 Alcance de las pruebas

### Métodos HTTP probados
- `GET` — Consulta de kits y servicios de entrega
- `POST` — Creación de nuevos kits y configuración de delivery
- `PUT` — Actualización de kits existentes
- `DELETE` — Eliminación de kits

### Tipos de pruebas ejecutadas
- ✅ Casos positivos — entradas válidas con respuestas esperadas
- ❌ Casos negativos — entradas inválidas, campos vacíos, límites excedidos
- 🔄 Validación de status codes (200, 201, 400, 404, etc.)
- 📦 Validación de estructura y contenido de respuestas JSON

---

## 📊 Resultados

| Métrica | Resultado |
|---|---|
| Total de casos de prueba | +50 |
| Casos positivos | ✅ Ejecutados |
| Casos negativos | ✅ Ejecutados |
| Bugs reportados en Jira | Documentados con evidencia |

---

## 📁 Estructura del repositorio

```
qa-urban-grocers-api/
├── 📄 README.md
├── 📁 test-cases/
│   ├── casos-positivos.md
│   └── casos-negativos.md
├── 📁 bug-reports/
│   └── bugs-encontrados.md
├── 📁 evidence/
│   ├── postman-responses/    
│   └── jira-bugs/           ← https://drive.google.com/drive/folders/1LoTu_sGrUFhunDT2Dj5vk6BJOVYR2lLC?usp=sharing
└── 📁 collections/
    └── urban-grocers.postman_collection.json
```

---

## 🐞 Proceso de reporte de bugs en Jira

Cada bug reportado incluye:
- **Título** — descripción clara y concisa del defecto
- **Pasos para reproducir** — numerados y detallados
- **Resultado esperado** — comportamiento correcto según requisitos
- **Resultado actual** — comportamiento incorrecto observado
- **Evidencia** — capturas de Postman (request + response)
- **Severidad / Prioridad** — clasificación del impacto

---

## 📎 Recursos adicionales

- 📂 [Documentación completa en Google Drive](#) ← *(https://docs.google.com/spreadsheets/d/17EOL3sCJjahwVLZXklyJWNgynEbJ6B0B/edit?usp=sharing&ouid=114380237435694438896&rtpof=true&sd=true)*


---

## 👤 Autor

**Josafat Gabriel Hernandez Rizo**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/josafatgabrielhernandezrizo)
[![Gmail](https://img.shields.io/badge/Gmail-Contacto-D14836?style=flat-square&logo=gmail)](mailto:josafatgabrielhernandezrizo@gmail.com)
