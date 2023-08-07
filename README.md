<div align="center">
<h1 align="center">
<img src="https://go.dev/images/gophers/motorcycle.svg" width="250" />
<br>
Go expert
</h1>
<h3>
<a href="https://goexpert.fullcycle.com.br/pos-goexpert/">Pós-Graduação Go Expert</a>
by
<a href="https://goexpert.fullcycle.com.br/">Full Cycle</a>
</h3>
<p align="center">
<a href="https://go.dev/">
<img src="https://img.shields.io/badge/Go-00ADD8.svg?style&logo=Go&logoColor=white" alt="Go"/>
</a>
<img src="https://img.shields.io/badge/Markdown-000000.svg?style&logo=Markdown&logoColor=white" alt="Markdown"/>
</p>
</div>

## 📒 Índice
- [📒 Índice](#-índice)
- [📍 Introdução](#-introdução)
- [⚙️ Módulos](#-módulos)
- [🚀 Começando](#-começando)
- [📄 Links](#-links)

---


## 📍 Introdução

Repositório destinado ao curso de Pós-Graduação Go Expert da Full Cycle, com anotações pessoais, exemplos, atividades e projetos desenvolvidos ao decorrer do curso. O curso tem foco em 6 Pilares: Fundamentos da linguagem, Testes Automatizados, Desenvolvimento de APIs, Performance e Multithreading, Go & Clean Architecture, Soft Skills. Elaborado por Wesley Willians, Fundador/CEO da Full Cycle, premiado como um dos 100 líderes em educação pelo "Fórum Global de Educação e Aprendizado".

---

## ⚙️ Módulos

<details closed><summary>Conteúdo</summary>

| Módulo | Tópicos |
| - | - |
| **ℹ️ Introdução a linguagem** | Sobre a linguagem e seu histórico, Motivações, Instalação, Configuração do ambiente no VSCode. |
| **🏛️ Fundação** | Primeiros passos, Trabalhando com tipagem forte, Arrays, Slices, Maps, Laços de repetição, condicionais, Ponteiros, Funções, Structs, Métodos, Interfaces e Generics, Trabalhando com packages, Módulos, Módulos privados, Instalação de pacotes, Compilando projetos Go, Workspaces. |
| **📦 Pacotes importantes** | Manipulação de arquivos, Chamadas HTTP, Trabalhando com objetos Json, Defer, Desenvolvendo um sistema Busca CEP, Trabalhando com HTTP, Criando servidores HTTP, Entendendo Multiplexers, Servidor de arquivos, Trabalhando com templates dinâmicos, Aprofundando em HTTP utilizando Context. |
| **🧩 Pacote Context** | Entendendo o conceito de um context, Armazenando e recuperando valores, Background, Timeout, Deadline e Cancelations, Context na prática. |
| **🧪 Testes automatizados** | Iniciando com testes no Go, Formas de asserção, Pacotes úteis, Trabalhando com Mocks, Fuzzes e testes de mutação, Testes em batch, Benchmarking, Criando suite de testes com Testify, Testes End-to-end. |
| **🎲 Bancos de dados** | Entendendo como Go trabalha com banco de dados, Estabelecendo conexão e realizando primeiras operações, Boas práticas de segurança, Realizando operações utilizando Context, Go puro vs ORM, Trabalhando com GORM, Migrations, SQLC: Geração automática de Queries. |
| **🧵 Concorrência e Multithreading** | Entendendo conceitos de concorrência e paralelismo, Como Go aborda concorrência e schedulers, Iniciando com Go Routines, Contadores atômicos, Trabalhando com Channels e buffers, Utilizando recurso de Select, Wait Groups, Mutex, Previnindo race conditions, Desenvolvimento de workers utilizando channels, Load Balancer. |
| **⚡️ Implementações** | gRPC, GraphQL, Upload de arquivos na AWS S3, Command line com cobra CLI, Unit of Work, Dependency Injection com Google Wire, Manipulação de eventos (Event Dispatcher, Handlers, etc), Integração com RabbitMQ, Gerenciamento de configuração com Viper. |
| **📐 Go e Clean Architecture** | Iniciando com Clean Architecture, Pontos importantes sobre arquitetura, Keep options opened, Use Cases, Limites arquiteturais, Input vs Output, DTOs, Entities, Desenvolvendo camada de domínio, Criando Use Cases, Criando adaptador para banco de dados, Criando adaptador para o RabbitMQ, Servindo endpoints HTTP, Consumindo mensagens com RabbitMQ, Criando CLI para iniciar a aplicação, Documentando aplicação, Go Doc. |
| **🔌 Desenvolvimento de APIs** | Retomando conceitos de HTTP Server e Mux, Criando Endpoints, Apresentando principais frameworks e roteadores, Trabalhando com “chi”, Middlewares, Autenticação e tokens JWT, Documentando API com Swagger. |
| **🚀 Deploy** | Entendendo processo de compilação, Gerando imagem Docker com multistage building, Criando manifestos Kubernetes, Realizando deploy no Kubernetes. |
| **👤 Marketing pessoal** | Imagem pessoal, Autoridade, Redes sociais, Networking, Seus projetos e sua marca pessoal. |
| **🧽 Trabalho em equipe** | Dificuldades enfrentadas pelo trabalho em equipe, Como melhorar a formação de equipes, Comunicação assertiva, Perfil Comportamental. |
| **💡 Empreendedorismo** | Empreendedorismo social, Empreendedorismo corporativo (intraempreendedorismo), Empreendedorismo digital, Empreendedorismo Serial. |

</details>

---

## 🚀 Começando

### 💻 Instalação

- Baixe e instale [Go](https://go.dev/) (no [Linux](https://linuxmint.com/) com [Zsh](https://ohmyz.sh/)):
    ```bash
    $ sudo wget https://go.dev/dl/go1.20.linux-amd64.tar.gz
    $ sudo tar -C /usr/local -xzf go1.20.linux-amd64.tar.gz
    ```
    Adicione a linha abaixo no `.zshrc` com `nano ~/.zshrc`:
    ```
    export PATH=$PATH:/usr/local/go/bin
    ```
    Verifique a instalação com `go version` e a configuração do `GOPATH` com `go env`.

- Baixe e instale a [extensão Go](https://marketplace.visualstudio.com/items?itemName=golang.Go) no [VS Code](https://code.visualstudio.com/). Em seguida tecle `ctrl + shift + P`, busque por `Go: Install/Update Tools`, selecione todas as opções e clique em "Ok".

---

## 📄 Links

Links interessantes encontrados ao decorrer dos estudos.

### ☑️ Oficiais

1. **[Documentação](https://golang.org/doc/)**: documentação oficial da linguagem Go.
1. **[Tour](https://tour.golang.org/welcome/1)**: introdução interativa e prática à sintaxe e recursos da linguagem Go.
1. **[Tutoriais](https://go.dev/doc/tutorial/)**: compilado de tutoriais para quem está começando com a linguagem Go.
1. **[Playground](https://play.golang.org/)**: ferramenta online para experimentar e testar os conceitos do código Go.
1. **[Effective Go](https://go.dev/doc/effective_go)**: guia detalhado que abrange práticas recomendadas para escrever código Go de maneira eficaz.
1. **[Blog](https://go.dev/blog/)**: blog oficial da equipe Go com artigos, atualizações e insights sobre a linguagem.
1. **[Pacotes](https://pkg.go.dev/)**: sistema de busca de pacotes da linguagem Go.
1. **[YouTube](https://www.youtube.com/c/golang)**: canal oficial do Go no YouTube com palestras, tutoriais e discussões sobre a linguagem.

### 🏴‍☠️ Não-oficiais

1. **[Go by Example](https://gobyexample.com/)**: coleção de exemplos de código Go que abrange diversos tópicos.
1. **[Golang News](https://golangnews.com/)**: notícias e artigos relacionados a Go.
1. **[Golang Weekly](https://golangweekly.com/)**: newsletter semanal que traz as últimas notícias, artigos e projetos relacionados a Go.
1. **[Gophercises](https://gophercises.com/)**: exercícios práticos para ajudar a praticar as habilidades em Go.
1. **[Go Fórum](https://forum.golangbridge.org/)**: fórum de discussão dedicado a conversas sobre a linguagem.

### 📚 Livros, artigos, apresentações

1. **[Aprendendo Go com Testes](https://larien.gitbook.io/aprenda-go-com-testes/)**: livro que ensina Go por meio de testes de unidade.
1. **[Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/en/)**: livro online gratuito que aborda o desenvolvimento de aplicativos web com Go.
1. **[Go Concurrency Patterns](https://go.dev/talks/2012/concurrency.slide#1)**: apresentação que explora padrões de concorrência em Go.

### 📃 Listas, aplicações, exemplos

1. **[Awesome Go](https://awesome-go.com/)**: lista curada de frameworks, bibliotecas e recursos para desenvolvimento em Go.
1. **[Go Patterns](https://github.com/tmrts/go-patterns)**: repositório de exemplos de padrões de design em Go.

---
