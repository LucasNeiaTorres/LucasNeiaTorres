# Lucas Néia Torres

> **In short.** CS undergrad at UFPR, in Curitiba, Brazil. I build systems in C and
> Python — a teaching OS kernel, parallel algorithms, vehicle routing heuristics,
> image classifiers — and I write READMEs that say where each one falls short.

Estudante de Ciência da Computação na UFPR. O que está aqui é código de disciplina
e de projeto próprio: sistemas em **C** (SO didático, programação paralela,
grafos), otimização e aprendizado de máquina em **Python**, web em **Java**.

Nos projetos que valem, o README diz o que é, por que foi feito daquele jeito e o
que ficou de fora.

## O que vale a pena olhar

- **[en-tracker](https://github.com/LucasNeiaTorres/en-tracker)** — painel de um
  plano de 30 dias de inglês falado com uma IA. O mais maduro daqui: CI no GitHub
  Actions e 151 testes. A regra central é nunca assumir que a IA registrou a
  sessão — o painel compara o que o plano esperava com o que está de fato no log.
- **[tcc-mdvrp](https://github.com/LucasNeiaTorres/tcc-mdvrp)** — TCC: roteamento
  de veículos com múltiplos depósitos (MDVRP) sob falhas. Clusterização capacitada
  e algoritmo genético montam o plano do dia sobre as instâncias de Cordeau; um
  simulador por eventos bloqueia vias com os veículos já na rua, e uma cascata de
  contingência em três estágios responde.
- **[PingPongOS](https://github.com/LucasNeiaTorres/PingPongOS)** — sistema
  operacional didático em C, construído etapa por etapa: fila de tarefas, troca
  de contexto e escalonador preemptivo por temporizador (`ITIMER_REAL`/`SIGALRM`).
- **[QueroEmprestar](https://github.com/LucasNeiaTorres/QueroEmprestar)** — TCC do
  técnico em informática no IFPR: sistema de locação de objetos entre usuários,
  em Java Web + MySQL.
- **[classificador-imagens-biomedicas](https://github.com/LucasNeiaTorres/classificador-imagens-biomedicas)**
  — classificação de radiografias DICOM (pneumotórax) por comparação de
  histogramas do OpenCV, avaliada em leave-one-out com sensibilidade e
  especificidade por método.
- **[classificador-mnist](https://github.com/LucasNeiaTorres/classificador-mnist)**
  — kNN e classificador linear no MNIST, varrendo PCA, métricas de distância e
  valores de `k`, com os resultados exportados para análise.
- **[parallel-partition-mpi](https://github.com/LucasNeiaTorres/parallel-partition-mpi)** ·
  **[parallel-partition-pool](https://github.com/LucasNeiaTorres/parallel-partition-pool)** ·
  **[parallel-binary-search](https://github.com/LucasNeiaTorres/parallel-binary-search)**
  — programação paralela em C: o mesmo tipo de problema atacado com MPI e com
  pool de threads.

## Contato

[LinkedIn](https://www.linkedin.com/in/lucas-neia-torres/) · <lucasneia07@gmail.com>
