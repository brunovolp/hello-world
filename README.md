# hello-world
Análise e Visualização de Dados em R - Aula 3

## SimulaCOVID: um simulador feito por gestores públicos para a gestão pública

A sociedade atravessa uma pandemia global _sem precedentes históricos_ desde a Gripe Espanhola - e com efeitos econômicos previstos **similares à Grande Depressão de 1929**. Nesse sentido, para que os governos possam atuar de maneira assertiva e rápida perante este flagelo, são necessários dados claros para subsidiar a tomada de decisão.

A plataforma [**SimulaCOVID**](https://simulacovid.coronacidades.org/) busca atuar em uma grande dor desta área: há muitos dados disponíveis, principalmente em plataformas como o DataSUS, porém sua análise é, muitas vezes, demorada e ineficiente para ser transformada em informação para a gestão da saúde pública local. Com isso, é, segundo o próprio site, um **_simulador de demanda por leitos hospitalares e ventiladores_**.

Criada por dois brasileiros egressos do _Master in Public Administration_ da Harvard Kennedy School, uma das mais prestigiadas escolas de administração pública do mundo, a solução é dividida em várias etapas, a serem abordadas a seguir.

### Análise da plataforma

O site é _bastante intuitivo_: há, em seu início, um [vídeo-tutorial](https://youtu.be/-4Y0wHMmWAs) explicando como o SimulaCOVID deve ser utilizado. A seguir, há, em ordem:

  1. **Seleção de região:** É necessário selecionar estado e município/região SUS.
  2. **Verificação de dados:** É possível verificar se os dados, para a sua região, estão atualizados e, em caso negativo, adequar os valores até chegarem aos corretos.
  3. **Análise do resultado:** A plataforma informa em quantos dias, em cenários de nenhuma política de restrição e com isolamento social, serão atingidas a capacidade máxima de leitos e ventiladores. Fazendo um teste para Belo Horizonte, a plataforma indica que, com isolamento social, demoraríamos **mais de 90 dias** para entrar em colapso. 
  4. **Próximos passos:** É possível simular o resultado de possíveis intervenções, informando em quantos dias se pretende adotar a estratégia de medidas restritivas e, logo após, a quarentena. Por fim, a plataforma provê um gráfico (_expresso abaixo, em que simulei o cenário atual de Belo Horizonte_) para mostrar, na curva amarela, a demanda por leitos, e, na curva azul, a demanda por respiradores. Em ambas, **a curva nunca pode ficar maior que a reta**.
  
  ![alt text](https://i.imgur.com/wENABbW.png)
  
Uma plataforma que fornece análises rápidas (índice de 84/100 no [Google PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?hl=pt-br&url=https%3A%2F%2Fsimulacovid.coronacidades.org%2F)) e de uma maneira clara e de fácil entendimento merece somente pontos positivos e louros. Em momentos como os que estamos enfrentando, boas ideias sendo executadas são um ponto fundamental para que consigamos uma rápida recuperação. Cuide-se e #fiqueemcasa! :eyes:
  

#### Dica

Há muitos dados disponíveis também neste link: https://www1.folha.uol.com.br/deltafolha/. Boa sorte e boa análise! :+1: :chart_with_upwards_trend:
