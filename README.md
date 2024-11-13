Este trabalho é parte de uma atividade acadêmica desenvolvida para o curso de **Tecnologia em Inteligência Artificial Aplicada da PUCPR**, na disciplina de **Processamento de Linguagem Natural (PLN)**. O objetivo desta atividade é aplicar técnicas de PLN para análise de sentimentos, utilizando um dataset de mensagens em português. A partir deste conjunto de dados, serão realizadas etapas de pré-processamento, vetorização e classificação dos textos em categorias de polaridade (positivo, neutro e negativo).

Além disso, o trabalho visa explorar diferentes classificadores e abordagens de pré-processamento para melhorar a precisão dos resultados obtidos.

### **Descrição do Projeto**
Este projeto é uma atividade de análise de sentimentos, onde utilizamos técnicas de Processamento de Linguagem Natural (PLN) para classificar textos de acordo com o sentimento (positivo, neutro ou negativo). O objetivo é treinar um modelo capaz de identificar o sentimento predominante em notícias.

### **Estrutura do Projeto**
* **corpus_reduzido.txt:** Arquivo de dados com a classificação reduzida dos sentimentos (positivo, neutro, negativo).
* **Notebook Jupyter (.ipynb):** Contém o código para leitura dos dados, pré-processamento, classificação e avaliação do modelo.
  
### **Tecnologias e Ferramentas Utilizadas**
* Python 3.x
* Bibliotecas:
  * scikit-learn
  * nltk
  * matplotlib (para visualizações)

### **Como Executar**

* Carregar o dataset do Google Drive no ambiente escolhido (VsCode, Google Colab).
* Executar o pré-processamento, incluindo a redução de granularidade dos sentimentos.
* Treinar o modelo com o classificador Naive Bayes.
* Avaliar a performance do modelo utilizando métricas como precisão e recall.

### **Resultados**
O modelo obteve uma precisão geral de aproximadamente 79%, com melhores desempenhos nas classes "positivo" e "neutro". Houve menor precisão para a classe "negativo", sugerindo que a detecção de sentimentos negativos pode ser aprimorada.

### **Contribuição**
Este projeto pode ser expandido com a inclusão de mais dados, ajustes de parâmetros ou aplicação de outros algoritmos de classificação.
