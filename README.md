# Projeto-Fechamento
Projeto de fechamento para calculo das comissões do time do call-center

Este projeto  foi criado com objetivo de otimizar o processo de calculo dos valores de fechamento dos atendentes da empresa.
Uma vez que o financeiro estava levando horas, se não dias, para faze-lo.

<h3>Resumo simples das etapas do projeto:</h3>
  <h6>Primeira etapa:</h6>
    1 - Criar uma "View" que encontre os casos tratados no último mês e descubra se foram sucesso ou insucesso<br>
    2 - Criar uma segunda "view" que, com base na primeira, verifique se o caso foi atendido ou não com sucesso no sistema do contratante.<br>
    3 -  Criar uma "Stored procedure" que gere um arquivo para conferência manual do time financeiro. Bem como um arquivo onde a supervisão possa marcar os atendentes que serão excetuados da meta.
    
  <h6>Segunda etapa:</h6>
    1 - Consumir os arquivos já analisados pela Supervisão e pelo time do financeiro<br>
    2 - Consumir o fechamento de horas enviado pelo RH (será usado para calcular os descontos referentes a atrasos e faltas)
   
  <h6>Terceira etapa</h6>
    1 - Conciliar todos os arquivos retornados e comparar as metas para calcular o valor final a ser pago para cada atendente.
