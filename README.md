# visao_computacional

## Classificação de imagens de dígitos escritos à mão

O conjunto de dados: 
- O conjunto de dados MNIST contém 60.000 exemplos de treinamento e 10.000 exemplos de teste de dígitos manuscritos que já estão classificados corretamente.
- Estas imagens têm uma resolução de 28x28 pixels.
- Será utilizado o módulo keras para carregar o conjunto de dados.
- Para obter o conjunto de dados, acessamos o objeto mnist de keras.datasets.
- Em seguida, chamamos o conjunto de dados load_function. Essa função automaticamente divide os dados adequadamente e retorna uma tupla com os dados de treinamento e uma tupla com os dados de teste.

Objetivos: 
- Visualização e interpretação dos dados
- Criação e treinamento do modelo de rede neural artificial
- Teste no conjunto de teste

Tópicos extras:
- Trocar a rede neural simples por uma rede neural convolucional
- Criar uma matriz de confusão para avaliar a qualidade das classificações. Utilize também o método confusion_matrix dentro do módulo sklearn.metrics