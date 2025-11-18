FERRAMENTA DE BANCO DE ITENS, APLICAÇÃO E ANÁLISE (simples)
Autor: Iraê César Brandão  17/11/2025.

Uso de linguagens:  HMTL, CSS E JAVASCRIPT
Finalidade: Pesquisa acadêmica e educacional sem fins lucrativos.
Link de acesso:  https://irae-cesar-brandao.github.io/aig_psicometric_test_read/  


<b>Relações entre geração automática de itens (AIG) com controle de dificuldade e os resultados dos testes de compreensão leitora; depois listo publicações-chave com uma breve explicação entre parênteses para cada referência.</b>

A geração automática de testes de compreensão leitora com controle de dificuldade tem sido apontada como uma estratégia capaz de melhorar a precisão e a validade das avaliações educacionais. Quando se utiliza modelos psicométricos ou abordagens baseadas em IA para ajustar o nível de desafio dos itens, os testes passam a oferecer medidas mais exatas da habilidade do leitor, reduzindo erros de avaliação e evitando problemas como itens muito fáceis ou impossíveis de serem resolvidos (Circi, 2023). Esse controle permite selecionar ou gerar automaticamente questões coerentes com o nível de proficiência dos estudantes, resultando em testes mais equilibrados, com maior poder discriminativo e aplicáveis tanto em avaliações em larga escala quanto em sistemas adaptativos (Uto, 2023). Além disso, autores destacam que a calibração da dificuldade também potencializa o uso de avaliações computadorizadas adaptativas, pois permite ajustar dinamicamente os itens ao desempenho do aluno (Attali & Burstein, 2022).

Em contraste, quando os itens são gerados sem considerar a dificuldade, os resultados dos testes podem ser distorcidos, com baixa precisão na estimativa de habilidade e menor validade pedagógica e psicométrica (Susanti et al.,2017). Estudos comparativos mostram que a simples adoção de técnicas de geração automática não garante qualidade, sendo o controle de parâmetros como dificuldade lexical, complexidade textual e estrutura lógica essencial para gerar questões que realmente avaliem compreensão leitora em diferentes níveis (Tomikawa, 2024). Assim, o avanço das técnicas de geração automática de itens (especialmente as baseadas em modelos de linguagem e teoria de resposta ao item) indica que a personalização e o controle da dificuldade não apenas alteram, mas elevam significativamente a qualidade dos resultados obtidos em testes de leitura.



<b>Resumo — como o controle de dificuldade em AIG afeta os resultados dos testes?</b>

- Melhora a precisão da medição: quando itens (passagens + questões) são gerados com dificuldade estimada e controlada segundo modelos psicométricos (p.ex. IRT), é possível selecionar ou montar testes que correspondam melhor às habilidades dos alunos, reduzindo efeitos de teto/chão e o erro padrão de medida nas pontuações (Uto, Tomikawa & Suzuki, 2023).

- Aumenta a informação discriminativa do teste: itens com dificuldade apropriada tendem a discriminar melhor entre níveis de habilidade (melhor índice de discriminação), o que muda a distribuição das notas e pode aumentar confiabilidade e validade. 

- Permite avaliação adaptativa / formativa: com controle de dificuldade, é possível gerar bancos de itens para sistemas adaptativos (CAT) e tutoria adaptativa, o que altera o processo de obtenção das pontuações (menor número de itens para estimar habilidade com mesma precisão) (Veldkamp, Matteucci &. Eggen, 1970).

- Efeito sobre resultados em comparação com geração sem controle: testes gerados sem considerar dificuldade tendem a produzir medidas menos precisas — mais viés para alunos muito fracos ou muito fortes, menor informação test-retest e possíveis problemas de validade (itens muito fáceis/ difíceis ou distractores mal calibrados). Estudos experimentais mostram que controlar a dificuldade (via IRT, heurísticas linguísticas ou LLMs com rótulos de dificuldade) altera as taxas de acerto, índices de discriminação e a estimativa de habilidade média da amostra(Susanti et al., 2017).
 

<b> Referências </b>

ArXiv: Automatic Generation and Evaluation of Reading Comprehension Test Items with Large Language Models. (2024),  License: CC BY 4.0, arXiv:2404.07720v2 [cs.CL] 20 May 2024. Disponível em: <https://arxiv.org/html/2404.07720v2>. (Exploração prática de LLMs para criar e avaliar itens de múltipla escolha; mostra que controle e avaliação automática da dificuldade são críticas para resultados úteis e comparáveis.) 

Attali, Y. & Burstein, J. (2022). The interactive reading task: Transformer-based automatic item generation for reading comprehension. Frontiers in Artificial Intelligence. Disponível em: <https://doi.org/10.3389/frai.2022.903077>. (Descreve um pipeline transformer para gerar passagens e questões automaticamente, com capacidade de criação ampla de itens e discussão sobre validade automática/automática pontuação.) 

