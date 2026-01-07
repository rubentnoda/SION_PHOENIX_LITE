# Cómo Usar SION PHOENIX LITE

Esta guía te ayudará a implementar y utilizar el GPT personalizado SION PHOENIX LITE.

## 📋 Contenido

1. [Estructura del Proyecto](#estructura-del-proyecto)
2. [Configuración en ChatGPT](#configuración-en-chatgpt)
3. [Personalización](#personalización)
4. [Base de Conocimientos](#base-de-conocimientos)

## 🗂️ Estructura del Proyecto

```
SION_PHOENIX_LITE/
├── custom-gpt-config.json    # Configuración del GPT
├── instructions.md            # Instrucciones del comportamiento
├── knowledge_base/            # Base de conocimientos
│   └── README.md             # Guía de la base de conocimientos
├── USAGE.md                  # Esta guía
└── README.md                 # Descripción del proyecto
```

## ⚙️ Configuración en ChatGPT

### Paso 1: Crear un nuevo GPT personalizado

1. Ve a [ChatGPT](https://chat.openai.com/)
2. Haz clic en tu perfil y selecciona "Mis GPTs"
3. Haz clic en "Crear un GPT"

### Paso 2: Configuración Básica

**Nombre:**
```
SION PHOENIX LITE
```

**Descripción:**
```
Cerebro de SION Fénix - Un asistente personalizado para gestión y análisis
```

### Paso 3: Instrucciones

Copia el contenido completo del archivo `instructions.md` en el campo de instrucciones del GPT.

### Paso 4: Conversación de Inicio

Agrega los siguientes iniciadores de conversación:
- ¿Cómo puedo ayudarte hoy?
- ¿Qué información necesitas analizar?
- ¿En qué proyecto estás trabajando?
- ¿Necesitas ayuda con alguna tarea específica?

### Paso 5: Capacidades

Configura las siguientes capacidades según lo definido en `custom-gpt-config.json`:
- ❌ Navegación web: Desactivado
- ✅ Intérprete de código: Activado
- ❌ Generación de imágenes DALL-E: Desactivado

### Paso 6: Base de Conocimientos

Si tienes archivos en el directorio `knowledge_base/`, súbelos en la sección de "Knowledge" del GPT:
1. Haz clic en "Upload files"
2. Selecciona los archivos del directorio `knowledge_base/`
3. Confirma la carga

## 🎨 Personalización

### Modificar Instrucciones

Edita el archivo `instructions.md` para cambiar:
- Personalidad del asistente
- Estilo de comunicación
- Capacidades específicas
- Restricciones y límites

### Actualizar Configuración

Edita `custom-gpt-config.json` para modificar:
- Nombre y descripción
- Capacidades habilitadas
- Iniciadores de conversación
- Modelo a utilizar

## 📚 Base de Conocimientos

### Agregar Documentos

1. Coloca tus archivos en el directorio `knowledge_base/`
2. Organiza por categorías si es necesario
3. Actualiza el `knowledge_base/README.md` documentando los cambios
4. Sube los archivos a tu GPT personalizado en ChatGPT

### Tipos de Archivos Soportados

- Documentos de texto: `.txt`, `.md`
- Documentos: `.pdf`, `.docx`
- Datos estructurados: `.json`, `.csv`
- Código: `.py`, `.js`, `.java`, etc.

### Límites

- Máximo 20 archivos
- Máximo 512 MB por archivo (planes Plus)
- Total máximo de 10 GB (planes Plus)

## 🔄 Actualización

Para actualizar tu GPT personalizado:

1. Edita los archivos locales según sea necesario
2. Ve a "Mis GPTs" en ChatGPT
3. Selecciona tu GPT personalizado
4. Haz clic en "Edit"
5. Actualiza las secciones necesarias
6. Guarda los cambios

## 💡 Consejos

- **Iteración:** Prueba tu GPT y ajusta las instrucciones según el comportamiento
- **Claridad:** Las instrucciones claras y específicas producen mejores resultados
- **Contexto:** Agrega conocimiento específico de tu dominio en la base de conocimientos
- **Ejemplos:** Incluye ejemplos en las instrucciones para comportamientos específicos
- **Limitaciones:** Define claramente lo que el GPT NO debe hacer

## 🆘 Solución de Problemas

### El GPT no sigue las instrucciones

- Verifica que las instrucciones sean claras y específicas
- Evita contradicciones en las instrucciones
- Simplifica instrucciones complejas

### El GPT no usa la base de conocimientos

- Asegúrate de que los archivos estén correctamente cargados
- Verifica que el contenido sea relevante para las consultas
- Menciona explícitamente en las instrucciones que debe usar los archivos

### Respuestas inconsistentes

- Refina las instrucciones para ser más específico
- Agrega ejemplos de comportamiento esperado
- Define mejor el estilo y tono de respuesta

## 📞 Soporte

Para más información sobre GPTs personalizados:
- [Documentación oficial de OpenAI](https://help.openai.com/en/articles/8554397-creating-a-gpt)
- [Mejores prácticas para GPTs](https://platform.openai.com/docs/guides/gpt-best-practices)

---

**Versión:** 1.0.0  
**Última actualización:** 2026-01-07
