# O que é um container

É um agrupamento ou isolamento de recursos de uma aplicação e suas dependências e que compartilha o kernel do host(máquina virtual ou física) onde está sendo executado.

Eles são mais leves e integrados ao OS, ou seja, no container o Kernel do host(Máquina virtual ou física) é compartilhado e permite os acessos aos recursos do OS do host.

Eles são semelhantes a VMs só que com muito mais performance devido ao compartilhamento de recursos do Kernel do OS do host.

As imagens de containers são bem enxutas e possuem somente o que é necessário para executar a aplicação. A sobrecarga é bem menor quando comparamos com máquinas virtuais devido ao compartilhamento de recursos com o host.

Quando usamos máquinas virtuais, emulamos o novo OS e virtualizamos os hardwares e isso consume recursos da máquina. Mas, no container os recursos são compartilhados e por isso conseguimos criar mais containers do que máquinas virtuais em um host.

A portabilidade de container é outra coisa importante porque não importa onde foi criado. Ele irá executar em outro ambiente porque as dependências estão no próprio container.
