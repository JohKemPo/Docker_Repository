<h1 align="center" id="head"><b>DOCKER REPOSITORY<b></h1>

<p align="center"><b>STUDY ABOUT DOCKER AND ITS APPLICATIONS</b><p>

<br>

<p align="justify">&emsp; Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
<br>
<br>
<br>

<h2 align="center"> S U M M A R Y </h2>
<br>

1. [Espailer ( Artigo )](#Espailer)
2. [TreeMerge ( Artigo )](#TreeMerge)
3. [PhyloFinder ( Artigo )](#PhyloFinder)
4. [Bibliotecas](#Bibliotecas)
    * [Dendropy](#Dendropy)
    * [Espailer](#Espailer)
    * [Tskit](#Tskit)
5. [Ferramentas Úteis](#Ferramentas)
    * [ITOL](#ITOL)
6. [Equipe](#Equipe)    
7. [Apêndice](#Apendice)

<hr>
<br>

<h2 id="Espailer"><a href="">Lorem Ipsum</a></h2><br>

<h4>Useful links:</h4><br>

- <a href="https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009960"> ARGs - Inferência bayesiana de gráficos de recombinação ancestral </a>
- <a href="https://pubmed.ncbi.nlm.nih.gov/31975170/"> ARGs - Inferência de gráficos de recombinação ancestral usando ARGweaver </a>


<p align="justify">&emsp; </p><br>

<!--------------------------------------------------------------------------->

<h2 id="TreeMerge"><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6612878/">TreeMerge ( Artigo )</a></h2><br>

<p align="justify">&emsp; </p><br>

<h2 id="PhyloFinder"><a href="https://pubmed.ncbi.nlm.nih.gov/18366717/">PhyloFinder ( Artigo )</a></h2><br>

<p align="justify">&emsp; </p><br>
<!--------------------------------------------------------------------------->



<h2 id="Bibliotecas">Bibliotecas</h2><br>

<p align="justify">&emsp; No projeto em questão, utilizaremos bibliotecas específicas que são fundamentais para a sua execução. Essas bibliotecas foram selecionadas cuidadosamente e suas documentações e exemplos estão disponíveis abaixo para facilitar o desenvolvimento do projeto.</p><br>

<p align="justify">&emsp; Certifique-se de consultar a documentação e exemplos de cada biblioteca para entender melhor como elas funcionam e como podem ser utilizadas no projeto. Com o conhecimento adequado sobre essas bibliotecas, podemos garantir um projeto mais eficiente e bem sucedido.</p><br>

<h3 id="Dendropy"><a href="https://dendropy.org/">Dendropy</a></h3><br>

<p align="justify">&emsp; DendroPy é uma biblioteca Python para computação filogenética. Ele fornece classes e funções para a simulação, processamento e manipulação de árvores filogenéticas e matrizes de caracteres, e suporta a leitura e escrita de dados filogenéticos em uma variedade de formatos, como NEXUS, NEWICK, NeXML, Phylip, FASTA, etc. scripts para executar algumas operações filogenéticas úteis, como conversão de dados e resumo da distribuição posterior da árvore, também são distribuídos e instalados como parte da biblioteca. O DendroPy pode, portanto, funcionar como uma biblioteca independente para filogenética, um componente de pipelines filoinformáticos multibibliotecas mais complexos ou como uma “cola” de script que monta e conduz tais pipelines.</p><br>

<h4>Links importantes:</h4><br>

- <a href="https://dendropy.org/primer/index.html">Dendropy doc</a><br>
- <a href="https://dendropy.org/search.html?q=raxml">Dendropy Raxml</a><br>
- <a href="https://github.com/JohKemPo/BioComp/blob/main/Codes/Dendropy.ipynb">Dendropy notebook</a><br>
- <a href="https://github.com/jeetsukumaran/DendroPy">Dendropy examples repository</a><br>

<p align="justify">&emsp; </p><br>

<h3 id="Dendropy"><a href="https://espalier.readthedocs.io/en/latest/">Espailer</a></h3><br>

<p align="justify">&emsp; Espalier reconcilia eficientemente árvores filogenéticas discordantes e reconstrói ARGs usando florestas de concordância máxima. Uma floresta de concordância entre um par de árvores é um conjunto de subárvores que são topologicamente concordantes entre ambas as árvores. A concordância topológica pode ser formalmente definida em termos de bipartições. Cada ramificação ou aresta em uma árvore define uma bipartição do conjunto de táxons X da árvore em dois conjuntos disjuntos.</p><br>

<h4>Links importantes:</h4><br>

- <a href="https://github.com/JohKemPo/BioComp/blob/main/Espalier.md">Espailer markdown</a><br>
- <a href="https://github.com/JohKemPo/BioComp/blob/main/Codes/Espalier.ipynb">Espailer notebook</a><br>
- <a href="https://espalier.readthedocs.io/en/latest/primer.html#computing-maximum-agreement-forests">Espailer primer</a><br>
- <a href="https://github.com/davidrasm/Espalier/blob/master/examples/reconciliation.py">Espailer examples repository</a><br>


<p align="justify">&emsp; </p><br>

<h3 id="Dendropy"><a href="https://tskit.dev/tskit/docs/stable/python-api.html">Tskit</a></h3><br>

<p align="justify">&emsp; kit de ferramentas de sequência de árvore. Sequências de árvores sucintas fornecem uma maneira altamente eficiente de armazenar um conjunto de sequências de DNA relacionadas, codificando sua história ancestral como um conjunto de árvores correlacionadas ao longo do genoma. A história evolutiva das sequências genéticas é muitas vezes referida tecnicamente como um Gráfico de Recombinação Ancestral (ARG); as sequências de árvores sucintas são totalmente compatíveis com esta formulação e, portanto, o tskit é uma plataforma poderosa para o processamento de ARGs.</p><br>

<h4>Links importantes:</h4><br>

- <a href="https://github.com/JohKemPo/BioComp/blob/main/Codes/Tskit.ipynb">Tskit notebook</a><br>


<p align="justify">&emsp; </p><br>

<!--------------------------------------------------------------------------->

<h2 id="Ferramentas">Ferramentas Úteis</h2><br>
<p align="justify">&emsp; Para garantir o sucesso do projeto, é importante utilizar as ferramentas adequadas. Nesse sentido, algumas ferramentas foram selecionadas e suas documentações e exemplos estão disponíveis abaixo:</p><br>

<h3 id="ITOL"><a href="https://itol.embl.de/">ITOL - Interactive Tree Of Life</a></h3><br>

<p align="justify">&emsp; Interactive Tree Of Life é uma ferramenta on-line para exibição, anotação e gerenciamento de árvores filogenéticas e outras.Gerencie e visualize suas árvores diretamente no navegador e anote-as com vários conjuntos de dados.</p><br>

![image](https://user-images.githubusercontent.com/74382074/199243693-ec326864-a849-4033-a27a-245bbadcfef2.png)
<spam><i>Exemplo de arvore gerada</i></spam>
<br>
<br>

<!--------------------------------------------------------------------------->

<h2 id="Apendice">Apêndice</h2><br>

<h3><a href="https://thihenos.medium.com/o-que-%C3%A9-uma-pipeline-para-desenvolvimento-de-softwares-para-iniciantes-9fc26150178e">Pipeline</a></h3><br>

<p align="justify">&emsp; A origem da palavra vem do inglês, que podemos entender como um duto ou tubo daqueles que podem passar oléo, água ou qualquer outro material liquido ou gasoso. O termo também vem sendo muito utilizado em indústria como um conjunto de instrução, ou uma esteira de processos ou comandos que alguém ou algo deve seguir sempre, por exemplo uma pipeline de vendas, onde tem sempre os passos e estratégias a serem seguidas.</p><br>
<p align="justify">&emsp; No mundo da engenharia da computação, o termo pipelining é utilizado para descrever a estratégia onde o CPU procura a próxima instrução para executar, como se numa esteira de instruções já enviadas que são executadas, um comando após o outro.</p><br>


<h3><a href="https://orthomcl.org/orthomcl/app">OrthoMCL </a></h3> 

<i>árvore esteja no formato Newick, Nexus ou phyloXML.</i><br>


<p align="justify">&emsp; OrthoMCL é um algoritmo em escala genômica para agrupar sequências de proteínas ortólogas. Essas sequências ortólogas não apenas compartilham a história evolutiva, mas também compartilham a função. Assim, a previsão ortóloga é importante para prever a função de proteínas recém-identificadas. De fato, a detecção de ortólogos tornou-se mais difundida com o rápido progresso no sequenciamento do genoma e a descoberta de sequências de proteínas ( Glover et al. 2019 ). É importante ressaltar que as proteínas nos grupos OrthoMCL demonstraram exibir um alto grau de conservação funcional (por exemplo, as proteínas de um grupo têm números EC consistentes) ( Li et al. 2003 ), destacando que OrthoMCL é útil para anotação funcional de genomas recém-sequenciados.</p><br>


<h4> Links importantes:</h4><br>

- <a href="https://orthomcl.org/orthomcl/app#orthosearches">Tipos de buscas em OrthoMCL</a><br>


<br>

<h3><a href="https://blog.varsomics.com/fasta-como-realizar-a-leitura-de-sequencias/">FASTA: como realizar a leitura de sequências? </a></h3><br>

<p align="justify">&emsp; A Sequência FASTA é um dos formatos mais versáteis de informações para análises de bioinformática, na qual pode ser feita com diferentes algoritmos e softwares. Por exemplo, é possível realizar a comparação de uma sequência contra um banco de dados para entender o que já é conhecido sobre sequências similares (sequências similares podem ter funções similares).</p><br>

<h3><a href="https://cran.r-project.org/web/packages/TreeTools/vignettes/load-trees.html">Loading phylogenetic trees into R</a></h3><br>

<p align="justify">&emsp; A Sequência FASTA é um dos formatos mais versáteis de informações para análises de bioinformática, na qual pode ser feita com diferentes algoritmos e softwares. Por exemplo, é possível realizar a comparação de uma sequência contra um banco de dados para entender o que já é conhecido sobre sequências similares (sequências similares podem ter funções similares).</p><br>

<h3><a href="https://www.uniprot.org/">Uniprot</a></h3><br>

- Alinhamento
- Banco de dados

<br>
<p align="justify">&emsp; O UniProt é o principal recurso mundial de alta qualidade, abrangente e livremente acessível de sequências de proteínas e informações funcionais. </p><br>


<h3><a href="https://bioinformatics.phylolab.net/form/tree-format-conversion">WebPhy</a></h3><br>

<p align="justify">&emsp; Existem dois formatos principais de arquivos de árvore - newick e nexus. Esta ferramenta pode converter um formato de tipo ( test.tre ) para outro tipo ( test.nexus.tre ). Vários arquivos são permitidos, mas devem ser carregados como um arquivo zip. Após o envio, um link exclusivo da web será gerado para que os usuários baixem o resultado da análise. </p><br>

### **Qual o processo de criação de uma arvore apartir de um arquivo FASTA?**

#### **1 - O que é um arquivo fasta?**

<p align="justify"> &emsp; Ele contém sequências de aminoácidos com informações adicionais no cabeçalho começando com o caractere ">". Cada sequência começa com uma linha contendo o cabeçalho e a sequência de aminoácidos segue em uma ou mais linhas abaixo.</p>

#### **2 - O que é preciso para a construção de uma árvore filogenética?**

<p align="justify"> &emsp; O arquivo fasta contém sequências de proteínas com seus identificadores e descrições, mas não há informações sobre relações evolutivas entre essas proteínas.</p>
<p align="justify"> &emsp; Para construir uma árvore filogenética, é preciso de informações adicionais, como <b>alinhamentos de sequências de proteínas ou sequências de DNA</b>, que permitiriam inferir relações evolutivas entre as proteínas.</p>

#### **3 - Como é o funcionamento de alinhamento de sequências de proteínas**

<p align="justify"> &emsp; O processo de alinhamento de sequências de proteínas envolve comparar as sequências e identificar as posições onde os aminoácidos são iguais ou similares. O resultado é uma matriz que mostra a correspondência entre as posições das sequências e os aminoácidos que ocupam essas posições. Com base nessa matriz, os programas de alinhamento realizam ajustes nas sequências para maximizar a semelhança entre elas, produzindo o alinhamento final.</p>

<p align="justify"> &emsp; Após o alinhamento das sequências, pode-se construir uma árvore filogenética que mostra as relações evolutivas entre as sequências. Esse processo envolve a seleção de um modelo evolutivo, que descreve as taxas de evolução das sequências, e a construção da árvore usando métodos como Neighbor-Joining, Maximum Likelihood ou Bayesian inference. O resultado é uma árvore que representa a história evolutiva das sequências de proteínas.</p>

#### **4 - Passo a passo para a construção de uma árvore filogenética a partir de um arquivo FASTA:**

<p align="justify"> &emsp; <b>Obter sequências de interesse:</b> Primeiro, é necessário obter as sequências das espécies que se deseja analisar. Essas sequências podem ser obtidas a partir de bancos de dados públicos como o NCBI, Uniprot, etc.</p><br>

<p align="justify"> &emsp; <b>Alinhar as sequências:</b> Em seguida, é necessário alinhar as sequências para que as posições correspondentes possam ser comparadas. Existem diversas ferramentas para realizar o alinhamento, como o MAFFT e o ClustalW. O resultado do alinhamento deve ser um arquivo em formato FASTA.</p><br>

<p align="justify"> &emsp;<b>Selecionar o modelo de evolução:</b> É necessário escolher um modelo de evolução para a análise filogenética. O modelo escolhido deve ser baseado no tipo de dados analisados e no número de sequências. Existem diversos modelos de evolução disponíveis, como o modelo de Jukes-Cantor, o modelo de Kimura, o modelo de Hasegawa-Kishino-Yano (HKY) e o modelo geral de Markov.</p><br>

<p align="justify"> &emsp;<b>Construir a árvore filogenética:</b> Para construir a árvore filogenética, é necessário utilizar um software de análise filogenética, como o PHYLIP, o MEGA ou o BEAST. É necessário fornecer ao software o arquivo FASTA com as sequências alinhadas e o modelo de evolução escolhido. O software irá gerar a árvore filogenética a partir dessas informações.</p><br>

<p align="justify"> &emsp;<b>Analisar a árvore filogenética:</b> Após a construção da árvore filogenética, é necessário analisá-la para obter informações sobre a relação evolutiva entre as espécies. Isso pode ser feito utilizando ferramentas de visualização de árvores, como o FigTree, e métodos estatísticos, como o bootstrap e o likelihood. É possível identificar grupos de espécies mais relacionados entre si e comparar as diferenças entre as sequências das diferentes espécies.</p><br>


<!--------------------------------------------------------------------------->

<h2 id="Equipe">Equipe</h2><br>

<div align="center">

|     Desenvolvedor              |           GitHub             |       LinkedIn     |
|--------------------------------|------------------------------|--------------------|
|👤 João Vitor Moraes            |https://github.com/JohKemPo   |https://www.linkedin.com/in/joao-vitor-de-moraes/|
</div>
<br>


