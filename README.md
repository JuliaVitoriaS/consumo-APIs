# consumo-APIs
Repositório para demonstrações e aprendizado sobre o consumo de APIs


As APIs possuem alguns elementos que servem à sua utilização:

-**Ponto de entrada**: é o endereço do serviço hospedado e que pode ser acessado através de um navegador ou uma ferramenta de consumo de APIs. Exemplo: <http://dadosabertos.camara.leg.br/api/v2>.
-**Recursos**;são serviçoes de dados disponiveis para o consumo.
Exemplo:/deputados -> <https://dadosabertos.camara.leg.br/api/v2/deputados>
-**Parâmetros**: são informações ou filtros que servem para evitar dados da consulta ou para serem processados pela API. Os parâmetros podem ser passados para a API através da URL Ou no corpo(body)da requisição.Exemplo: ?nome=bebeto -> <https://dadosabertos.camara.leg.br/api/v2/deputados?nome=bebeto>
-**Métodos**: são os modos de consumo de uma API, que podem ser:
- POST:inserção (CREATE)
- GET: consulta/leitura (READ)
- UPTADE:atualização (UPDATE)
- DELETE: deleção (DELETE)


Para este projeto vamos user.Node.js e o NPM (Node Package Manager)
- Node.js v20.13.0 LTS -> Long Term Suport (versão estável)


NPX -> Node Package eXecuter (Executor de pacote do Node
)



 TO-DO (documentar):
 -Instalação e uso Json Server: <https://github.com/typicode/json-server>
 Como baixar o Json server: <https://nodejs.org/en/> Aperte Download Node.js (LTS)
O JSON Server é uma ferramenta que permite criar rapidamente uma API REST completa com base em um arquivo JSON. Isso é útil para prototipagem rápida, testes de front-end ou qualquer situação em que você precise de uma API fake para simular um servidor real.


~~~~

-Criação do **.gitinore**
O arquivo **.gitignore** é utilizado para especificar arquivos e diretórios que você deseja excluir do controle de versão do Git. Isso é útil para evitar que arquivos desnecessários, como arquivos de compilação, arquivos temporários ou arquivos sensíveis, sejam incluídos no repositório.

~~~~
 -Criação do script "start" no package.json:
 -**Achar o json no terminal** : Escreva npm start (e aperte o enter)
 exemplo :npm start 
 Resultado:npx json-server data/db.json5

 -Observações em relação ao uso do JSON5 vs JSON
 -Instalação das extensões para formatação de arquivo .json5

 -Chamada do script start com NPM ao invés do NPX

 ~~~
- O que é o chocolatey (e porque não istalá-lo agora)
 Ele é gerenciador de pacotes para Windows. Ele foi projetado para ser uma estrutura descentralizada para instalar pacotes (aplicativos/ferramentas) mais rapidamente. É muito semelhante ao que temos no mundo Linux, citando os dois gerenciadores de pacotes mais famosos (apt e yum). O Chocolatey é construído sobre a infraestrutura do NuGet, que atualmente usa o PowerShell por debaixo do capô.





 Da aula de sexta (10/05):
 -Instalação de dependencias de projeto com o comando npm install 