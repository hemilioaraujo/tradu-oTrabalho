# Abstrato

A Mineração de Fluxo de Dados é uma das áreas que ganham muito significado prático e está progredindo em um ritmo acelerado com novos métodos,
metodologias e resultados em várias aplicações relacionadas à previsão de medicina, ciência da computação, bioinformática e mercado de ações, previsão do tempo, texto, processamento de áudio e vídeo para citar alguns. Os dados são a principal preocupação na mineração de dados.
Com os enormes dados online gerados a partir de vários sensores, o Internet Relay Chats, o Twitter, o Facebook, Transações de Online Bank ou ATM, o conceito de dados que mudam dinamicamente está se tornando um desafio-chave, o que chamamos de fluxos de dados. Nesse papel,
nós damos o algoritmo para encontrar padrões freqüentes de fluxos de dados com um estudo de caso e identificar os problemas de pesquisa em manipulação de fluxos de dados.

1. Introdução

Mineração de dados é o processo de encontrar padrões e informações escondidas nos dados existentes. A diferença entre o dado no banco de dados e o dado em um data warehouse é que no banco de dados os dados estão sempre de forma estruturada enquanto no data warehouse nem sempre os dados estão estruturados. A  estrutura dos dados devem ser definidas para tornar-lo compatível para processamento. Consequentemente na mineração de dados precisamos de concentrar primeiramente na limpeza dos dados, tornando-o viável para futuros processamentos. O processo de limpeza dos dados tambem é conhecido como eliminação de ruído, redução de ruído ou eliminação de recursos. Ele pode ser feito usando ferramentas como ETL, ferramentas disponíveis no mercado ou pode ser feito usando várias técnicas adequadas disponíveis. O aspecto importante a ser considerado na mineração de dados é se os dados considerados são estáicos ou dinâmicos. A manipulação de dodos estáticos comparados com dados dinâmicos é muito mais fácil. No caso de um conjunto de dados estático, todos os dados estão a disposição para fins de análise antes do processamento e geralmente não são dados que variam com o tempo. No entanto, dados dinâmicos referem a dados continuamente variáveis e volumosos, variam com o tempo e não estão em mãos antes do processamento.

A mineração de dados requer um algorítimo ou método para analizar o dado de interesse.Os dados podem ser dado de sequência, dados sequênciais, séries temporais, espaço-temporais, sinais de audio, sinais de vídeo entre outros. O conceito de fluxo de dados tem ganhou muito interesse prático no campo da mineração de dados. O fluxo de dados é uma sequência infinita de pontos definidos usando marcadores de tempo ou um índice. Nós tambem podemos ver os dados nos fluxos de dados como um vetor multidimensional contendo número inteiro, categórico, gráfico com os dados na forma estruturada ou não estruturado. Se o dado é não estruturado, talvez tenhamos de transformar em um formato compatível para o processamento pelo algorítimo que está sendo usado. Com o altíssimio volume de dados contínuos estruturados e não estruturados sendo gerados por aplicações e dispositívos, o conceito de dado não é mais stático e está se tornando dinâmico. Isto trás muitos desafios na análize de dados. Tradicionalmente os algorítimos de mineração de dados não são compatíveis para manipular fluxo de dados porque os algorítimos projetados realizam várias varreduras sobre os dados, o que não é possível fazer com fluxo de dados. Isso traz um desafio real aos pesquisadores de mineração de dados que estão trabalhando na área de fluxo de dados.

2. Trabalhos Relacionados

No caso de fluxo de dados, o número de recursos distintos ou itens existentes seriam muito grande, o que faria que a memória cache ou memória do sistema disponíveis não seriam adequadas para guardar todo o fluxo de dados. O problema principal com fluxo de dados é a velocidade em que ele chega, pois é mais rápida que a taxa na qual os dados podem ser processados e armazenados.

Na conferência Internacional ACM KDD realizada em 2010,os autores discutiram o problema de encontrar os top-k itens frequentes em fluxo de dados com flexible sliding windows[3]. A idéia é mineirar somente os top-k itens frequentes ao invés de reportar todos os itens frequentes. Mas o fator crucial ou limitação envolvido é a quantidade de memória necessária para mineirar para encontrar os top-k itens envolvidos ainda é um fator limitante. Os autores finalmente discutem que existe, no entanto, um algoritmo eficiente de memória, fazendo algumas suposições.

Em [2] os authores focam em desenvolver um framework para classificar dados que evoluem dinâmicamente considerando os fluxos de treino e teste para classificação dinâmica dos conjuntos de dados. O objetivo é desenvolver um sistema de classificação no qual o sistema de treinamento pode se adaptar para rápidas mudanças do fluxo de dados subjacente.

