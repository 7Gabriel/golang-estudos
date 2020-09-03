# Go

https://github.com/cod3rcursos/curso-go

https://go-tour-br.appspot.com/basics/6

https://medium.com/@denis_santos/primeiros-passos-com-golang-c3368f6d707a

https://gobyexample.com/

https://gowebexamples.com/

https://meshstudio.io/blog/2017-11-06-serving-html-with-golang/

https://www.codigofluente.com.br/algoritmo-linguagem-de-programacao/go/

https://gohugo.io/functions/eq/
https://github.com/jimmykuu/go-echarts

Go é a linguagem desenvolvida pelo Google para resolver problemas da escala que a gigante da tecnologia tem e, sem dúvida, essa linguagem também vai ajudar a turbinar as suas aplicações.

Ele é uma das poucas linguagens que surgiu depois dos processadores com múltiplos núcleos e isso fez com que a linguagem tenha mecanismo de concorrência no cerne da linguagem, o que a torna ideal para aplicações na qual são exigidos um alto grau de desempenho.

Go é uma linguagem enxuta, moderna, compilada (muito rápida), que tem vários recursos que irão te ajudar nos desafios de desenvolver uma aplicação escalável!

Go é uma linguagem concorrente

Paralelismo - Executar código simultaneamente em processadores físicos diferente
Concorrência - Intercalar (administrar) vários processos ao mesmo tempo e isso pode ocorrer em um único processador físico

Concorrência viabiliza paralelismo

É possível que a concorrência seja melhor que o paralelismo!
Paralelismo exirge muito mias do SO e do Hardware.

Concorrência - É a forma de estruturar seu programa
É a composição de processos (tipicamente funções) que executam de forma independente

## Comandos
Instalar MYSQL DRIVE: ```go get -u github.com/go-sql-driver/mysql```
Copilar aplicação para rodar no linux ```GOOS=linux GOARCH=amd64 go build```
Passando variavel de ambiente ```version=5 go run *.go```

## Publicar aplicação no servidor de produção
https://kenyaappexperts.com/blog/how-to-deploy-golang-to-production-step-by-step/