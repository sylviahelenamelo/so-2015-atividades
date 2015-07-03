======================
Glossário de comandos
======================

:Disciplina: Fundamentos de Sistemas Operacionais
:Professor: Jurandy Soares
:Nome: Sylvia Helena Cortez de Melo
:Matrícula: 20121144010273
:Data: 01/07/2015

cat
  Imprime na tela no conteúdo do arquivo, é útil quando se deseja ler ou abrir uma arquivo .txt.
        Ex.: cat sylvia.txt


cd
  Serve para acessar e/ou mudar de diretório; é muito utilizado para navegação entre pastas do computador.
        Ex.: cd /home/sylvia/downloads
             cd /home/20121144010273/downloads
             cd ..: um diretório acima do atual;

cowsay
  Troca mensagens com animações de vacas e outros.
        Ex.: cowsay -l: exibe todos os tipos de animações;
             cowsay "oi": manda a mensagem com a vaca pro próprio terminal;
             cowsay -f vader "oi": manda uma vaquinha darth vader pro próprio terminal;
             cowsay -f vader "ola" | write jurandy: envia a mensagem para alguém;


echo
  Permite exibir textos na tela e também exibe toda a estrutura de um diretório em ordem alfabética.
        Ex.: echo 'Olá': envia para a saída da tela a expressão Olá;
             echo /sylvia/: lista tudo que está no diretório sylvia, em ordem alfabética;
             echo $Sylvia: lista tudo que está na variável de ambiente: $Sylvia;


env
  Lista todas as variáveis de ambiente.
        Ex.: env


exit
  ou Ctrl D;
  Possibilita sair do local atual do usuário;
        Ex.: exit


help
  Descrição do comando


HISTTIMEFORMAT="%d/%m/%y
  Descrição do comando


hostname
  Comando que exibe o nome da máquina. 
        Ex.: hostname;


ifconfig
  Permite configurar as interfaces de rede, sendo o comando utilizado na iniciação do sistema para configuração dessa interfaces; informa o IP.
        Ex.: sudo ifconfig sylvia (p/ exibir o estado e as informações da interface);
             sudo ifconfig 10.209.1.158 (?);


last
  Mostra todas as informações referentes a entradas e saidas de usuários do sistema.
        Ex.: last;
             last -a: exibe o nome da máquina onde foi efetuado o login ou logout;
             last -b: exibe o endereço IP;


lastb
  Exibe informações sobre tentativas mal sucedidas de se logar no sistema.
        Ex.: lastb


ls
  Exibe os arquivos que estão dentro da pasta (diretório), na qual o usuário se encontra.
        Ex.: ls ou ls -l (informações mais detalhadas dos arquivos);


mkdir
  Cria diretórios no local onde o usuário se encontra.
        Ex.: mkdir sylvia (criou a pasta sylvia);


nome="fulano
  Descrição do comando


passswd
  Altera a senha do usuário que logo depois é repetida para confirmação.
  Ex.: sudo passwd sylvia (altera a senha de sylvia);


pwd
  Exibe a pasta (diretório) atual onde o usuário se encontra.
        Ex.: pwd

set
  Descrição do comando


tree
  Descrição do comando


tty
  Descrição do comando


vim
  Descrição do comando


wait
  Descrição do comando


wall
  Descrição do comando


which
  Descrição do comando


while
  Descrição do comando


who
  Mostra quais usuários estão logados no sistema.
        Ex.: who
             who -m: mostra o nome dos usuários logados no sistema;
             who -q: mostra a quantidade de usuários logados no sistema;


whoami
  Mostra quem sou eu: O usuário.
        Ex.: whoami
             sylvia


    write
        Descrição do comando

