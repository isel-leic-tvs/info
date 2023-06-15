## ISEL - Instituto Superior de Engenharia de Lisboa
### Técnicas de Virtualização de Sistemas / System Virtualization Techniques
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/isel-leic-tvs/info/blob/main/README.md)
[![pt](https://img.shields.io/badge/lang-pt-green.svg)](https://github.com/isel-leic-tvs/info/blob/main/README.pt.md)

#### Informações institucionais
* [Informação oficial sobre a unidade curricular](https://www.isel.pt/leic/tecnicas-de-virtualizacao-de-sistemas)
* [Informações gerais para estudantes Erasmus+ (*incoming*)](https://www.isel.pt/ensino/programas-de-mobilidade/erasmus-alunos-incoming/informacoes-gerais)

---

#### Informações suplementares
*As informações abaixo são fornecidas por conveniência, mas estão incompletas, não são oficiais, podem estar desatualizadas e não substituem as informações institucionais oficiais.*

| Informações Gerais        |                                               |
|---------------------------|-----------------------------------------------|
| Área Científica           | Informática e Computadores                    |
| Créditos ECTS             | 6 créditos                                    |
| Grau, Ano/Semestre        | Licenciatura, 3º ano / 5º semestre            |
| Língua                    | Português ou Inglês                           |
| Disponível em             | Semestre Outono/Inverno (Set. - Fev.)         |
| Horas de contacto em aula | 15 semanas x 4,5 horas/semana em aula         |
| Docente responsável       | [João Trindade](mailto:joao.trindade@isel.pt) |

#### Descrição
A distribuição e execução de software depende frequentemente de infraestruturas computacionais virtualizadas, em que a virtualização ocorre em diferentes níveis e formas. Numa das suas formas mais elementares, os sistemas operativos geralmente oferecem a possibilidade de executar múltiplos programas em simultâneo em ambientes (razoavelmente) isolados, chamados *processos*, em que um programa em execução aparenta ter um ambiente computacional só para si. Alguns sistemas operativos também oferecem a possibilidade de, através de *emulação*, executar software produzido para um sistema com um microprocessador bastante diferente. Noutros casos, permitem executar programas desenhados para outro sistema operativo. Adicionalmente, existe software de sistema especializado em criar, sobre um único sistema físico, múltiplas instâncias de computadores virtuais, usualmente designados como *máquinas virtuais*. E, noutro nível e forma, temos sistemas prontos para executar software contentorizado, em que um determinado arranjo de peças de software é colocado em execução num ambiente computacional dedicado, conhecido como *contentor*, sobre um sistema operativo.

Nesta unidade curricular, exploraremos estas técnicas de virtualização, maioritariamente da perspetiva da distribuição/implantação de software, mas também, quando for razoável, procurando compreender como cada tipo de virtualização é conseguida. Durante o semestre, para além de assistirem às aulas, os alunos formarão grupos para completarem os trabalhos práticos, explorando estes tópicos na prática. Um teste final (geralmente em Jan./Fev.) irá avaliar individualmente o conhecimento de cada aluno.

#### Pré-requisitos
* Será necessário desenvolver código em C, incluindo para interagir com o sistema operativo. Os alunos deverão ter pelo menos dois (mas preferencialmente três) semestres de experiência de programação, em qualquer linguagem, incluindo pelo menos uma unidade curricular não introdutória em C.
* É necessário ter conhecimentos elementares de arquitetura de computadores, incluindo alguma linguagem *assembly*.
* Conta-se que os alunos estejam familiariados com *multithreading* e sincronização. Embora a unidade curricular não tenha um foco ou peso particular nestes assuntos, não existirá um esforço para os evitar e serão usados quando for necessário.
* Os alunos devem ter conhecimentos essenciais sobre redes IP e ser capazes de escrever software usando *sockets*, se for necessário.
