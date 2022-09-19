# Trabalhando com GitHub

### Configurações iniciais

1. Criar um repositório dentro do GitHub
2. Iniciar o repositório local
   * git init

3. Passar os parâmetros necessário (Metadados) antes de dar o commit

   * git config --global user.email "seuemail@dominio.com"
   * git config --global user.name seunome

4. git add*

   * Está definindo tudo que está no diretório será levado para o repositório do github

5. git commit -m "mensagemqueseráregistradanocommit"

   * Lembrando que um commit não pode ser desfeito
   * Configurações iniciais

### Configurações Finais

1. Adicionar link do repositório criado no github

2. - git remote add origin      linkdorespositorionogithub

3. - Para remover o link      adicionado no origin
   - git remote remove origin

4. Publicar o conteúdo do     repositório local no repositório do github

5. - git push origin master
