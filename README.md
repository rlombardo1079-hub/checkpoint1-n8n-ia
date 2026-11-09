# Checkpoint 1 - AI Automation Workflow (n8n)

## 📌 Descripción del Proyecto
Este proyecto consiste en la implementación de un agente inteligente modular desarrollado en n8n para la calificación autónoma de consultas y triaje corporativo. El agente procesa mensajes desestructurados, toma decisiones autónomas e invoca herramientas de observabilidad y notificación.

## 🔗 Entregables
- **Workflow JSON:** `checkpoint1_romina_lombardo.json`
- **Video de presentación (Loom):** [PEGA_ACÁ_TU_LINK_DE_LOOM]

## 🛠️ Componentes del Flujo
1. **Disparador:** Chat Trigger (`When chat message received`)
2. **Cerebro (AI Agent):** Modo `Tools Agent` con límite de 7 iteraciones (`Max Iterations`).
3. **Modelo LLM:** OpenAI Chat Model (`gpt-4o-mini`).
4. **Herramienta:** Gmail Tool configurada autónomamente.
5. **Observabilidad:** Nodo `Edit Fields`.

## 📸 Capturas de Verificación

### 1. Lienzo Completo y Ejecución Exitosa (Flujo en verde)
<img width="581" height="227" alt="image" src="https://github.com/user-attachments/assets/1a8dbec5-e742-471f-b266-993c8705bd9b" />

### 2. Configuración del AI Agent y Límite de Iteraciones (7)
<img width="932" height="337" alt="image" src="https://github.com/user-attachments/assets/afce71e4-604a-461c-b814-3fa375a69f2f" />
