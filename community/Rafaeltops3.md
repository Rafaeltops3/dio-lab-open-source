Meu Nome é Rafael esse é um mundo novo onde quero aprender e me tornar um grande profissional na aréa da tecnologia, sou formado em tecnico em Recursos Humanos e Graduado em Administração.
Fiz uma breve pesquisa cujo as referências de cada palavra usada esta logo abaixo para verificção do autor espero poder ajudar coloquei alguns comando mais usados no gitHub para criação de alguma resoluão de algum problema para quem é iniciante no assunto. 
 
 10 Atalhos para usar o GitHub (praticar e aprender)

1 git config --global user.name "[nome]" Configura o nome que você quer ligado as suas transações de
commit

2 git clone <https://link-com-o-nome-do-repositório>  Caso queira baixar um projeto no GitHub basta colocar o camando git clone + link do projeto a frente para clonar

2 git branch <nome-da-branch> Podemos usar o comando git branch para criar, listar e excluir as branches.

3 git push -u <local-remoto> <nome-da-branch> Esse comando criará uma branch em seu local de trabalho

4 git checkout <nome-da-branch> Usamos git checkout, na maioria dos casos, para trocar de uma branch para outra.

5 git status O comando git status nos dá todas as informações necessárias sobre a branch atual.O comando git status nos dá todas as informações necessárias sobre a branch atual.

6 git add <arquivo> Esse o comando git add para incluir as alterações de um ou vários arquivos em nosso próximo commit.

7 git commit -m "mensagem do commit" Git commit é como definir um ponto de verificação no processo de desenvolvimento. Você pode voltar a esse ponto mais tarde, se necessário.

8 git push <repositório-remoto> <nome-da-branch> Git push faz o upload dos seus commits no repositório remoto.

9 git pull <repositório-remoto> O comando git pull é usado para obter as atualizações de um repositório remoto.

10  Git merge, basicamente, integra sua branch com o recurso e todos os seus commits na branch de desenvolvimento (dev) ou na branch principal (master ou main). 
10.1 Primeiro, troque para a branch dev:
git checkout dev
10.2 Antes do merge, atualize sua branch dev local:
git fetch
10.3 Por fim, faça o merge da sua branch do recurso em dev:
git merge <nome-da-branch-com-o-recurso>


Referências 
https://www.freecodecamp.org/portuguese/news/10-comandos-do-git-que-todo-desenvolvedor-deveria-conhecer/
https://docs.github.com/pt/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf
