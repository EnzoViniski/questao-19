Algoritmo "Soma"

var
   n1, n0, soma, divi: real
   
inicio
   //Entrada de dados
   escreva("Digite o valor de n (deve ser maior que 1 e inteiro): ")
   leia(n1)
   
   se (n1 < 1) entao
      escreva("NUMERO INVALIDO, DIGITE UM NUMERO INTEIRO MAIOR QUE UM")
   senao
      n0 <- 0
      enquanto (n1 > 0) faca
         divi <- 1 / n1
         soma <- n0 + divi
         n1 <- n1 - 1
         n0 <- soma
      fimenquanto
      escreva(n0)
   fimse
fimalgoritmo
         
      
