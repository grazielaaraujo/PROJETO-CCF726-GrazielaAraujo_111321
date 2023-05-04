
    
<h1><center> Previsão de Diabetes, Hipertensão e AVC </center></h1>

Como proposta, pretende-se utilizar três conjuntos de dados para predição de diabetes, hipertensão e o AVC. Ainda pretende-se verificar se a predição de uma das doenças podem influenciar na predição de outra. 

## Diabetes:

 O diabetes é uma doença sem cura que atinge cerca de 16 milhões de brasileiros, de acordo com o relatório da Organização Mundial de Saúde. Seus sintomas costumam ser sutis, por isso, muitas vezes, passam despercebidos. Ainda, é considerado o segundo principal fator de risco para o AVC. Enfim, descobrir a doença no seu início é fundamental, pois, mantendo um nível bom de glicose e ter acompanhamento médico, pode evitar graves consequências [[1], [2]].

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


## Hipertensão

Apesar de 90% dos casos, a hipertensão (pressão alta) serem herdada dos pais [[4]]. Tem-se vários fatores que influenciam nos níveis de pressão arterial, como, fumo, consumo de bebidas alcoólicas, obesidade, estresse, elevado consumo de sal, níveis altos de colesterol e falta de atividade física. E uma das formas de prevenção é controlando o diabetes.


[No Brasil, 388 pessoas morrem por dia por hipertensão](https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/h/hipertensao#:~:text=A%20hipertens%C3%A3o%20arterial%20ou%20press%C3%A3o,(ou%2014%20por%209).).

O conjunto de dados "hypertension_data.csv", disponibilizado para previsão de AVC, está organizado com a seguintes informações:

1. "age": idade do paciente (em anos);
2. "sex": sexo do paciente (1: masculino; 0: feminino);
3. "cp": Tipo de dor torácica: 0: assintomática 1: angina típica 2: angina atípica 3: dor não anginosa;
4. "trestbps": Pressão arterial em repouso (em mm Hg);
5. "chol": Colesterol sérico em mg/dl;
6. "fbs": se a glicemia de jejum do paciente > 120 mg/dl (1: sim; 0: não);
7. "restecg": Resultados do ECG em repouso: 0: normal 1: anormalidade da onda ST-T;
8. "thalach": Frequência cardíaca máxima alcançada.
9. "exang": Angina induzida por exercício (1: sim; 0: não)
10. "oldpeak": Depressão de ST induzida por exercício em relação ao repouso.
11. "slope": A inclinação do segmento ST do exercício de pico: 0: ascendente 1: plana 2: descendente
12. "ca": Número de vasos principais (0–3) coloridos por fluoroscopia
13. "thal": 3: Normal; 6: Defeito corrigido; 7: Defeito reversível
14. "target": Se o paciente tem hipertensão (1) ou não (0).



## AVC
O acidente vascular cerebral (AVC) ocorre quando o fluxo sanguíneo para o cérebro é reduzido ou bloqueado, causando perda de funções neurológicas [[3]]. Visto que a pressão arterial é seu principal fator de risco, seu controle é fundamental paraa prevenção do AVC.

O conjunto de dados "stroke_data.csv" é utilizado para verificar as possiblidades de um paciente sofrer um AVC com base em características, como: 

1. "sex": sexo do paciente (1: masculino; 0: feminino);
2. "age": idade do paciente (em anos);
3. "hypertension": paciente já teve hipertensão (1) ou não (0);
4. "heart_disease": paciente já teve doença cardíaca (1) ou não (0);
5. "ever_married": paciente casado (1) ou não (0);
6. "work_type": tipo de trabalho do paciente: 0 - Never_worked, 1 - filhos, 2 - Govt_job, 3 - Autônomo, 4 - Particular;
7. "Residence_type": área do paciente: 1 - Urbano, 0 - Rural;
8. "avg_glucose_level": nível médio de açúcar no sangue do paciente;
9. "bmi": Índice de massa corporal;
10. "smoking_status": 1 - fuma, 0 - nunca fumou;
11. "stroke": Se o paciente tem AVC (1) ou não (0).



## Problemas a serem tratados: 

1. Quais fatores de risco são mais preditivos da doença?
2. Podemos usar um subconjunto dos fatores de risco para prever com precisão se um indivíduo tem a determinada doença?
3. Podemos criar uma forma de perguntas rápidas usando a seleção de recursos para prever com precisão se alguém pode estar doente ou está em alto risco?


## Dataset: 
  * [Conjunto de dados para previsão de diabetes, e hipertensão e AVC](https://www.kaggle.com/datasets/prosperchuks/health-dataset) no Kaggle 




[1]:  http://www.prontosaude.com.br/post/diabetes-a-importancia-do-diagnostico-precoce
[2]: https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/h/hipertensao#:~:text=A%20hipertens%C3%A3o%20arterial%20ou%20press%C3%A3o,(ou%2014%20por%209).
[3]: https://www.prefeitura.sp.gov.br/cidade/secretarias/saude/noticias/?p=320188#:~:text=Popularmente%20conhecido%20como%20derrame%2C%20o,de%20risco%20%C3%A9%20a%20hipertens%C3%A3o.
[4]: https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/h/hipertensao#:~:text=A%20hipertens%C3%A3o%20arterial%20ou%20press%C3%A3o,(ou%2014%20por%209).


<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p> 
