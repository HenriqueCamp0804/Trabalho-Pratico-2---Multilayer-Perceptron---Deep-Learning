# Trabalho-Pratico-2---Multilayer-Perceptron---Deep-Learning

### Classificador de Imagens com uma Rede Neural Profunda (MLP)

Este projeto consiste na implementação de um algoritmo **Multilayer Perceptron (MLP)**, uma rede neural profunda com múltiplas camadas, construído do zero utilizando apenas Python e NumPy. O objetivo é criar um modelo capaz de diferenciar imagens de **gatos** e **não-gatos** com uma performance superior à da Regressão Logística.

Este trabalho foi desenvolvido como um exercício prático para solidificar os conceitos por trás das arquiteturas de redes neurais profundas e do processo de treinamento de um modelo de machine learning mais complexo.

🧠 Conceitos Abordados

O notebook percorre todas as etapas essenciais para a construção de um classificador MLP, incluindo:

-   **Carregamento de Dados:** Leitura de datasets no formato `.h5`.
-   **Pré-processamento de Imagens:** Redimensionamento, achatamento (flattening) e normalização dos dados.
-   **Inicialização de Parâmetros:** Criação dos vetores de pesos `W` e bias `b` para uma rede de L camadas.
-   **Funções de Ativação:** Implementação das funções **ReLU** (para camadas ocultas) e **Sigmoid** (para a camada de saída).
-   **Forward Propagation:** Implementação do passe adiante generalizado para uma rede profunda, calculando as ativações e o custo final (Entropia Cruzada Binária).
-   **Backward Propagation:** Implementação da retropropagação de erros generalizada para calcular os gradientes em todas as camadas.
-   **Gradiente Descendente:** Aplicação do loop de otimização para atualizar os parâmetros de todas as camadas e treinar o modelo.
-   **Avaliação:** Medição da acurácia do modelo nos conjuntos de treino e teste.
-   **Previsão:** Uso do modelo treinado para classificar uma nova imagem fornecida pelo usuário.

🛠️ Tecnologias Utilizadas

-   **Python 3**
-   **NumPy:** Para todas as operações matemáticas e manipulação de vetores.
-   **Matplotlib:** Para visualização das imagens e gráficos.
-   **h5py:** Para carregar os dados do dataset.
-   **Pillow (PIL):** Para o processamento da imagem final de teste.
-   **Jupyter Notebook / Google Colab:** Como ambiente de desenvolvimento.

🚀 Como Executar

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
    ```
2.  Abra o arquivo `.ipynb` no Jupyter Notebook ou Google Colab.
3.  Execute as células em ordem sequencial.
4.  Para a parte de teste com uma imagem própria, faça o upload de um arquivo para o ambiente e atualize a variável que contém o caminho da imagem.

---
