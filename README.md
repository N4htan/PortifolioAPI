# PortifolioAPI
Portfólio com os projetos desenvolvidos em cada semestre destacando as contribuições individuais

# OPERAÇÃO LAVA BOT - 1º Semestre de Banco de Dados FATEC/SJC 2019/2.

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

# MEGA DEV - 2º Semestre de Banco de Dados FATEC/SJC 2020/1.

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

![image](https://user-images.githubusercontent.com/19509794/142543911-364a1b41-8d61-49fe-9a67-ff16a37f4f69.png)
![image](https://user-images.githubusercontent.com/19509794/142544009-4a450d42-4ff8-4277-a6b8-bc685ce68148.png)
![image](https://user-images.githubusercontent.com/19509794/142544119-a947b6e8-79cb-4f0e-99c9-2ef4d93bdf82.png)
![image](https://user-images.githubusercontent.com/19509794/142544251-9cdff6f8-1ab9-45d5-8626-2c6dc379f2af.png)
![image](https://user-images.githubusercontent.com/19509794/142544366-f5ce6f29-30ff-4b9f-8432-4cf12504dbdd.png)
![image](https://user-images.githubusercontent.com/19509794/142544598-4b5538c3-1497-4c20-83db-2a802ddbc0db.png)
![image](https://user-images.githubusercontent.com/19509794/142544746-4aa3199f-d5e1-43c1-8f62-37924ca0d87d.png)
![image](https://user-images.githubusercontent.com/19509794/142544824-b87e6776-637a-4e5f-8249-fa1c0b9d0473.png)
![image](https://user-images.githubusercontent.com/19509794/142545011-3b3bacf2-08ac-4426-805c-0f342012d944.png)
![image](https://user-images.githubusercontent.com/19509794/142545099-a7dd88b6-d263-4e86-ae0f-4934d11b2da3.png)
![image](https://user-images.githubusercontent.com/19509794/142545187-5505337a-3d31-46e1-9ac1-0b07080e4e3c.png)

### Como Instalar o git na máquina:


- Abra o terminal clicando dentro de uma pasta com o botão direito e selecione a opção git bash here
- Utilize a função git clone https://gitlab.com/projeto-II/OEP.git para instalar os arquivos no seu computador

### Referências


- Editor Html: www.w3schools.com/html/tryit.asp?filename=tryhtml_default
- Diagramas Gantt:
https://frappe.io/gantt
https://developers.google.com/chart/interactive/docs/gallery/ganttchart



# KIND OF - 3º Semestre de Banco de Dados FATEC/SJC 2020/2.

<p align="center">O projeto integrador consiste na criação de uma aplicação web com dashboard. </p>

<p align="center">
   <a href="#-entregas">Entregas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-sobre">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalacao">Instalação e execução</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  
</p



### :heavy_check_mark: Entregas e Vídeos <a name="-entregas"/></a>


|  DATA  | SPRINT | Link do vídeo|
|--------|--------|--------------|
|  27-09 |   0    |       -       |
|  18-10 |   1    |[Video](https://www.youtube.com/watch?v=hSxAHHQWt9Q&feature=youtu.be)              |
|  08-11 |   2    |[Video](https://www.youtube.com/watch?v=6RoibaiDX_k&feature=youtu.be)              |
|  29-11 |   3    |[Video](https://youtu.be/us_hd_7H2kc)     |
|  14-12 |   4    |[Video](https://youtu.be/pS3nGC5DPVQ)|



### :page_with_curl: Sobre o projeto <a name="-sobre"/></a>

> É proposto o desenvolvimento de um Sistema de Recompensas dentro de uma aplicação do cliente. O cliente busca otimizar seu negócio através de uma dashbord, com as informações mais atrativas e impactantes para seus clientes. O cliente pode acompanhar seus respectivos dados de maneira segura e organizada, e caso necessário, e tomar a decisões a partir delas.

O objetivo do trabalho é reinventar a forma de aproximação do usuário da plataforma. Não consistindo na criação web de apenas consultas, mas sim em uma aplicação utilizando o sistema de recompensas, na qual o usuário poderá utiliza-los dentro da aplicação com o que o cliente poderá fornecer. As recompensas foram demostradas através de cursos que poderão auxiliar o usuário com a própria gestão financeira. 


### :memo: Referências <a name="-tecnologias"/></a> 

```
- Java, Html, Css, JavaScript
- frameworks: Spring Boot, Boostrap 
- banco de dados relacional: MySQL
```

### :memo: Levantamento de Requisitos <a name="-requisitos"/></a> 


> Criação de uma aplicação web com dashbord estatistica, com a linguagem principal utilizada sendo o Java.

> A aplicação deve conter um login. As informações apresentadas devem ser intuitivas pois trata-se de um ambiente com assuntos financeiros, ou seja, deve agregar pessoas bancarizadas e não bancarizadas. 

> A aplicação precisa agregar valor a um sistema já em andamento. A aproximação do cliente/usuário será realizada atraves da utilização de pontos e utilizar na "loja" virtual ambientalizada dentro do login de cada usuário.



### Requisitos Funcionais

| Requisitos funcionais               |Código|Descrição                                             | Prioridade | Sprint|
|-------------------------------------|------|------------------------------------------------------|------------|-------|
|Acesso ao score e dashboard          |RF05  |Acesso dos usuários o score gerado                    | 01         | 18/10 |
|Acesso ao sistema de pontos          |RF06  |Acesso a recompensa conforme variação do score        | 01         | 18/10 |
|Tratamento de dados                  |RF02  |Organização dos dados forneceidos                     | 02         | 08/11 |
|Comunicação com o Banco de dados     |RF07  |Comunicação com o dataset fornecido pelo cliente      | 02         | 08/11 |
|Sistema de Recompenas                |RF03  |Disponibilidade de recursos da recompensas de pontos  | 03         | 29/11 |
|Modificar informações pontos         |RF04  |Alteração de pontos pelo sistema de recompensas       | 03         | 29/11 |
|Cadastro de usuários                 |RF01  |Registro de novos usuários (Pessoa juridica e física) | 02         | 08/11 |



### Requisitos não funcionais

| Requisitos não funcionais           |Código|Descrição                                                                    | 
|-------------------------------------|-------|----------------------------------------------------------------------------|
|Documentação do produto              |RNF01  | Documentação do código/Utilização das informações                          |
|Autenticação de usuário              |RNF02  |Verificar autenticidade do usuário                                          |
|Usabilidade                          |RNF03  |Estética e Design minimalista (aplicação web)                               |
|Visibilidade do status do sistema    |RNF04  |As informações serão apresentadas de forma organizadas, intuitiva e amigável|
|Consistência e padrões               |RNF05  |Consistência e padrões na apresentação das informações                      |    
|Portabilidade                        |RNF06  |A consulta deve estar disponivel nos principais navegadores disponíveis     |
|Acesso de segurança                  |RNF07  |Acesso seguro das informações                                               |     
|Responsividade                       |RNF08  |Velocidade de resposta e tempo de atualização de tela                       |      


### :computer: Instalação e execução <a name="-instalacao"/></a>
1. Clonar a aplicação
2. Abrir a aplicação na IDE que desejar (Eclipse, IntelliJ, Spring Tool) 
3. Ajustar as configurações do banco de dados na Application.properties.
3. Rodar como JavaApplication
4. Abrir localhost:8080

Você também pode acompanhar através desse [link](https://gitlab.com/ferpsalles/kind-of-pi/-/blob/master/bd/MANUAL_PARA_RODAR_O_PROJETO_PELA_PRIMEIRA_VEZ.pdf)

### :computer: Visões do Usuário <a name="-visao"/></a>

1. Tela de login

<p align="center">
  <img src="./bd/login.png" alt="Logo" width=50% height=50%>
</p>

2. Tela de Cadastro

<p align="center">
  <img src="./bd/cad.png" alt="Logo" width=50% height=50%>
</p>

3. Home View

<p align="center">
  <img src="./bd/HOME.png" alt="Logo" width=50% height=50%>
</p>

### :computer: Referências <a name="-referencias"/></a> 
1. https://spring.io/projects/spring-boot
2. https://www.chartjs.org/
3. https://www.mysql.com/



### :email: Contato
- Fernanda Ramos - [Gitlab](https://gitlab.com/ferpsalles) - [Linkedin](https://www.linkedin.com/in/fernanda-ramos-de-padua-salles-44329b157/)

- Gabriel Angelo - [Gitlab](https://gitlab.com/Angelog)- [Linkedin](https://www.linkedin.com/in/gabriel-angelo-a4b251116/)

- Nathan Nascimento - [Gitlab](https://gitlab.com/n4htan)- [Linkedin](https://www.linkedin.com/in/n4htan/)

- Vitor Daniel Silva - [Gitlab](https://gitlab.com/VitorDan)- [Linkedin](https://www.linkedin.com/in/vitor-daniel-9343bb150/)


### Agradecimentos

Agradecemos aos professores pelo suporte oferecido para o progresso do projeto.

