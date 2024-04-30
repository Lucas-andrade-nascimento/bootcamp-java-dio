# bootcamp-java-dio
repositorio para armazenar os códigos e notas do bootcamp da dio 

**Obs:** esse arquivo serão notas pessoais. Eu ja possuo conhecimento em Java e nao vou ficar anotando cada nota de aula aqui, somente aquelas que eu revisei ou aprendi nesse curso. 

## Trilha 1 - Java Básico
[Repositório com material da trilha](https://github.com/digitalinnovationone/trilha-java-basico.git)

## Curso - Aprendendo a sintaxe java

### Anatomia das classes 

java usa camelCase para variaveis e métodos e PascalCase para classes.

para mais regras de declaração de variaveis, acesse o material do processos no caminho:
gitbook/sintaxe/anatomia-das-classes.md

A própria IDE vai mostrar como erro, caso as regras sejam quebradas. 

### Tipos e variáveis

a palavra `final`, é reservada e indica que a variável em que ela foi atribuida não pode ser modificada. Ela pode ser atribuida totalmente em upper case para deixar claro que não devem ser modificadas.

**Dica do prof:** Estudar a Classe String (pq ele nao vai passar kk).

### Operadores 

Sobre operador soma e concatenação: Se for imprimir um ou mais numeros como um `int` com uma `String`, o Java vai tratar como concatenação, nao soma:
`System.out.print("1" + 1 + 1);`
O Java nao vai somar 1 + 1, ele vai imprimir: 1 + 1 +1.

A menos que os valores numericos estejam entre parenteses: 
`System.out.print("1" + (1 + 1));`
O Java vai imprimir: 12.
