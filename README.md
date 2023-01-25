# task01-grupo02

## Git rebase

O git rebase é um comando Git usado no CLI do Git. Ele é usado para fazer o rebasing, processo de mover ou combinar uma sequência de commits para um commit base, é uma forma de alterar a uma branch da aplicação adicionando outra branch, como se você tivesse criado a ramificação a partir de um commit diferente. Dessa forma, o Git cria novos commits e os aplica à branch escolhida.

![Rebase1](Rebasing-in-git.png)

### Principais usos
O git rebase integra alterações de uma branch em outra e seu principal motivo para ser usado é para manter um histórico de projeto linear.
Com o git rebase também é possível juntar diversos commits em um único.

![Rebase2](Git-img-1.PNG)
### Exemplos

* Um bug foi identificado na ramificação principal. Um recurso que estava funcionando bem agora está com falha, o desenvolvedor examina o histórico da ramificação principal usando git log, vê o que está errado, arruma e usa o git rebase para juntar a branch correta na incorreta.
* Criou uma branch para si a partir da branch principal, logo, a branch que você criou está atualizada. Mas, houve algum imprevisto e ficou sem desenvolver por um tempo e, consequentemente, sem atualizar a sua branch. O time atualizou a branch principal, logo, quando você for tentar subir as suas alterações para a branch principal, terá conflito.

![Exemplo](Git-Img-2.PNG)

## Git Cherry Pick

O git cherry pick é um comando que copia um commit específico de uma branch para outra.

![afterCherryPick](AfterCherryPick.png)

### Principais usos
* Replicar um commit no branch atual, porém mantendo o commit original sem alterações.
* Projetos grandes onde há muitos desenvolvedores trabalhando no mesmo código. 

### Exemplos

* Há um commit que você deseja levar para outra ramificação, fazendo assim uma cópia.
* Procura pelo ID do commit que será copiado na sua respectiva branch.
![GitLog](gitLog.PNG)

* Há também a possíbilidade de pegar todos os commits da branch:
![gitCherryPickAll](gitCherryPickAll.PNG)

* Ou um intervalo de commits:
![gitCherryPickBreak](gitCherryPickBreak.PNG)