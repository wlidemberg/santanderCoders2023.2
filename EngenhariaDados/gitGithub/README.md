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
