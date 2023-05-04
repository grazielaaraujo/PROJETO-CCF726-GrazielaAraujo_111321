
    
<h1><center> Previsão de Diabetes, Hipertensão e AVC </center></h1>

Como proposta, pretende-se utilizar três conjuntos de dados para predição de diabetes, hipertensão e o AVC. Ainda pretende-se verificar se a predição de uma das doenças podem influenciar na predição de outra. 

## Diabetes:

 O diabetes é uma doença sem cura que atinge cerca de 16 milhões de brasileiros, de acordo com o relatório da Organização Mundial de Saúde. Seus sintomas costumam ser sutis, por isso, muitas vezes, passam despercebidos. Ainda, é considerado o segundo principal fator de risco para o AVC. Enfim, descobrir a doença no seu início é fundamental, pois, mantendo um nível bom de glicose e ter acompanhamento médico, pode evitar graves consequências [[1],[2]].

Este conjunto de dados "diabetes_data.csv", possui 17 atributos e 1 uma variável alvo. Os dados são organizados da seguinte forma: 

1. "Age": categoria de idade de 13 níveis 1 = 18-24 9 = 60-64 13 = 80 ou mais;
2. "Sex": sexo do paciente (1: masculino; 0: feminino);
3. "HighChol": 0 = sem colesterol alto 1 = colesterol alto;
4. "CholCheck": 0 = nenhuma verificação de colesterol em 5 anos 1 = sim verificação de colesterol em 5 anos;
5. "BMI": Índice de massa corporal;
6. "Smoker": Você fumou pelo menos 100 cigarros em toda a sua vida? [Nota: 5 maços = 100 cigarros] 0 = não 1 = sim;
7. "HeartDiseaseorAttack": doença coronariana (DCC) ou infarto do miocárdio (IM) 0 = não 1 = sim;
8. "PhysActivity": atividade física nos últimos 30 dias - não inclui trabalho 0 = não 1 = sim;
9. "Fruits": Consumir Fruta 1 ou mais vezes por dia 0 = não 1 = sim;
10. "Veggies": Consumir Vegetais 1 ou mais vezes ao dia 0 = não 1 = sim;
11. "HvyAlcoholConsump": (homens adultos>=14 drinques por semana e mulheres adultas>=7 drinques por semana) 0 = não 1 = sim;
12. "GenHlth": Você diria que, em geral, sua saúde é: escala 1-5 1 = excelente 2 = muito boa 3 = boa 4 = regular 5 = ruim;
13. "MentHlth": dias de saúde mental ruim escala 1-30 dias;
14. "PhysHlth": dias de doença física ou lesão nos últimos 30 dias escala 1-30;
15. "DiffWalk": Você tem muita dificuldade para andar ou subir escadas? 0 = não 1 = sim;
16. "Stroke": você já teve um derrame. 0 = não, 1 = sim;
17. "HighBP": 0 = sem alta, PA 1 = PA alta;
18. "Diabet": 0 = sem diabetes, 1 = diabetes.


## Hipertenção
Em 90% dos casos, a hipertensão (pressão alta) é ordada dos pais. Contudo, possiu vários fatores que influenciam nos níveis de pressão arterial, como segue:

1. Fumo;
2. Consumo de bebidas alcoólicas;
3. Obesidade;
4. Estresse;
5. Elevado consumo de sal;
6. Níveis altos de colesterol;
7. Falta de atividade física.

[No Brasil, 388 pessoas morrem por dia por hipertensão](https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/h/hipertensao#:~:text=A%20hipertens%C3%A3o%20arterial%20ou%20press%C3%A3o,(ou%2014%20por%209).).


## AVC
O conjunto de dados "stroke_data.csv" é utilizado para verificar as possiblidades de um paciente sofrer um AVC com base em características, como: sexo, idade, hipertensão, doença_cardíaca, se casado, tipo de trabalho, tipo de residência, nível de glicose, IMC, se fumante.


## Problemas a serem tratados: 

1. Quais fatores de risco são mais preditivos da doença?
2. Podemos usar um subconjunto dos fatores de risco para prever com precisão se um indivíduo tem a determinada doença?
3. Podemos criar uma forma de perguntas rápidas usando a seleção de recursos para prever com precisão se alguém pode estar doente ou está em alto risco?


## Dataset: 
  * [Conjunto de dados para previsão de diabetes, e hipertensão e AVC](https://www.kaggle.com/datasets/prosperchuks/health-dataset) no Kaggle 




[1]:  http://www.prontosaude.com.br/post/diabetes-a-importancia-do-diagnostico-precoce
[2]: https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/h/hipertensao#:~:text=A%20hipertens%C3%A3o%20arterial%20ou%20press%C3%A3o,(ou%2014%20por%209).


<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p> 
