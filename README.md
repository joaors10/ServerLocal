# ServerLocal
criação de um servidor local 

configurei meu próprio ambiente de desenvolvimento local usando a plataforma VMware e estabeleci uma conexão com o Postman. Esta configuração tem sido uma parte fundamental do meu trabalho como desenvolvedor, facilitando significativamente o processo de teste e aprimoramento de aplicativos e serviços.

A primeira etapa foi criar uma máquina virtual (VM) usando o VMware. Essa VM funciona como um ambiente isolado dentro do meu computador, onde posso emular um sistema operacional completo. Isso é extremamente útil, pois me permite executar aplicativos e serviços sem afetar o sistema operacional principal da minha máquina.

Dentro dessa VM, criei um servidor local. Este servidor é como o núcleo das minhas operações de desenvolvimento. Ele é responsável por receber solicitações de outros dispositivos, processá-las e fornecer respostas relevantes. Através dele, posso hospedar e testar aplicativos, APIs e serviços sem depender de servidores externos.

Em seguida, configurei uma conexão com o Postman, uma ferramenta que se tornou indispensável para mim. Com o Postman, consigo enviar facilmente solicitações HTTP para o meu servidor local, receber respostas e analisar os resultados. Isso agiliza o processo de teste e depuração, economizando muito tempo e esforço.

A principal vantagem dessa configuração é a capacidade de testar minhas APIs e serviços de forma isolada, sem a necessidade de infraestrutura de produção. Além disso, essa abordagem me permite iterar rapidamente em minhas aplicações e simular cenários de uso real, identificando problemas antes de implantá-las em um ambiente de produção.

Em resumo, a configuração do meu ambiente de desenvolvimento local com VMware e Postman tem sido essencial para meu trabalho como desenvolvedor. Ela oferece um ambiente controlado e eficiente para testar, aprimorar e depurar aplicativos e serviços, tornando o desenvolvimento mais suave e confiável.


todos os componentes da topologia de IoT.

![Descrição da imagem](https://raw.githubusercontent.com/fabiocabrini/fiware/main/FiwareDeploy.png)


Para a criação do servidor local utilizamos uma série de comandos:

(Após a instalação de todos os softwares necessários)

Passo 1 - no CMD da sua máquina virtual digitar "sudo apt-get install net-tools" para atualizar os pacotes do Linux

Passo 2 - digitar "sudo apt-get install net-tools" para o ifconfig identificar o IP da máquina virtual

Passo 3 - digitar "ifconfig" para ler o IP da máquina virtual

Passo 4 - digitar "sudo apt install git" para instalar o git

Passo 5 - Após a instalação do Docker, usamos o repositório de Fiware Descomplicado do Professor Cabrini. Digitar "git clone (*https://github.com/fabiocabrini/fiware*)

Passo 6 - digitar "cd fiware" para acessar a pasta do Fiware

Passo 7 - digitar "sudo docker compose up -d" para rodar os containers 

Passo 8 - digitar "sudo docker stats" para ver o status dos containers

Passo 9 - Fazer os testes no postman





ARQUIVOS NECESSÁRIOS PARA O FUNCIONAMENTO!

https://www.vmware.com/br/products/workstation-player/workstation-player-evaluation.html (para instalação da sua máquina virtual)

https://ubuntu.com/download/desktop (instalação do sistema usado para a demonstração (Ubuntu))

https://www.postman.com/downloads/ (instalação do Postman para a comunicação com o servidor)

https://github.com/fabiocabrini/fiware/blob/main/FIWARE.postman_collection.json (Fazer o download da collection de comandos do Postman no github do Fiware Descomplicado disponibilizado pelo professor Cabrini)

https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04-pt (para a instalação do Docker)
