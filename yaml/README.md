# YAML

Há um arquivo XML para cada versão descrita acima. Os arquivos XML estão codificados em UTF-8 e possuem a seguinte estrutura:

## Curiosidade

```bash
---
1-1:
  curiosidade:
  - texto: "TEXTO"
1-2:
  curiosidade:
  - texto: "TEXTO"
1-3:
  curiosidade:
  - texto: "TEXTO"
...
```

## Eventos

```bash
---
1-1:
    - |-
        TEXTO
    - |-
        TEXTO
    - |-
        TEXTO
    - |-
        TEXTO
    - |-
...
```

## Feriados

```bash
---
1-1:
    births:
        - name: "TEXTO"
        - name: "TEXTO"
1-2:
    births:
        - name: "TEXTO"
...
```

## Frases

```bash
---
1-1:
    quote: TEXTO
    author: |-
        TEXTO
1-2:
    quote: TEXTO
    author: |-
        TEXTO
...
```
