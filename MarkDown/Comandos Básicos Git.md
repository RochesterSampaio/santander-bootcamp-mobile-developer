# Comandos Git.

Neste artigo mostro alguns comandos básicos em Git.

- Gerar key de identificação 40 char:

  ```
  #openssl sha1 "nome do arquivo"
  ```

- Comando para geração de ssh-key:

  ```
  #ssh-keygen -t ed25519 -C "email"
  ```

- Inicializar ssh agent:

  ```
  #eval $(ssh-agent -s)
  ```

- Entregar chaves ssh ao agente:

  ```
  #ssh-add id-25519
  ```

- Inicializar versionamento:

  ```
  #git init
  ```

- Configurar e-mail / user:

  ```
  #git config --global user.email "email"
  #git config --global user.name "user"
  ```

- Adicionar arquivos stage(todos no diretório atual):

  ```
  #git add .
  ```

- Commit com comentário:

  ```
  #commit -m "comentário"
  ```

- Informa status de arquivos:

  ```
  #git status
  ```

- Adicionar origem(onde os arquivos serão armazenados), no GitHub:

  ```
  #git remote add origin "link"
  ```

- Listar repositórios cadastrados:

  ```
  #git remote -v
  ```

- Empurrar código para repositório:

  ```
  #git push origin "master"
  ```

 ![ ](https://res.cloudinary.com/practicaldev/image/fetch/s--4RSUi4LD--/c_imagga_scale,f_auto,fl_progressive,h_420,q_66,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/3kfoy92ty0sds2a0nz4h.gif)