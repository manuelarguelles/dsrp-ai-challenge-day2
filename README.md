# DSRP — AI Engineer Challenge — Día 2

Repo técnico de apoyo para el webinar de 2 días de Data Science Research Peru (17 y 18 de septiembre de 2026).

## Notebooks

- `notebooks/dia1_reconstruido_openai.ipynb` — Reconstrucción (a partir de capturas de pantalla) del notebook de Día 1 dictado en vivo por Juan Pablo Corona, con OpenAI + Responses API. No es una copia oficial; hay 3 celdas marcadas `# COMPLETADO` que quedaron sin terminar en la clase original.
- `notebooks/dia1_reconstruido_deepseek.ipynb` — La misma reconstrucción, adaptada para correr con DeepSeek (`chat.completions` + `response_format=json_object` en vez de la Responses API + `json_schema strict=True` de OpenAI). Validado en ejecución local.
- `notebooks/dia2_de_entender_a_actuar.ipynb` — Material de Día 2 (Manuel Argüelles): retoma el contrato de Día 1, agrega una herramienta real (`crear_ticket`) y un gate humano-en-el-medio antes de ejecutar. Validado en ejecución local.

## Abrir en Colab

- [dia1_reconstruido_openai.ipynb](https://colab.research.google.com/github/manuelarguelles/dsrp-ai-challenge-day2/blob/main/notebooks/dia1_reconstruido_openai.ipynb)
- [dia1_reconstruido_deepseek.ipynb](https://colab.research.google.com/github/manuelarguelles/dsrp-ai-challenge-day2/blob/main/notebooks/dia1_reconstruido_deepseek.ipynb)
- [dia2_de_entender_a_actuar.ipynb](https://colab.research.google.com/github/manuelarguelles/dsrp-ai-challenge-day2/blob/main/notebooks/dia2_de_entender_a_actuar.ipynb)

Requieren un secret en Colab (candado 🔑): `OPENAI_API_KEY` para el notebook de OpenAI, `DEEPSEEK_API_KEY` para los dos de DeepSeek.
