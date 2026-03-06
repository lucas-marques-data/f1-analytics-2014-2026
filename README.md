# F1 Analytics 2014–2026

> O que esperar da F1 em 2026 — e por que Bortoleto me surpreendeu.

Projeto completo de coleta, analise e previsao de dados da Formula 1,
cobrindo 12 temporadas reais (2014–2025) via API oficial e integrando
os primeiros dados de 2026: Bahrain Test 2, FP1 e FP2 da Australia.

---

## O que este projeto entrega

- Coleta automatica de dados via API Ergast (jolpi.ca) — 2014 a 2025
- Analise das tres eras: Mercedes, Red Bull e McLaren
- Heatmap de vitorias, evolucao de pontos e analise de dominancia por ano
- Performance detalhada de pilotos: consistencia, posicao media e pontos totais
- Integracao manual dos treinos de 2026 com dados verificados
- Duelo interno Bortoleto vs Hulkenberg — sessao a sessao
- Modelo de previsao ponderado: 60% treinos 2026 + 40% historico recente
- Ranking previsto de pilotos e construtores para o campeonato 2026

---

## Estrutura do notebook

| Bloco | Conteudo                                        |
|-------|-------------------------------------------------|
| 0     | Instalacao de dependencias e imports            |
| 1     | Coleta via API Ergast — 2014 a 2024             |
| 2     | Dados 2025 + treinos 2026 (Bahrain, FP1, FP2)  |
| 3     | Gabarito oficial dos campeoes 2014–2025         |
| 4     | Analises historicas — 6 visualizacoes           |
| 5     | Analise especial: Bortoleto + Audi 2026         |
| 6     | Modelo de previsao e ranking 2026               |
| 7     | Insights completos                              |

---

## Principais insights

**As tres eras (2014–2025)**
Mercedes dominou de 2014 a 2020 com 7 titulos consecutivos.
Red Bull assumiu o controle de 2021 a 2024, com Verstappen batendo
o recorde historico de 575 pontos em 2023.
Em 2025, Norris e a McLaren quebraram a hegemonia por apenas 2 pontos
de margem sobre Verstappen (423 x 421).

**2026 — nova era, novos favoritos**
Com os novos regulamentos, o grid embaralhou.
Ferrari liderou o Bahrain Test 2 e o FP1 da Australia.
McLaren reagiu forte no FP2, mostrando que a defesa do titulo esta viva.
Red Bull perdeu o referencial de performance.

**Gabriel Bortoleto**
O estreante brasileiro venceu o duelo interno contra Hulkenberg
em 2 das 3 primeiras sessoes de 2026.
O modelo de previsao estima aproximadamente 88 pontos na temporada —
expressivo para um rookie com carro em desenvolvimento.

---

## Tecnologias

- Python 3
- Pandas
- NumPy
- Plotly
- Matplotlib
- Seaborn
- Google Colab
- kaleido 0.2.1 (renderizacao de graficos)

---

## Fontes

- API Ergast: https://api.jolpi.ca/ergast/f1/
- Resultados oficiais: https://www.formula1.com/en/results
- Stats F1: https://www.statsf1.com

---

## Como executar

1. Abra o notebook no Google Colab
2. Execute o Bloco 0 para instalar as dependencias
3. Reinicie o runtime apos a instalacao (Runtime > Reiniciar sessao)
4. Execute todos os blocos em sequencia (Runtime > Executar tudo)

A coleta completa via API leva aproximadamente 3 minutos.

---

## Dados validados

Os pontos de 2025 foram verificados via formula1.com:

| Piloto          | Pontos |
|-----------------|--------|
| Lando Norris    | 423    |
| Max Verstappen  | 421    |
| Oscar Piastri   | 410    |

| Construtor | Pontos |
|------------|--------|
| McLaren    | 833    |
| Mercedes   | 469    |

---

## Proximos passos

- Atualizar com resultados reais das corridas de 2026
- Adicionar analise de pontos por circuito
- Incluir dados de qualificacao e ritmo de corrida separados

---

Se este projeto foi util ou interessante, deixe uma estrela no repositorio.

Sugestoes e contribuicoes sao bem-vindas via Issues ou Pull Requests.
