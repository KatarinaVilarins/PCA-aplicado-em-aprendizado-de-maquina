![Logos MCTI, CNPEM e ILUM](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/93c3eb13-410c-40c0-a412-7096187678a4)
<h1 align='center'> Projeto final Álgebra Linear Computacional - PCA aplicado em aprendizado de máquina </h1>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Colaboradores
[<img src="https://avatars.githubusercontent.com/u/172425100?v=4" width=115>](https://github.com/jojomolinetes)
[<img src="https://avatars.githubusercontent.com/u/172424779?v=4" width=115>](https://github.com/JuliaGuedesASantos)
[<img src="https://avatars.githubusercontent.com/u/172425306?v=4" width=115>](https://github.com/KatarinaVilarins)
[<img src="https://avatars.githubusercontent.com/u/172425251?v=4" width=115>](https://github.com/RaquelGVianna)


* Joana de Medeiros Oliveira Hulse Molinete, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Julia Guedes Almeida dos Santos, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Katarina da Silva Vilarins, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Raquel de Godoy Vianna, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais

## Descrição do Projeto
Trabalho final do segundo período do curso de Bacharelado em Ciência e Tecnologia da turma 2024 da _Ilum - Escola de Ciência (CNPEM)_ referente à disciplina 'Álgebra Linear Computacional', ministrada pelo Professor Doutor Vinicius Francisco Wasques.
<br>
<p align="justify">
Uma implementação computacional de Análise de Componentes Principais (PCA) associado aos métodos de decomposição QR e ortogonalização por Gram-Schmidts, para redução de dimensionalidade e treinamento de modelos de aprendizado de máquina.  
</p>
<br>

<p align="justify">
PCA (Análise em Componentes Principais) é uma técnica estatística utilizada para reduzir a dimensionalidade de grandes conjuntos de dados enquanto preserva a maior parte da variabilidade do conjunto. O PCA é amplamente utilizado pois permite otimizar diversos processos como interpretação de dados, identificação de padrões, redução de complexidade de dados em grandes dimensões.  Os métodos modernos de redução de dimensionalidade são importantes em diversas áreas do conhecimento, como mecânica quântica, processamento de imagens, análise de vibrações, estatística etc. 
</p>
<br>

<p align="justify">
Em formato de código, aplicamos o método de Gram-Schmidt para converter um conjunto de vetores linearmente independentes em um conjunto ortonormal, que será utilizado para a decomposição QR e pode ser usado como parte do cálculo dos componentes principais do PCA, ao construir bases ortogonais no processo de análise. Com a matriz Q ortonormal gerada pela ortogonalização de Gram-Schmidt, uma matriz R inicialmente nula é construída a partir dos coeficientes do processo de ortogonalização, dando origem a matriz QR. Por fim, implementamos o método de Francis, que consiste em repetir a decomposição QR de uma matriz e recompor a matriz A multiplicando as partes resultantes. Após muitas iterações, a matriz inicial converge para uma matriz triangular superior, onde os autovalores de A aparecem na diagonal. O método QR é utilizado aqui, pois fornece uma maneira estável de fatorar a matriz A, e garante a separação dos autovalores. Todos esses métodos possibilitam que encontremos os autovalores e autovetores de uma matriz de dados complexa, que podem reduzir significativamente a a dimensão dos dados se utilizadas corretamente, simplificando a implementação do algoritmo e nos ajudando a identificar padrões nas amostras sem exigir conhecimento prévio sobre a origem ou características específicas dos grupos de tratamento.  
</p>
<br>

![PCA Visualization](https://via.placeholder.com/800x400?rtext=PCA+Graph)  

<br>


## Objetivo principal 
<p align="justify">
Este estudo tem como objetivo a investigação de métodos de redução de dimensionalidade de dados, que possibilitem a otimização do processo de cálculo de autovalores e autovetores para grandes conjuntos. Procuramos implementar o método de decomposição QR, Francis e Gram-Schmidt com posterior aplicação em PCA, buscando reduzir a complexidade de dados, diminuindo o custo computacional dos modelos e possibilitando uma execução otimizada para algoritmos de aprendizado de máquina.
Dada a relevância da otimização do cálculo de autovalores e autovetores, buscamos desenvolver uma ferramenta que associe os métodos de decomposição QR e ortogonalização por Gram-Schmidt, oferecendo uma solução útil para as diversas áreas que demandam esses cálculos. Essa ferramenta visa, assim, aprimorar o processo de cálculo, contribuindo para a resolução de problemas de forma mais eficiente.
</p>
 
<br>
<p align="justify">
O presente trabalho conta com 3 partes principais: implementação em linguagem Python dos métodos discutidos em datasets didáticos, trabalho escrito em Latex e apresentação oral. Procuramos explicar de forma didática o funcionamento, implementação e aplicações dos métodos de Gram-Schmidt, decomposição QR e método de Francis, para que na aplicação final, a análise em componentes principais, todo o processo fique claro para o leitor.
</p>
<br>

## ÍNDICE
* [Colaboradores](#colaboradores)
* [Descrição do Projeto](#descrição-do-projeto)
  - [Objetivo Principal](#objetivo-principal)
* [Índice](#índice)
* [Demonstrações da Aplicação](#demonstrações-da-aplicação)
  - [Ortogonalização por Gram-Schmidt](#ortogonalização-por-Gram-Schmidt)
  - [Decomposição QR](#decomposição-QR)
  - [Método de Francis](#método-de-Francis)
* [Informações técnicas](#informações-técnicas)
* [Conclusão](#conclusão)
* [Agradecimentos](#agradecimentos)
* [Referências](#referências)
* [Nota adicional](#nota-adicional)

<br>

## Demonstrações da Aplicação
### Ortogonalização por Gram-Schmidt

<br>

<br><br>

### Decomposição QR

<br><br>

### Método de Francis

<br><br>

## Informações técnicas
* Linguagem de programação
  - Python 3.9
* Software
  - Jupyter Notebook
* Bibliotecas
* REVISAR
  - BoxPlot 0.1.1
  - Collections 0.1.6
  - Matplotlib 3.9.0
  - Matplotlib.pyplot 3.9.0
  - Numpy 1.26.4
  - Os 2.1.4
  - Pandas 2.2.2

<br><br>

## Conclusão
Os avanços da tecnologia da informação, ciência e manipulação de dados se apresentam cada vez mais integrados na sociedade, desempenhando papéis fundamentais no dia a dia das pessoas e facilitando processos que anteriormente eram manuais e trabalhosos. Tendo em vista esses aspectos, a intenção desse projeto era 
<br>
Os resultados apresentados no trabalho contribuem com os diversos objetivos alcançados pelos algoritmos, tornando o processo 
<br>
Apesar de ser um projeto puramente didático, as aplicações foram notáveis e satisfatórias, cumprindo com o propósito do grupo.
<br>

## Agradecimentos


## Referências
