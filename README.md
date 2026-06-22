# O QUE É O GIT-E-GITHUB, QUAIS AS SUA FUNÇÕES E COMO ARMAZENAR CÓDIGOS NELES.

##O que é e qual a função do Git
O Git é um software de controle de versão distribuído que roda localmente no computador do desenvolvedor. A sua principal função é registrar o histórico de alterações de um conjunto de arquivos ao longo do tempo.

Na prática, o Git monitora cada linha de código modificada, adicionada ou removida. Isso permite que o desenvolvedor reverta o projeto para estados anteriores caso ocorram erros, identifique quem fez determinada alteração e isole o desenvolvimento de novas funcionalidades através de ramificações (chamadas de branches). Com as branches, é possível trabalhar em modificações complexas sem alterar o código principal que já está funcionando. Quando a nova funcionalidade é testada e aprovada, o Git realiza a fusão (merge) desses códigos de forma automatizada, gerenciando os possíveis conflitos de escrita entre arquivos.

O que é e qual a função do GitHub
O GitHub é uma plataforma de hospedagem de código baseada na nuvem que utiliza o sistema do Git. Enquanto o Git gerencia as versões no ambiente local (computador), o GitHub atua como o servidor remoto onde esses repositórios são armazenados e compartilhados através da internet.

A sua função primordial é facilitar a colaboração em equipe e o backup de segurança dos projetos. O GitHub oferece uma interface visual para que desenvolvedores revisem códigos uns dos outros (através de Pull Requests), gerenciem problemas e tarefas (utilizando Issues e quadros de projeto), e controlem permissões de acesso. Além de centralizar o trabalho de equipes, a plataforma funciona como um portfólio público para programadores, permitindo que qualquer pessoa ou empresa visualize a qualidade e o progresso do código desenvolvido.

O processo de publicação de um projeto no GitHub
O envio de um projeto local para o GitHub segue um fluxo padronizado de comandos executados no terminal do sistema operacional.

O processo começa com a inicialização do Git na pasta do projeto. Esse comando cria um diretório oculto que permite ao Git começar a rastrear os arquivos. Em seguida, o desenvolvedor executa o comando de seleção, informando ao sistema quais arquivos modificados devem ser preparados para o próximo registro. O passo seguinte é a consolidação desse registro através de um comando de confirmação (chamado de commit), que salva o estado atual dos arquivos localmente e exige uma mensagem descritiva sobre o que foi alterado.

Com o código registrado localmente, o desenvolvedor acessa o site do GitHub e cria um novo repositório vazio, que gerará um link URL exclusivo. No terminal do computador, o desenvolvedor vincula o repositório local a esse endereço remoto do GitHub. Por fim, executa-se o comando de envio (conhecido como push), que transfere os dados e todo o histórico de alterações do computador para os servidores do GitHub, tornando o projeto disponível online.
