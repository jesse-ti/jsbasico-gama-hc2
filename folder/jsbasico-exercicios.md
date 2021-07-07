##### EXERCÍCIOS:



|  1 | Descrição |
| --- | --- |
| `FizzBuzz` | - Divisivel por 3 => 'Fizz' \ Divisivel por 5 => 'Buzz'\ Divisivel por 3 e 5 => 'FizzBuzz'\ Se não for um número => 'Não é um número'\ Se não for divisivel nem por 3 e nem por 5 => Entrada|

    let  resultado  =  fizzBuzz();

	console.log(resultado)

	function  fizzBuzz(entrada){
	
	// ele verifica se o operador typeof  for diferente de número, ele vai retornar 'não é um número'
	if (typeof  entrada  !==  'number')
	return  'Não é um número';
	
	// Aqui ele diz se o resto da divisão da entrada por 3 e 5 for igual a 0, ele me retorna o 'FizzBuzz'
	if ((entrada  %  3  ===  0) && (entrada  %  5  ===  0))

	return  'FizzBuzz'

	// Se o resto da divisão da entrada por 3 for igual a 0, ele me retorna apenas o 'Fizz'
	if (entrada  %  3  ===  0)

	return  'Fizz'

	  
    // Se o resto da divisão da entrada por 5 for igual a 0, ele me retorna apenas o 'Buzz'
	if (entrada  %  5  ===  0)

	return  'Buzz'

	// E por último se não atender nenhum dos casos a cima, me retorna a própria entrada
	return  entrada;

	}
---
|  2 | Descrição |
| --- | --- |
| `Reverse a String` | Imprima a string no console ao contrário|

	let  newStr  =  '';
	
	function  reverseAString (str){
	// Inicio o contador no comprimento da string - 1 e que se repita enquanto i for maior ou igual a 0, e decrementando
	for (let  i  =  str.length -  1; i  >=0; i--) {
			newStr += str [i];
		}
		console.log(newStr);
	}

	let resultado = reverseAString('Hello Hiring Coders #2')

---
|  3 | Descrição |
| --- | --- |
| `Convert Celsius to Fahrenheit` | Converter Celsius em Fahrenheit|

	function  convertToFahrenheit(value){
	// a fórmula para se obter o resultado esperado sabendo que na matemática primeiro se faz a multiplicação e depois a soma
	return  value  *  1.8  +  32

	}
	// na saída ao colocar nosso valor que nesse caso é 40 obtemos o resultado da conversão
	let  result  =  convertToFahrenheit(40)

	console.log(`O valor em Fahrenheit é ${result}`)



