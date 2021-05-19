# AppAcademy Challenge

Bem vindo ao seu primeiro desafio do **AppAcademy**! Esperamos que seja o primeiro de muitos!

## Sobre o desafio 🎯

O programa de capacitação da **PremierSoft**, o **AppAcademy**, contou com diversas inscrições. Do norte ao sul do país, pessoas interessadas em ingressar na área de TI se manifestaram. Entender de onde vêm essas pessoas, qual vaga despertou mais interesse nelas e a faixa etária, são alguns dos números que podemos extrair desse programa.

Os números servem como indicadores para que possamos aperfeiçoar o **AppAcademy** nas suas futuras edições. Investir mais em regiões que tiveram uma taxa de adesão menor, seria uma das possíveis melhorias a se fazer. Porém, extrair esses indicadores pode ser algo repetitivo e que requer iterar sobre uma grande massa de dados.

Portanto, para simplificar a contabilização desses indicadores e possibilitar a realização dessa mesma tarefa nas futuras edições, foi idealizado um programa. Programa esse no qual resolvemos lançar o seu desenvolvimento como desafio do **AppAcademy**.

## Getting started ☕️

Na pasta principal desse repositório há uma planilha chamada [**AppAcademy_Candidates.csv**](./AppAcademy_Candidates.csv). Essa planilha contém algumas informações básicas de alguns candidatos que se inscreveram para o **AppAcademy**. Lá você encontrará dados como **nome**, **vaga**, **idade** e **estado**. Para proteger a identidade dos participantes, os nomes foram gerados aleatoriamente.

## O que precisamos que o programa faça ?

- mostrar a porcentagem de candidatos de **Android**, **iOS** e **QA**
- mostrar a idade média dos candidatos de **QA**
- mostrar o número de estados distintos presentes na lista
- mostrar o nome do estado e a quantidade de candidatos dos 2 estados com menos ocorrências
- ordenar por ordem alfabética a lista de candidatos e salvar como **Sorted_AppAcademy_Candidates.csv**

## Mais uma coisinha...

Incluímos o nome dos instrutores de **Android** e **iOS** do **AppAcademy** na planilha. Queremos que o seu programa seja capaz de mostrar o nome do instrutor da vaga para qual você se inscreveu.

Para ~~complicar~~ te ajudar, disponibilizaremos os seguintes fatos:
- o instrutor de **iOS** tem mais de 20 anos
- o instrutor de **Android** é mais ~~esperto~~ novo do que o instrutor do **iOS**
- a idade do instrutor de **iOS** é um número primo
- o primeiro nome do instrutor de **Android** tem 3 vogais
- a última letra do primeiro nome do instrutor de **Android** é a letra "o"
- a primeira letra do último nome do instrutor de **iOS** é a letra "V"
- a idade dos instrutores é um número ímpar
- os instrutores nasceram na mesma década
- os instrutores tem menos de 31 anos
- a vaga atribuída aos instrutores (na planilha) não é a vaga na qual eles vão instruir
- os instrutores são de SC

## Pick your tool 👇

Aceitaremos apenas programas desenvolvidos nessas linguagens:
- Python
- Java
- JavaScript (ou TypeScript)
- Bash
- Kotlin
- Swift
- Objective-C
- C/C++
- C#

## Como o seu programa deve parecer ?

Não estamos avaliando interfaces gráficas nesse momento. Você pode entregar algo visualmente simples, contando que atenda os [critérios citados](#o-que-precisamos-que-o-programa-faça-).

Exemplo:
![alt text](__assets/py_academy_numbers.png)

Caso queira elaborar uma interface, sem problemas!

🤔💭*mostrar a porcentagem de candidatos por vaga em gráfico de 🍕...*

## 🎉 Consegui! e agora !?

- revise o código
- deixe o mais **clean** possível
- teste o seu programa
- compacta (como **.zip**) a pasta contendo **APENAS** os arquivos fontes do seu programa

Por fim, enviar um e-mail com a solução em anexo para [rh@premiersoft.net](mailto:rh@premiersoft.net). No título botar:
> Desafio AppAcademy - {NOME_COMPLETO} - {VAGA}

Exemplo:
> Desafio AppAcademy - John Doe - Android

*GLHF*

## FAQ

Talvez essa possa ser a sua dúvida.

### Qual é o prazo para entregar a solução ?
> No máximo até 21/05/2021 às 23:59 (horário de brasília).

### Como faço para abrir o arquivo da planilha (.csv) ?
> O formato de arquivo **CSV** é bem simples e pode ser aberto com qualquer editor de texto. Também é possível abrir com o **Microsoft Excel**, **LibreOffice Calc** ou qualquer outro leitor de planilha.

### Os nomes na planilha estão aparecendo com caracteres estranhos, como "OtÃ¡vio"
> O programa que você está usando para abrir a planilha esta abrindo o arquivo com o formato de texto ASCII. O formato certo para exibir as informações é UTF-8. Observe nesse conversor online o que acontece quando se converte texto em UTF-8 para ASCII: [Online ASCII Tools](https://onlineasciitools.com/convert-utf8-to-ascii?input=Ot%C3%A1vio).

### Os dados da planilha são reais ?
> Com exceção do nome dos inscritos, todos os demais dados são reais.

### Preciso atender todos os critérios antes de mandar a solução por e-mail ?
> Idealmente sim. Se você não conseguiu atender todos os critérios, tente mais uma vez. [usar atalho](#getting-started-%EF%B8%8F)

### Como faço pra tirar alguma dúvida sobre o desafio ?
> Você pode mandar um e-mail para [rh@premiersoft.net](mailto:rh@premiersoft.net).