# Relatório Técnico

# Relatório Técnico - Tutorial do GitHub

## Introdução

Neste relatório técnico, documentaremos o progresso do tutorial do GitHub, conforme apresentado no W3 Schools. O objetivo deste tutorial é aprender os conceitos fundamentais do GitHub e praticar as principais operações, como criar repositórios, fazer commits, trabalhar com branches e fazer pull requests.

## Etapa 1: GitHub Get Started

### Objetivo

O objetivo desta etapa é fornecer uma introdução ao GitHub e seus conceitos básicos.

### Resultados

![Screenshot 2023-08-06 212243.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20212243.png)

![Screenshot 2023-08-06 212307.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20212307.png)

![Screenshot 2023-08-06 212432.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20212432.png)

![Screenshot 2023-08-06 213049.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20213049.png)

![Screenshot 2023-08-06 221914.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20221914.png)

Nesta etapa eu crio um novo repositório no GitHub, defino um nome, deixo público e deixo marcada a opção de criar um arquivo README.

Depois de criar o repositório eu, decido cloná-lo dentro da pasta Documents/GitHub utilizando o comando ‘git clone <URL do repositório>’ na linha de comando do windows, para fins de verificação vou na opção “Code” copio a URL de configuração do Git local, após isso, digito o comando ‘git remote add origin <URL do repositório.git>’ e vejo que preciso realmente estar dentro de um repositório Git, ou seja, que haja uma pasta .git com as configurações necessárias.

Depois de verificar, acesso o repositório local que havia clonado e digito o comando ‘git init’ para reinicializar o repositório existente, depois disso ocorre a inserção do comando ‘git remote add origin <URL do repositório.git>’ e verifica-se que o repositório realmente já existe.

Para enviar o branch main para a URL de origem e defini-lo como o branch remoto padrão é necessário digitar o comando ‘git push --set-upstream origin master’ e verifica-se o resultado na tela do prompt de comando no qual diz “Está tudo atualizado”.

Como eu já estava autenticado, não apareceu a janela de autenticação no navegador que normalmente apareceia no final desta etapa.

### Conclusão

Percebi que como já havia interagido com o Git e o GitHub anteriormente, não tive dificuldades nesta etapa, porém percebi que estava autenticado com minha conta pessoal do GitHub e para limpar as credenciais que estavam salvas foi preciso entrar na opção executar do Windows e digitar “control /name Microsoft.CredentialManager” > Acessar a opção Credenciais do Windows > Procurar e e expandir a opção “github:https://github.com” e remover a credencial salva para depois autenticar novamente com o login correto.

## Etapa 2: GitHub Edit Code

### Objetivo

O objetivo desta etapa é aprender a fazer edições em um repositório do GitHub usando a interface web.

### Resultados

![Screenshot 2023-08-06 230406.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20230406.png)

![Screenshot 2023-08-06 231559.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20231559.png)

![Screenshot 2023-08-06 231740.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20231740.png)

![Screenshot 2023-08-06 231847.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20231847.png)

Ao cliar na opção de editar(ícone de lápis), fui apto a utilizar o editor de código do GitHub e dentro do editor, alterei o texto contigo anteriormente pela seção e etapa 1 do relatório.

Depois de realizar a alteração, cliquei no botão “Commit changes“ > Coloquei uma mensagem breve de commit e a descrição estendida e com a opção “commit directly to the main branch” selecionada, clico em “Commit changes” e ao voltar na página prinncipal do repositório foi possível observar a mudança.

### Conclusão

Foi uma operação bem simples e autoexplicativa, não houveram dificuldades e nem anomalias ao realizar um novo commit através da interface e editor web do GitHub.

## Etapa 3: Pull from GitHub

### Objetivo

O objetivo desta etapa é aprender como fazer um pull (puxar) do código de um repositório remoto para o repositório local.

### Resultados

![Screenshot 2023-08-06 233834.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20233834.png)

![Screenshot 2023-08-06 233847.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20233847.png)

![Screenshot 2023-08-06 233942.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20233942.png)

![Screenshot 2023-08-06 234037.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20234037.png)

![Screenshot 2023-08-06 234510.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20234510.png)

![Screenshot 2023-08-06 234541.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20234541.png)

