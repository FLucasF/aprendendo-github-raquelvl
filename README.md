# :wave: Os Fundamentos do GitHub

## 🤓 Visão geral do curso e resultados de aprendizagem

O objetivo deste curso é fornecer uma breve introdução ao GitHub. Também forneceremos materiais para aprendizado adicional e algumas ideias para você começar em nossa plataforma. 🚀

## :octocat: Git e GitHub

O Git é um Sistema de Controle de Versão Distribuído (VCS), o que significa que é uma ferramenta útil para rastrear facilmente as alterações em seu código, colaborar e compartilhar. Com o Git, você pode acompanhar as mudanças que faz em seu projeto, garantindo que sempre tenha um registro do que trabalhou e possa facilmente voltar a uma versão anterior, se necessário. Ele também facilita a colaboração com outras pessoas - grupos de pessoas podem trabalhar juntos no mesmo projeto e mesclar suas alterações em uma única fonte final!

O GitHub é uma maneira de usar o mesmo poder do Git online, com uma interface fácil de usar. Ele é usado em todo o mundo do software e além para colaborar e manter o histórico de projetos.

O GitHub abriga algumas das tecnologias mais avançadas do mundo. Seja visualizando dados ou construindo um novo jogo, há toda uma comunidade e conjunto de ferramentas no GitHub que podem levar você ao próximo nível. Este curso começa com os conceitos básicos do GitHub, mas exploraremos o restante posteriormente.	

## :octocat: Compreendendo o fluxo do GitHub
O fluxo do GitHub é um fluxo de trabalho leve que permite que você experimente e colabore em seus projetos facilmente, sem o risco de perder seu trabalho anterior.

### Repositórios
Um repositório é onde o trabalho do seu projeto acontece - pense nele como a pasta do seu projeto. Ele contém todos os arquivos e o histórico de revisões do seu projeto. Você pode trabalhar em um repositório sozinho ou convidar outras pessoas para colaborar com você nesses arquivos.

### Clonagem
Quando um repositório é criado no GitHub, ele é armazenado remotamente na nuvem ☁️. Você pode clonar um repositório para criar uma cópia local no seu computador e, em seguida, usar o Git para sincronizar os dois. Isso facilita a correção de problemas, a adição ou remoção de arquivos e o envio de commits maiores. Você também pode usar a ferramenta de edição de sua escolha em vez da interface do GitHub. Clonar um repositório também baixa todos os dados do repositório que o GitHub tinha naquele momento, incluindo todas as versões de cada arquivo e pasta do projeto! Isso pode ser útil se você experimentar com o seu projeto e perceber que gostou mais de uma versão anterior. Para saber mais sobre clonagem, leia ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

### Commits e push
Commits e push são como você pode adicionar as alterações feitas em sua máquina local ao repositório remoto no GitHub. Dessa forma, seu instrutor e/ou colegas de equipe podem ver o seu trabalho mais recente quando você estiver pronto para compartilhá-lo. Você pode fazer um commit quando fez alterações no seu projeto que deseja “marcar”. Você também pode adicionar uma mensagem de commit útil para lembrar a si mesmo ou aos seus colegas de equipe sobre o trabalho que você fez (por exemplo, “Adicionado um README com informações sobre nosso projeto”).

Depois de ter um commit ou vários commits prontos para adicionar ao seu repositório, você pode usar o comando push para adicionar essas alterações ao seu repositório remoto. Fazer commits e push pode parecer novo no início, mas prometemos que você vai se acostumar 🙂

## 💻 Termos do GitHub que você deve conhecer
### Repositórios
Já mencionamos os repositórios, eles são onde o trabalho do seu projeto acontece, mas vamos falar um pouco mais sobre os detalhes deles! À medida que você trabalha mais no GitHub, terá muitos repositórios, o que pode parecer confuso no início. Felizmente, o seu ["GitHub dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) ajuda a navegar facilmente pelos seus repositórios e ver informações úteis sobre eles. Certifique-se de estar logado para visualizá-lo!

Os repositórios também contêm READMEs. Você pode adicionar um arquivo README ao seu repositório para informar outras pessoas sobre a utilidade do seu projeto, o que elas podem fazer com ele e como podem usá-lo. Estamos usando este README para explicar como aprender Git e GitHub com você. 😄 Para saber mais sobre repositórios, leia ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) e ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branches
Você pode usar branches no GitHub para isolar o trabalho que você não deseja mesclar em seu projeto final ainda. Branches permitem que você desenvolva recursos, corrija bugs ou experimente com segurança novas ideias em uma área contida do seu repositório. Normalmente, você pode criar um novo branch a partir do branch padrão do seu repositório - main. Isso cria uma nova cópia de trabalho do seu repositório para você experimentar. Depois que suas novas alterações forem revisadas por um colega de equipe, ou se você estiver satisfeito com elas, você pode mesclar suas alterações no branch padrão do seu repositório. Para saber mais sobre branches, leia ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
Um fork é outra maneira de copiar um repositório, mas geralmente é usada quando você deseja contribuir para o projeto de outra pessoa. Fazer um fork de um repositório permite que você experimente livremente com alterações sem afetar o projeto original e é muito popular ao contribuir para projetos de software de código aberto! Para saber mais sobre forks, leia ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo).

