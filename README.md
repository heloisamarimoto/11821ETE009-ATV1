# 11821ETE009-ATV1
Em relação ao roteiro de atividade 1 a, que consistia em fazer a instalações dos acessos aos programas necessários. 
A única dificuldade encontrada foi no momento de fazer a verificação se havia sido instalado de forma correta o GCC ARM Toolchain, não estava aparecendo a versão do GNU, para gcc,g++ e gdb. 
A solução encontrada foi reinstalar o GCC ARM Toolchain, sendo assim funcionado corretamete. Sendo assim em relação a essa ativadade todos os outros passos seguiram o fluxo de acordo com o roteiro sem encontrar dificuldades.

Para a Atividade de Laboratório 2:
Criei a partir do Ubunti 20.04 LTS a pasta lab-02, onde foram criados os arquivos main.c, startup.c e Makefile. 
Sendo criado de inicio o arquivo main.c e após isso para a melhor execução e facilitação na compilação foi criado o Makefile, e como estamos trabalhando com sistemas embarcados, sabemos que quando um executavel é carregado na memoria ele não vai de inicio na função main, sendo assim criei o arquivo startup.c para poder fazer a inicalização, a preparação, adicionar argumentos, chamar a função main entre outros.

Para a Ativide de Laboratório 3:
Foi criada igual o laboratório 2 a pasta par realizar o programa que é piscar um led. 
Para realizar o programa foi definido o em qual pino do microcontrolador o LED ia ser conectado e o tipo de sinal para ligar/desligar. Para acionar o LED configurei o pino PC13, consegui fazer a alteração para que a saída dosse de forma atômica, foi criando um array para o armazenamento de informações referentes à versão do programa, foi feito o processo de linkedição para o objeto se junte ao código objeto relocável em um local e assim gerar apenas um arquivo, e por fim foi alterado no Makefile para a realização do processo de linking automaticamente. 
