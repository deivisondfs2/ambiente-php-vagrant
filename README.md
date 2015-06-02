## Ambiente de desenvolvimento PHP constru�do com Vagrant

### Introdu��o
Esse projeto automatiza a cria��o de um ambiente para desenvolvimento com PHP.
Fique � vontade para expandir essas configura��es de acordo com suas necessidades.

### Requisitos
* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)

### O que tem na VM?
* Ubuntu 14.04
* PHP 5.5
* Apache
* MySQL
	* usu�rio: root
	* obs: esse usu�rio n�o possui senha.
* Postgres
	* usu�rio: postgres
	* obs: esse usu�rio n�o possui senha (na verdade a senha pode ser qualquer coisa).
* Git
* Composer
* cURL
* MCrypt
* ImageMagick

### Iniciando sua m�quina virtual
* Clone o reposit�rio do projeto;
* No terminal, acesse o diret�rio raiz do projeto clonado e execute o comando "vagrant up";
* Aguarde o Vagrant finalizar a constru��o da m�quina virtual. A VM ser� provisionada com o [Puppet](https://puppetlabs.com).