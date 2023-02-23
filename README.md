# Modulo14

###Exercícios:

1.	Resolva as operações:
●	10 + 15 = 25 (number)
●	“10” + 2 = 12(string)
●	“10” * 2 = 20(number)
●	“10” / 3 = 3.3333333333333335 (float)
●	“10” % 3 = 1 (number)
●	10 + true = 11  (number)
●	10 == ”10” = true (boolean)
●	10 === “10” = false (boolean)
●	10 < 11 = true (boolean)
●	10 > 12 = false (boolean)
●	10 <= 10.1 = true (boolean)
●	10 > 9.99 = true (boolean)
●	10 != “dez” = true (boolean)
●	10 + true =11 (number)
●	“dez” + true = deztrue (string)
●	10 + false = 10 (number)
●	10 * false = 0 (number)
●	true + true = true (boolean)
●	10++ = Uncaught SyntaxError
●	10-- = Uncaught SyntaxError
●	1 & 1 = 1(number)
●	1 & 0 = 0 (number)
●	0 & 0 = 0 (number)
●	1 & 0 = 0 (number)
●	0 / 1 = 0 (number)
●	5 + 5 == 10 = true (boolean)
●	“5” + ”5” == 10 = false (boolean)
●	“5” * 2 > 9 = true (boolean)
●	(10 + 10) * 2 = 40 (number)
●	10 + 10 * 2 = 30 (number)
2.	Responda as perguntas de acordo com as variáveis. var branco = “preto”;
var preto = “cinza”; var cinza = “branco”; var carro = “preto”; var valor = 30000; var prestacao = 750;
 
 


a)	branco == “branco”  false (boolean)
b)	branco == cinza   false (boolean)
c)	carro === branco false (boolean)
d)	var cavalo = carro == “preto” ? “cinza” : “marron”; false (boolean)

e)	Quantas prestações são necessárias para pagar o valor do carro com uma entrada de 3.000? Demonstre a operação.

			30000-3000=27000/750=36


f)	Somando as variáveis de cores é formada uma string de quantos caracteres? 20 incluindo virgula


<p>Find the length of "Preto, cinza, branco":</p>

<p id="demo"></p>

	<script>
        let text = "Preto, cinza, branco";
        let length = text.length;

        document.getElementById("demo").innerHTML = length;
	</script>
