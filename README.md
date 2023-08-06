# Go expert

## Instalando

### Go

Instale [Go](https://go.dev/) no [Linux Mint 20](https://linuxmint.com/) (com [Zsh](https://ohmyz.sh/)):
```bash
$ sudo wget https://go.dev/dl/go1.20.linux-amd64.tar.gz
$ sudo tar -C /usr/local -xzf go1.20.linux-amd64.tar.gz
$ nano ~/.zshrc
```
Adicione a linha abaixo no `.zshrc`:
```
export PATH=$PATH:/usr/local/go/bin
```
Carregue a nova configuração do Zsh:
```bash
$ source ~/.zshrc
$ go version
```
Verifique a `GOPATH` com `go env`.

### Go no VS Code

Instale [Go](https://go.dev/) no [VS Code](https://code.visualstudio.com/): https://marketplace.visualstudio.com/items?itemName=golang.Go

No VS Code: `ctrl+shift+P`, busque por `Go: Install/Update Tools` e selecione todas as opções.
