Base:
Git Add . = Adiciona tudo que modificou
Git add (nome do arquivo) = Adiciona um arquivo específico. <font color="red">Recomendado priorizar usar esse !</font>

git commit -m "Nome do commit" = Após adicionar os arquivos modificados, o commit serve para enviar sua modificação para o repositório original, o "-m" serve para você descrever o que foi modificado no commit. É de suma importância que você escreva bem resumido mas detalhado o que foi modificado.
Exemplo de commit bom: "Feat: Adiciona botão de reset"
Exemplo de commit ruim: "Adiciona botão"

git pull - puxa as modificações feitas no repositório remoto, é bom usar sempre que for começar a trabalhar no projeto, pois atualiza seu repositorio local, com o repositorio remoto.
git push - empurra as modificações do seu repositório local, para o repositório remoto.