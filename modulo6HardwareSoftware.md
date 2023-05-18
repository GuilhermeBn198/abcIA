# modulo 6
## frameworks
## pyTorch
PyTorch é um framework de computação de aprendizado de máquina baseado em Python desenvolvido pelo Facebook. Ele é desenvoldio com base no Torch que é uma biblioteca de operação de tensor semelhante ao NumPy, caracterizada por alta flexibilidade, mas é menospopular porque usa a linguagem de programação Lua. É por isso que o PyTorch foi desenvolvido.

## Rede Neurais Dinâmicas: 
muitas frameworks convencionais, cocmo o TensorFlow 1.x, não oferecem suporte a esse recurso. Para executar o TensorFlow 1.x, os desenvolvedores devem criar gráficos computacionais estáticos. Eme constraste, o PyTorch com esse recurso está livre de tal complexidade e os programas PyTorch podem construir/ajustar dinamicamente  grafos computacionais durante a execução.
- facil de depurar
- suporta uso de CPUS e GPUS

## TensorFlow
- TensowrFlow é a biblioteca de software de código aberto do Google
- suporta vários algoritmos de aprendizado profundo
- suporta várias plataformas de computação, garantindo alta estabilidade do sistema
- código aberto
- multicódigo
  
## MindSpore
- O MindSpore é a estrutura de computação da IA. Totalmente desenvolvido peles Huawei desde o início, ele implementa a colaboração sob demanada no cloud-edge-device.
- O MindSpore faz pleno uso do poder computacional dos processadores de IA Ascende reduz os requisitos de entrada no desenvolvimento de IA do setor, levando a IA inclusiva mais rapidamente à realidade

## Aprendizagem por transferência
- corta-se uma parte da rede neural, utilizando-se de uma parte da estrutura do modelo base para fazer uma nova rede neural


---


# CHIPS DE INTELIGENCIA ARTIFICIAL
- quatro elmentos da ia:
  - dados
  - algoritmo
  - cnário
  - poder de computação
- os chips de IA:
  - são conhecidos como aceleradores de IA
  - são modulos de função processam tarefas de computação massivas em aplicativos de IA

## classificação dos chips de IA
- os chips podem ser divididos em quatro tipos pela sua arquiterura
  - CPUS
  - GPUS
  - ASICS
  - FPGA

- GPUS
  - desempenho notável m computação matricial e paralla atuando como um chip de aceleração para aprendizado profundo
  - Usando a arquitetura de GPU, a NVIDIA se concentra em:
    - CUDA Deep Neural NetWork
    - melhorar a personalização suportando vários tipos de dados e módulos dedicados e otimizados para calculo de tensores
  - Problemas:
    - Altos custos
    - alto consumo energético

- TPU
  - são chips ASICS especializados para aprendizado profundo
    - projetados e otimizados para executar calculos de matriz(tensores)
    - treinamento mais rapido e maior precisão
    - alta eficiência computacional e são energeticamente mais eficientes
  - não estão amplamente disponíveis, mas estão se tornando cada vez mais populares

- Ascend
  - projetados e desenvolvidos pela Huawei para uso em aplicativos de IA
  - são baseados na arquitetura Da Vinci proprietária da Huawei
  - principais vantagens: 
    - Alto desempernho
    - baixa latência
    - eficiência energética
    - versatilidade


# plataforma de computação IA ATLAS
- plataforma de IA abrangente que fornece componentes de hardware e software para aplicativos de IA
- suas opções:
  - algoritmos de aprendizado profundo e ML
  - tecnologias ed hardware: gpu, tpus e fpgas
  - facildiade de uso
  - alto desempenho e escalabildiade
  - 