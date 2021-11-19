# PortifolioAPI
Portfólio com os projetos desenvolvidos em cada semestre destacando as contribuições individuais

# WebBot

Projeto Integrador do curso de Banco de Dados da Fatec-SJC 1º Semestre 2019.

O objetivo do projeto é que um grupo de alunos desenvolva uma aplicação em que
seja utilizado um WebBot desenvolvido pelo grupo, usando o na solução de um
problema proposto pelo grupo.

### Objetivo

Desenvolver um web bot que faça uma raspagem de dados em um site, coletando dados
referentes as despesas gastas por políticos de cargo eletivo, coletando informações
que serão arquivadas, onde as mesmas serão desmembradas em quanto cada tipo de despesa
consumiu do valor pago em impostos pelo contribuinte.

### Público Alvo

As informações podem ser acessadas pela imprensa, com fim de divulgação
em seus veículos de comunicação, por associações que fazem um trabalho independente
de fiscalização dos órgãos públicos e pela população em geral, com o intuito de
cobrar atitudes mais corretas de políticos que tiverem despesas excessivas.

### Finalidade

Tornar mais acessível a população informações que podem ajudá-los a
pressionar os políticos a trabalharem em causas de interesse popular e colaborar
com órgãos de segurança pública, como a polícia federal e o judiciário por exemplo,
a identificar possíveis crimes vinculados a corrupção que podem ser identificados
através de valores anormais ou alguma outra irregularidade, como improbidade administrativa
e lavagem de dinheiro.

### Requisitos

- Desenvolver um programa em linguagem Python que faça a coleta de dados em um site
que disponibilize as informações necessarias;
- Reunir os valores coletados em um banco de dados ou em forma de tabelas;
- Organizar as informações em categorias a serem definidas.
- Listar os dados de forma estatística com o objetivo de identificar os principais
focos de onde se precisa trabalhar para que os recursos públicos sejam utilizados
de forma mais eficiente.

### Desenvolvimento

### Front End

- Programa desenvolvido nas linguagens Html, Css e Javascript
- A estrutura do Html será utilizada para criar a interface que será utilizada pelo usuário
- Alguns recursos de Css serão utilizados para melhorar a aparência da página e definir o alinhamento e tamanho de fonte do que será mostrado pela aplicação
- Os recursos do Javascript terão funções de redirecionamento no clique dos botões ou na escolha de alguma opção e de associar essa escolha à parte correspondente do programa

### Back End

- Programa desenvolvido em linguagem Python
- A biblioteca request fará a raspagem de dados através da api do site dos dados abertos da câmara dos deputados
- As informações obtidas na raspagem serão armazenadas em um arquivo csv
- utilizamos a biblioteca pandas para o tratamento do arquivo, sendo ordenados e aparecerem para o usuário de acordo com o critério de pesquisa que ele escolher
- Os recursos da biblioteca Matplotlib serão utilizados para que o usuário possa visualizar os dados em forma de gráfico.

### Para executar o projeto

- Para começar, entre na pasta do projeto "operacao-lava-bot" e execute o seguinte comando:

    ```bash
    pip install -r requirements.txt
    ```

- O comando acima importará as bibliotecas "request" e "os" utilizadas no projeto
- Execute o primeiro codigo (DEPESAS_SCRAPING.py)
- Este codigo fara a raspagem dos dados e a criação dos arquivos para analise
- Posteriormente importe as bibliotecas pandas e matplotlib e execute o segundo codigo (ANALISE_DAS_DESPESAS.py)
- Este é o codigo que fara o tratamento e a impressão dos dados ao usuario, instruções são exibidas durante a execução.

### Back End:

- Programa desenvolvido em linguagem Python.
- Uma solicitação de biblioteca faz a raspagem de dados através da API do site de dados abertos da câmara dos deputados.
- As informações incluídas na raspagem serão armazenadas em um arquivo csv.
- Utiliza uma biblioteca de pandas para tratamento de arquivo, sendo ordenada e exibida para o usuário de acordo com o critério de pesquisa que ele escolheu.
- Os recursos da biblioteca Matplotlib serão utilizados para que o usuário possa visualizar os dados em forma de gráfico.

# Projeto Integrador II - 2º Semestre de Banco de Dados FATEC/SJC

O principal objetivo do projeto é desenvolver um sistema para a Visão Estratégica de Projetos,
o sistema sera desenvolvido para facilitar o planejamento de projetos de uma empresa.

### Disciplinas:

- Engenharia de Software - Profº Giuliano Bertoti.
- Linguagem de Programação I - Profª Adriana Jacinto.
- Laboratório de Desenvolvimento em Banco de Dados II - Profª Adriana Jacinto.
- Arquitetura e Modelagem de Banco de Dados - Profº Emanuel Mineda.

### Equipe:

[Felipe Santos](https://gitlab.com/felipefsc)

[Gabriel Angelo](https://gitlab.com/Angelog)

[Nathan Nascimento](https://gitlab.com/N4htan)

### LEVANTAMENTO DE REQUISITOS

![image](https://user-images.githubusercontent.com/19509794/142542143-b081cddd-2cc9-428f-bd5c-3e1206623ff6.png)

### Como Instalar o git na máquina:


- Abra o terminal clicando dentro de uma pasta com o botão direito e selecione a opção git bash here
- Utilize a função git clone https://gitlab.com/projeto-II/OEP.git para instalar os arquivos no seu computador

### Referências


- Editor Html: www.w3schools.com/html/tryit.asp?filename=tryhtml_default
- Diagramas Gantt:
https://frappe.io/gantt
https://developers.google.com/chart/interactive/docs/gallery/ganttchart
