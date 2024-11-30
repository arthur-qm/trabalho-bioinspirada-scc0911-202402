# Computação Bioinspirada 2024-02

Este repositório contém o trabalho da Tópicos Avançados em Ciências de Computação II
(Computação Bioinspirada, no semestre 2024-02).

O trabalho consiste em trabalhar com um conjunto de dados multirrótulo onde cada instância representa uma sequência de
proteína. Cada rótulo (classe) corresponde a uma localização subcelular e as proteínas podem estar presentes
simultaneamente em dois ou mais compartimentos celulares. O conjunto de dados possui seis localizações
subcelulares: Proteínas do Capsídeo Viral, Proteínas da Membrana Celular do Hospedeiro, Proteínas do Retículo
Endoplasmático do Hospedeiro, Proteínas do Citoplasma do Hospedeiro, Proteínas do Núcleo do Hospedeiro e
Proteínas Secretadas. As colunas representam os códigos de Gene Ontology (relacionados à função da proteína),
com valores que indicam a frequência do código para cada proteína. As seis últimas colunas indicam a presença
(1) ou ausência (0) da proteína em cada uma das localizações subcelulares mencionadas.

Desenvolvemos um modelo de classificação multirrótulo usando redes neurais artificiais.

Existem dois conjuntos de dados: um de vírus e um de plantas.


Algumas refs sobre PSO para otimizar Hiperparâmetros de Redes Neurais (tema mais específico do trabalho): 

[artigo](https://www.researchgate.net/publication/318069806_Particle_swarm_optimization_for_hyper-parameter_selection_in_deep_neural_networks)

[post no medium](https://medium.com/next-level-german-engineering/hyperparameter-optimisation-utilising-a-particle-swarm-approach-5711957b3f3f)
