Passo 1: Instalação do Ubuntu 14.04 LTS (Suporte de Longo Prazo)
------------------------------------------------------------------

Preferencialmente a Edição Servidor amd64

http://www.ubuntu.com/download

* Ubuntu Servidor 14.04 LTS amd64 tem todos os pacotes necessários.
* Ubuntu Servidor 14.04 LTS tem algumas pequenas diferenças comparadas com a versão 12.04 LTS, 
  principalmente a configuração de sítios eletrônicos do Apache, que agora fica em 
  /etc/apache2/sites-available/000-default.conf e a raiz padrão de documentos Web que agora está em /var/www/html. 
  Este documento foi atualizado para refletir estas mudanças.
* Você pode utilizar tanto o VI (editor leve) quanto o VIM (editor pesado), entretanto, se você deseja utilizar 
  o VIM você precisa instalá-lo::
  
    sudo apt-get install vim
    
* Comandos do VI ou do VIM

  #. Para editar um arquivo pressione a tecla "Insert"
  #. Para finalizar a edição pressione a tecla "Esc"
  #. Para gravar o arquivo pressione ":w"
  #. Para sair do editor pressione ":q"
  #. Você também pode gravar e sair ":wq"

* No Ubuntu, o usuário padrão, a conta criada durante a instalação, não possui direito de instalar/escrever em muitos diretórios. 
  No tutorial abaixo, utilizaremos o termo "sudo", que significa "super usuário faça" (*super user do"), antes da maioria dos comandos.
  
