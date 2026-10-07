![Logos MCTI, CNPEM e ILUM](https://github.com/leticiaalmnunes/PCD---Boletim/assets/172425156/93c3eb13-410c-40c0-a412-7096187678a4)

<h1 align='center'> Investigação de assinaturas de vesículas extracelulares associadas à modulação fenotípica de células mamárias no contexto do câncer de mama  </h1>

<h2 align="center">Tópicos Avançados em Inteligência Artificial</h2>



**Autores:** Joana de Medeiros Oliveira Hulse Molinete e Pedro Henrique Medeiros Bramante.

**Contribuições:** A introdução e embasamento teórico, tratamento dos dados, análise por componentes principais (PCA) e regressão logística foram realizadas pela autora Joana Molinete.
As partes "A PCA acompanha a linhagem ou o eletrodo?" e "Módulo, fase e referência de PBS", teste ANOVA, aplicação do modelo SISSO e considerações finais foram realizados pelo autor Pedro Henrique Bramante.

**Orientação:** Ana Clara Bastos e Emanuel Carrilho.

---

![Status](https://img.shields.io/badge/STATUS-EM%20TESTES-yellow)

## 🔬 Abordagem computacional para o tratamento de dados de EIS  
O câncer de mama é a neoplasia mais incidente em mulheres no Brasil, e o desenvolvimento de métodos acessíveis para sua caracterização e acompanhamento continua sendo um desafio. Vesículas extracelulares (VEs) têm ganhado espaço nos estudos oncológicos por seu papel na comunicação intercelular, por serem estruturas secretadas pelas células que transportam proteínas, lipídios e ácidos nucleicos. Vesículas derivadas de células tumorais estão associadas a processos de progressão do câncer e metástase, que é o processo de modulação de células e tecidos não tumorais. Investigar se VEs são capazes de induzir alterações fenotípicas em células não tumorais trás maior compreensão das interações entre células e o microambiente em que estão inseridas, e permite o desenvolvimento de novas estratégias de monitoramento do câncer.
No Trabalho de Conclusão de Curso (TCC) do curso de Bacharelado em Ciência e Tecnologia, a proposta é responder a pergunta "VEs derivadas de células de câncer de mama podem alterar o fenótipo de células mamárias não cancerosas?" e validar o uso de um dispositivo eletroquímico *label-free* para diferenciar amostras de VEs secretadas por células tumorais e não tumorais. A espectroscopia de impedância eletroquímica (EIS) é uma técnica que permite analisar as propriedades da interface entre eletrodo e amostra e os processos eletroquímicos que ocorrem entre elas. Medidas de EIS são muito sensíveis mesmo a sinais baixos, e diferenças nas condições experimentais podem influenciar nos parâmetros e combinações das frequências dos resultados, por isso medidas de EIS costumam apresentar desafios no tratamento e interpretação dos dados. 

## ✅ Pré-requisitos
**Ambiente:** Python 3.8+ (ideal: entre 3.8 e 3.11)

Como pré-requisitos para a utilização dos notebooks presentes nesse repositório, é necessário utilizar editor de linguagem compatível com Python 3.13, bem como instalar as versões especificadas das seguintes bibliotecas:
```bash
numpy==1.24.4
scikit-learn==1.3.0
``` 


## 📚 Bases de dados:
`Datasets de treino, teste e validação`: dados de medidas de espectroscopia de impedância eletroquímica (EIS), realizados em potenciostato AutoLab modelo PGSTAT204 (Metrohm Autolab B.V., Utrecht, Países Baixos). 


## ⚠️ Aviso:
Este repositório foi desenvolvido como um trabalho de graduação do sexto semestre do curso de Bacharelado em Ciência e Tecnologia, na matéria de Tópicos Avançados em Inteligência Artificial. 

--- 
