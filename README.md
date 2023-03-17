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


<br>
<br>

<!--------------------------------------------------------------------------->

<h2 id="Apendice">Apêndice</h2><br>

<h3><a href="https://thihenos.medium.com/o-que-%C3%A9-uma-pipeline-para-desenvolvimento-de-softwares-para-iniciantes-9fc26150178e">link</a></h3><br>

<p align="justify">&emsp; A origem da palavra vem do inglês, que podemos entender como um duto ou tubo daqueles que podem passar oléo, água ou qualquer outro material liquido ou gasoso. O termo também vem sendo muito utilizado em indústria como um conjunto de instrução, ou uma esteira de processos ou comandos que alguém ou algo deve seguir sempre, por exemplo uma pipeline de vendas, onde tem sempre os passos e estratégias a serem seguidas.</p><br>
<p align="justify">&emsp; No mundo da engenharia da computação, o termo pipelining é utilizado para descrever a estratégia onde o CPU procura a próxima instrução para executar, como se numa esteira de instruções já enviadas que são executadas, um comando após o outro.</p><br>



<!--------------------------------------------------------------------------->

<h2 id="Equipe">Equipe</h2><br>

<div align="center">

|     Desenvolvedor              |           GitHub             |       LinkedIn     |
|--------------------------------|------------------------------|--------------------|
|👤 João Vitor Moraes            |https://github.com/JohKemPo   |https://www.linkedin.com/in/joao-vitor-de-moraes/|
</div>
<br>


