# Desenvolvimento Web Sustentável

Estratégias para redução do consumo energético em aplicações web de grande porte.

Repositório de apoio ao trabalho acadêmico **"Desenvolvimento Web Sustentável: estratégias para redução do consumo energético em aplicações de grande porte"** (Vila Nova do Piauí/PI, agosto de 2026).

## Resumo

O crescimento das aplicações web de grande porte amplia a demanda por processamento, armazenamento, comunicação de dados e infraestrutura de servidores. O desenvolvimento web sustentável busca criar e manter aplicações que cumpram seus objetivos usando recursos computacionais de forma mais eficiente, considerando backend, rede e frontend.

## Objetivo geral

Analisar e propor estratégias de desenvolvimento web sustentável capazes de reduzir o consumo energético e o uso desnecessário de recursos computacionais em aplicações de grande porte, mantendo desempenho, funcionalidade e boa experiência de uso.

## Objetivos específicos

- Identificar fatores do desenvolvimento web que aumentam o consumo de recursos.
- Investigar otimizações de código, recursos, rede, backend, banco de dados e frontend.
- Analisar métricas de carregamento, dados transferidos, CPU e memória.
- Avaliar ferramentas como Google Lighthouse, PageSpeed Insights e calculadoras de pegada de carbono.
- Estruturar cenário experimental comparando a aplicação antes e depois das otimizações.

## Estratégias abordadas

| Área | Práticas |
| --- | --- |
| Frontend | Minificação, redução de arquivos JS/CSS, imagens otimizadas, lazy loading, menos requisições HTTP |
| Rede | Caching, compressão, CDN, redução do payload |
| Backend | Algoritmos de menor complexidade, estruturas de dados adequadas, uso controlado de CPU e memória |
| Dados | Índices, seleção apenas dos campos necessários, paginação, menos consultas repetidas |
| UX/UI | Interfaces leves, carregamento progressivo, acessibilidade preservada, modos escuros em telas OLED |

## Ciclo de Otimização Web Sustentável

1. **Medir** — coletar indicadores da versão inicial.
2. **Identificar** — localizar desperdícios de processamento e transferência.
3. **Otimizar** — aplicar as estratégias sustentáveis.
4. **Comparar** — medir novamente e confrontar resultados.
5. **Documentar** — registrar ganhos, limitações e recomendações.

## Indicadores

| Indicador | Descrição | Finalidade |
| --- | --- | --- |
| Tempo de carregamento | Tempo até a página estar utilizável | Reduzir espera e trabalho |
| Tamanho do payload | Volume de dados transferidos | Diminuir tráfego |
| Número de requisições | Quantidade de chamadas | Evitar comunicação desnecessária |
| Uso de CPU | Carga de processamento | Reduzir operações dispensáveis |
| Uso de memória | Recursos de memória utilizados | Evitar consumo excessivo |
| Tempo de resposta | Tempo de atendimento das operações | Melhorar eficiência do backend |

## Metodologia

Pesquisa aplicada, de caráter exploratório e descritivo: revisão bibliográfica, levantamento de técnicas de otimização, desenvolvimento de protótipo ou cenário experimental (página inicial com multimídia, API e banco de dados) e comparação de indicadores antes e depois das intervenções. Quando não houver medição energética direta, os indicadores são tratados como aproximações da carga de trabalho, com as limitações explicitadas.

## Estrutura sugerida do repositório

```
docs/        textos, referências e resultados
prototipo/   versão inicial e versão otimizada
medicoes/    relatórios de Lighthouse e demais métricas
```

## Autores

Érika Leal de Sousa · Joana Maria Leal Silva · Josimedio Leal de Araújo · Rízia de França Leal · Robert Kleber da Silva

Orientador: Daniel Alves

## Palavras-chave

Desenvolvimento web sustentável · Green IT · Eficiência energética · Aplicações web · Otimização de software · Sustentabilidade digital
