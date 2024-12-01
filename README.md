![Logos MCTI, CNPEM e ILUM](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/93c3eb13-410c-40c0-a412-7096187678a4)
<h1 align='center'> Projeto final Álgebra Linear Computacional - PCA aplicado em aprendizado de máquina </h1>

<p align="center">
<img loading="lazy" src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Colaboradores
[<img src="https://avatars.githubusercontent.com/u/172425100?v=4" width=115>](https://github.com/jojomolinetes)
[<img src="https://avatars.githubusercontent.com/u/172425104?v=4" width=115>](https://github.com/JuliaGuedesASantos)
[<img src="https://avatars.githubusercontent.com/u/172425156?v=4" width=115>](https://github.com/KatarinaVilarins)
[<img src="https://avatars.githubusercontent.com/u/172424981?v=4" width=115>](https://github.com/RaquelGVianna)


* Joana de Medeiros Oliveira Hulse Molinete, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Julia Guedes Almeida dos Santos, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Katarina da Silva Vilarins, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais
* Raquel de Godoy Vianna, Ilum Escola de Ciência, Centro Nacional de Pesquisa em Energia e Materiais

## Descrição do Projeto
Trabalho final do segundo período do curso de Bacharelado em Ciência e Tecnologia da turma 2024 da _Ilum - Escola de Ciência (CNPEM)_ referente à disciplina 'Álgebra Linear Computacional', ministrada pelo Professor Doutor Vinicius Francisco Wasques.<br>
Uma implementação computacional de Análise de Componentes Principais (PCA) associado aos métodos de decomposição QR e ortogonalização por Gram-Schmidts, para redução de dimensionalidade e treinamento de modelos de aprendizado de máquina.  

## Objetivo principal 
Este estudo tem como objetivo a investigação de métodos de redução de dimensionalidade de dados, que possibilitem a otimização do processo de cálculo de autovalores e autovetores para grandes conjuntos. Procuramos implementar o método de decomposição QR, Francis e Gram-Schmidt com posterior aplicação em PCA, buscando reduzir a complexidade de dados, diminuindo o custo computacional dos modelos e possibilitando uma execução otimizada para algoritmos de aprendizado de máquina.
 
<br>
O presente trabalho conta com 3 partes principais: implementação em linguagem Python dos métodos discutidos em datasets didáticos, trabalho escrito em Latex e apresentação oral. Procuramos explicar de forma didática o funcionamento, implementação e aplicações dos métodos de Gram-Schmidt, decomposição QR e método de Francis, para que na aplicação final, a análise em componentes principais, todo o processo fique claro para o leitor.

<br>

## ÍNDICE
* [Colaboradores](#colaboradores)
* [Descrição do Projeto](#descrição-do-projeto)
  - [Objetivo Principal](#objetivo-principal)
* [Índice](#índice)
* [Demonstração da Aplicação](#demonstração-da-aplicação)
  - [Professor](#professor)
  - [Aluno](#aluno)
* [Informações técnicas](#informações-técnicas)
* [Contribuições](#contribuições)
* [Conclusão](#conclusão)
* [Agradecimentos](#agradecimentos)
* [Referências](#referências)
* [Nota adicional](#nota-adicional)


![PCA Visualization](https://via.placeholder.com/800x400?rtext=PCA+Graph)  

---

## **Descrição**  
Em formato de código, aplicamos o método de Gram-Schmidt para converter um conjunto de vetores linearmente independentes em um conjunto ortonormal, que será utilizado para a decomposição QR e pode ser usado como parte do cálculo dos componentes principais do PCA, ao construir bases ortogonais no processo de análise. Com a matriz Q ortonormal gerada pela ortogonalização de Gram-Schmidt, uma matriz R inicialmente nula é construída a partir dos coeficientes do processo de ortogonalização, dando origem a matriz QR. Por fim, implementamos o método de Francis, que consiste em repetir a decomposição QR de uma matriz e recompor a matriz A multiplicando as partes resultantes. Após muitas iterações, a matriz inicial converge para uma matriz triangular superior, onde os autovalores de A aparecem na diagonal. O método QR é utilizado aqui, pois fornece uma maneira estável de fatorar a matriz A, e garante a separação dos autovalores. 
PCA (Principal Component Analysis) é uma técnica estatística utilizada para reduzir a dimensionalidade de grandes conjuntos de dados enquanto preserva a maior parte da variabilidade dos dados.  
Este projeto implementa o PCA em Python utilizando bibliotecas populares como NumPy e Matplotlib, e pode ser aplicado em conjuntos de dados numéricos para visualização e análise.  
O PCA é amplamente utilizado pois permite otimizar diversos processos como interpretação de dados, identificação de padrões, redução de complexidade de dados em grandes dimensões.  Os métodos apresentados são importantes em diversas áreas do conhecimento, como mecânica quântica, processamento de imagens, análise de vibrações, estatística.

---

## **Tabela de Conteúdos**  
1. [Instalação](#instalação)  
2. [Uso](#uso)  
3. [Exemplo](#exemplo)  
4. [Contribuindo](#contribuindo)  
5. [Licença](#licença)  

---

## **Instalação**  
### Pré-requisitos  
- Python 3.8 ou superior  
- Bibliotecas: NumPy, Matplotlib, pandas  

1. Clone o repositório:  
   ```bash  
   git clone https://github.com/usuario/pca-toolkit.git  
   cd pca-toolkit  

## Informações técnicas
* Linguagem de programação
  - Python 3.9
* Software
  - Jupyter Notebook
* Bibliotecas
  - BoxPlot 0.1.1
  - Collections 0.1.6
  - Matplotlib 3.9.0
  - Matplotlib.pyplot 3.9.0
  - Numpy 1.26.4
  - Operator 1.0.1
  - Os 2.1.4
  - Pandas 2.2.2
  - Plotly.graph_objects 5.22.0
  - Statistics 1.0.3.5
  - Time 0.3.0

## Contribuições
HANNEMANN, Thomas: Responsável pela leitura e estruturação dos dados de saída (gráficos), elaboração dos trechos do código referentes ao retorno do aluno e tratamento dos dados.
<br><br>
LELIS, Maria: Responsável pela estruturação dos dados de saída (interface e arquivos), elaboração dos trechos do código referentes ao retorno do aluno, pesquisas para o aprimoramento das funções e realização dos testes. 
<br><br>
MOLINETE, Joana: Responsável pela estruturação dos dados de entrada, elaboração dos trechos do código referentes ao retorno do professor (gráficos), documentação (introdução, objetivos e conclusão) e slides.
<br><br>
NUNES, Letícia: Líder da equipe, idealizadora do projeto, responsável pela estruturação dos dicionários, padronização das funções, elaboração dos trechos do código referentes ao retorno do professor e documentação.
<br><br>

## Conclusão
Os avanços da tecnologia da informação, ciência e manipulação de dados se apresentam cada vez mais integrados na sociedade, desempenhando papéis fundamentais no dia a dia das pessoas e facilitando processos que anteriormente eram manuais e trabalhosos. Tendo em vista esses aspectos, a intenção desse projeto era auxiliar em situações rotineiras, aprimorando o método de inserção e distribuição de notas dentro de cursos educacionais, demonstrando como a linguagem _python_ e diversas bibliotecas oferecem aplicações muito úteis para a otimização das tarefas acadêmicas e aproximação entre professor e aluno. <br>
Os resultados apresentados no trabalho contribuem com os diversos objetivos alcançados pelos algoritmos, tornando o processo de recebimento e controle de nota muito mais fácil e visual, tanto para os estudantes quanto para os docentes, desempenhando assim, os objetivos almejados inicialmente.<br>
Apesar de ser um projeto puramente didático, as aplicações foram notáveis e satisfatórias, cumprindo com o propósito do grupo.<br>

## Agradecimentos
Agradecemos ao professor Leandro Nascimento Lemos pela orientação durante todo o decorrer do semestre na disciplina de Práticas em Ciências de Dados. Ao Duanny Onorio, pela disponibilização do seu tempo em horário de almoço, fim de expediente, e durante a aula para sanar nossas dúvidas, dar dicas e corrigir nossos códigos. Aos nossos colegas e amigos Rômulo Emanuel Cruz e Raquel de Godoy Vianna.

## Referências
