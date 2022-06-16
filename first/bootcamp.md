# Desafio Bootcamp Git/Github :cat:



_O **Git** é uma ferramenta de versionamento de arquivos em geral, mas muito usada por desenvolvedores de software para versionamento de código._ _Linus Torvalds é o criador dessa ferramenta, onde criou para ajudar no desenvolvimento do sistema operacional Kernel Linux. Sobre a sigla **Git**, Torvalds menciona que pode ser qualquer coisa, o termo git vem do britânico, e quer dizer "cabeça-dura". Ele diz que dependendo do Humor também pode ser "Global Information Tracker", ou quando o git trava "goddamn idiotic truckload of sh*t". :laughing:

_**Versionamento de software** por sua vez é uma estratégia organizada para a realização de melhorias do código, assim temos desde o início do projeto até a última atualização._

_O **Github** é um serviço de armazenamento na nuvem, onde podemos criar repositórios público ou privado e interagir com os usuários da plataforma._



_**Etapas de um Arquivo**_

- _**Untracked and Tracked**_

  - _**Untracked** é o estado em que o arquivo se encontra quando a ferramenta de versionamento Git ainda não tem o conhecimento._

  - _**Tracked** é quando o Git já tem a ciência do arquivo._

    _Em Tracked o arquivo se encontra em três estágios:_

    - _**Unmodified**_ - _O arquivo ainda não sofreu modificações ou já está armazenado em um repositório._

    - _**Modified**_ - _O arquivo já recebeu alguma modificação._

    - _**Staged**_ - _O arquivo se encontra pronto para para "entrar no palco", aguardando para ser armazenado._

      

_**Ambiente de Desenvolvimento**_

- _**Working Directory**_

 _Working Directory  é  a árvore de diretórios dos arquivos iniciais (fonte), onde pode-se ver e editar. (Nessa etapa o Git ainda não conhece o arquivo, o arquivo é Untracked)_.

- **_Staging Área_**

_Staging Área é o nível em que o arquivo se encontra pronto para avançar de nível, ou seja, pronto para embarcar a um repositório local. (Nessa etapa do processo o Git já tem conhecimento do arquivo, o arquivo passa a ser Tracked)._

- _**Repository**_

_Repositório é o lugar onde o arquivo fica armazenado, temos o **Local Repository** e o **Remote Repository**. (O arquivo continua a ser Tracked)._

_O Local Repository é o nível em que o arquivo se encontra após passar pela Staging Área, é um arquivo onde já recebeu todas as modificações da sua versão atual e está armazenado no repositório local aguardando novos comandos. (Nessa Etapa o arquivo volta a ser Unmodified)._

_O Remote Repository é um serviço de armazenamento na nuvem, ou seja, o arquivo que se encontra em um repositório remoto (externo a máquina). (Nessa etapa o arquivo está localizado no serviço de armazenamento Github, onde ficará aberto ao publico ou privado dependendo da forma de escolha ao cria-lo)._



_**Ciclo dos Arquivos**_

_Quando criamos um arquivo usando o terminal Git, usamos **Mkdir** (Make Directory). O arquivo em questão está na fase em que o Git não tem ciência do que está lá, ou seja, Untracked. Para informar ao git usamos o **git add**, que leva o arquivo de Untracked direto para Staged, onde o git já o reconhece, portanto é um arquivo Tracked. Na fase staged o arquivo esta pronto para ser commitado, ou seja, armazenado em um repositório. Para isso é usado **git commit**._

_O **git add** pode ser usado de três maneiras:_

- _**git add <nome do arquivo>**  - transporta o arquivo digitado que esta no working directory para staging área;_
- _**git add * ** - transporta todos arquivos que estão no working directory para staging área;_
- _**git add.** - igual ao anterior._



_Quando o arquivo passa a ser conhecido pela ferramenta **Git**, ele passa a ser um arquivo Trancked. E é nesse momento em que acontece o ciclo de versionamento do arquivo, que são eles Unmodified, Modified e staged._

_Se removermos o arquivo Unmodified ele retorna a ser um arquivo untracked. Ao editarmos o arquivo Unmodified, ele passa a ser um arquivo modified, aguardando um commit e logo após ele ser commitado, passa a ser novamente um arquivo Unmodified, ou seja um arquivo sem novas modificações._

​                             



​                                                                                      

​                                                                                                     

​                                                           



​                                                                             
