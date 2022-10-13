Considere o código anexo (original.c) como referência para esse trabalho.

O desenvolvedor assumiu as seguintes hipóteses:

- duas threads competem por dois mutexes: mutex1 e mutex2

- para o seu correto funcionamento, a thread1 precisa adquirir, e manter consigo, mutex1 E mutex2 (nessa ordem)

- para o seu correto funcionamento, a thread2 precisa adquirir, e manter consigo, mutex2 E mutex1 (nessa ordem)

A atividade consiste em apresentar uma solução (funcional) para o problema, já que a solução de

referência apresenta a possibilidade de resultar em um deadlock (impasse).

Para tanto, deve-se empregar a chamada de sistema "pthread_mutex_trylock" que é a variante não

bloqueante de acesso (lock) em mutexes. Consulte a página do manual no sistema para obter todos

os detalhes sobre essa chamada.
