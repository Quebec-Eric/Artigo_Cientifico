# Artigo_cient-fico
Utilizando o Aprendizado de Máquina para Combater a Criminalidade em Chicago


Este projeto contém a estrutura de arquivos e diretórios para a pesquisa realizada no contexto de um artigo científico. Os dados analisados, as metodologias de pré-processamento, clustering, modelagem e visualização estão organizados em diretórios específicos para facilitar o entendimento e a replicação dos resultados.


## Estrutura de Diretórios

- `BaseDados/`: Contém os conjuntos de dados brutos e modificados utilizados na pesquisa.
  - `alterado.csv`: Dados modificados ou transformados a partir dos conjuntos brutos.
  - `Crimes_-_2001_to_Present.csv`: Dados sobre crimes ocorridos desde 2001 até o presente.
  - `CPD_Parks.csv`: Informações sobre parques.
  - `ParaClasificacao.csv`: Dados preparados para classificação.
  - `Sex_Offenders.csv`: Dados sobre agressores sexuais.



  - `Clustering/`: Notebooks e scripts dedicados às técnicas de clustering aplicadas aos dados.
  - `DBSCAN/`: Análise específica usando o algoritmo DBSCAN.
  - `KMeans/`: Análise específica usando o algoritmo KMeans.
  - `Som/`: Análise específica usando Mapas Auto-Organizáveis (SOM).


  `Modelos/`: notebooks que tratam da aplicação de modelos de aprendizado de máquina além dos métodos de clustering.



- `Pre_Processamento/`: Scripts e notebooks dedicados ao pré-processamento dos dados, preparando-os para análises subsequentes.
  - `Base_Crimes/`: Pré-processamento dos dados de crimes.
  - `Base_parks/`: Pré-processamento dos dados dos parques.
  - `Base_SexOffenders/`: Pré-processamento dos dados dos agressores sexuais.
  - `IntegracaoDasBases/`: Pré-processamento final da base pronta.

- `Visualização/`: Notebooks que contêm visualizações dos dados e dos resultados das análises.
  - `Visualizacao_Dados.ipynb`: Notebook com visualizações gerais e específicas dos dados e resultados.
