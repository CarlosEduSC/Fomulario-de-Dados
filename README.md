# Formulario de Dados
 
Requisitos do Formulario:

* O programa tera os seguintes dados de pessoas que trabalham em uma
empresa:

*
*

       (a) nome;
       (b) grau de estudo: 1, 2, 3, 4 ou 5;
       (c) quantidade de línguas que fala;
       (d) cargo que ocupa: 1º, 2º, 3º ou 4º nível;
       (e) seu índice de produtividade: entre 0 e 1,0;
       (f) 


Baseado nisto, o programa atende aos seguintes requisitos:
       
       3) O salário será calculado, em uma função, pela seguinte regra:
              
              Se Índice de Produtividade > 0,7 então
              Salário = (Salário base + (Formação*100) + (Poliglota*100)) + (Salário base* Índice de
              Produtividade).
              
              Se Índice de Produtividade entre 0,4 e 0,7 então
              Salário = (Salário base + (Formação*100) + (Poliglota*100))
              
              Se Índice de Produtividade < 0,4 então
              Salário = (Salário base + (Formação*100) + (Poliglota*100)) - (Salário base* (0,4 - Índice de
              Produtividade))
              
       4) O programa ainda disponibilizara, também por uma função, a quantidade de funcionários
          que ganham acima da média.

       5) O programa permitirá ao usuário escolher entre funcionalidades (cadastro, cálculo de
             salário, quantidade maior que a média, e edição e visualização das informações de um
             determinado funcionário). O usuário poderá escolher as funcionalidades por meio de um menu,
             podendo repeti-las até que ele deseje sair do programa.
