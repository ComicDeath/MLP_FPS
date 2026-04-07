![ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/ComicDeath/Proton-Collision-Classifier/blob/main/Figuras/ilum_colorida.png)

<h1 align="center">A Rota da Neuromante</h1>

O projeto **A Rota da Neuromante** foi desenvolvido como a primeira entrega da disciplina Redes Neurais e Algoritmos Genéticos, ministrada no terceiro semestre do Bacharelado em Ciência e Tecnologia da Ilum - Escola de Ciências. O objetivo é prever FPS (frames por segundo) em jogos a partir de dados de hardware, aplicando regressão supervisionada. O trabalho inclui pré-processamento de dados, criação de embeddings para variáveis categóricas, ajuste de hiperparâmetros com Optuna, definição de funções de ativação, escolha de otimizadores e técnicas de regularização, visando precisão e convergência estável do modelo.

# Algoritmo utilizado

### `MLP (Multi-Layer Perceptron)`
Rede neural capaz de capturar padrões complexos nos dados. O MLP foi ajustado com diferentes otimizadores (Adam, AdamW, SGD), funções de ativação para camadas ocultas e de saída, e técnicas de regularização, com hiperparâmetros otimizados via Optuna.

# Instalação e como usar

Para utilizar o projeto, clone este repositório em sua máquina e abra-o em uma IDE compatível com arquivos `.ipynb`. Em seguida, abra o notebook `neuromante.ipynb`, que contém a introdução teórica, o pré-processamento de dados, o treino dos modelos e sua avaliação, a otimização de hiperparâmetros, a comparação com outros algoritmos, a análise da convergência com diferentes otimizadores, a explicação do modelo por meio da `Permutation Importance`, a discussão dos resultados e a conclusão.

É importante que o ambiente de execução possua todas as bibliotecas necessárias instaladas, incluindo **PyTorch**, **LIghtning**, **Optuna** e demais dependências utilizadas no notebook.  

A pasta `Estudos do Optuna` contém os arquivos `.db` gerados durante a otimização de hiperparâmetros. A pasta `lightning_logs` armazena os arquivos `.csv` referentes às curvas de aprendizado. Além disso, os melhores modelos treinados estão salvos na pasta `Melhores modelos`, com os arquivos `.pth` correspondentes aos melhores parâmetros treinados encontrados para os modelos que utilizam Adam, AdamW e SGD.

# Docente
A matéria de Redes Neurais e Algoritmos Genéticos foi ministrada por:
- **Profº Dr. Daniel Roberto Cassar**
  
# Licença
Distribuído sob a licença GNU General Public License 3.0, cheque `LICENSE` para mais informações.
