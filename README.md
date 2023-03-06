
Desafio de Projeto do Curso de Linux da DIO.ME

Infraestrutura como código: Script de criação de estrutura de usuários, diretórios e permissões.

O que é? Infraestrutura como código(IaC) é o gerenciamento e provisionamento da infraestrutura por meio de códigos, em vez de processos manuais.

Com a IaC, são criados arquivos de configuração que incluem as especificações da sua infraestrutura, facilitando a edição e a distribuição de configuações. Ela também assegura o provisionamento do mesmo ambiente todas as vezes.

Fonte: Red Hat - https://www.redhat.com

O que será feito?

Todo provisionamento deve ser feito em um arquivo do tipo Bash Script;
O dono de todos os diretórios criados será o usuário root;
Todos os usuários terão permissão total dentro do diretório publico;
Os usuários de cada grupo terão permissão total dentro do seu respectivo diretório;
Os usuários não poderão ter permissão de leitura, escrita e execução em diretórios de departamentos que eles não pertencem.
