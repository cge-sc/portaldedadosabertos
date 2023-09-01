# 🎲 O que são Dados Abertos Governamentais?

{% hint style="info" %}
Dados abertos governamentais são aqueles produzidos ou custodiados pelo Estado e que podem ser livremente utilizados, reutilizados e redistribuídos por qualquer pessoa. A única exigência que pode ser feita é a atribuição à fonte original e compartilhamento pelas mesmas licenças em que as informações foram apresentadas.
{% endhint %}

A abertura de dados está interessada em evitar um mecanismo de controle e restrições sobre os dados que forem publicados, permitindo que tanto pessoas físicas quanto jurídicas possam explorar estes dados de forma livre ([Open Definition](https://opendefinition.org/), 2014).

Como premissas básicas, um dado só pode ser considerado aberto se (OPEN KNOWLEDGE, 2012):

* **Disponibilidade e acesso:** estiver disponível por inteiro, em formato conveniente e modificável;
* **Reuso e redistribuição:** estiver em condições de reuso e redistribuição, podendo ser combinado com outros; e
* **Participação universal:** todos podem usar, reusar e redistribuir o dado sem restrições de áreas, pessoas ou grupos.

## Por que abrir?

Países considerados sociedades da informação, como Alemanha, Japão e Reino Unido, possuem a maior parte de seu Produto Interno Bruto - PIB - relacionado a bens intangíveis. Essas nações dependem de uma constante e massiva geração e consumo de dados para manter-se em funcionamento e em crescimento (Isotani; Bittencourt, 2015).&#x20;

Nas sociedades do conhecimento, os dados são considerados recursos extremamente valiosos e precisam estar disponíveis para:

* geração de desenvolvimento econômico e social;
* melhoria dos serviços públicos prestados ao cidadão; e
* aumento da transparência, controle social e confiança no governo.

O [Tribunal de Contas da União](https://portal.tcu.gov.br/5-motivos-para-a-abertura-de-dados-na-administracao-publica.htm) (2015), por sua vez, elenca os seguintes motivos para abertura de dados na administração pública:

* exigência legal;
* necessidade de mais transparência na gestão pública;
* estímulo à criação de serviços inovadores;
* aprimoramento da qualidade dos dados públicos; e
* viabilização de novos negócios.

## Qualidade dos Dados Abertos

Tim Bernes-Lee, cientista da computação, professor do MIT e um dos criadores da Internet, propôs um sistema de cinco estrelas para qualidade de abertura de dados ([Berners-Lee, 2010](https://pt.wikipedia.org/wiki/Tim\_Berners-Lee)).

Para o pesquisador, a preparação dos dados para disponibilização à sociedade ocorre por meio de uma série de transformações intermediárias. Ela se inicia em formato de licença aberta (OL) e aprimora sua qualidade até o nível em que são considerados dados abertos conectados (linked open data).

<figure><img src="../.gitbook/assets/5-star-steps.png" alt=""><figcaption><p>5 estrelas </p></figcaption></figure>

Os níveis podem ser assim descritos:

* **Open Licence (OL)** - Disponível na Internet (qualquer formato, por exemplo PDF), desde que com licença aberta, para que seja considerado um dado aberto;
* **Readable (RE) -** Disponível na Internet de maneira estruturada (em um arquivo Excel, com extensão XLS);
* **Open Format (OF) -** Disponível na Internet, de maneira estruturada e em formato não proprietário (CSV em vez de Excel);
* **Uniform Resource Identifier (URI) -** Utilização de padrões da [W3C](https://www.w3c.br/) (RDF e SPARQL), usar URL para identificar coisas e propriedades, de forma que as pessoas possam direcionar para suas publicações; e
* &#x20;**Linked Open Data (LD) -** Todas as regras anteriores, adicionando a conexão dos seus dados a outros dados, de forma a fornecer um contexto.

## Formatos de arquivos

Existem diversos formatos de arquivos não proprietários para a distribuição de dados em formato aberto. Dentre eles, os mais adequados são (RAUTEMBERG, 2018):

* **RDF** - Resource Description Framework: é uma linguagem que usa um modelo padrão para a troca de dados na web. Ela tem forma de triplas, realizando a descrição de um recurso em três partes, ligando um sujeito (recurso) a um objeto através de um predicado. Isso gera uma estrutura de ligações que, por sua vez, formam um grafo RDF;
* **PAQRQUET** - O Parquet é um formato binário que permite o armazenamento dos dados utilizando alguns tipos específicos, como: o BOOLEAN, INT32, INT64, INT96, FLOAT, DOUBLE e BYTE\_ARRAY. Os metadados no Parquet, incluindo esquema e estrutura, são integrados individualmente em cada arquivo tornando o formato de arquivo em autodescritivo;
* **XML** - Extensible Markup Language: é uma linguagem de marcação extensível que usa um formato padrão para a descrição e troca na web. Os dados são organizados de forma hierárquica, permitindo a representação de todos os tipos de estruturas de dados;
* **CSV** - Comma-Separated Values: é um formato para armazenar dados tabulares em texto, e cada linha do arquivo apresenta um registro. Cada registro é composto de um ou mais campos separados por vírgula. É usado para apresentar dados de estruturas simples, diretamente processados por editores de planilhas ou de texto;
* **JSON** - JavaScript Object Notation: é um formato para a troca de dados, de fácil escrita e leitura para pessoas e fácil análise e geração para máquinas. É construído sobre duas estruturas: i) uma coleção de pares nome/valor; ii) uma lista ordenada de valores. Ambas as estruturas são amplamente usadas em linguagens de programação, facilitando o seu entendimento e uso;
* **ODS** - Open Document Spreadsheet: é um formato não proprietário para arquivo de planilhas, baseado em XML;
* **SVG** - Scalable Vector Graphics: é um formato para descrição e troca de imagens e grafos bidimensionais, dados vetoriais e gráficos na web; e
* **GML** - Geography Markup Language: é um formato para troca de dados geográficos baseado em XML.
