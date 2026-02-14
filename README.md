# Automatización de Publicaciones en LinkedIn con n8n

## Descripción

Este proyecto consiste en la automatización de publicaciones en LinkedIn utilizando n8n.  
El workflow recibe un mensaje desde un Chat Trigger, genera un post profesional y lo publica automáticamente en LinkedIn.

El objetivo es demostrar la integración entre generación de contenido automatizada y publicación directa en redes profesionales.

---

## Tecnologías utilizadas

- n8n
- LinkedIn API
- Webhooks / Chat Trigger
- JSON
- Automatización de Workflows

---

## Arquitectura del Workflow

Chat Trigger  
↓  
AI Agent (Generación del contenido)  
↓  
Nodo LinkedIn (Publicación automática)  
↓  
Confirmación de ejecución (opcional)

---

## Funcionamiento

1. El usuario envía una idea o texto base mediante el Chat Trigger.
2. El sistema procesa la entrada.
3. Se genera un post profesional.
4. El contenido se publica automáticamente en LinkedIn.
5. (Opcional) Se devuelve mensaje de confirmación.

---

## Casos de uso

- Publicación automatizada de contenido profesional
- Compartir CV automáticamente
- Generación de posts técnicos
- Automatización de marketing personal

---

## Cómo usar el workflow

1. Importar el archivo `workflow.json` en n8n.
2. Configurar credenciales de LinkedIn.
3. Activar el workflow.
4. Enviar un mensaje al Chat Trigger.
5. Verificar la publicación en LinkedIn.

---

## Archivo incluido

- `workflow.json` → Exportación completa del flujo de n8n
- `capturas/` → Imágenes del workflow
- `README.md` → Documentación del proyecto

---

## Autor

Mateo Paredes  
Tecnólogo en Desarrollo de Software  
Interesado en automatización, backend y arquitectura de sistemas.

GitHub: https://github.com/tuusuario
LinkedIn: https://linkedin.com/in/tuusuario
