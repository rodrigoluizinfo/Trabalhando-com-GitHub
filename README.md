# Trabalhando com GitHub

### Configurações iniciais

1. Criar um repositório dentro do GitHub

2. Iniciar o repositório local
   * git init

3. Passar os parâmetros necessário (Metadados) antes de dar o commit
   * git config --global user.email "seuemail@dominio.com"
   * git config --global user.name seunome

4. git add *

   * Está definindo tudo que está no diretório será levado para o repositório do github

5. git commit -m "mensagemqueseráregistradanocommit"

   * Lembrando que um commit não pode ser desfeito. Qualquer alteração, deverá ser feito um novo commit.

   

### Configurações Finais

1. Adicionar link do repositório criado no github
   * git remote add origin linkdorespositorionogithub
     * Para remover o link adicionado no origin
       * git remote remove origin
2. Publicar o conteúdo do repositório local no repositório do github
   * git push origin master
3. Quando ocorre uma alteração do arquivo no github e precisa atualizar o repositório local
   * git pull origin master
     * Vai ter o arquivo do github e atualizar no repositório local
       * push = Empurrar (Upload)
       * pull = Puxar (Download)
4. git clone urldorepositorionogit
   * Clona um repositório do git dentro do repositório local, criando um novo repositório com todas as configurações originais
5. git remote -v
   * Mostra os repositórios remotos apontados para o github
