# APE 11 - Versionamento e Git

Acadêmico: Cristiano Fernandes  
RA: 09024599

**1. O que é o Git?**  
O Git é um sistema para controle de versões de código com um projeto de código aberto desenvolvido em 2005 por Linus Torvalds, o criador do kernel do sistema operacional Linux. Hoje o Git é uma das ferramentas mais utilizadas no mundo e ganhou esse espaço por seu desempenho, segurança e flexibilidade, além de possuir várias integrações com IDEs e outros softwares de gestão.  
Diferente de outros sistemas para controle de versão, o Git tem uma arquitetura distribuída, chamada DVCS (Sistema de Controle de Versão Distribuído) com isso o clone do projeto que o desenvolvedor do código está trabalhando, também é um repositório contendo o histórico de todas as alterações.

**2. O que é versionamento de software?**  
Podemos dizer que é um sistema de controle de versão de códigos de um software. Um software é construído aos poucos e em etapas, que são incrementadas com o decorrer do desenvolvimento.  
Como exemplo, digamos que em cada finalização de uma etapa, é gerado uma versão, isso facilita para o desenvolvedor ou uma equipe de devs verificar o histórico das alterações, podendo até voltar uma versão estável, em casos que uma nova versão esteja com problemas, assim são feitas as devidas correções, na versão com problema, e gerado uma nova versão atualizada.  
Hoje em dia é quase que uma obrigação utilizar uma ferramenta de versionamento, principalmente se falando em trabalho em equipe. Uma das mais utilizadas é o Git.

**3. Por que utilizar o Git como controle de versionamento?**  
O Git é fundamental em quase todos os projetos realizados em equipes, têm confiabilidade no gerenciamento das versões dos códigos e possibilita o trabalho distribuído, o que para o trabalho em equipe é essencial, pois ele evita que haja conflitos entre as alterações realizadas pelos membros do time.  
Os projetos de um software estão em constante evolução e utilizando o Git, toda essa evolução é mapeada e rastreada, assim em caso de problemas em alguma nova versão, é possível reverter para uma estável.  
Tudo isso pode ser disponibilizado em repositórios remotos, como Github, Gitlab, entre outros. Facilitando mais uma vez o trabalho em equipe, pois essa pode estar distribuída em qualquer parte do mundo compartilhando do mesmo código.

**4. Quais as vantagens do Git?**  
Segurança, confiabilidade, desempenho, desenvolvimento distribuído, ramificações (branches), gerenciamento de conflitos, etc. Essas são algumas das vantagens do Git, algumas já falamos anteriormente, agora podemos falar sobre ramificações e gerenciamento de conflitos.  
Ramificações (branches), como o próprio nome diz, são “ramos”, “galhos” de um código. Ao criar uma branch com base no código principal (branch master / main) essa nova branch tem uma cópia do código rodando em produção por exemplo e o desenvolvedor poderá trabalhar em uma correção, ou nova funcionalidade em paralelo, sem que a branch master sofra qualquer alteração, ao fim do trabalho é solicitado um (merge) ou seja, uma unificação do código desenvolvido na branch com o código da master.  
Feito isso entramos no gerenciamento de conflitos, onde ao solicitar o merge, o Git verifica se há algum conflito entre a nova branch e a branch master, caso houver, o desenvolvedor terá que resolver todos os conflitos de códigos antes de fazer o merge, isso além de facilitar, traz confiabilidade no código.

**5. Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?**

**6. Cite pelo menos três ferramentas de controle de versão e faça um breve detalhamento sobre cada uma delas.**
