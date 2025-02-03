# Desenvolvimento de um site como requisito para aprovação na disciplina projetos-1.

#1 - Baixar o programa git, basta pesquisar no google

#2 - crie no seu computador uma pasta onde será desenvolvido o seu projeto, abra a pasta com o programa "VS Code"

#3 - Para escolher o nome de usuário que irá aparecer em seus porjeto. Acesse a linha de comando do "VS code" - TERMINAL -, e digite a seguinte linha de código: git config --global user.name "aqui você digita o nome que você escolheu" depois aperte o botão ENTER,  se tudo ocorrer bem, o sistema não retornará nenhuma mensagem

#4 - Para configurar o endereço de email associado a sua conta. Acesse a linha de comando do "VS code" - TERMINAL -, e digite a seguite linha de código: git config --global user.emal seu-email@email.com ,  aperte o botão ENTER,  se tudo ocorrer bem, o sistema não retornará nenhuma mensagem

# 5 - PARA BAIXAR UM REPOSITÓRIO QUALQUER PARA O SEU COMPUTADOR

  a) No perfil git hub que você quer baixar, escolha o projeto e depois clique no botão "CODE", após clicar no botão "CODE" irá aparecer um link, você deve copiá-lo;

  b) no seu computador, crie uma pasta onde irá receber o repositório escolhido, ou utilize uma pasta já existente ou a que você criou nos item anterior, copie o caminho da pasta, geralmente o caminho começa com "c:";

  c) entre no prompt de comando do computador, no caso estamos utilizando o windows 11 e digite o comando: cd e clique com o botão direito do mouse, será colado no cursor - tela- o caminho da pasta que você criou e copiou o caminho  para receber o repositório "conforme item anterior", pressione a tecla ENTER; ou se você tiver conhecimento, navegue até a pasta que você criou e acesse ela.

  d) Verifique se o caminho descrito no prompt de comando relaciona-se a pasta que você criou para receber o repositório, se estiver correto, digie o comando: git clone - lembre-se de dar um espaço depois de cada palavra -  e cole o link referente ao passo 5 -a, ou seja, o link do repositório que voocê quer copiar, após, pressione a tecla ENTER; será copiado para a sua máquina/ repositório local, todo o projeto referente ao link que você copiou.

# 6 - PARA CRIAR UM REPOSITÓRIO DO ZERO

a) abra o "VS code" e acesse a pasta onde você irá desenvolver seu projeto, ou crie uma pasta por meio da opção do "VS code" chamada New Folder;

b) crie os arquivos, e desenvolva o seu código, quando estiver satisfeito, no terminal do "VS Code" digite: git init e pressione a tecla ENTER - se tudo ocorrer bem, irá retornar uma mensagem informando o local onde o repositório foi iniciado, mais ou menos assim: "Initialized empty Git repository in C:/Users/..."

c) No terminal do "VS code" digite: git add e o nome do arquivo, ou adicione um espaço e um ponto após o comando add "git add ." e pressione a tecla ENTER;

d) No terminal do "VS code" digite: git commit -m "digite uma mensagem, geralmente a mensagem se refere a alteração que voçê fez" e precione a tecla ENTER;

e) No canto esquerdo da tela do "VS Code", abaixo do símbolo de uma lupa clique no ícone chamado "SOURCE CONTROL";

f) Clique no botão chamado "PUBLISH BRANCH", assim, será criado um repositório remoto no guithub contendo todos os arquivos, em alguns casos é solicitado que se faça login na conta do github.

# 7 - Manipulação de conteúdos no repositório remoto a partir do repositório local através do "VS CODE"

a) Após desenvolver o código, ou após o trabalho do dia digite:

1) git add e o nome do arquivo, ou adicione um espaço e um ponto após o comando add "git add .", para adicionar as mudanças;
2) git commit -m "digite uma mensagem, geralmente a mensagem se refere a alteração que voçê fez", para salvar as mudanças no seu repositório local;
3) git push para enviar as mudanças do repositório local para o repositório remoto;

Atenção:
 O comando git pull - BAIXA TODOS OS ARQUIVOS DO REPOSITÓRIO REMOTO PARA O REPOSITÓRIO LOCAL - BAIXA E SUBSTITUI A PASTA DO SEU COMPUTADOR PARA A PASTA QUE ESTÁ DO GITHUB -, porém, antes de usar o: git pull, utilize o comando: git fetch, e depois: git diff origin/master  para listar todas as diferenças entre o repositório local e o repositório remoto. Se a qualquer momento o prompt do terminal do "VS code" ficar travado, aperte a tecla "Q", que será destravado.
