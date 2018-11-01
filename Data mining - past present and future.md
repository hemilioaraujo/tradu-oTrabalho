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

A tabela abaixo mostra a comparação do processamento em banco de dados e em fluxo de dados.

|Nº|Parâmetro|Banco de dados|Fluxo de dados|
|----|-----------|----------------|----------------|
|1|Acesso aos dados|Pode ou não ser sequencial|Sequencial|
|2|Memória disponível|Flexível|Memória limitada|
|3|Difusão de dados|Não distribuído|Distribuído|
|4|Resultado comutacional|Preciso|Aproximado|
|5|Verificação de dados|Flexível|Limitado a uma verificação|
|6|Algorítimos|Tempo de processamento não é restrição|Tempo de processamento é mais importante do que dados perdidos|
|7|Amostras|Não necessário|Complexo de decidir quando obter amostra|
|8|Velocidade dos dados|Pode ser ignorado|Chegada dos dados é mais rápida que a taxa de processamento|
|9|Modelagem de dados|Permanente|Modelado como fluxo de dados transientes|
|10|Esquema de dados|Estático|Dinâmico|


[RETORNAR]

[RETORNAR]: https://github.com/hemilioaraujo/traducaoTrabalho/blob/master/README.md
