# Comandos do Git:

### Comandos para Windows

Mudança de pasta:

`cd`

Voltar para pasta anterior:

`cd ..`

Listar as pastas e arquivos:

`dir`

`ls`

Criar pastas e arquivos:

`mkdir`

Mudar nomes de arquivos:

`git mv arquivo_origem arquivo_destino`

Deletar pastas:

`del/rmdir`

`rmdir` `nome da pasta/s /q`

Deletar só os arquivos da pasta:

`del` `nome da pasta`

Para mover arquivos de pasta:

`mv` `nome do arquivo./ nome da pasta`

Remover arquivo do seu diretório:

`git rm `

Limpar a tela do seu terminal:

 Pressione CTRL + L

Para criar um projeto:

`git init`

* Para configurar seu e-mail e usuário no seu terminal:

Para verificar qual e-mail e usuário está configurado no terminal:

`git config user.name`

`git config user.email`

É sempre bom manter os mesmos e-mail e usuário que estão no seu GitHub. Mas caso não esteja configurado essa é a forma para configurar.

`<u>git config --global user.name "Seu usuário"</u>`
`<u>git config --global user.email seuemail@exemplo.com`</u>~~



Para clonar seu repositório no seu terminal:

`git clone https://github.com/vihfreiitas/exemplo` 

​                        Onde copiar a URL necessária para a função git clone: 

![](C:\Users\vicfr\OneDrive\Imagens\git clone exemplo.png)



Quando houver alterações no seu diretório de trabalho, para que você consiga salva-lo: 

Primeiro salvar uma copia:

`git add`

Depois confirmar no histórico do seu projeto:

`git commit`

Para que consiga deixar uma mensagem para que te direcione o que foi mudado:

`git commit -m "Mensagem"`

Para verificação do Status do seu projeto:

`git status`

Para saber o que foi alterado no seu projeto:

`git diff`

