![.](img\Turnover.png)

## 🔁 Turnover

O Turnover (rotatividade de funcionários) é um grande problema para as empresas. Sempre que um funcionário deixa um determinado trabalho, a empresa perde dinheiro e tempo com novas entrevistas e treinamentos do novo funcionário. Isso sem falar da perda de produtividade do setor afetado por esse turnover. São muitas as questões que fazem um funcionário deixar a empresa, entre eles: melhores oportunidades, clima organizacional ruim, chefes ruins, baixo equilíbrio entre vida pessoal e profissional, entre outros.

## 🤔 O Problema

Para tentar entender quais as características que fazem um funcionário ficar ou deixar uma empresa de Tecnologia, o RH desta empresa catalogou informações de 1470 funcionários que deixaram ou permaneceram na companhia no último ano. O resultado desse levantamento gerou 19 possíveis fatores que explicam o comportamento do turnover, que estão disponíveis no arquivo Base_RH.xlsx. Para conhecer esses fatores, verifique a tabela de metadados existente na guia Metadados.

Com base nisso, o RH encomendou um estudo para o analista de dados da área para responder a seguinte pergunta:

**Quais políticas/fatores da empresa deveriam mudar de forma a minimizar o turnover?**

## 📊 Análise Exploratória de Dados

[📘 Notebook](notebook\EDA.ipynb)

Foram realizadas análises univariadas e bivariadas para entender os dados individualmente e como elas se relacionam com a nossa variável target `Funcionário_deixou_a_empresa`

E após serem realizada analises de associação com o Information Value (IV), foi constatado os seguintes resultados:

- **Faz horas extras (0,40)**
	- A taxa de turnover dos funcionários que costumam fazer hora extra é de **31%**
- **Tempo de carreira (0,36) e Idade (0,28)**
	- Podemos observar que os funcionarios de até 32 anos tem uma taxa de turnover acima da média.
	- O grupo de 18 a 22 anos tem a maior taxa de turnover com 47% sendo necessário e isso se correlaciona ao tempo de carreira.
- **Salário (0,33)**
	- Vemos uma forte relação entre a taxa de turnover com os funcionários mais perto do piso salarial.
- **Quantidade de ações da empresa (0,32)**
	- A taxa de turnover para quem não possui açoes é de 24%.

## 🎯 Possíveis Planos de Ação

### Redução de Horas Extras

- **Política de Limitação de Horas Extras**: 
	Estabelecer uma política clara para limitar horas extras, incentivando o equilíbrio entre vida pessoal e trabalho.
- **Revisão de Processos e Redistribuição de Carga**: 
	Identificar áreas com maior carga de trabalho e revisar processos para uma distribuição mais equilibrada entre a equipe.

### Aprimoramento de Planos de Carreira

- **Desenvolvimento de um Plano de Carreira Estruturado**: 
	Oferecer um caminho claro de crescimento na empresa, definindo competências e metas para promoção.
- **Programas de Mentoria e Treinamento**: 
	Implementar mentorias e treinamentos contínuos para desenvolver habilidades específicas e preparar funcionários para progressões de carreira.
- **Revisão Periódica de Carreira com Funcionários**:
	Realizar conversas periódicas sobre as expectativas de carreira e abrir espaço para feedback, ajustando o plano de acordo com o desempenho e os objetivos individuais.

### Ajustes em Políticas de Compensação e Benefícios

- **Desenvolvimento de um Plano de Carreira Estruturado**: 
	Oferecer um caminho claro de crescimento na empresa, definindo competências e metas para promoção.
- **Programas de Mentoria e Treinamento**:
	Implementar mentorias e treinamentos contínuos para desenvolver habilidades específicas e preparar funcionários para progressões de carreira.
- **Revisão Periódica de Carreira com Funcionários**:
	Realizar conversas periódicas sobre as expectativas de carreira e abrir espaço para feedback, ajustando o plano de acordo com o desempenho e os objetivos individuais.
- **Participação nos Lucros e Resultados (PLR)**: 
	Se possível, implementar uma política de participação nos lucros para aumentar o engajamento.