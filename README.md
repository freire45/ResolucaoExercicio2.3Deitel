# ResolucaoExercicio2.3Deitel

**Resolução do exercício 2.3 do Deitel**

**2.3 Escreva instruções para realizar cada uma das tarefas a seguir:**<br>
**a) Declare que as variáveis c, thisIsAVariable, q76354 e number serão do tipo int.**<br><br>
Resposta<br><br>

int c, thisIsAVariable, q76354, number; <br><br>
Ou <br><br>

int c;<br>
int thisIsAVariable;<br>
int q76354; <br>
int number;<br><br>

**b) Solicite que o usuário insira um inteiro.**<br><br>

System.out.print("Digite um valor inteiro: "); <br><br>

**c) Insira um inteiro e atribua o resultado à variável int value. Suponha que a variável Scanner input possa ser utilizada para ler um valor digitado pelo usuário.** <br><br>

int value = entrada.nextInt();<br><br>

**d) Imprima “This is a Java program" em uma linha na janela de comando. Use o método System.out.println.** <br><br>

System.out.println("This is a Java Program"); <br><br>

**e) Imprima “This is a Java program" em duas linhas na janela de comando. A primeira deve terminar com Java. Utilize o método System.out.printf e dois especificadores de formato %s.** <br><br>

System.out.printf("%s%n%s%n", "This is a Java", "program"); <br><br>

**f) Se a variável number não for igual a 7, exiba “The variable number is not equal to 7".**<br><br>

If(number != 7)<br>
System.out.println("The variable number is not equal to 7"); <br><br>