Circi, R., Hicks, J., & Sikali, E. (2023). Automatic item generation: foundations and machine learning-based approaches for assessments. Frontiers in Education. Download PDF. Disponível em: <https://www.frontiersin.org/journals/education/articles/10.3389/feduc.2023.858273/pdf>. (Revisão crítica do estado da arte em AIG; cobre fundamentos psicométricos (p.ex. IRT), abordagens ML/LLM, e implicações para qualidade dos resultados quando se controla (ou não) a dificuldade dos itens.) 

Gierl, M. J., Lai, H., & Turner, A. (2017). Using Automatic Item Generation to Create Solutions and Distractors: A review and demonstration. Disponível em: <https://pmc.ncbi.nlm.nih.gov/articles/PMC5978592/>. (Artigos/relatórios sobre métodos clássicos de AIG que mostram como variabilidade controlada nos parâmetros do item afeta índices psicométricos e resultados de teste.) 

Huang, Y. (2016). Automatic generation of short answer questions for reading comprehension assessment. Natural Language Engineering / Cambridge. Disponível em: <https://www.cambridge.org/core/journals/natural-language-engineering/article/abs/automatic-generation-of-short-answer-questions-for-reading-comprehension-assessment/701D7F67BE5C8DBEE60C7906C5E0E437>.(Um dos trabalhos pioneiros em geração automática de perguntas de compreensão leitora; discute seleção de sentenças-fonte, tipos de perguntas e impacto na validade das avaliações automatizadas.) 

Ma, W. A., et al. (2025). Automatic Generation of Inference Making Questions for Reading Comprehension. PDF. Disponível em: <https://aclanthology.org/2025.bea-1.31.pdf>. (BEA/ACL 2025 — avalia LLMs (p.ex. GPT-4o) para gerar questões de inferência; conclui que AIG com LLMs tem grande potencial, mas qualidade e validade muitas vezes precisam de julgamento humano — especialmente para itens mais sofisticados.) 

Song, Yishen; lei Du, Jun; Zheng, Qinhua - Revisão sistemática (2025). Automatic item generation for educational assessments: a systematic literature review. March 2025Interactive Learning Environments 33(2):1-20, DOI: 10.1080/10494820.2025.2482588. Disponível em: <https://www.researchgate.net/publication/390147704_Automatic_item_generation_for_educational_assessments_a_systematic_literature_review>.(Resumo recente de estudos sobre AIG, incluindo uso de IRT, CAT e LLMs; discute como estudos empíricos com controle de dificuldade tendem a reportar melhorias em precisão e validade em comparação com AIG sem controle.) 

Susanti, Y. et al. (2017). Controlling item difficulty for automatic vocabulary question generation. Research and Practice in Technology Enhanced Learning. Disponivel em: <https://telrp.springeropen.com/articles/10.1186/s41039-017-0065-5>. (Estudo experimental que identifica fatores que controlam dificuldade em questões de vocabulário geradas automaticamente — p.ex. dificuldade da passagem, similaridade semântica entre correta e distratores — e mede efeito nas taxas de acerto.) 

Tomikawa, Y., et al. (2024). Difficulty-Controllable Reading Comprehension Question Generation Considering the Difficulty of Reading Passages. ICCE/Proceedings (2024), Download PDF.Disponível em: <https://library.apsce.net/index.php/ICCE/article/download/4931/4861>. (Estende modelos IRT para estimar dificuldade tanto de passagens quanto de questões; apresenta um framework que seleciona passagens e gera perguntas apropriadas ao nível do aluno, mostrando impacto direto na adequação dos itens.) 

Uto, M.; Tomikawa, Y.; & Suziki,A. (2023). Difficulty-Controllable Neural Question Generation for Reading Comprehension using Item Response Theory. In: Proceedings of the 18th Workshop on Innovative Use of NLP for Building Educational Applications (BEA 2023), pages 119–129, July 13, 2023. Association for Computational Linguistics, PDF. Disponível em: <https://aclanthology.org/2023.bea-1.10.pdf>.(Gera pares pergunta-resposta considerando dificuldade estimada por IRT; propõe método para treinar um gerador controlando o nível de dificuldade e discute como isso melhora a seleção de itens adequados à habilidade do aprendiz.) 

Veldkamp, B. P.; Matteucci, M.; & Eggen T. J. H. M. (1970). Computerized Adaptive Testing in Computer Assisted Learning? In book: Interdisciplinary Approaches to Adaptive Learning. A Look at the Neighbours. DOI: 10.1007/978-3-642-20074-8_3. ResearchGate, January 1970. Disponível em: <https://www.researchgate.net/publication/225873260_Computerized_Adaptive_Testing_in_Computer_Assisted_Learning>

