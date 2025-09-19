# Ciclo 14 - Aulas de Git e GitHub

Durante as duas primeiras semanas de setembro, tivemos aulas com a Jaqueline de Almeida, que nos ensinou usos avançados de GitHub.

1. Ciclo de vida dos arquivos: </br>
    Untracked -  quando ainda não foi inicializado no git </br>
    Unstaged - já foi inicializado, mas ainda não adicionado e commitado</br>
    Commited - já adicionado e commitado, pronto para subir no repositório remoto.


2. Segurança no uso do Git e GitHub
    Criação de chaves SSH

3. Uso de branches
    Na segunda semana, aprendemos a criar, manipular e até deletar branches.

    Também aprendemos as diferenças entre: </br>
    Clone vs. Fork </br>
    Rebase vs. Merge

4. Boas práticas
    .gitignore
    git stash
    Importância do READme - fundamental para uma boa comunicação e para trabalhar em equipe.
    Tags de versões - mais usado em caso de desenvolvimento de software, durante o processo de atualizações.
    Alias - o próprio dev pode criar atalhos dentro de um repositório ou globalmente no seu perfil para acelerar o ritmo de trabalho, abreviando comandos maiores em poucas letras.



## Alguns comandos:
<ul>
<li>git init -> inicializa localmente um repositório git em determinado diretório</li>
<li>git status -> mostra o status dos arquivos do repositório</li>
<li>git add nome-do-arquivo -> muda o status do arquivo em questão de unstaged para staged</li>
<li>git add . -> torna TODOS os arquivos staged</li>
<li>git commit -m "nome-do-commit" -> é o que permite salvar as alterações feitas, mudando o status do arquivo para commited, o que o prepara para subir ao repositório remoto.</li>
<li>git remote add origin link -> vincula o repositório local a um repositório remoto.</li>
<li>git remote -v -> checa se o repositório local está vinculado a um repositório remoto.</li>
<li>git push -u origin main -> serve para fazer o push inicial na branch main, também podendo ser usado posteriormente para novos pushes na main.</li>
<li>git push -> forma mais simples e direta de realizar o push, mas só funciona sem erros se todo o ambiente de trabalho estiver corretamente configurado.</li>
<li>git log -> mostra o histórico de commits da branch atual com id e data</li>
<li>git log --oneline -> mostra o log de maneira resumida para consultas rápidas.</li>
<li>git restore --staged nome-do-arquivo -> pode ser utilizado ao perceber que um arquivo que já está em estado staged ainda precisa de algumas alterações. Com esse comando, ele volta a ser unstaged.</li>
<li>git checkout -b nome-da-branch -> cria e já entra em uma nova branch.</li>
<li>git checkout nome-da-branch -> entra numa branch já existente, indicada pelo nome.</li>
<li>git push origin -u nome-da-branch -> toda vez que uma branch nova é criada, seu primeiro push deve ser realizado obrigatoriamente com esse comando. Os pushes subsequentes podem ser feitos normalmente.</li>
</ul>
