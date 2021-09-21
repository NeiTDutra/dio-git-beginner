# Clonando repositório

*É posível clonar ou baixar os arquivos de um repositório*

Para [clonar um repositório](https://docs.github.com/pt/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository):

- Na página do projeto selecione "code"(1);
- Escolha o tipo de conexão com o serviço do Github(2);
- Copie o endereço / link / path(3);

![clone github](https://github.com/NeiTDutra/dio-git-beginner/blob/main/images/clonandoRepositorio.png)

- No terminal do sistema e na pasta do projeto, com o [Github cli](https://cli.github.com/) instalado digite (neste caso SSH);

```bash
git clone git@github.com:NeiTDutra/dio-git-beginner.git
```

Os arquivos do projeto do github estarão no diretório local do projeto (no mesmo diretório onde o comando foi executado).

## Próximo passo

[Alterar arquivos e commitar mudanças](https://github.com/NeiTDutra/dio-git-beginner/blob/main/alterandoECommitando.md)