### Pull requests
Ao trabalhar com branches, você pode usar um pull request para informar aos outros sobre as alterações que deseja fazer e solicitar feedback. Uma vez que um pull request é aberto, você pode discutir e revisar as alterações potenciais com colaboradores e adicionar mais alterações, se necessário. Você pode adicionar pessoas específicas como revisores do seu pull request, mostrando que deseja o feedback delas sobre suas alterações! Quando um pull request estiver pronto para ser mesclado, ele pode ser incorporado ao seu branch principal. Para saber mais sobre pull requests, leia ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

### Problemas (Issues)
Os problemas são uma maneira de rastrear melhorias, tarefas ou bugs em seu trabalho no GitHub. Eles são uma ótima forma de acompanhar todas as tarefas que você deseja realizar em seu projeto e informar aos outros o que você planeja fazer. Você também pode usar problemas para relatar a um projeto de código aberto favorito sobre um bug que você encontrou ou uma funcionalidade que você acha que seria ótima adicionar!

Para projetos maiores, você pode acompanhar muitos problemas em um quadro de projeto. Os Projetos do GitHub ajudam a organizar e priorizar seu trabalho, e você pode ler mais sobre eles neste documento [in this "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards).. Provavelmente, você não precisará de um quadro de projeto para suas atribuições, mas, quando passar para projetos ainda maiores, eles serão uma ótima maneira de organizar o trabalho da sua equipe! Você também pode vincular pull requests e problemas para mostrar que uma correção está em andamento e para fechar automaticamente o problema quando alguém mescla o pull request. Para saber mais sobre problemas e como vinculá-los aos seus pull requests, leia ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues)..

### Seu perfil de usuário
Sua página de perfil conta a história do seu trabalho por meio dos repositórios em que você está interessado, das contribuições que você fez e das conversas que você teve. Você também pode dar ao mundo uma visão única de quem você é com o seu README de perfil. Use seu perfil para mostrar aos futuros empregadores tudo sobre você! Para saber mais sobre o seu perfil de usuário e como adicionar e atualizar o seu README de perfil, leia ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Usando markdown no GitHub
Você pode ter percebido isso, mas é possível adicionar um pouco de estilo divertido às suas issues, pull requests e arquivos no GitHub. O ["Markdown"](https://guides.github.com/features/mastering-markdown/) é uma maneira fácil de formatar suas issues, pull requests e arquivos com uma sintaxe simples. Isso pode ser útil para organizar suas informações e torná-las mais fáceis de ler. Você também pode incluir gifs e imagens para ajudar a transmitir sua mensagem! Para saber mais sobre o markdown específico do GitHub, leia ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax).

### Interagindo com a comunidade do GitHub
A comunidade do GitHub é vasta. Existem muitos tipos de pessoas que usam o GitHub em seu dia a dia: estudantes como você, desenvolvedores profissionais, entusiastas trabalhando em projetos de código aberto e exploradores que estão entrando no mundo do desenvolvimento de software por conta própria. Existem várias maneiras de interagir com a comunidade do GitHub, mas aqui estão três lugares onde você pode começar.

### Favoritando repositórios
Se você achar um repositório interessante ou quiser acompanhá-lo, marque-o com uma estrela! Quando você marca um repositório com uma estrela, isso também é usado como um sinal para melhorar as recomendações em github.com/explore. Se você quiser voltar aos seus repositórios favoritos, pode fazer isso através do seu perfil de usuário. Para saber mais sobre como favoritar repositórios, leia ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars).

### Seguindo usuários
Você pode seguir pessoas no GitHub para receber notificações sobre suas atividades e descobrir projetos em suas comunidades. Quando você segue um usuário, a atividade pública dele no GitHub aparecerá no seu painel para que você possa ver todas as coisas legais em que ele está trabalhando. Para saber mais sobre como seguir usuários, leia ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).

### Explorando o GitHub Explore
O GitHub Explore é um ótimo lugar para fazer exatamente isso… explorar! 😊 Você pode encontrar novos projetos, eventos e desenvolvedores para interagir.

Você pode conferir o site do GitHub Explore em [at github.com/explore](https://github.com/explore). Quanto mais você interage com o GitHub, mais personalizada será a sua visualização no Explore.

## 📝 Próximos passos opcionais
Abra um pull request e informe ao seu professor que você concluiu este curso.
Crie um novo arquivo Markdown neste repositório. Conte o que você aprendeu e o que ainda está confuso! Experimente diferentes estilos!
Crie o README do seu perfil. Conte um pouco mais sobre você! O que você está interessado em aprender? Em que projetos você está trabalhando? Qual é o seu hobby favorito? Saiba mais sobre como criar o README do seu perfil no documento ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
Acesse o painel do usuário e crie um novo repositório. Experimente os recursos dentro desse repositório para se familiarizar com eles.
[Nos conte o que você gostou ou não gostou sobre o conteúdo deste curso.](https://support.github.com/contact/education). O que você gostaria de ver mais? O que seria interessante ou útil para a sua jornada de aprendizado?


## 📚  Recursos 
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)

