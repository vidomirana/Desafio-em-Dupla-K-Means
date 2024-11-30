# Desafio-em-Dupla-K-Means
## Identificando atividades humanas por meio de sensores de celular
 Repositório com os arquivos referentes ao projeto K-Means de clusterização

# Autores
Vitor Miranda e Wallisson Dias.
- Residência em Ciência de Dados - RESTIC 36, organizada pela CEPEDI.

# Descrição do projeto
- O projeto traz uma modelagem de clusterização para identificar atividades humanas (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) com base em sensores como acelerômetro e giroscópio de um smartphone. 
- O modelo foi criado com base no algoritmo K-Means, o qual está implementado na biblioteca Scikit-learn. 
- Os dados foram coletados com a participação de 30 pessoas.

# Instalação das bibliotecas necessárias
- !pip install pandas
- !pip install numpy
- !pip install seaborn
- !pip install matplotlib
- !pip install scikit-learn
- !pip install gdown
- !pip install scipy

# Estrutura dos arquivos
* As bases .txt estão sendo puxadas publicamente do Google Drive, mas serão deixadas também nesse repositório
A pasta /src contém o código-fonte e os dados baixados, /UCI HAR Dataset contém as bases de dados usadas e algumas adicionais, enquanto /docs contém o relatório do projeto.

# Sobre a base de dados
Nos arquivos existem dados dos sensores de acelerômetro e giroscópio, cada sensor com valores de coordenada X, Y e Z, para as 30 pessoas do experimento. Também há os clusters reais para posterior verificação de acurácia do modelo.

# Instruções para execução do código
Apenas é necessário instalar as bibliotecas do tópico "Instalação das bibliotecas necessárias" e executar as células em sequência, pois as bases de dados estão sendo baixadas pela biblioteca gdown do Google.