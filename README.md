
🐾 Transfer Learning para Classificação de Gatos e Cachorros
Este projeto utiliza técnicas de Transfer Learning e uma arquitetura de rede neural personalizada para classificar imagens de gatos e cachorros. Foram implementados dois modelos principais:

Modelo Customizado: Construído do zero com camadas convolucionais.
Modelo Baseado no VGG16: Aproveitando os pesos pré-treinados na ImageNet.
📋 Descrição do Projeto
O objetivo do projeto é classificar imagens de gatos e cachorros usando aprendizado profundo. Dois modelos foram desenvolvidos e comparados:

Modelo Customizado:
Rede convolucional profunda com camadas de ativação, pooling e dropout.
Foco na simplicidade e no aprendizado direto a partir dos dados.
Modelo VGG16 Modificado:
Transferência de aprendizado com a arquitetura VGG16.
Adição de uma camada densa customizada com softmax para adaptar o modelo ao problema.
Congelamento das camadas convolucionais para preservar os pesos pré-treinados.
🛠️ Ferramentas e Tecnologias
Python
TensorFlow e Keras
Matplotlib para visualização
