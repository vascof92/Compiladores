**PROJECT TITLE: #18 cykparser

**GROUP: T03G03

	NAME1: <name>, NR1: <number>, GRADE1: <0 to 20 value>, CONTRIBUTION: <0 to 100 %)

	Jorge Filipe Monteiro Lima, 201000649, 16, 15
	Luís Miguel Barroso Natividade, 201000618, 16, 15
	Nuno Filipe Dinis Cruz, 201004232, 16, 40
	Vasco Manuel Pérola Filipe, 201001926, 16, 30

**SUMMARY: O nosso programa verifica se uma dada frase pertence a uma dada gramática fora de contexto que esteja na CNF (Chomsky Normal Form), usando
	o algoritmo CYK.

**DEALING WITH SYNTACTIC ERRORS: Se houverem erros sintácticos a execução do programa é terminada, com indicação de que a sintaxe é inválida.

**SEMANTIC ANALYSIS: A análise semântica consiste em verificar se todos os símbolos existentes nas regras da gramática dada têm um valor atribuído.

**INTERMEDIATE REPRESENTATIONS (IRs): É apresentada no início uma árvore sintática abstrata.

**OVERVIEW: O programa aceita regras de uma gramática seguidas da frase a verificar (ver txt's de exemplo). As regras são aceites com a seguinte sintaxe: 
	"A -> B C;" ou "B -> a".
	Ao fazer parse das regras estas são guardadas em estruturas (arraylist bidimensional), sendo então feita a análise semântica. Se a gramática for
	válida, é então aplicado o algoritmo CYK para verificar se a frase pertence à gramática. No fim é apresentada a tabela CYK e indicação se a frase
	pertence ou não.

**TESTSUITE AND TEST INFRASTRUCTURE: Na pasta testsuite está um jar que corre (sem argumentos) os exemplos na pasta "examples".

**PROS: O algoritmo foi implementado com sucesso.

**CONS: A representação intermédia podia estar melhor estruturada.