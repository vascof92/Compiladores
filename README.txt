**PROJECT TITLE: #18 cykparser

**GROUP: T03G03

	NAME1: <name>, NR1: <number>, GRADE1: <0 to 20 value>, CONTRIBUTION: <0 to 100 %)

	Jorge Filipe Monteiro Lima, 201000649, 16, 15
	Lu�s Miguel Barroso Natividade, 201000618, 16, 15
	Nuno Filipe Dinis Cruz, 201004232, 16, 40
	Vasco Manuel P�rola Filipe, 201001926, 16, 30

**SUMMARY: O nosso programa verifica se uma dada frase pertence a uma dada gram�tica fora de contexto que esteja na CNF (Chomsky Normal Form), usando
	o algoritmo CYK.

**DEALING WITH SYNTACTIC ERRORS: Se houverem erros sint�cticos a execu��o do programa � terminada, com indica��o de que a sintaxe � inv�lida.

**SEMANTIC ANALYSIS: A an�lise sem�ntica consiste em verificar se todos os s�mbolos existentes nas regras da gram�tica dada t�m um valor atribu�do.

**INTERMEDIATE REPRESENTATIONS (IRs): � apresentada no in�cio uma �rvore sint�tica abstrata.

**OVERVIEW: O programa aceita regras de uma gram�tica seguidas da frase a verificar (ver txt's de exemplo). As regras s�o aceites com a seguinte sintaxe: 
	"A -> B C;" ou "B -> a".
	Ao fazer parse das regras estas s�o guardadas em estruturas (arraylist bidimensional), sendo ent�o feita a an�lise sem�ntica. Se a gram�tica for
	v�lida, � ent�o aplicado o algoritmo CYK para verificar se a frase pertence � gram�tica. No fim � apresentada a tabela CYK e indica��o se a frase
	pertence ou n�o.

**TESTSUITE AND TEST INFRASTRUCTURE: Na pasta testsuite est� um jar que corre (sem argumentos) os exemplos na pasta "examples".

**PROS: O algoritmo foi implementado com sucesso.

**CONS: A representa��o interm�dia podia estar melhor estruturada.