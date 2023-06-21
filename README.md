# Inteli - Instituto de Tecnologia e Liderança 

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2022/04/28103439/Logo-Container.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Site InovTech

## Nome do grupo: InovTech

## Integrantes:
- <a href="https://www.linkedin.com/in/eduarda-cardoso-de-souza-8bb802268/">Eduarda Cardoso de Souza</a> 
- <a href="https://www.linkedin.com/in/fernando-machado-84673a212/">Fernando Machado</a>
- <a href="https://www.linkedin.com/in/gabriellysilvavitor/">Gabrielly Vitor</a>
- <a href="https://www.linkedin.com/in/luan-ramos-de-mello-253b28268/">Luan Ramos</a> 
- <a href="https://www.linkedin.com/">Mário Ventura</a> 
- <a href="https://www.linkedin.com/in/rodrigo-sales-07/">Rodrigo Sales</a>

# Professores:
## Orientador

- <a href="https://www.linkedin.com/">Marcelo Gonçalves</a>

## Instrutores

- <a href="https://www.linkedin.com/">Fátima Toledo</a>
- <a href="https://www.linkedin.com/">Francisco Escobar</a>
- <a href="https://www.linkedin.com/">Henrique Paiva</a>
- <a href="https://www.linkedin.com/">Victor Quiroz</a>

## 📝 Descrição

Uma das áreas de atuação do IPT na atualidade diz respeito ao monitoramento e avaliação estrutural com direcionamento ao segmento ferroviário, proporcionando as informações necessárias para as tomadas de decisão e minimizando os custos operacionais. Essas informações são apresentadas aos clientes no formato de volumosos relatórios, repletos de textos, gráficos, mapas e tabelas, disponibilizado de forma impressa aos usuários. A grande problemática, entretanto, está na grande quantidade de tempo gasta para análise e entendimento destes ensaios, dificultando, portanto, o processo de tomada de decisões.
Nosso projeto tem por objetivo sistematizar o processo de apresentação dos dados e informações obtidos pelos estudos realizados pelo laboratório LInE em uma aplicação WEB, melhorando a experiência dos clientes do IPT e facilitando a tomada de decisões por parte do usuário final. Desenvolvemos uma aplicação WEB que demonstra o trajeto realizado pelo trem e que aponta os pontos nos quais ocorreu uma mudança de estado anormal no veículo, seja em quesito de pressão, velocidade ou outros fatores que impactam (ou podem impactar) a segurança dos vagões durante o caminho.


## 📁 Estrutura de pastas

|--> documentos<br>
  &emsp;| --> outros <br>
  &emsp;| T8_G4_V3.0_Web_application_document.docx<br>
  &emsp;| T8_G4_V3.0_Web_application_document.pdf<br>
|--> imagens<br>
|--> scr<br>
  &emsp;| --> Banco_de_dados <br>
  &emsp;| --> Public (Frontend) <br>
  &emsp;| --> scripts de suporte <br>
  &emsp;| --> app.js <br>
| readme.md<br>
| license.txt

Dentre os arquivos presentes na raiz do projeto, definem-se:

- <b>readme.md</b>: arquivo que serve como guia e explicação geral sobre o projeto (o mesmo que você está lendo agora).

- <b>documentos</b>: aqui estarão todos os documentos do projeto. Há também uma pasta denominada <b>outros</b> onde estão presentes aqueles documentos complementares ao <b>web application document</b>.

- <b>imagens</b>: imagens relacionadas ao projeto como um todo (por exemplo imagens do sistema, do grupo, logotipos e afins).

- <b>src</b>: nesta pasta encontra-se todo o código fonte do sistema (existem duas subpastas <b>backend</b> e <b>frontend</b> que contêm, respectivamente, o código do servidor e o código da página web).

## 💻 Configuração para desenvolvimento

Aqui encontram-se todas as instruções necessárias para a instalação de todos os programas, bibliotecas e ferramentas imprescindíveis para a configuração do ambiente de desenvolvimento.

1.  Baixar e instalar o node.js:  [https://nodejs.org/pt-br/](https://nodejs.org/pt-br/) (versão 16.15.1 LTS)
2. Clone o repositório em questão.
3.  No modo administrador, abra o "prompt de comando" ou o "terminal" e, após,  abra a pasta no diretório raiz do repositório clonado e digite o segundo comando:

```sh
npm i
```

Isso instalará todas as dependências definidas no arquivo <b>package.json</b> que são necessárias para rodar o projeto. Agora o projeto já está pronto para ser modificado. Caso ainda deseje iniciar a aplicação, digite o comando abaixo no terminal:

```sh
node app.js
```
5. Agora você pode acessar a aplicação através do link http://localhost:1234/
6. O servidor está online.

OBS: O site também pode ser acessado através desse link: https://j657tr-3000.csb.app/


## 🗃 Histórico de lançamentos

* 5.0 - 22/06/2023
    * Mudanças na página info.html
    * Responsividade nas páginas analise.html, info.html, mapa.html, relatório.html
    * Incrementos no banco de dados
    * Incremento no Script Analise_Dados.js
    * Revisão do WAD
    * Criação do Script navbar.js
* 4.0 - 09/06/2023
    * Incrementos na página analise.html, info.html
    * Criação do Script Analise_Dados.js, csvToDb_choques.js, csvToDb_Picos,js, mapa.js
    * Análise dos testes de usabilidade realizados
    * Criação da página mapa.html
    * Criação do CSS mapa.css
    * Criação da responsividade da página home.html
* 3.0 - 26/05/2023
    * Criação da página Home.html, analise.html, info.html, paghome.html 
    * Criação do arquivo visual.css
    * Atualização do banco de dados
    * Criação do fetch no arquivo analise.js para integração do frontend com o backend
* 2.0 - 11/05/2023
    * Criação dos endpoints de chamadas no banco de dados
    * Criação da arquitetura do Sistema
    * Fluxograma da aplicação WEB
    * Criação do proótipo
* 1.0 - 24/04/2023
    * Atualização dos itens 1 (Visão geral do projeto), 2(Análise do problema) e 3 (Requisitos do sistema) do WAD.



## 📋 Licença/License

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/2023M2T8-Inteli/Projeto4">Site InovTech</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/2023M2T8-Inteli/Projeto4">Inteli, Eduarda Cardoso de Souza, Fernando Machado ,Gabrielly Vitor, Luan Ramos, Mário Ventura ,Rodrigo Sales</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"></a></p>

## 🎓 Referências

Aqui estão as referências usadas no projeto:

1. ADMIN@DBSCHEMA.COM. DbSchema | Professional GUI Client for Database Management. Disponível em: <https://dbschema.com/>. Acesso em: 20/04/2023.
2. DB Browser for SQLite. Disponível em: <https://sqlitebrowser.org/>. Acesso em: 20/04/2023.
3. SQLITE. SQLite Home Page. Disponível em: <https://www.sqlite.org/index.html>. Acesso em: 20/04/2023.
4. MICROSOFT. Visual Studio Code. Disponível em: <https://code.visualstudio.com/>. Acesso em: 20/04/2023.
5. NODE.JS. Node.js. Disponível em: <https://nodejs.org/en>. Acesso em: 20/04/2023.
6. OPENAI. ChatGPT. Disponível em: <https://chat.openai.com/>. Acesso em: 11/05/2023.
7. Poe - Fast, Helpful AI Chat. Disponível em: <https://poe.com/>. Acesso em: 08/06/2023.
8. IPT - Instituto de Pesquisas Tecnológicas. Disponível em: <https://www.ipt.br/>. Acesso em: 17/04/2023.

