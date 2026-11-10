# Festa do Michael Jackson · Ingressos

Página de ingressos (link na bio do @festadomichael): https://gnarly-eventos.github.io/festadomichael/

- `eventos.json`: gerado sozinho pelo robô (de hora em hora) a partir da conta 1 do Sympla. Não editar.
- `ajustes.json`: editar à mão para marcar `"selo": "esgotado"` ou `"ultimos"`, trocar o `"titulo"` ou `"ocultar": true` um evento (pelo id, ex.: `s373835`).
- Para atualizar na hora: aba Actions → "Publicar página" → Run workflow.
- O token do Sympla fica em Settings → Secrets → `SYMPLA_TOKEN_1`. Nunca colocar token nos arquivos.
