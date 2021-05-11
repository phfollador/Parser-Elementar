# Parser-Elementar
Parser desenvolvido na disciplina de compiladores.

## Como usar?
Antes de tudo, você deve se certificar de que possui o JavaCC em sua máquina!

Feito isso, podemos partir ao passo-a-passo:
* Baixe os arquivos e deixe-os todos na mesma pasta
* Inicie um CMD e vá até o diretório da pasta onde se encontram os arquivos
* Podemos então montar o parser através dos seguintes comandos:
  * javacc Gramatica.jj
  * javac *.java
* Feito isso, temos o parser completamente montado, o que devemos fazer em seguida é aplicar uma entrada e conferir se a sintaxe está sendo avaliada corretamemte. Podemos fazer isso através do comando:
  * java Gramatica <Entrada.txt
* Observe no PDF que contém a descrição do trabalho que existem várias entradas para testes. Algumas entradas são aceitas e outras não devido a erros sintáticos.
