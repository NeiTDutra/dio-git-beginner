## Alterando arquivos e fazendo "commit" das mudanças

Na pasta onde o comando clone foi executado é preciso agora ascender no diretório baixado.

Dentro deste diretório além dos arquivos do proojeto clonado, existe uma pasta oculta que guarda todas alterações, chamada ".git".

![pasta clonada](https://github.com/NeiTDutra/dio-git-beginner/blob/main/images/arquivoGit.png)

Após alterar o(s) arquivo(s) no editor preferido:

### Enviar ao repositório remoto as mudanças

São três comandos básicos;

- [*git add .* ou *git add ***nome do arquivo****](https://github.com/git-guides/git-add)

```bash
$ git add .
$ git add <nome_do_arquivo>
```

- [*git commit -m 'mensagem...'*](https://git-scm.com/docs/git-commit)

```bash
$ git commit -m 'mensagem breve sobre as alterações'
```

- [*git push -u origin main*](https://git-scm.com/docs/git-push)

```bash
$ git push -u <nome_do_repositório> <nome_da_branch>
```

Feito isso o repositório remoto é atualizado com as mudanças locais.
