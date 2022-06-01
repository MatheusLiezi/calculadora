[![Github Actions Status for matheusliezi/calculadora](https://github.com/matheusliezi/calculadora/workflows/javaciwithmaven/badge.svg)](https://github.com/matheusliezi/calculadora/actions)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=MatheusLiezi_calculadora&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=MatheusLiezi_calculadora)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=matheusliezi_calculadora&metric=coverage)](https://sonarcloud.io/component_measures?id=matheusliezi_alculadora&metric=coverage)

# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção
Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.<br>
- A cobertura do código é realizada através do JaCoCo.<br>
