## Qual a diferença entre Bibliotecas e Frameworks?
A diferença principal entre as duas está no **controle de fluxo** e na **estrutura** que eles impõem.
#### Bibliotecas são como suas ferramentas:
- Uma caixa de ferramentas com martelo, serra, furadeira, chaves de fenda, etc.
- Você que decide quando pegar o martelo ou quando usar uma serra (chamar uma função da biblioteca), etc. 
- Você tem o **controle total sobre o processo de construção** e **decide a ordem e a maneira como usar** cada ferramenta.
	- Exemplo no código: Uma biblioteca que só tem uma função para calcular a raiz quadrada. 
		- ``double raiz = MinhaBiblioteca.CalcularRaiz(16);``
	- Você **chama essa função no ponto exato que seu código precisa dela**.
		- **Seu código é o chefe**.
#### Frameworks são como a fundação e a estrutura inicial:
- Os frameworks **fornecem a estrutura básica** (paredes, telhados, encanamento principal) e **definem como o restante da casa deve ser construído**.
- Os frameworks dita a **arquitetura geral**, **como as peças se encaixam** e o **fluxo de eventos**. 
- Muitas vezes o framework é quem "chama de volta" o seu código em pontos especificos.
	- Exemplo no código: Um **framework web** como o **ASP.NET Core**, ele tem um **ciclo de vida de requisição e resposta** bem definido.
	- Quando uma **requisição HTTP** chega do cliente, o **ASP.NET intercepta essa requisição HTTP**, **processa através de uma série de middlewares** e em determinado ponto, **ele chama o seu código** (por exemplo o método de uma Controller) **para gerar a resposta HTTP**.
	- O Framework está no **controle principal do fluxo de execução**, e o seu código **preenche as "lacunas"** ou **responde quando o framework chama**.
## Resumo
- Bibliotecas são **funcionalidades que usamos em nosso código para realizar uma tarefa especifica**.
- Frameworks são um **template que guia como a gente constrói a nossa aplicação** inteira ou grande parte dela.
#### Bibliotecas
- São uma **coleção de funcionalidades prontas** que o nosso código chama quando precisar, **não precisarmos ficar escrevendo tudo do zero**. 
- O **nosso código que controla o fluxo de execução da aplicação**, decidindo **quando e onde usar essas funcionalidades** da biblioteca.
- A principal vantagem é a **reutilização de código para tarefas especificas**.
#### Frameworks
- **Fornece uma estrutura** e um **esqueleto para a sua aplicação**.
- Eles definem a **arquitetura do projeto**, as **convenções** e o **fluxo principal de execução da aplicação**.
- **O framework está no controle da execução** e chama seu código em momentos apropriados quando precisar (**Inversão de Controle (IoC)**).
- Frameworks também utilizam muitas bibliotecas internamente, incluindo a BCL para realizar suas tarefas.
