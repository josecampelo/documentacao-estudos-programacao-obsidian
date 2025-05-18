## C# é a Linguagem, .NET é a Plataforma:
- **C#** é a linguagem de programação que você usa para **escrever suas instruções para a maquina** (a sintaxe, a "gramática" do código).
- **.NET** é o **ecossistema completo** e a **plataforma** onde o seu **código C# é executado**.
## Compilação e Execução:
- Você escreve seu **código (código fonte)** em **C#**.
- O **Compilador Roslyn** (faz parte do **.NET SDK**) converte seu código **C#** em um código **Intermediate Language (IL)**, que é um código intermediário e **independente do sistema operacional**.
- O **.NET Runtime (CLR - Common Language Runtime)** pega esse novo código **IL** e o converte novamente **"Just-In-Time" (JIT)**  para um código de **Máquina Nativo (Binário)** que a máquina entende, e então **executa seu código**.
	- **CLR** também **gerencia memória (Garbage Collection)**, **segurança** e **tratamento de exceções**.
## Base Class Library (BCL):
- A **BCL** é um **conjunto vasto de bibliotecas e tipos prontos** (como `List`, `Array`, `string`, `Console`, `DateTime`, etc.) que vêm com o **.NET**.
- Esses códigos prontos **não são definidos pela especificação pura do C#**, mas sim fazem parte da **plataforma .NET**.
	- O **C# te dá a sintaxe para usar** esses tipos da BCL.
## .NET: Plataforma vs. Framework:
- É chamado de **Plataforma** porque é o **ecossistema completo** que fornece o **Runtime**, **SDK**, **Compiladores**, a **BCL** e a **base para construir** diversos tipos de aplicações **usando frameworks específicos**.
- É chamado de **Framework** porque oferece **conjuntos estruturados de bibliotecas e convenções para facilitar o desenvolvimento**. A **BCL** é um framework fundamental dentro da **plataforma .NET**, e **existem frameworks mais específicos em cima dela** (como **ASP.NET Core** para web).
## Uso Essencial do .NET:
- Mesmo em um programa **C#** simples (como um "Olá Mundo!" no console), você **já está usando a plataforma .NET** porque está utilizando a **BCL** para acessar o `Console`, o **compilador Roslyn** e o **.NET Runtime (CLR)** para executar seu código.
## Linguagens de Implementação do .NET:
- O núcleo de baixo nível do **Runtime (CLR)** é majoritariamente escrito em **C++** para **performance**.
- A maior parte da **Base Class Library (BCL)** e muitos dos **frameworks de nível superior** são escritos na própria linguagem **C#**.
## Visual Studio Code:
- O **VS Code** é o seu **editor/ambiente de desenvolvimento** que, com a ajuda do **.NET SDK** e **extensões** relevantes, te permite **escrever**, **compilar**, **executar** e **depurar seu código C#** dentro do ecossistema **.NET**.
## Resumo
- Você **escreve seu código usando C#** e **utilizando as bibliotecas da BCL** que pertence ao **.NET**.
- Esse **código C# é convertido para código IL** pelo compilador **Roslyn**.
- A **CLR executa seu código** pegando esse **código IL** e convertendo para **código de máquina** usando o **JIT** em **tempo de execução**.
- Tudo isso forma a **Plataforma .NET**, que **também contém Frameworks** para **tipos de aplicações mais específicos**.