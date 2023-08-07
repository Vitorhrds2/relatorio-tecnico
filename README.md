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

![Screenshot 2023-08-07 005346.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10859508-3e54-4494-969a-64ae87030be5/Screenshot_2023-08-07_005346.png)

![Screenshot 2023-08-07 010211.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/98da0fb0-b3d8-4da6-b3e6-2e0cd185ab75/Screenshot_2023-08-07_010211.png)

Primeiro estou fazendo algumas mudanças no repositório local, criei a pasta Screenshots e copiei todas as capturas de tela feitas para o relatório até agora para a nova pasta. Em seguida adiciono os arquivos da pasta Screenshots ao “staged” digitando “git add Screenshots/” na linha de comando pois o diretório foi criado, mas o Git ainda não está rastreando o conteúdo. Após fazer com que o conteúdo seja rastreado, faço o commit descrevendo quais foram as mudanças locais feitas e que serão enviadas para a origem. As atualizações são mostradas corretamente.