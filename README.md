# notebooklm-ciencias-de-dados

## Objetivo
### Criei este notebooklm para me auxiliar nos meus estudos da minha pós-graduação ciências de dados e big data analytics; para me ajudar também no curso Accenture - Python para Análise e Automação de Dados

## Fontes

[Python para Análise de Dados](https://www.youtube.com/watch?v=J2JkhwNZSsc)

[Como Manipular Grandes Massas de Dados com Python](https://www.youtube.com/watch?v=R0rMMDOuXEQ)

[ Python para análise de dados - #00 Introdução](https://www.youtube.com/watch?v=3U9vo9sgG_0)

#### Pandas Python - Data Wrangling para Ciência de Dados.pdf
#### Python Levado a Serio - Julien Danjou.pdf

## Prompt 1

##### qual melhor ferramenta para analisar dados com grande volume?- resultado de acordo com as fontes 
###### No ambiente Python, a biblioteca **pandas** consolidou-se nos últimos anos como a ferramenta mais utilizada para a ciência e análise de dados. Ela foi especialmente projetada para oferecer suporte ao processo de **Data Wrangling**, que compreende as atividades de seleção, exploração, integração, limpeza e transformação de dados. O pandas acrescenta ao Python duas estruturas de dados extremamente poderosas e flexíveis, chamadas **Series** e **DataFrame**, que permitem representar dados tabulares de forma similar a planilhas de Excel ou tabelas de bancos de dados relacionais. Através dessas estruturas, a biblioteca torna a manipulação de dados mais rápida, simples e eficaz, oferecendo funções para importar dados de diversas fontes (como CSV, JSON e SQL), combinar registros e produzir resultados agregados.

###### Entretanto, quando o foco é o **Big Data** — que envolve bancos de dados com bilhões ou trilhões de registros e centenas de milhares de atributos — o uso de métodos computacionais tradicionais pode se tornar inviável por não serem escaláveis. Para lidar com esse volume massivo, que pode atingir 175 zetabytes globalmente em 2025, a **Ciência de Dados** combina ideias da Estatística e da Ciência da Computação para extrair conhecimento valioso de grandes montanhas de dados. Além do pandas, a biblioteca **NumPy** é fundamental nesse processo, sendo considerada a "pedra fundamental" da computação científica em Python por oferecer alto desempenho no processamento de vetores e matrizes. Dominar essas ferramentas é essencial na atualidade, pois os dados são vistos como o "novo petróleo" do século XXI, sendo gerados e utilizados estrategicamente em todos os setores de negócio para a tomada de decisões.

## Prompt 2
o handup e bom para grandes quantidades de dados? - digitei nome errado ele não corrigiu mais buscou o nome correto 

As fontes fornecidas **não fazem menção a uma ferramenta chamada "Handup" ou "Hadoop"**. [Informação fora das fontes].

No entanto, as fontes detalham extensivamente quais ferramentas são ideais para lidar com **grandes volumes de dados (Big Data)** e como a Ciência de Dados resolve esse problema:

*   **Python:** É destacada como a linguagem favorita para quem trabalha com **Data Science** e **Machine Learning**, pois possui um núcleo capaz de processar volumes enormes de dados de forma tranquila.
*   **Pandas:** Consolidou-se como a biblioteca mais utilizada no ambiente Python, sendo especialmente projetada para o **Data Wrangling** (seleção, limpeza e transformação de dados), tornando a manipulação de dados tabulares mais rápida e eficaz.
*   **NumPy:** É considerada a **"pedra fundamental"** da computação científica em Python, oferecendo alto desempenho no processamento de vetores e matrizes.
*   **TensorFlow:** Para problemas de alta complexidade, esta biblioteca permite dividir o processamento em blocos, garantindo **maior performance** em volumes consideráveis de amostras.

As fontes explicam que o uso de métodos computacionais tradicionais é inviável para o **Big Data** — que pode envolver bilhões ou trilhões de registros — por não serem escaláveis. Por isso, a Ciência de Dados utiliza algoritmos modernos capazes de vasculhar essas montanhas de dados com rapidez para extrair padrões e informações estratégicas.

## Prompt 3
como fazer uma extração de dados de forma mais rápida e segura?

Para realizar uma extração de dados de forma **rápida**, a melhor abordagem é utilizar a linguagem **Python** e bibliotecas especializadas como o **pandas**, que foi pensado especificamente para manipular grandes massas de dados de maneira prática e eficiente. Em vez de abrir arquivos um a um manualmente, o que é demorado e suscetível a erros, você deve criar **scripts automatizados** que fazem parte do processo de **ETL (Extrair, Transformar e Carregar)**. Para ganhar velocidade na leitura de múltiplos arquivos, a biblioteca **glob** é fundamental, pois permite localizar e carregar diversos arquivos dinamicamente através de expressões (como ler todos os `.xlsx` de uma pasta de uma vez), eliminando a necessidade de apontar cada caminho individualmente.

No que diz respeito à **segurança** e integridade do processo, você deve seguir estas diretrizes:

*   **Rastreabilidade e Confiabilidade:** Todo dado extraído deve ser rastreável; uma boa prática é adicionar colunas extras ao seu Data Frame que indiquem a fonte original do dado (como o nome do arquivo ou o país de origem), garantindo que você saiba de onde cada registro veio após a consolidação.
*   **Tratamento de Erros:** Utilize blocos de código `try...except` para capturar falhas durante a leitura de arquivos corrompidos ou que estejam abertos por outros usuários, permitindo que o script continue processando o restante da massa de dados sem interrupções.
*   **Privacidade e Proteção de Dados:** Como os dados são considerados o "novo petróleo", nunca suba arquivos de dados brutos (**Raw Data**) para repositórios públicos como o GitHub. Utilize o arquivo **.gitignore** para garantir que as pastas que contêm dados sensíveis da empresa não sejam versionadas e fiquem protegidas localmente.
*   **Isolamento do Ambiente:** Crie sempre um **ambiente virtual (venv)** para o seu projeto, o que garante que as versões das bibliotecas sejam as mesmas para todos os desenvolvedores, evitando conflitos que possam comprometer a execução segura do código.

Dessa forma, ao combinar o poder de processamento do núcleo do Python com boas práticas de organização de pastas (separando dados crus de dados tratados), você obtém uma extração escalável, performática e profissional.