![Screenshot 2023-08-06 234600.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-06%20234600.png)

![Screenshot 2023-08-07 003105.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20003105.png)

![Screenshot 2023-08-07 003205.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20003205.png)

Primeiro eu ful na linha de comando do windows e inserio o comando “git fetch origin” para realizar uma busca no repositório de origem.

Após fazer a busca, realizei uma verificação do status do repositório através do comando “git status” e com isso foi possível perceber que o repositório local estava com um commit(entrega) pendente em relação à origem para estar atualizado. Foi eferecida a opção de dar “pull(puxar)” para atualizar o branch local, porém só farei isto posteriormente ao testar o comando merge(mesclar).

Ao inserir o comando “git log origin/main” consegui verificar os “commits” feitos com seus respectivos nomes, autores, e também datas e horários realizados.

Em seguida verifico as diferenças entre a origem do repositório na branch main e o repositório local utilizando o comando “git diff origin/main”. O que está em vermelho nas linhas de código não se encontra no local mas se encontra na origem, o que está em verde se encontra em ambos.

Depois de ver as diferenças, realizo um “merge” para mesclar os repositórios no meu local, percebe-se que as alterações foram feitas, com 37 inserções e 2 exclusões.

Depois dos passos anteriores, verifiquei o arquivo que foi atualizado, percebi a mudança e após inserir o comando “git status” noto que o “branch” local está atualizado com o “origin/main” e sem novos commits.

Para finalizar a etapa, realizo um novo commit direto pela interface gráfica do GitHub e digito “git pull origin” na linha de comando do windows. “Pull” é uma combinação do fetch(buscar) e merge(meclar), tendo o intuito de atualizar o repositório local pegando novas inserções de código, pastas e arquivos do repositório de origem.

### Conclusão

Por mais que utilizar o pull para obter novas atualizações de um repositório seja bem prático, é possível perceber que outras etapas podem ser seguidas e sendo assim notar diversas informações, como versões existente de um código para assim escolher qual deseja-se puxar ou apenas verificar quando os “commits” foram realizados. No mais, foi bem interessante notar a diferença de uso das interfaces e linha de comando para controlar versões de um projeto.

## Etapa 4: Push to GitHub

### Objetivo

O objetivo desta etapa é aprender como fazer um push (enviar) do código do repositório local para o repositório remoto no GitHub.

### Resultados

![Screenshot 2023-08-07 005346.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20005346.png)

![Screenshot 2023-08-07 010211.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20010211.png)

![Screenshot 2023-08-07 035008.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20035008.png)

![Screenshot 2023-08-07 041055.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20041055.png)

Primeiro estou fazendo algumas mudanças no repositório local, criei a pasta Screenshots e copiei todas as capturas de tela feitas para o relatório até agora para a nova pasta. Em seguida adiciono os arquivos da pasta Screenshots ao “staged” digitando “git add Screenshots/” na linha de comando pois o diretório foi criado, mas o Git ainda não está rastreando o conteúdo. Após fazer com que o conteúdo seja rastreado, faço o commit descrevendo quais foram as mudanças locais feitas e que serão enviadas para a origem. As atualizações são mostradas corretamente.

Depois de fazer o “commit” pude verificar o status do “branch” local, que estava com um commit à frente da origem, e sendo recomendado a realizar o “push(empurrar)” para que atualizasse o “branch” principal da origem.

Realizando o “push” obtemos como resultado o número de objetos, o peso dos arquivos o nome do “commit” e de qual “branch” para qual foi feito o "push”.

### Conclusão

