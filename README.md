## ISEL - Instituto Superior de Engenharia de Lisboa
### System Virtualization Techniques / Técnicas de Virtualização de Sistemas
[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/isel-leic-tvs/info/blob/main/README.md)
[![pt](https://img.shields.io/badge/lang-pt-green.svg)](https://github.com/isel-leic-tvs/info/blob/main/README.pt.md)

#### Institutional information
* [Official course unit information](https://www.isel.pt/en/leic/systems-virtualization-techniques)
* [General information for Erasmus+ incoming students](https://www.isel.pt/en/ensino/programas-de-mobilidade/erasmus-alunos-incoming/informacoes-gerais)

---

#### Supplementary information

| General Information    |                                               |
|------------------------|-----------------------------------------------|
| Scientific Area        | Computer Science and Engineering              |
| ECTS Credit Points     | 6 credit points                               |
| Level, Year/Semester   | Undergraduate, 3rd year / 5th semester        |
| Language               | English or Portuguese                         |
| Available in           | Autumn-Winter Semester (Sep. - Feb.)          |
| In-class contact hours | 15 weeks x 4.5 hours per week in class        |
| Course Manager         | [João Trindade](mailto:joao.trindade@isel.pt) |

#### Description
In order to optimize the use of existing hardware resources and to simplify the management and maintenance of computer systems, software deployment and execution frequently relies on virtualized computing infrastructures, where the virtualization occurs in different levels and forms. Operating systems use basic virtualization techniques to allow multiple programs to execute simultaneously in (somehow) isolated environments called *processes*, where a program in execution appears to have a computing environment for itself. Some operating systems also offer, via *emulation*, the possibility of running programs originally produced for microprocessors with different instruction sets. In other cases, they allow running software programs designed for a different operating system. Additionally, there exists specialized system software that is able to provide, on top of a single physical system, multiple instances of virtual computers, usually known as *virtual machines*. Also, in a different level and form, we have systems ready to run containerized software, where a particular arrangement of software parts is set to run as a group of processes in a dedicated computing environment, known as a *container*, on top of an operating system.

In this course unit, we will explore these virtualization techniques, mainly from the perspective of software deployment, but also, when reasonable, looking at how each type of virtualization is achieved. During the semester, besides attending lectures, students will also work in groups to complete assigned coursework, exploring these subjects in practice. A final written test (usually in Jan./Feb.) will assess students' knowledge individually.

Note that there is a partial overlap of topics with traditional course units about Operating Systems, except for concurrency and synchronization, which is covered in another course unit: [Concurrent Programming](https://www.isel.pt/en/leic/concurrent-programming). Also note that a particular form of virtualization, usually know as *managed runtime environments* or *virtual execution environments* (such as the Java Virtual Machine, Microsoft's Common Language Runtime or WebAssembly runtimes) are not covered in this course unit, as there is a specific course unit dedicated to these: [Languages and Managed Runtimes](https://github.com/isel-leic-ave/info/blob/main/README.md).

#### Prerequisites
* Students will need to write software in C, including interacting with the operating system. We expect at least two (but preferably three) semesters of programming experience, using any language, but including some non-introductory programming experience in C. Equivalent experience in C++ is also acceptable, but it may require an additional effort to adapt. 
* Students are expected to know basic computer architecture, including some assembly language. Ideally, they would understand how a native computer program is executed.
* We expect students to be familiar with multithreading and synchronization. Although the course is not particularly focused or heavy on these subjects, there will be no effort to circumvent them and they will be used when necessary.
* We expect student to have basic knowledge about IP networks and to be able to write software using sockets, if needed.

*Disclaimer: The above information is provided for convenience and does not replace official institutional information.*
