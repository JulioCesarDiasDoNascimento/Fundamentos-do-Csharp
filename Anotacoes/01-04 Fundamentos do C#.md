**# Anotações
### O C# te obriga a trabalhar com orientação a objeto!
* Elá é uma linguagem de alto nível
---

### Interpretado vs Compilado
* Interpretado é python, javascript, typescript o codigo é lido pelo "navegador"
* Compilado é c#, java, ele gerar apenas um arquivo "executável"
---

### C# também é fortemente tipada!
* Igual a Java!
* Então todos os objetos e atributos tem que ter ou ser um tipo!

* O C# faz parte do ecosistema .NET
* Maturidade muito grande, 2001! Ótimo o tempo de mercado.

##### Código gerenciado
* Runtime(CLR) - ele que gerencia os programas
    * Gerencia:
        * memoria
        * segurança
        * outros recursos básicos!
* Então a gente interage menos com recursos de máquina!

### Microsoft
* Suporta varias linguagens
* Cada um tem seu compilador
    * E depois dela tem a IL - Intermediate Language
    * Depois é compilada.

* IL
    * primeiro: compila no da linguagem
        * segundo: il ⇾ depois o clr leva para jit
            * por último: (JIT - just in time) código binário.

### Frameworks
* Um conjunto de bibliotecas

> .NET Framework(LEGADO)
> * Não é mais tão usado
> * Apenas compatível com Windows

> .NET CORE
> * O mais atual
> * Suporta todos os sistemas operacionais
> * O mais usado atualmente
> * coexistem com o antigo -> Framework

> .NET Standard
> * ele é quem une os dois frameworks mencionados anteriormente

> .NET 5 é o futuro haha no tempo do curso, atualemte estamos no 10
> * É o framework principal hoje, que substitute os outros

* Sempre focar em aplicações lts

### Runtime é igual o jre kkkk
* SDK E O JDK
* RUNTIME È O JRE
---

## CLI - comand line interface
* Comandos que rodamos no terminal:
    * dotnet --list-sdks
    * dotnet --list-runtimes
    * dotnet help

# Tipos de projeto
![tiposProjetos.png](/Anotacoes/img/tiposProjetos.png)

* Para especificar -o !!!!