---
question: "¿Qué sintaxis de comandos de flujo de trabajo configura correctamente una variable de entorno llamada 'API_VERSION' con el valor '2.1' para pasos subsecuentes en un trabajo de GitHub Actions?"
title: "Pregunta 127"
---

> https://docs.github.com/en/actions/using-workflows/workflow-commands-for-github-actions#setting-an-environment-variable

1. [x] `echo "API_VERSION=2.1" >> "$GITHUB_ENV"`
1. [ ] `echo "API_VERSION=2.1" >> "$GITHUB_OUTPUT"`
1. [ ] `export API_VERSION=2.1 >> "$GITHUB_ENV"`
1. [ ] `set-env name=API_VERSION value=2.1`
