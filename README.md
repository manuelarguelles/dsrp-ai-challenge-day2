# DSRP — AI Engineer Challenge — Día 2

Repo técnico de apoyo para el webinar de 2 días de Data Science Research Peru (17 y 18 de septiembre de 2026).

## Notebooks

- `notebooks/dia1_reconstruido_openai.ipynb` — Reconstrucción (a partir de capturas de pantalla) del notebook de Día 1 dictado en vivo por Juan Pablo Corona, con OpenAI + Responses API. No es una copia oficial; hay 3 celdas marcadas `# COMPLETADO` que quedaron sin terminar en la clase original.
- `notebooks/dia1_reconstruido_deepseek.ipynb` — La misma reconstrucción, adaptada para correr con DeepSeek (`chat.completions` + `response_format=json_object` en vez de la Responses API + `json_schema strict=True` de OpenAI). Validado en ejecución local y en Colab.
- `notebooks/dia2_de_entender_a_actuar.ipynb` — Material de Día 2 (Manuel Argüelles): retoma el contrato de Día 1 y agrega dos cosas reales — `crear_ticket()` ahora crea un **Issue de GitHub** y lo agrega a un **GitHub Project** (no un diccionario simulado), con un gate humano-en-el-medio antes de ejecutar. Validado en ejecución local y en Colab.

## Abrir en Colab

- [dia1_reconstruido_openai.ipynb](https://colab.research.google.com/github/manuelarguelles/dsrp-ai-challenge-day2/blob/main/notebooks/dia1_reconstruido_openai.ipynb)
- [dia1_reconstruido_deepseek.ipynb](https://colab.research.google.com/github/manuelarguelles/dsrp-ai-challenge-day2/blob/main/notebooks/dia1_reconstruido_deepseek.ipynb)
- [dia2_de_entender_a_actuar.ipynb](https://colab.research.google.com/github/manuelarguelles/dsrp-ai-challenge-day2/blob/main/notebooks/dia2_de_entender_a_actuar.ipynb)

## Secrets necesarios en Colab (candado 🔑)

- `OPENAI_API_KEY` — para `dia1_reconstruido_openai.ipynb`.
- `DEEPSEEK_API_KEY` — para los dos notebooks de DeepSeek.
- `GITHUB_TOKEN` — solo para `dia2_de_entender_a_actuar.ipynb`. Fine-grained personal access token
  con permiso `Issues: read/write` sobre el repo de tickets y `Projects: read/write` a nivel cuenta.
  El propio notebook trae las instrucciones paso a paso antes de la celda que lo usa.

## Destino real de los tickets de Día 2

Los Issues que crea el prototipo en vivo van a **[manuelarguelles/dsrp-ai-challenge-tickets](https://github.com/manuelarguelles/dsrp-ai-challenge-tickets)**
(privado), agregados al Project **[AI Engineer Challenge — Día 2](https://github.com/users/manuelarguelles/projects/5)**
con los campos `Categoria` y `Prioridad` seteados automáticamente.
