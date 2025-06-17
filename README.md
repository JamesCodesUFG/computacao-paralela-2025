# Trabalho Final Prático - Computaçã Paralela 2025

## Descrição

Este é o trabalho final da disciplina de Computação Paralela. Ele representa a oportunidade de aplicar, de forma integrada e prática, todos os conceitos e técnicas que exploramos ao longo do semestre.

Em grupos de 3 a 5 alunos, vocês deverão projetar, implementar e avaliar uma solução paralela ou distribuída para um problema computacionalmente intensivo de sua escolha. A solução deve demonstrar o uso de técnicas de programação paralela, explorando os benefícios em termos de desempenho (speedup, eficiência, etc.) em comparação com uma solução sequencial.
Requisitos do Trabalho

* Escolha do problema e justificativa:
    * Selecione um problema computacionalmente desafiador que se beneficie da paralelização. Alguns exemplos incluem:
        * Processamento de imagens (filtros, transformações, reconhecimento de padrões).
        * Simulações científicas (física, química, biologia, etc.).
        * Análise de grandes volumes de dados (mineração de dados, aprendizado de máquina).
        * Problemas de otimização (roteamento, alocação de recursos, etc.).
        * Criptografia e segurança.
        * Algoritmos de ordenação e busca
    * Justifique a escolha do problema, destacando por que ele é adequado para a paralelização e quais os ganhos esperados.
    * Descreva os dados de entrada, ou o dataset que será utilizado. Pode ser um dataset público ou dados gerados por você.
* Projeto da solução paralela:
    * Escolha um modelo de programação paralela apropriado (memória compartilhada, memória distribuída ou ambos) com base nas características do problema e nas tecnologias disponíveis (CUDA, Spark, etc...).
    * Detalhe a decomposição do problema em tarefas ou dados, a distribuição dessas tarefas/dados entre os processadores/threads e a comunicação/sincronização necessária.
    Apresente diagramas (ex: fluxo de trabalho, arquitetura) que ilustrem o projeto da solução paralela.
* Implementação:
    * Implemente a solução paralela utilizando a(s) tecnologia(s) escolhida(s).
    * Implemente também uma versão sequencial do algoritmo para fins de comparação.
    * O código deve ser bem documentado, organizado e seguir boas práticas de programação.
* Avaliação de desempenho:
    * Realize experimentos para medir o desempenho da solução paralela e da solução sequencial. Varie o tamanho do problema e o número de processadores/threads.
    * Calcule métricas de desempenho relevantes, como speedup, eficiência, escalabilidade, etc.
    * Apresente os resultados em gráficos e tabelas, analisando e discutindo os ganhos obtidos com a paralelização. Identifique gargalos e oportunidades de melhoria.
* Programação com memória compartilhada e distribuída
    * Implementar o algoritmo com memória distribuída ou compartilhada.

## Entregas

* Apresentação: slides da apresentação.
* Relatório técnico (máximo de 5 páginas): detalhando o trabalho realizado, incluindo a descrição do tema, os requisitos, a modelagem dos dados, as tecnologias utilizadas, as consultas implementadas e a análise de dados. 
* Código-fonte do projeto: disponibilizado em um repositório Git (ex: Github, GitLab).

## Links

* Apresentação: [Canva](https://www.canva.com/design/DAGqj6UUHi4/XBePVU2iMZY13kW7MbLQjA/edit?utm_content=DAGqj6UUHi4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
* Relatório técnico: [Google Docs](https://docs.google.com/document/d/1VtnQoxiJyaHXdWE0d8vynXJSHd-NxIGZ1BWsiXEgviU/edit?usp=sharing)
* Código-fonte: [Github](https://github.com/JamesCodesUFG/computacao-paralela-2025)
