## Git :computer:



### O que é Git?

Git é um sistema de controle de versão open-source. Ele é utilizado para a criação de um histórico de alterações em código-fonte de projetos de desenvolvimento de software. Foi desenvolvido por Linus Torvalds, o criador do sistema operacional Linux.

Por meio de sua utilização, podemos saber quais foram as alterações realizadas, quem fez cada uma das alterações e baixar essas mudanças em nossa máquina. Se necessário, revertê-las para uma versão anterior.



## GitHub :file_folder:



### O que é GitHub?

O Github é um repositório remoto, criado como um serviço online de hospedagem de repositórios do Git.

Funciona como um servidor que agrega todas as modificações realizadas por cada uma das pessoas envolvidas em um projeto, unificando as diferentes versões de código e seus históricos, permitindo compartilhamento entre as equipes.



### Diferenças entre Git e GitHub



1. **Git é um software VCS local** que permite aos desenvolvedores salvar snapshots de seus projetos ao longo do tempo. 
2. **GitHub é uma plataforma baseada na web que incorpora os recursos de controle de versões do Git** para que possam ser usados colaborativamente. Também inclui recursos de gerenciamento de projetos e equipes, assim como oportunidades para networking e codificação social.



### Principais conceitos do Git



#### Repositório

O primeiro é o repositório, local físico onde os arquivos e suas cópias ficarão armazenados. O repositório pode ser local ou remoto, podendo salvar não apenas arquivos de texto, mas também imagens, áudios e outros elementos relacionados ao projeto.

#### Branch

Branches são os ramos, cópias do código original que podem ser manipuladas de forma livre pela pessoa que trabalha em programação, sem afetar as funcionalidades em produção no código-fonte.

Isso **permite que todas as alterações sejam realizadas de forma segura**, sem que erros ocorram na cópia principal do projeto.

#### Merge

Após a finalização de um trabalho em um Branch, é necessário realizar o Merge, fundir a cópia e seus arquivos modificados com o ramo principal do projeto. Isso acontece apenas no repositório local para que ajustes possam ser feitos.

#### Push Request

O Push Request é o envio das modificações após o Merge para o repositório central, para que todas as outras pessoas que atuam no desenvolvimento possam atualizar suas cópias e revisar o código criado, verificando conflitos com seus próprios trabalhos.

#### Pull Request

O Pull Request é utilizado quando outra pessoa que atua no desenvolvimento muda o ramo principal no repositório central, puxando as modificações realizadas para a sua máquina, fundindo a nova versão com o seu código local.

#### Fork

Trata-se do comando de cópia de um repositório remoto para a máquina local, realizado sempre que vamos começar a trabalhar em um projeto que já existe. Também é usado para pegar um código público para posterior modificação e utilização em um programa interno.