É uma etapa simples mas no meu caso foi um pouco trabalhoso pois decidi subir as imagens presentes no [README.md](http://README.md) para uma pasta dentro do diretório de origem e precisei ver como colocar o links das imagens corretamente e como adicionar os arquivos novos corretamente. No mais é um processo simples e que envolve fazer as alterações, “commitar”, verificar o status e realizar o push para o repositório e “branch” desejados.

## Etapa 5: GitHub Branch

### Objetivo

O objetivo desta etapa é aprender sobre branches (ramificações) no GitHub e como eles são usados para desenvolver recursos isoladamente.

### Resultados


![Screenshot 2023-08-07 042208.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20042208.png)

![Screenshot 2023-08-07 042219.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20042219.png)

![Screenshot 2023-08-07 042313.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20042313.png)

![Screenshot 2023-08-07 042449.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20042449.png)

![Screenshot 2023-08-07 042759.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20042759.png)

![Screenshot 2023-08-07 042208.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/badfd89f-f273-45e3-a350-91dc2e442c1c/Screenshot_2023-08-07_042208.png)

![Screenshot 2023-08-07 042219.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10b2dd85-4fe5-4ff3-8082-5ca98bbc1a3d/Screenshot_2023-08-07_042219.png)

![Screenshot 2023-08-07 042313.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/35624b22-44be-4a48-96b3-2968625f8d30/Screenshot_2023-08-07_042313.png)

![Screenshot 2023-08-07 042449.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/355f07fd-7b5f-497d-86db-24ec5efba84e/Screenshot_2023-08-07_042449.png)

![Screenshot 2023-08-07 042759.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bb210d05-4385-41a2-ac10-5589cb743421/Screenshot_2023-08-07_042759.png)

Nesta etapa eu criei uma nova “branch” baseada na main. Dentro dela, realizei uma alteração no final do arquivo [README.md](http://README.md) através do editor de código do GitHub, comparei as alterações com a versão anterior e fiz o “commit” direto na branch-secundaria.

### Conclusão

Criar uma ramificação pela interface do GitHub é bem simples, realizar alterações e verificá-las não envolve muitos recursos, uma nova ramificação é útil para criar cópias de um projeto e com isso trabalhar em versões diferentes sem interferir nas outras versões.

## Etapa 6: Pull Branch from GitHub

### Objetivo

O objetivo desta etapa é aprender como fazer um pull de uma branch específica do repositório remoto para o repositório local.

### Resultados

![Screenshot 2023-08-07 044011.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044011.png)

![Screenshot 2023-08-07 044042.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044042.png)

![Screenshot 2023-08-07 044102.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044102.png)

![Screenshot 2023-08-07 044129.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044129.png)

![Screenshot 2023-08-07 044223.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044223.png)

![Screenshot 2023-08-07 044302.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044302.png)

![Screenshot 2023-08-07 044313.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20044313.png)

![Screenshot 2023-08-07 044011.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7ca6db58-8494-4512-846b-30feeec99aee/Screenshot_2023-08-07_044011.png)

![Screenshot 2023-08-07 044042.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/39a6fd03-2640-4253-baa9-09cb89628cdd/Screenshot_2023-08-07_044042.png)

![Screenshot 2023-08-07 044102.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b25a3404-9979-489a-962f-8ed8cebe63cf/Screenshot_2023-08-07_044102.png)

![Screenshot 2023-08-07 044129.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3c166535-d995-4850-9895-b17c51937dc4/Screenshot_2023-08-07_044129.png)

![Screenshot 2023-08-07 044223.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/54e5fae4-ca3c-46d9-8acd-a6b12013cd4c/Screenshot_2023-08-07_044223.png)

![Screenshot 2023-08-07 044302.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/610818a0-b49c-4a2d-947b-136e34c92b6c/Screenshot_2023-08-07_044302.png)

![Screenshot 2023-08-07 044313.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f5745696-fad0-46ef-8e11-eb712d860c18/Screenshot_2023-08-07_044313.png)

Depois de criar uma branch através da interface, podemos ver que ela está disponível utilizando a linha de comando. Utilizo o “git pull” para puxar as alterações existente e logo percebo que uma nova branch foi criada.

Utilizando o “git status” percebe-se que a “branch” main é o meio de comparação com o reposítório de origem.

Para confirmar as “branches” que tenho e estou trabalhando no momento, utilizo o comando “git branch”.

Como resultado é visível que não aparece a branch-secundaria que foi criada na seção 5, apenas a “branch” main é mostrada pois aqui consultamos apenas as locais. Para ver tanto as “branches” locais quantos as remotas, digito “git branch -a”.

Verifiquei que a branch-secundaria está disponível remotamente, mas não no git local. Utilizando o comando “git checkout branch-secundaria” trocamos de “branch” de trabalho para a nova que foi criada. Para verificar se está tudo atualizado eu digito “git pull” novamente.

Utilizando o “git branch” de novo, verifiquei que ambas ramificações estão disponíveis localmente e atualmente a branch-secundária é a de trabalho.

### Conclusão

Foi um processo muito interessante pois entendi o valor de puxar uma branch ramota para trabalhar localmente nela, isso me possibilita trabalhar de forma muito mais prática com outras pessoas. O tutorial foi bem intuitivo e relevante.

## Etapa 7: Push Branch to GitHub

### Objetivo

O objetivo desta etapa é aprender como fazer um push do código da branch local para o repositório remoto no GitHub.

### Resultados

![Screenshot 2023-08-07 051102.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051102.png)

![Screenshot 2023-08-07 051138.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051138.png)

![Screenshot 2023-08-07 051215.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051215.png)

![Screenshot 2023-08-07 051336.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051336.png)

![Screenshot 2023-08-07 051507.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051507.png)

![Screenshot 2023-08-07 051631.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051631.png)

![Screenshot 2023-08-07 051718.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051718.png)

![Screenshot 2023-08-07 051805.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20051805.png)

![Screenshot 2023-08-07 052445.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20052445.png)

![Screenshot 2023-08-07 052240.png](https://github.com/Vitorhrds2/relatorio-tecnico/blob/main/Screenshots/Screenshot%202023-08-07%20052240.png)

Nesta seção eu criei uma nova “branch” para enviar ao GitHub. Para criar utilizo o comando “git checkou update-readme”.

Atualizei o arquivo [README.md](http://README.md) com as duas seções anteriores e depois verifiquei o status com o comando “git status”. Aqui foi possível verificar que as alterações foram lidas, e fui alertado que as mudanças não foram ao “staging” para serem “commitadas”. Para isso preciso utilizar o comando git add README.md.

Depois de deixar o README no “staging”, preciso verificar o status do git com “git status”, então foi perceptível que as alterações estavam prontas para serem “commitadas”. Para fazer o commit, é como das outras vezes, utilizei ‘ “git commit -m "Atualização do README da branch-secundaria” ’.

De pois do “commit”, fui realizar o push com: “git push origin update-readme”. Em seguida foi possível ver o processo das alterações sendo enviadas como solicitações de “push” e agora existem 3 branches no repositório.

Ao clicar em “Compare & pull request” vi as alterações feitas com comparações. Após verificar as alterações estive apto a criar o “pull request(solicitação para puxar)” que é quando proponho mudanças ao repositório.

Sendo meu próprio repositório, eu mesmo pude fazer a mesclagem do “pull request” solicitado.

Depois de ter feito o “merge(mesclar)” alguns elementos que antes estavam verde, ficaram roxos e a junção foi confirmada pela interface.

Para evitar confusões e excesso de arquivos, resolvi deletar a ramificação “update-reademe” e “branch-secundaria”, pois agoratudo está na ramificação principal, a “main”.

### Conclusão

A funcionalidade de mandar “branhes” para o GitHub entrega inúmeras possibilidades de contribuição dentre equipes de forma que uma ou mais pessoas responsáveis pelo repositório aceitem novas adições ou modificações de forma segura e com o máximo controle de versões remoto.

## Conclusão Geral

De forma geral o tutorial foi de grande valia, me trouxe segurança em utilizar o Git e o GitHub através da linha de comando, durante a realização do tutorial percebi outros efeitos que podem ocasionar falhas ou atrasos na execução de um comando e consegui resolvê-los. É perceptiível o valor do controle de versões de projetos, eles precisam estar seguros, especialmente em desenvolvimento escalado, no qual múltiplas equipes trabalham entregando partes diferentes de uma mesma plataforma, aplicação, protótipo, dentre outros. Foi um conhecimento que será aplicado em projetos futuros, de forma recorrente. Estive utilzando controle de versão de forma que não garantisse um backup seguro de cada alteração realizada, por menor que fosse, e agora planejo unir a prática mais recorrente de controle de versão à uma estrutura mais limpa e organizada aos projetos futuros.
Foi um processo muito interessante pois entendi o valor de puxar uma branch ramota para trabalhar localmente nela, isso me possibilita trabalhar de forma muito mais prática com outras pessoas. O tutorial foi bem intuitivo e relevante.
