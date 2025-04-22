# Análise locações de bicicletas 3º trimestre 2023

A empresa empresa Ficticia XPTO presta o serviço de locação de bicicletas para pessoas físicsa e para isso conta com várias estações de início e de término.

São disponibilizados 03 tipos de bicicletas(clássica, elétrica, docked) para o atendimento das demandas de  02 tipos de clientes(membro e casual).

Para auxiliar no gerenciamento de locações, o setor de frotas, solicitou a análise de dados de locação de bicicletas do 3º trimestre de 2023.


## Problema de negócio
 * Caracterizar o perfil de locação de bicicletas no 3º trimestre de 2023.

  
## Tópicos para análise
* 5.1- quantidade de locações 
* 5.2- quantiade de devoluções 
* 5.3- %  de clientes 
* 5.4- %  de tipo de bicicleta
* 5.5- %  de demanda por dias da semana
* 5.6- %  de horários de início e de conclusão
* 5.7- identificar o perfil de locação por tipo de bicicleta e cliente(top3)
* 5.8- identificar o perfil de locação por estação (top5)
* 5.9 - identificar o perfil de devoluções por estação (top5)



## Ferramentas utilizadas

* Pyhton bibliotecas Pandas e Numpy - para limpeza,tratamento e análise de dados.
* VS Code - Editor de código


## Fonte de dados

Foram utilizados disponíveis no link: <https://divvy-tripdata.s3.amazonaws.com/index.html>


## Resumo Geral das análises

Na análise de dados de locações do 3º trimestre de 2023 (Julho a Setembro/2023) foram identicados os seguintes insights:

* 2,2 milhões de locações,

* 1,8 milhões de devoluções,

* 83 % de devoluções no período,

* 59% dos clientes são membro,

* 50% das locações são para bicicleta clássica,

* O mês de Agosto possui a maior quantidade de locações (34,99%) e de devoluções (34,99%);

* Poucas  devoluções são feitas no mês seguinte ao da locação, 

* Os dias com mais locações foram: Sábado(17,42%), Sexta-feira(15,12%) e Quinta-feira(14,35%).

* A maioria das locações acontecem às 17hs foram mais de 220 mil o que representa 10,07% no trimestre;

* Os horários de pico são entre 15 e 19 horas,

* A estação N/A possui os maiores percentuais de locação(15%) sendo a maior demanda para clientes membro e de bicicletas elétricas mais de 200mil,
horários com mais locações entre 17 e 18horas e dias de pico sexta-feira e sábado.

*A estação N/A apresenta a maior quantidade de devolução(16%), a maior parte dos clientes são membros e de bicicletas elétricas (197mil), 
horários com mais devoluções 17 e 18 horas, dias de pico sexta-feira e sábado.




## Perfil de locação por tipo de bicicleta e clientes

Descreve dias da semana e horários com a maior quantidade de locações detalhada por clientes por tipo de bicicleta.

| Tipo Bicicleta  | Cliente Casual | Cliente Membro |
| ------------- | ------------- | ------------- |
| Clássica  | Sábado de 13 às 15hs  | Terça, Quarta e Quinta – 17hs  |
| Elétrica  | Sexta-feira 17hs e Sábados 14 e 15hs  |Terça, Quarta e Quinta no horário das 17hs  |
| Docked  | Sábado de 13 às 15hs  | Não houve locação|


## Perfil de locação por estações

Para a análise foram consideradas as 5 estações com as maiores quantidades de locações no 3º trimestre de 2023.

* A Estação N/A(nome não identificado) apresentou 15,56% das locação sendo a maior demanda de locações para bicicletas elétricas sendo 200 mil para clientes membro e 142 mil  para clientes casuais.

Os dias com mais locações foram:
* sábado com 62 mil,
* sexta-feira com 54 mil
* quinta, domingo e terça com mais de 45mil

Os horários de pico são entre 15 e 19 horas, sendo:
* 17hs(30mil)
* 16 e 18 hs(28,4 mil), 
* 15 e 19hs(23 mil).

As demais estações tiveram mais locações para bicicletas clássicas e clientes casuais:
* Streeter Dr & Grand Ave  - representou 1,41% da demanda com 15 mil locações
* DuSable Lake Shore Dr & Monroe St – 0,86% da demanda com  9 mil locações	
* Michigan Ave & Oak St – representa 0.83% da demanda com  7 mil locações



## Perfil de devolução por estações


Para a análise foram consideradas as 5 estações com as maiores quantidades de devoluções no 3º trimestre de 2023.

* A Estação N/A(nome não identificado) apresentou 16,46% das locação sendo a maior quantidde de devoluções para bicicletas elétricas sendo 197 mil para clientes membro e 162 mil  para clientes casuais.

Os dias com mais devoluções foram:
* sábado com 65 mil, 
* sexta-feira com 58 mil
* quinta com 51mil 
* domingo e terça com mais de 48mil.

Os horários de pico são entre 15 e 19 horas, com :
* 17 e 18hs (mais de 33mil)
* 16 e 19 hs (com mais de 26 mil),
* 15 hs (mais de 23 mil).

As demais estações tiveram mais devoluções para bicicletas clássicas e clientes casuais, sendo:
* Streeter Dr & Grand Ave  - representou 1,42% da demanda com 16 mil devoluções
* DuSable Lake Shore Dr & North Blvd – 0,95% da demanda com 9 mil devoluções
* DuSable Lake Shore Dr & Monroe St – 0,82% da demanda com  8 mil devoluções


