# curso_git_GitHub
# Repositório para curso de Desenvolvimento de Sistemas 

#O que é controle de versão? 
Um técnica que ajuda  a gerenciar o código-fonte de um plicação;
Registrando todas as modificações de código, podendo também reverter as mesmas; 
Criar versões de um software em diferentes estágios, podendo alterar facilmente entre elas; 
Cada membro da equipe pode trabalhar em uma versão diferente; 
Há ferramentas para trabalhar o controle de versão com: git e SVN;

#O que é git?
O sistema de controle de versão mais utilizado do mundo atualmente; 
O git é baseado em repositório, que contém todas as versões do código e também as cópias de cada desenvolvedor; 
Todas as operações do git são otimista por ter alto desempen
ho;
Todos os objetos do git são protegidos com criptografia para evitar alterações indesejadas e maliciosas; 
O git é um projeto de código aberto; 

#O que é repositório?
É onde o código será armazenado; 
Na maioria das vezes cada projeto tem um repositório; 
Quando criamos um repositórios estamos iniciando um projeto; 
O repositório pode ir para servidores que são especializados em gerenciar repos, com GitHub e Bitbucket; 
Cada um dos desenvolvedores do time pode baixar o repositório e criar versões diferentes em sua máquina; 

#Criando repositório

Para criar um repositório utilizamos o comando : git init; 
Desta maneira o git vai criar os arquivos necessários para inicializar-lo; 
Que estão na pasta oculta .git; 
Após este comando o diretório atual será reconhecido pelo git como um projeto e responderá aos seus demais comandos; 

#O que é  o GitHub?

É um serviço para gerenciar repositórios , gratuito e amplamente utilizado; 
Podemos enviar nossos projetos para o GitHub e disponibilizá-lo para outros devs;
O gitHub é gratuito tanto para projetos públicos com privados; 
vamos criar uma conta em: https://github.com 



#Comando para saber se existe repositório (Branch e Comint)
 git status  

#Enviando repositório para o GH

Podemos facilmente enviar nossos repos para o Github;
Precisa criar o projeto no GitHub, inicializar o mesmo no git em nossa máquina, sincronizar com o GH e enviar; 
E esta sequência que parece ser complexa é facilmente executada por poucos comandos;
Vale lembrar que só fazemos uma vez por projeto este fluxo;
Porém alguns dos comandos utilizados vão ser úteis ao longo do curso;

#Códigos para criar repositório

git init 
git add primeiro_arquivo
git commit -m "primeiro commit"
git branch -M main
remote add oringin https://github.com/EmillySSilva/curso_git_1.git
git push -u origin main  