A quantidade de memória disponível para minereação de fluxo de dados online usando algoritimos de uma passagem é muito menor, portanto, tem chance de perder dados. Também não é possível  mineirar dados online como e onde aparecem por causa da incompatibilidade de velocidade e vários outros fatores significativos.

Em [4] os autores discutem o método de encontrar os itens mais frequentes usando uma abordagem baseada em hash. A idéia é chamar de 'h' as funções de hash e construir uma tabela de hash usando congruências lineares. Fluxo de dados podem ser classificados em dois tipos: Fluxo de dados Offline e Fluxo de dados Online.

Em [6] o método de decomposição do valor singular is used to find a correlação entre multiplos fluxos. O método de SVD era particularmente usado para encontrar fluxo de dados offline. Clusterização de fluxos de dados de texto é um dos tópicos que evoluiram como importante desafio para pesquisas de mineração de dados. O problema de detecção de spam, filtro de email, clusterização de comportamento de clientes, detecção e identificação de tópicos, clusterização de documentos são interesses típicos das pesquisas em mineração de dados.

Em [7], Liu e outros discutem sobre clusterização de fluxo de dados de texto. A ideia é ampliar a semantica existente a qual fuciona bem com fluxo de dados estáticos para clusterização dinâmica de fluxo de dados. Os autores propõem dois algoritimos de clusterização online (OCTS e OCTSM) para clusterização de fluxo de dados massívos de texto.

Uma tremenda quantidade de dados são gerados pela internet a todo instante de várias formas como redes sociais, dados de sensores, facebook e twitter. Os dados que surgem pela internet também são chamados de fluxo de mensagens de texto, que saõ gerados de vários aplicativos de mensagens instantâneas e chats na internet.

Este tornou-se um tema primordial que se tornou um tema de interesse para os pesquisadores que trabalham na área de mineração de dados e tem muito espaço para trabalhar para contribuir com a comunidade de pesquisa.

Na ACM SIGIR, realizada em 2006, os autores, Shen, Yang e outros [8], propuseram  o método de detectar os threads nods fluxos de dados dinâmicos. O artigo discute três variações de algoritimo de clusterização de passagem única seguidos por um novo algorítimo de clusterização baseado em características linguísticas. Um método de redução de dimensão de fluxo de dados usando algorítmos de supervisão escalada é proposto em [9].

As limitações das abordagens de PCA, LDA e MMC são discutidas. Os autores apontam inadequação do MMC para fluxo de dados. Um algorítimo supervisionado de reduçao de dimensão incremental é proposto para encontrar os requisitos do conjunto de fluxo de dados. Em [10] os autores mostram que o resultados mais citados são inválidos.

3. Problemas no tratamento de fluxo de dados nas pesquisas

A tabela [Tabela.1] abaixo mostra a comparação do processamento em banco de dados e em fluxo de dados.

> Tabela.1. Dados processados **X** fluxo de dados 
>
> |Nº|Parâmetro|Banco de dados|Fluxo de dados|
> |----|-----------|----------------|----------------|
> |1|Acesso aos dados|Pode ou não ser sequencial|Sequencial|
> |2|Memória disponível|Flexível|Memória limitada|
> |3|Difusão de dados|Não distribuído|Distribuído|
> |4|Resultado comutacional|Preciso|Aproximado|
> |5|Verificação de dados|Flexível|Limitado a uma verificação|
> |6|Algorítimos|Tempo de processamento não é restrição|Tempo de processamento é mais importante do que dados perdidos|
> |7|Amostras|Não necessário|Complexo de decidir quando obter amostra|
> |8|Velocidade dos dados|Pode ser ignorado|Chegada dos dados é mais rápida que a taxa de processamento|
> |9|Modelagem de dados|Permanente|Modelado como fluxo de dados transientes|
> |10|Esquema de dados|Estático|Dinâmico|

* 3.1 Restrição de memória

O principal fator que precisamos reduzir, no tratamento de fluxo de dados é a quantidade de memória requerida pelo algorítimo de mineração de dados usado ou em desenvolvimento. Os algorítimos desenvolvidos para dados estáticos também chamados de dados non-stream, não são mais viáveis para manipular dados de um fluxo ou fluxo de dados. O desafio em trabalhar com fluxos de dados é que os dados tem sido gerados não são regulares e principalmente com tempo de intervalo irregulares. O foco do algorítimo deve ser essencialmente na otimização da memória utilizada pelo algorítimo de processamento. Uma vez que o dado no fluxo de dados é dinâmico, isto não está em mãos no instande de processa-los e também podem não estar em formato apropriado. A quantidade de dados gerados é geralmente enorme e continua crescendo e aumentando à medida que o tempo avança, isso torna a situação mais complicada ao lidar com dados de fluxo.

