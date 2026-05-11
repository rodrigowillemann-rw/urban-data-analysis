# Metodologia

A analise sintetica combina vulnerabilidade, acesso a transporte e tempo medio de deslocamento para priorizar territorios.

## Variaveis

- `indice_vulnerabilidade`: indicador sintetico entre 0 e 1
- `acesso_transporte_pct`: percentual de acesso a transporte
- `tempo_medio_deslocamento_min`: tempo medio de deslocamento em minutos

## Formula

```text
score_atencao = indice_vulnerabilidade*100 + (60 - acesso_transporte_pct)*0,4 + tempo_medio_deslocamento_min*0,3
```

## Interpretacao

Scores maiores indicam maior necessidade relativa de atencao territorial. A metodologia e demonstrativa e deve ser recalibrada com dados reais e validacao local.
