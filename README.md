# Inteli - Instituto de Tecnologia e Liderança 

<p align="center">
<a href= "https://www.inteli.edu.br/"><img src="https://www.inteli.edu.br/wp-content/uploads/2021/08/20172028/marca_1-2.png" alt="Inteli - Instituto de Tecnologia e Liderança" border="0"></a>
</p>

# Null Churn

## Rappitenderos

## Integrantes: 
- <a href="https://br.linkedin.com/in/eric-tachdjian-27044b232">Eric Tachdjian</a>
- <a href="https://www.linkedin.com/in/giovana-lisboa-thome/">Giovana Thomé</a>
- <a href="https://www.linkedin.com/in/rodrigo-moraes-martins-a81703202/">Rodrigo Martins</a> 
- <a href="https://www.linkedin.com/in/victorbarq/">Sergio Lucas</a> 
- <a href="https://www.linkedin.com/in/victorbarq/">Pedro Munhoz</a>
- <a href="https://www.linkedin.com/in/beatriz-hirasaki-leite-b2261923a">Beatriz Hirasaki</a> 
- <a href="https://www.linkedin.com/in/arthur-reis-575532241/">Arthur Reis</a>

## 📝 Descrição

A Rappi apresentou um problema onde uma quantidade significativa dos seus entregadores davam churn (deixavam a plataforma), então o trabalho do grupo é identificar os possíveis motivos dessa decisão de sair do aplicativo e a partir de uma inteligência artificial supervisionada, utilizando as bibliotecas do python, que ajudariam na classificação de quais entregadores tem uma tendência maior a deixar a plataforma.

## 📁 Estrutura de pastas

```
Alunos inteli (remover essa observação do readme.md após leitura e execução):

Supondo que você é da Turma 4 e Projeto 5, substitua:

T(NUMERO_DA_TURMA)_G(NUMERO_DO_GRUPO)_V(VERSÃO)_Web_application_document.pdf
por
T4_G5_V01_Web_application_document.pdf

Faça o mesmo para a documentação em formato DOCX.
```

|--> documentos<br>
  &emsp;| --> outros <br>
  &emsp;| T(NUMERO_DA_TURMA)_G(NUMERO_DO_GRUPO)_V(VERSÃO)_Web_application_document.pdf<br>
  &emsp;| T(NUMERO_DA_TURMA)_G(NUMERO_DO_GRUPO)_V(VERSÃO)_Web_application_document.docx<br>
|--> imagens<br>
|--> src<br>
  &emsp;|--> Backend<br>
  &emsp;|--> Frontend<br>
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
3.  No modo administrador, abra o "prompt de comando" ou o "terminal" e, após,  abra a pasta "src/backend" no diretório raiz do repositório clonado e digite o segundo comando:

```sh
npm install
```

Isso instalará todas as dependências definidas no arquivo <b>package.json</b> que são necessárias para rodar o projeto. Agora o projeto já está pronto para ser modificado. Caso ainda deseje iniciar a aplicação, digite o comando abaixo no terminal:

```sh
npm start
```
5. Agora você pode acessar a aplicação através do link http://localhost:1234/
6. O servidor está online.


```
Alunos inteli (remover essa observação do readme.md após leitura e execução):

1. Certifique-se que há um arquivo "package.json" na pasta backend do projeto.

2. Dentro deste arquivo, encontre a propriedade "scripts", e adicione um atributo de nome "start"
com o valor "node <CAMINHO_DO_ARQUIVO_DO_SERVIDOR>." Atenção: "<CAMINHO_DO_ARQUIVO_DO_SERVIDOR>" 
deve ser substituído pelo caminho para o arquivo principal da aplicação, utilizado para subir o
servidor. Por exemplo, se o arquivo utilizado para subir o servidor é "app.js", o atributo start
deve possuir o valor "node app.js".

3. No arquivo utilizado para subir a aplicação, defina a porta padrão de execução para "1234".
````

## 🗃 Histórico de lançamentos

* 1.0 - 06/10/2022
    *

* 0.9 - 23/09/2022
    * Determinação dos hiperparâmetros
    * Utilização da ferramenta Pycaret para definição dos melhor algorítmo para o caso Rappi

* 0.7 - 09/09/2022
    * Criação dos modelos
    * Escolha dos algorítmos
    * Avaliação dos resultados obtidos a partir dos modelos.
    
* 0.5 - 26/08/2022
    * Entendimento dos dados
    * Criação de features 
    
* 0.2 - 12/08/2022
   * Análise da Industria
   * Estudo do negócio
   * Matriz de Riscos
   
* 0.1 - 01/08/2022
    * Início do Projeto

## 📋 Licença/License

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/Spidus/Teste_Final_1">Null Churn Model</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.yggbrasil.com.br/vr">Inteli, Eric Tachdjian, Beatriz Hirasaki, Sergio Lucas, Pedro Munhoz, Giovana Thomé, Rodrigo Martins, Arthur Reis</a> is licensed under <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>

## 🎓 Referências

Aqui estão as referências usadas no projeto:

1. <https://creativecommons.org/share-your-work/>
2. <https://scikit-learn.org/stable/modules/tree.html>
3. <https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.ExtraTreesClassifier.html>
4. <https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html>
5. <https://pycaret.org/>
6. <https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html>
7. <
