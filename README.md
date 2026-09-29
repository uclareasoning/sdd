# The Sentential Decision Diagram Package
sdd version 2.0, January 8, 2018

This repository provides the source code of the SDD package released at http://reasoning.cs.ucla.edu/sdd

## Description

The SDD package is implemented in the C language.

- `libsdd/`: source code of the SDD library
- `sdd/`: source code of the FNF-to-SDD compiler for compiling CNFs and DNFs to SDDs
- `doc/`: manuals for both beginner users and advanced users

## Talks and Tutorials

- **SDD: A New Canonical Representation of Propositional Knowledge Bases**.
Presented at IJCAI 2011. 
[youtube](https://www.youtube.com/watch?v=_5Estmve91o)

- **Tutorial: Bottom-Up Knowledge Compilers**.
[youtube](https://www.youtube.com/watch?v=8yZapazT9Ls)

## Papers

### Fundamentals

- Adnan Darwiche. **SDD: A New Canonical Representation of Propositional Knowledge Bases.**
In Proceedings of the Twenty-Second International Joint Conference on Artificial Intelligence (IJCAI), pages 819-826, 2011. [pdf](http://reasoning.cs.ucla.edu/fetch.php?id=121&type=pdf)
- Yexiang Xue, Arthur Choi, and Adnan Darwiche. **Basing Decisions on Sentences in Decision Diagrams.**
In Proceedings of the Twenty-Sixth AAAI Conference on Artificial Intelligence (AAAI), pages 842-849, 2012. [pdf](http://reasoning.cs.ucla.edu/fetch.php?id=123&type=pdf)
- Guy Van den Broeck and Adnan Darwiche. **On the Role of Canonicity in Knowledge Compilation.**
In Proceedings of the 29th Conference on Artificial Intelligence (AAAI), pages 1641-1648, 2015. [pdf](http://reasoning.cs.ucla.edu/fetch.php?id=151&type=pdf)
- Simone Bova. **SDDs Are Exponentially More Succinct than OBDDs.**
In Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence (AAAI), pages 929-935, 2016. [pdf](https://arxiv.org/abs/1601.00501)

### Compilers: Bottom-Up

- Arthur Choi and Adnan Darwiche. **Dynamic Minimization of Sentential Decision Diagrams.**
In Proceedings of the Twenty-Seventh Conference on Artificial Intelligence (AAAI), pages 187-194, 2013. 
[pdf](http://reasoning.cs.ucla.edu/fetch.php?id=128&type=pdf)

### Compilers: Top-Down

- Umut Oztok and Adnan Darwiche. **A Top-Down Compiler for Sentential Decision Diagrams.**
In Proceedings of the 24th International Joint Conference on Artificial Intelligence (IJCAI), pages 3141-3148, 2015. 
[pdf](http://reasoning.cs.ucla.edu/fetch.php?id=157&type=pdf) 
[miniC2D compiler](http://reasoning.cs.ucla.edu/minic2d/)

## Related Software

- [PySDD](https://github.com/wannesm/PySDD): a python wrapper for interactive use of the SDD library
- [SDD.jl](https://github.com/pedrozudo/SDD.jl): a Julia wrapper for interactive use of the SDD library
- [JSDD](https://github.com/ML-KULeuven/JSDD): a Java wrapper for the SDD library
- [LearnSDD](https://github.com/ML-KULeuven/LearnSDD): for learning tractable Markov networks
- [LearnPSDD](https://github.com/UCLA-StarAI/LearnPSDD): for learning the structure of Probabilistic SDDs (PSDDs)

## Contact

Feedback, bug reports, and questions can be sent to sdd@cs.ucla.edu
