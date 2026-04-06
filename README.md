# PintOS Kernel Shell

## Descrição

Este projeto implementa um shell interativo em nível de kernel no sistema operacional educacional PintOS.

O shell é iniciado automaticamente quando o PintOS é executado **sem argumentos de linha de comando**.

---

## Funcionalidades

O shell apresenta o seguinte comportamento:

- Exibe o prompt:

  ```text
  wm>

- Comandos suportados:

  ```text
  wm> whoami
  imprime o nome do autor

  wm> exit
  encerra o shell e permite que o kernel finalize

  wm> qualquer outro comando
  imprime invalid command