* 3.2 Pré-processamento de dados

A tarefa de processar dados é tambem um critério que se deve ter muito cuidado no processo de mineração de dados. O dado de entrada para o algorítimo de mineração de dados não precisa estar em formato adequado e por isso não é adequado para um processamento eficiente. Neste caso, nós precisamos de ver os dados em formato adequado para que este seja adequado para processamento. Este caso geralmente chega quando nós tentamos mineirar dados usando as ferramentas de mineração ou algorítimos existentes. Diferentes ferramentas de mineração disponíveis no mercado tem diferentes formatos de entrada de dados o que faz o usuário a converter o conjunto de dados de entrada existente para o novo formato. ISto por si só consome muito tempo, é trabalhoso e tem a chance de perder dados pois o dados é para ser inserido manualmente dentro de um novo formato que é suportado pela ferramenta.

O segundo fator é o tamanho do dos dados. A dimensão dos dados podem ser muito grande o que torna muito mais complexo para analizar. Muito do tempo de algorítimo é perdido neste caso. Um cuidado adequado deve ser tomado na redução do tamanho dos dados o que por outro lado pode ser muito destrutivo para o tempo de execução dos algorítimos. Por exemplo, se nós consideramos dados em texto, haverá vários recursos que serão desnecessários e indesejados, que não contribuirão para a tomada de decisão ou análise.

Redução da dimensão dos conjuntos de dados de entrada também ajudam na redução de memória necessária e assim alcança a eficiência do algorítimo de mineração de dados.

* 3.3 Desafios no desenvolvimento de algorítimos padrões de mineração de dados

Embora maiores quantidades de memória estejam disponíveis atualmente, o fator memória está dominando o campo da mineração de dados e colocando desafios para os pesquisadores deste campo, mais especificadamente o campo de fluxo de dados. A razão para isso é a exigência de memória principal o que é normalmente muito menor comparado a outras memórias disponíveis fora do processador. Desenvolver algorítimos padrões para lidar com fluxo de dados é um tanto quanto trabalhoso, pois temos a limitação de memória principal. Encontrar itens frequentes usando algorítimo de passagem simples é também impraticável no caso de trabalho com fluxo de dados por causa da natureza dinâmica do fluxo de dados.

* 3.4 Escolha da estrutura dos dados

A escolha de uma estrutura adequada e efetiva é também um dos critérios que necessitam de cuidados no desenvolvimento  de algorítimos para fluxo de dados.

* 3.5 Identificando distribuições de dados e conceitos de destino

Outro fator importante ao considerar mineração de fluxo de dados é identificar as mudanças nas distribuições de dados e conceitos de destino no decorrer do tempo. Identificando e explorando estas variações e adaptando classificadores adequados aos desvios de conceito também é um dos maiores desafios para os pesquisadores de mineração de dados desenvolverem novos algorítimos escalaveis para trabalhar com fluxo de dados.

* 3.6 Redução da dimensão

Embora as técnicas matemáticas ou estatísticas estavam disponíveis na literatura anteriormente, a importância e adequação dessas técnicas estão sendo muito exploradas pelos pesquisadores de mineração de dados muito recentimente. O problema da redução de dimensão é estudada aplicando as abordagens matemática e estatística. No entanto, lidar com dimensionalidade ainda é um problema na mineração de dados quando se trabalha com dados estáticos ou dinâmicos.

4. Padrões frequentes dos fluxos de dados

Consideramos o método de encontrar os itens frequentes de um fluxo de dados usando sliding windows(janelas deslizantes). Seja S a janela deslizante de tamanho n com I = {i1, i2, i3...im} como conjunto de todos os itens disponíveis. Dependendo do tipo de transação feita, a transação Tj pode conter todo o conjunto de itens indicados através de I ou apenas um conjunto apropriado de I como seus itens.

Seja A e B dois itens quaisquer na transação. O vetor binário para A e B é demonstrado por Bin-Vector(A) e  Bin-Vector(B).

Agora, como o tamanho da janela deslizante é restrito a contar n transações, restringimmos a representação do vetor binário dos itens A e B para ser na forma de vetor binário n-bit como no exemplo:

> Vetor_Binario(A) = A1 A2 A3 A4... An
>
> Vetor_Binario(B) = B1 B2 B3 B4... Bn
>
> *Onde n é o tamanho da janela deslizante.*

