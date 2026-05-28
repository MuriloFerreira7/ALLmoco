# Introdução
Este documento apresenta a visão geral de um sistema voltado ao planejamento e gerenciamento operacional de um Restaurante Estudantil. A proposta consiste no desenvolvimento de uma aplicação capaz de integrar o planejamento do cardápio com o controle de estoque e a geração de demandas de compra, auxiliando a gestão de insumos alimentícios e produtos perecíveis. Além disso, o sistema busca oferecer uma experiência rápida e prática, adequada à rotina dinâmica do ambiente de utilização.

# Problema
Com a inauguração do Restaurante Estudantil do IFPR Campus Cascavel, a escala das operações relacionadas ao planejamento alimentar e à gestão de suprimentos tende a aumentar significativamente. Atualmente, o controle é realizado por meio de planilhas eletrônicas simples, abordagem que atende pequenas demandas, mas se torna limitada em operações de maior volume.

Entre os principais problemas identificados estão:

Cálculo manual de insumos: atualmente, a definição da quantidade de produtos necessários depende da soma manual dos ingredientes exigidos por cada prato do cardápio. Esse processo aumenta a probabilidade de erros, podendo resultar tanto na falta de alimentos quanto no desperdício de recursos públicos.

Risco sanitário relacionado à validade: o controle de produtos perecíveis em planilhas é passivo, não havendo alertas automáticos sobre lotes próximos do vencimento. Isso eleva o risco de perdas de estoque ou da utilização de itens fora do prazo de validade.

Dificuldade de planejamento: a ausência de projeções de médio prazo dificulta o planejamento do setor de compras, reduzindo a capacidade de negociação com fornecedores e comprometendo a garantia do abastecimento necessário. 

# Objetivo 
O objetivo do nosso sistema é resolver todos os problemas presentes no dia a dia com tecnologias inovadoras que não tragam maiores dificuldades. O sistema busca resolver um problema complexo de forma extremamente simples e intuitiva para quem o usa.   ]

# Proposta de aplicativo
Como solução para os problemas identificados, propõe-se o desenvolvimento de uma aplicação voltada ao gerenciamento do Restaurante Estudantil do IFPR Campus Cascavel, integrando planejamento de cardápio, controle de estoque, monitoramento de validade e emissão de relatórios. O objetivo do sistema é reduzir processos manuais, minimizar desperdícios e auxiliar a tomada de decisão, sem tornar a rotina dos usuários mais complexa ou burocrática.

A aplicação será estruturada de forma simples e intuitiva, permitindo que nutricionistas, responsáveis pelo estoque e setor de compras realizem suas atividades rapidamente, mesmo em momentos de alta demanda. A tela principal do sistema funcionará como um painel de acompanhamento rápido, exibindo informações importantes, como produtos próximos ao vencimento, necessidades de compra pendentes e o cardápio da semana atual. Dessa forma, informações críticas poderão ser visualizadas sem a necessidade de navegar por várias telas.

No gerenciamento de estoque, o sistema permitirá o cadastro e acompanhamento de alimentos com informações como quantidade disponível, lote e data de validade. Os produtos serão organizados automaticamente com base na proximidade do vencimento, seguindo a lógica FEFO (First Expire, First Out), que prioriza a utilização dos itens que vencem primeiro. Além disso, o sistema emitirá alertas configuráveis, considerando que diferentes tipos de alimentos exigem diferentes cuidados e prazos de utilização, permitindo que o nutricionista adapte avisos conforme a necessidade de cada produto.

A elaboração do cardápio ocorrerá de forma organizada, sendo estruturada em períodos mensais, divididos por semanas, dias e refeições. Durante a montagem, o sistema exibirá automaticamente a disponibilidade estimada dos ingredientes no estoque e calculará a quantidade necessária de cada produto com base nos pratos selecionados. Assim, será possível visualizar rapidamente se o estoque atual é suficiente, se existe risco de vencimento de alimentos antes do uso ou se haverá necessidade de novas compras. Para facilitar ainda mais esse processo, o sistema permitirá importar planilhas utilizadas pelo nutricionista, reduzindo o tempo gasto com inserções manuais e criando automaticamente cardápios e pratos no sistema.

Como forma de reduzir desperdícios, a aplicação contará com uma funcionalidade de sugestão de pratos baseada na validade dos alimentos disponíveis. O sistema identificará ingredientes próximos do vencimento e recomendará receitas já cadastradas que utilizem esses produtos, incentivando o aproveitamento adequado dos insumos antes da perda. Além disso, por se tratar de um Restaurante Universitário, os cálculos relacionados às datas considerarão apenas dias úteis, evitando recomendações incorretas em finais de semana, feriados ou períodos sem funcionamento do restaurante.

A plataforma também oferecerá relatórios voltados à gestão do restaurante, permitindo a emissão de documentos de demanda de compras, indicando o que precisa ser adquirido, em qual quantidade, para qual período e por qual motivo. Também estarão disponíveis relatórios de produtos próximos ao vencimento e versões simplificadas do cardápio para exibição aos alunos, apresentando apenas as refeições previstas e seus respectivos horários.

Por fim, planeja-se a implementação da tecnologia PWA (Progressive Web App), permitindo que partes importantes do sistema continuem acessíveis mesmo sem conexão com a internet. Isso possibilitará a consulta de informações já carregadas anteriormente, reduzindo impactos causados por instabilidades de rede e garantindo maior praticidade no uso diário.

A proposta busca, portanto, oferecer uma ferramenta de apoio à rotina do Restaurante Estudantil, automatizando cálculos e centralizando informações importantes de forma clara e acessível. Em vez de adicionar complexidade à operação, o sistema pretende reduzir retrabalho e agilizar processos, permitindo que os usuários foquem na organização do serviço e na qualidade da alimentação oferecida.