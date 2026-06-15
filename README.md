# PROSE NES 2026/1 - Leva Sprint 2

Repositorio dos dashboards SPACE do NES preparados para a coleta da Sprint 2.

Cada equipe fica isolada em `teams/tX`, compartilhando o mesmo motor em
`common/dashboard_app.py`. As planilhas brutas e auditorias nominais nao sao
versionadas.

## Estado desta leva

- T1, equipe da Lourdes: Sprints 0, 1 e 2 carregadas.
- T4, equipe da Sophya: Sprints 0, 1 e 2 carregadas.
- T2, T3, T5, T6, T7 e T8: Sprints 0, 1 e 2 carregadas.
- T9: Sprints 1 e 2 carregadas (Sprint 0 sem respostas, exibido como `n/d`).
- PDFs das devolutivas de todas as equipes (T1-T9) gerados a partir da Sprint 2, com historico S0-S2 (S1-S2 para o T9).
- Dashboard e PDF exibem Survey e dimensoes SPACE em todas as sprints; dados
  sem respostas aparecem como `n/d`.

## Deploy no Streamlit Cloud

Use este repositorio e a branch `main`.

Para o T1:

```text
teams/t1/app.py
```

Para o T4:

```text
teams/t4/app.py
```

Os demais times seguem o mesmo formato:

```text
teams/t1/app.py
teams/t2/app.py
...
teams/t9/app.py
```

## Execucao local

```bash
python -m pip install -r requirements.txt
python -m streamlit run teams/t4/app.py
```

## Dados publicados

Somente artefatos agregados necessarios ao dashboard sao versionados, como
relatos Markdown e imagens. Respostas individuais, planilhas de Forms e
auditorias de classificacao devem permanecer fora do repositorio.

## Relatorio PDF

- [T1 - Sprint 2, com historico S0-S2](pdfs/relatorio_T1_sprint_2.pdf)
- [T2 - Sprint 2, com historico S0-S2](pdfs/relatorio_T2_sprint_2.pdf)
- [T3 - Sprint 2, com historico S0-S2](pdfs/relatorio_T3_sprint_2.pdf)
- [T4 - Sprint 2, com historico S0-S2](pdfs/relatorio_T4_sprint_2.pdf)
- [T5 - Sprint 2, com historico S0-S2](pdfs/relatorio_T5_sprint_2.pdf)
- [T6 - Sprint 2, com historico S0-S2](pdfs/relatorio_T6_sprint_2.pdf)
- [T7 - Sprint 2, com historico S0-S2](pdfs/relatorio_T7_sprint_2.pdf)
- [T8 - Sprint 2, com historico S0-S2](pdfs/relatorio_T8_sprint_2.pdf)
- [T9 - Sprint 2, com historico S1-S2 (Sprint 0 sem respostas)](pdfs/relatorio_T9_sprint_2.pdf)
