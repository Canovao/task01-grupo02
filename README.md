# task01-grupo02

## Git rebase

O git rebase é um comando Git usado no CLI do Git. Ele é usado para fazer o rebasing, processo de mover ou combinar uma sequência de commits para um commit base, é uma forma de alterar a uma branch da aplicação adicionando outra branch, como se você tivesse criado a ramificação a partir de um commit diferente. Dessa forma, o Git cria novos commits e os aplica à branch escolhida.

![Rebase image](Rebasing-in-git.png)

### Principais usos
O git rebase integra alterações de uma branch em outra e seu principal motivo para ser usado é para manter um histórico de projeto linear.
Com o git rebase também é possível juntar diversos commits em um único.

![Rebase example](Git-img-1.PNG)
### Exemplos

* Um bug foi identificado na ramificação principal. Um recurso que estava funcionando bem agora está com falha, o desenvolvedor examina o histórico da ramificação principal usando git log, vê o que está errado, arruma e usa o git rebase para juntar a branch correta na incorreta.
* Criou uma branch para si a partir da branch principal, logo, a branch que você criou está atualizada. Mas, houve algum imprevisto e ficou sem desenvolver por um tempo e, consequentemente, sem atualizar a sua branch. O time atualizou a branch principal, logo, quando você for tentar subir as suas alterações para a branch principal, terá conflito.