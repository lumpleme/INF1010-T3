Descrição:
Implementar uma tabela de dispersão (ou hash) criando o TDA hashtable (interface hashtable.h e arquivo 
hashtable.c)

Implementar algoritmos de inclusão, busca e exclusão em vetor de M posições (onde M é o maior número primo 
após 1024, ou 210), usando hashing com tratamento de colisão para armazenar placas de automóveis no formato 
“CCCNNNN” onde C é um caractere maiúsculo e N um numeral. Os algoritmos devem prever a entrada de dados 
via arquivo texto contendo as placas de automóveis geradas aleatoriamente (em cada linha do arquivo texto 
deverá vir uma placa seguida pelos caracteres <cr> <lf>). 

A rotina de tratamento de colisão deve armazenar a nova placa no próprio vetor (encadeamento interno). Não 
devem ser usadas outras estruturas de dados. A função hash deve ser definida individualmente e utilizar 
encadeamento interior.

Calcule o total de colisões geradas e os tempos de inclusão e de busca a todos os elementos do vetor (a busca 
deve ser feita após o término da inclusão de todas as placas). Gere e imprima gráficos de linha onde o eixo Y seja 
o tamanho de entrada e eixo X o tempo de execução para diferentes valores de entrada, por exemplo: 128, 256 
e 512 placas (complexidade prática). 

Todos os aspectos considerados deverão ser avaliados. A avaliação vai ser feita em um mesmo equipamento 
para todos os trabalhos. A maior nota caberá ao grupo que entregar o trabalho completo, com menor número 
de colisões e menor tempo de execução dos algoritmos. Para a avaliação será fornecido um arquivo de placas 
geradas aleatoriamente para servir de comparação entre os trabalhos (número de colisões e tempo de 
execução). 

Orientações de entrega: 
Faça o upload no site do EAD dos seguintes: 
 O TDA hashtable (interface .h e arquivos .c) 
 Um relatório em formato .pdf contendo: 
• Identificação. Nome e matricula do(s) aluno(s), sendo no máximo 2 alunos por trabalho; 
• Introdução. Breve descrição sobre o conteúdo do trabalho; 
• Estrutura do programa. Descrição da interface e as funções implementadas; 
• Solução. Descrição da solução passo a passo de cada item do programa, incluindo capturas do código 
fonte e a saída do programa. A descrição da solução deve incluir ainda: 
 O total de colisões geradas e os tempos de inclusão e de busca a todos os elementos do vetor 
 Os tempos tomados para cada algoritmo 
 Gráfico de tamanho da entrada x tempo de execução de cada um, para diferentes valores de 
entrada por exemplo: 128, 256 e 512 placas (complexidade prática). 
• Observações e conclusões. Descrição de aspectos que precisem ser destacados, tais como dificuldades 
e facilidades encontradas.
