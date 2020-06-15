# ProjectElectricJava
## Dimensionamento Elétrico Residencial Desenvolvido Em Java

### Introdução
Indispensável para maior parte da populção a utilização de energia elétrica. É essa energia que nos auxilia nos afazeres domésticos, nos deixa mais confortáveis em nossas casas, nos permite conversarmos com quem está distante e também nos proporciona lazer.
Mas se uma instalação elétrica for mal dimencionada a mesma pode proporcinar grande perigo de acidentes que podem levar a obtos em situações mais graves, para sanar quande partes destes problemas existem normas para a instalação da rede elétrica.

### Levantamento de cargas elétricas

Para se instalar uma rede elétrica é necessário, um levantamento de cargas elétricas correta do local.
O mesmo é feito uma previsão das a potências mı́nimas de iluminação e tomadas a serem instaladas no local, possibilitando determinar a potência total aparente, ativa e reativa da rede eletrica.

### Potência Aparente

É o produto da ação da tensão e da corrente, sua unidade de medida é o Volt-Ampère (VA).

### Potência Ativa

É a parte da potência aparente que é transformada em potência mecânica, térmica ou luminosa, tendo como unidade de media o Watt(W).

### Potência Reativa

É a parte da potência aparente que é transformada em um campo magnético, tendo como unidade de media o Volt-Ampère (VAr).

### Fator De Potencia
Sendo a potência de ativa uma parcela de potência aparente, pode-se dizer que a mesma representa uma porcentagem da potência aparente que é transformada em potência mecânica, termica ou luminosa.
A isso damos o nome de fator de potência, nos projetos resindeciais, desejando-se saber o quanto da potência aparente foi transformada em potência ativa, aplica-se os seguintes valores de fotor de potência:
Fator 1,0 para lâmpadas e 0,8 para tomadas de uso geral, a razão disto é que numa lâmpada toda sua potência é ativa então sua potência reativa é zero, então 100% da potência aparente é transfomada em ativa, e em um aparelho de tomada a perdas em sua potência em media cerca de 80% da mesma é transformada em ativa.

### Levantamento Da Carga De Iluminação

##### Recomendações da NBR 5410:2004.

#### Condições para se estabelecer a quantidade mı́nima de pontos de luz

| Prever pelo menos um ponto de luz no teto,comandado por um interruptor de parede |
|----------------------------------------------------------------------------------|

| Arandelas no banheiro devem estar distantes no mı́nimo, 60cm do limite do box     |
|----------------------------------------------------------------------------------|

### Condições para se estabelecer a potência mı́nima de iluminção

A carga de iluminção é feita em função a área do cômodo a ser dimencionado.
###### Para área igual ou inferior a 6m²
Atribuir um mı́nimo de 100 VA.
###### Para área superior a 6m² 
Atribuir um mı́nimo de 100 VA para os primeiros 6m2, acrescido de 60 VA para cada aumento de 4m2 inteiros.
Nota: A NBR 5410:2004 não estabelece criterios para iluminação de áreas externas em recidências, ficando a cargo do projetista e do cliente.

### Exemplo dos calculos para carga de ilumonação

|   Dependências  |   Dimensões área (m²)   | Potência de iluminação (VA) | (VA) |
|:---------------:|:-----------------------:|:---------------------------:|:----:|
|       Sala      |  A = 3,25 x 3,05 = 9,91 |       9,91 = 6 + 3,91       |  100 |
|       Copa      |  A = 3,10 x 3,05 = 9,45 |       9,45 = 6 + 3,45       |  100 |
|     Cozinha     | A = 3,45 x 3,05 = 11,43 |     11,43 = 6 + 4 + 1,43    |  160 |
|    Dormitorio   | A = 3,15 x 3,40 = 10,71 |     10,71 = 6 + 4 + 0,71    |  160 |
|      Banho      |  A = 1,80 x 2,30 = 4,14 |          4,14 → 100         |  100 |
| Área de Serviço |  A = 1,75 x 3,40 = 5,95 |          5,95 → 100         |  100 |
|       hall      |  A = 1,80 x 1,00 = 1,80 |          1,80 → 100         |  100 |
|   Área externa  |            -            |              -              |  100 |

### Levantamento Da Carga De Tomadas

##### Recomendações da NBR 5410:2004.

#### Condições para se estabelecer a quantidade mı́nima de pontos de tomadas

| Ponto de tomada é o ponto onde a conexão do equipamento à instalação elétrica é feita através de tomada corrente.O mesmo pode ter uma ou mais tomadas de corrente |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
