# Relatório Técnico - Tutorial do GitHub

## Introdução

Neste relatório técnico, documentaremos o progresso do tutorial do GitHub, conforme apresentado no W3 Schools. O objetivo deste tutorial é aprender os conceitos fundamentais do GitHub e praticar as principais operações, como criar repositórios, fazer commits, trabalhar com branches e fazer pull requests.

## Etapa 1: GitHub Get Started

### Objetivo

O objetivo desta etapa é fornecer uma introdução ao GitHub e seus conceitos básicos.

### Resultados

![Screenshot 2023-08-06 212243.png](https://github.com/Vitorhrds2/relatorio-tecnico/Screenshots/Screenshot_2023-08-06_212243.png)

![Screenshot 2023-08-06 212307.png](https://github.com/Vitorhrds2/relatorio-tecnico/Screenshots/Screenshot_2023-08-06_212307.png)

![Screenshot 2023-08-06 212432.png](https://github.com/Vitorhrds2/relatorio-tecnico/Screenshots/Screenshot_2023-08-06_212432.png)

![Screenshot 2023-08-06 213049.png](https://github.com/Vitorhrds2/relatorio-tecnico/Screenshots/Screenshot_2023-08-06_213049.png)

![Screenshot 2023-08-06 221914.png](https://github.com/Vitorhrds2/relatorio-tecnico/Screenshots/Screenshot_2023-08-06_221914.png)

Nesta etapa eu crio um novo repositório no GitHub, defino um nome, deixo público e deixo marcada a opção de criar um arquivo README.

Depois de criar o repositório eu, decido cloná-lo dentro da pasta Documents/GitHub utilizando o comando ‘git clone <URL do repositório>’ na linha de comando do windows, para fins de verificação vou na opção “Code” copio a URL de configuração do Git local, após isso, digito o comando ‘git remote add origin <URL do repositório.git>’ e vejo que preciso realmente estar dentro de um repositório Git, ou seja, que haja uma pasta .git com as configurações necessárias.

Depois de verificar, acesso o repositório local que havia clonado e digito o comando ‘git init’ para reinicializar o repositório existente, depois disso ocorre a inserção do comando ‘git remote add origin <URL do repositório.git>’ e verifica-se que o repositório realmente já existe.

Para enviar o branch main para a URL de origem e defini-lo como o branch remoto padrão é necessário digitar o comando ‘git push --set-upstream origin master’ e verifica-se o resultado na tela do prompt de comando no qual diz “Está tudo atualizado”.

Como eu já estava autenticado, não apareceu a janela de autenticação no navegador que normalmente apareceia no final desta etapa.

### Conclusão

Percebi que como já havia interagido com o Git e o GitHub anteriormente, não tive dificuldades nesta etapa, porém percebi que estava autenticado com minha conta pessoal do GitHub e para limpar as credenciais que estavam salvas foi preciso entrar na opção executar do Windows e digitar “control /name Microsoft.CredentialManager” > Acessar a opção Credenciais do Windows > Procurar e e expandir a opção “github:https://github.com” e remover a credencial salva para depois autenticar novamente com o login correto.
