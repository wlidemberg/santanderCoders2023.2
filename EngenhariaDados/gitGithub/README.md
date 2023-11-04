# Inciando o curso de Git

> ## Principais comandos
> - *git init*       -> usado para iniciar um repositorio git(uma pasta oculta será criada com o nome git)
> - *git status*     -> verifica o status de altereção do repositorio local e mostra a branch que estamos
> - *git diff*       -> Mostra exatamente as linhas que foram modificadas o que aparece em vermelho e que foi retirado e verde o que alterado ou acrescentado
> - *gif diff --staged* -> Mostra as linha que foram modificadas nos arquivos que ja foram para o staged, ou seja, apos o comando *git add .*
> - *git add .*      -> adiciona todas as modificações feitas em nosso repositório local coloca em staged
> - *git commit - m* -> Efetua um commit nas alterações alterando seu estado pra unmodified acompanhado de uma mensagem descrevendo esse commit
> - *git log* -> Exibe um histrórico de commits, mostrando a branch, o autor, a data, a mensagem do commit e a hash(checksun) desse commit
> - *git restore* -> Remove as alterações feitas no arquivo
> - *git restore --staged* -> Remove o arquivo da area de staged change(unmodified) e retorna pro changes(modified)
> - *git push* -> Sobe nossos arquivos e alterações para nosso repositório remoto.
> - *git pull* -> faz um merge(junta) automatico do que tinha no seu repositótio remoto com o que vc tem no local
