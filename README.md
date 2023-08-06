# Go expert

## Instalando

Para instalar Go (utilizando Linux Mint 20 e terminal Zsh), baixe o `.gz` e:
```
$ sudo wget https://go.dev/dl/go1.20.linux-amd64.tar.gz
$ sudo tar -C /usr/local -xzf go1.20.linux-amd64.tar.gz
$ nano ~/.zshrc
```
Adicione a linha abaixo no arquivo `.zshrc`:
```
export PATH=$PATH:/usr/local/go/bin
```
Carregue a nova configuração do terminal e verifique a instalação:
```
$ source ~/.zshrc
$ go version
```