Se um item A é presente na transação Ti então o bit do Vetor_Binario(A) correspondente é setado em 1. Igualmente, se o item A não  está presente na transação Ti o bit do Vetor_Binario(A) correspondente é setado em 0. Isto é demonstrado como os nós primeiro nível do Padrão Frequente de Geração de Árvores chamado FPGT (Frequent-Pattern-Generation-Tree) - [fig.1].

* **Definição.1.** Seja Bit-1 e Bit-2 dois números ternários de um bit. Definimos a função F sobre Bit-1 e Bit-2 como na tabela.2



















* Referências

[1] Bifet A, Holmes G, et.al. Mining Frequent Closed graphs on evolving data streams. Proceedings of 17th ACM SIGKDD International
Conference on knowledge discovery and data mining, 2011: 591-98.

[2] Charu C. Aggarwal, Jiawei Han, Philip S. Yu. On Demand Classification of Data Streams, in the proceedings of ACM KDD’04, USA, 2004.

[3] Hoang Thanh Lam, Toon Calders, Mining Top-K Frequent Items in a Data Stream with Flexible Sliding Windows. Proceedings of in the
proceedings of ACM KDD’10, USA, 2010.

[4] Cheqing Jin et.al. Dynamically Maintaining Frequent Items over a Data Stream, in the proceedings of CIKM USA, 2003.

[5] Nan Jiang and Le Grunewald. Research Issues in Data Stream Association Rule Mining, SIGMOD Record, 2006: 35(1).

[6] Sudipta Guha, D.Gunopulos, N. Kaudas. Correlating synchronous and asynchronous data streams, in the proceedings of SIGKDD 2003 held
from august 24th -27th, USA, 2003.

[7] Yu.Bao.Liu et.al. Clustering Text data streams, Journal of computer science and technology, volume 23, issue 1, pages 112-128, 2008.

[8] Dou Shen,Qiang Yang, Jian-Tuo-Sun, Zheng Chen. Thread Detection in Dynamic Text Message Streams, in the proceedings of SIGIR USA, 2003.

[9] Jun Yan et.al. A scalable supervised algorithm for dimensionality reduction on streaming data. Information Sciences, An International
Journal, Published by Elsevier, 2006; 176: 2042-65.

[10] L.Rutkowski et.al. Decision trees for mining data streams based on the McDiarmid’s bound. IEEE Transactions on Knowledge and Data
Engineering, 2013; 25(6).

[11] Jun Yan et.al, “Effective and Efficient Dimensionality Reduction for Large-Scale and Streaming Data Preprocessing”, published in the IEEE
Transactions on Knowledge and Data Engineering, 2006; 18(2).

[12] Graham Cormode et.al. Comparing Data Streams Using Hamming Norms (How to Zero In). IEEE Transactions on Knowledge and Data
Engineering, 2003; 15(3).

[13] Chen Ling, Zou Ling-Jun, Tu Li, Clustering algorithm for multiple data streams based on spectral component similarity, Information
Sciences, An International Journal, Published by Elsevier, 2012; 183: 35-47.

[14] Panagiotis Antonellis, Christos Makris, Nikos Tsirakis. Algorithms for clustering click stream data. Information Processing Letters 109,
published by Elsevier, 2009: 381–385.

[15] Chang-Dong Wang, Dong Huang. A support vector based algorithm for clustering data streams, published in the IEEE Transactions on
Knowledge and Data Engineering, 2013; 25(6).

[16] Shi Zhong. Efficient streaming text clustering, Neural Networks, Neural Networks, published by Elsevier, 2005;18: 790–798.

[17] Pedro Pereira Rodrigues, Joao Gama and Joao Pedro Pedroso, “Hierarchical Clustering of Time Series Data Streams”, published in the IEEE
Transactions on Knowledge and Data Engineering, 2008; 20(5).

[18] Vaneet Aggarwal, Shankar Krishnan. Achieving Approximate Soft Clustering in Data Streams, 2012. http://arxiv.org/abs/1207.6199.

[19] Haiyan Zhou, Xiaolin Bai, Jinsong Shan.A Rough-Set-based Clustering Algorithm for Multi-stream. Procedia Engineering, 2011; 15: 1854-58.

[20] Hua-Fu Li, Suh-Yin Lee. Approximate mining of maximal frequent itemsets in data streams with different window models, Expert Systems
with Applications, 2008; 35: 781–789.

[RETORNAR]

[RETORNAR]: https://github.com/hemilioaraujo/traducaoTrabalho/blob/master/README.md

[Sliding Window]: https://www.coursera.org/lecture/machine-learning/sliding-windows-bQhq3
