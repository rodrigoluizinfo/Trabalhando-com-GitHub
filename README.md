Trabalhando com GitHub
Configurações iniciais
Criar um repositório dentro do GitHub

Iniciar o repositório local

git init
Passar os parâmetros necessário (Metadados) antes de dar o commit

git config --global user.email "seuemail@dominio.com"
git config --global user.name seunome
git add*

Está definindo tudo que está no diretório será levado para o repositório do github
git commit -m "mensagemqueseráregistradanocommit"

Lembrando que um commit não pode ser desfeito
Configurações iniciais
Configurações Finais
Adicionar link do repositório criado no github

git remote add origin linkdorespositorionogithub
Para remover o link adicionado no origin
git remote remove origin
Publicar o conteúdo do repositório local no repositório do github

git push origin master