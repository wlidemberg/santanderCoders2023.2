# Inciando o curso de Git

## Principais comandos
> - *git init*       -> usado para iniciar um repositorio git(uma pasta oculta será criada com o nome git).<br>
> - *git status*     -> verifica o status de altereção do repositorio local e mostra a branch que estamos.<br>
> - *git diff*       -> Mostra exatamente as linhas que foram modificadas o que aparece em vermelho e que foi retirado e verde o que alterado ou acrescentado.<br>
> - *gif diff --staged* -> Mostra as linha que foram modificadas nos arquivos que ja foram para o staged, ou seja, apos o comando *git add .*.<br>
> - *git add .*      -> adiciona todas as modificações feitas em nosso repositório local coloca em staged.<br>
> - *git commit - m* -> Efetua um commit nas alterações alterando seu estado pra unmodified acompanhado de uma mensagem descrevendo esse commit.<br>
> - *git log* -> Exibe um histrórico de commits, mostrando a branch, o autor, a data, a mensagem do commit e a hash(checksun) desse commit.<br>
> - *git restore* -> Remove as alterações feitas no arquivo.<br>
> - *git restore --staged* -> Remove o arquivo da area de staged change(unmodified) e retorna pro changes(modified).<br>
> - *git push* -> Sobe nossos arquivos e alterações para nosso repositório remoto.<br>
> - *git pull* -> faz um merge(junta) automatico do que tinha no seu repositótio remoto com o que vc tem no local.<br>
> - *git fetch* -> faz um merge(junta) do que tinha no seu repositório remoto mas não executa automaticamente, e usamos o comando *git diff* para verificar as alterações que esta vindo do repositório remoto e logo apos de verificar as alterações entramos com o comando *git pull* para mergear nossos  repositorios.

## Branch
>é uma linha independente de desenvolvimento que representa uma série de commits (ou confirmações) em um repositório Git. 
>Cada branch é uma ramificação da árvore de commits principal, que é geralmente chamada de "branch master" ou "branch main".
>Branches permitem que você trabalhe em diferentes recursos, correções de bugs ou versões do seu projeto sem interferir no trabalho em outras partes do código.
>Aqui estão alguns conceitos-chave relacionados a branches no Github:

### Conceitos chaves de branch no GIT

1. **Branch Principal (Master/Main):** O branch principal é a linha de desenvolvimento padrão em um repositório Git. É a base a partir da qual outras branches podem ser criadas.

2. **Criar um Branch:** Você pode criar um novo branch a partir do branch principal ou de outro branch existente. Isso cria uma cópia independente do código que você pode modificar sem afetar o branch original.

3. **Comitar em um Branch:** Quando você faz commits em um branch, os commits são registrados nesse branch específico. Isso permite que você desenvolva recursos ou correções de bugs separadamente.

4. **Mudança de Branch:** Você pode alternar entre branches ativos no seu repositório Git. Isso permite que você trabalhe em diferentes partes do projeto.


5. **Fusão (Merge) de Branches:** Quando você termina o trabalho em um branch e deseja incorporar as mudanças de volta ao branch principal ou a outro branch, você pode fazer uma fusão (merge). Isso combina os commits de um branch em outro.

6. **Branches Remotos:** Além de branches locais, o Git também permite que você trabalhe com branches remotos em repositórios compartilhados. Isso é útil para colaboração em equipe.

7. **Rastreamento (Tracking) de Branches:** Você pode configurar branches locais para rastrear branches remotos. Isso permite que você mantenha seu branch local sincronizado com as atualizações do branch remoto.

8. **Exclusão de Branches:** Você pode excluir branches após concluí-los ou quando não são mais necessários.

Em resumo, branches no Git são uma ferramenta fundamental que permite o desenvolvimento paralelo e organizado de código, facilitando a colaboração e o gerenciamento de diferentes recursos e versões de um projeto.

### Comandos

> 1. **Criar uma branch:** para criar um novo branch no Git, você pode usar o comando **'git branch'** seguido pelo nome do novo branch.por exemplo:

> ![comando criar branch](/imgs/criarBranch.jpeg)

> 2. **Comitar em um branch:** Use o comando **'git commit'** para confirmar as mudanças em um branch especifico. Certifique-se de estar no branch desejado antes de fazer um commit.

> ![Commit na branch](/imgs/comitarBranch.jpg)

> 3. **Mudança de branch:** Para alternar entre branch's, você pode usar o comando **'git checkout'** seguido do nome o branch que deseja mudar.

> ![Mudança de branch](/imgs/alternarBranch.jpg)

> 4. **Fusão(merge) de branches:** Use o comando **'git merge'** para fundir um branch em outro.Certifique-se no branch de destino antes de executar o comando.

> ![Merge de branch's](/imgs/mergeBrach.jpg)

> 5. **Branches Remotos:** Ao trabalhar com repositórios remotos, você pode usar o comando **'git push'** para enviar um repositório local para um repositório remoto e **'git pull'** para obter atualizações dos branches remotos.Para rastrear um branch remoto, use **'git fetch'** seguido do **'git checkout'** ou **'git merge'**.

> ![branches remotos](/imgs/branchRemoto.jpg)

> 6. **Rastreamento(tracking) de branches:** Para configurar um branch local para rastrear um branch remoto, você pode usar o comando **'git branch'** com a opção **'--set-upstream-to'** ou **'--track'**, ou simplismente usar **'git push'** com a opção **'-u  '** para definir o upstream.

> ![Rastreamento(tracking) de branches](/imgs/trackingBranch.jpg)

> 7. **Exclusão de branches:** Para excluir um branch no Git, use o comando **'git branch'**, com a opção **'-d'** para excluir localmente.Use a opção **'-D'** para forçar a exclusão, mesmo se houver commits não mesclados.

> ![Exclusão de branches](/imgs/exclusaoBranch.jpg)

Lembre-se de que é importante ter cuidado ao usar comandos que excluam branches, pois os commits e as mudanças não mescladas podem ser perdidos. Certifique-se de que você está fazendo isso com segurança.

