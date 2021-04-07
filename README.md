Testes Unitários em C# - O Kata String Calculator

Vamos criar uma classe chamada StringCalculator, com um único método estático com a assinatura estática int Add(string numbers);
O método pega uma string representando números separados por uma vírgula, e retorna sua soma.
Se passarmos uma string vazia, o método deve retornar zero.
A passagem de um único número deve resultar no próprio número.
Se passarmos números negativos, o método deve lançar uma ArgumentException, com a mensagem “Números negativos não permitidos:” seguida dos negativos que foram especificados.
O método deve ignorar números maiores que 1000 devem. Portanto, “1.2.1000” deve resultar em 1003, mas “1.2.1001” deve resultar em 3.
