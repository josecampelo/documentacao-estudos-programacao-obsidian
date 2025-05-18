## Formato do commit

```
<tipo>: <mensagem resumida no imperativo>
```

- Sempre escrever mensagens de commit com o verbo no **imperativo**.
	- Exemplo: "adiciona", "atualiza", "corrige".
- Mensagens de commit devem ser **claras e diretas**, com no máximo **72 caracteres**.
## Tipos de commit mais usados
**docs**
- Criar ou alterar conteúdo de **anotações**, **explicações**, **textos**.
	- ``docs: adiciona anotações sobre REST com ASP.NET``
**feat**
- Nova funcionalidade para o **ambiente de estudo** (estrutura, templates, automações, plugins).
	- ``feat: adiciona template de estudo para algoritmos``
**chore**
- Tarefas que não afetam conteúdo técnico diretamente.
	- ``chore: adiciona .gitignore e README.md inicial``
**refactor**
- Reorganização de pastas, arquivos ou nomes, **sem alterar conteúdo**.
	- ``refactor: reorganiza notas de banco de dados por assunto``
**fix**
- Correção de erro de informação, **links quebrados**.
	- ``fix: corrige conceito sobre polimorfismo em orientação a objetos``
## Exemplos práticos
**docs**
```
docs: adiciona resumo sobre Clean Architecture
docs: atualiza anotações de Entity Framework Core
docs: corrige formatação nas anotações de Git
```
**feat**
```
feat: cria estrutura de pastas para estudos de JavaScript
feat: adiciona modelo de nota para resumos semanais
feat: integra plugin de backlinks no Obsidian
```
**chore**
```
chore: adiciona README inicial com descrição do repositório
chore: configura .gitignore para arquivos do Obsidian
```
**refactor**
```
refactor: renomeia arquivos para usar padrão kebab-case
refactor: move anotações de .NET para nova subpasta 'backend'
```
**fix**
```
fix: corrige explicação incorreta sobre tipos de dados em C#
fix: ajusta link quebrado para documentação do Docker
```