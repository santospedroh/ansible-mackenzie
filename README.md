# ansible-mackenzie
Arquivos e exemplos das aula de Ansible - IaC curso DevOps Engineering and Cloud Solutions da Mackenzie.

[Documentação Ansible](https://docs.ansible.com/ansible/latest/index.html)

## Instalação do ansible amazon linux 2

Step 1 — Install the latest version of a packages: 
`$ sudo yum update -y`

Step 2 — Use the amazon-linux-extras command to install ansible: 
`$ sudo amazon-linux-extras install ansible2 -y`

Step 3 – Check Ansible Version: 
`$ ansible — version`

## Desafio 1
[Código fonte](desafios/install_packages_utils.yml)

Criar um playbook que seja responsável pela instalação de alguns pacotes vitais para a sustentação e manutenção dos sistemas operacionais, são eles:

* nmap
* telnet
* dig
* htop
* mtrace
* vim
* git
* curl

## Desafio 2
[Código fonte](desafios/install_apache_rename.yml)

Neste playbook o objetivo é subir um apache, remover a página padrão e colocar uma página contendo o seu nome e sobrenome como página de exebição padrão do apache.

---

Made with ♥ by Pedro Santos :wave: [Get in touch!](https://www.linkedin.com/in/santospedroh/)
