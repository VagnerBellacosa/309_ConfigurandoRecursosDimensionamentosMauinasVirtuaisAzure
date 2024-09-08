# Máquinas virtuais:

## Computadores virtuais dentro de computadores

Uma máquina virtual, também conhecida como VM, não é diferente de qualquer outro computador físico, como um laptop, um smartphone ou um servidor. Ela tem CPU, memória, discos para armazenar os arquivos e pode se conectar à Internet, se necessário. Embora as partes que compõem o seu computador (chamadas de hardware) sejam físicas e tangíveis, as VMs costumam ser consideradas como computadores virtuais ou computadores definidos pelo software em servidores físicos, existindo apenas como código.

![Uma ilustração de computadores virtuais armazenados dentro de computadores físicos como código.](https://cdn-dynmedia-1.microsoft.com/is/image/microsoftcorp/what-is-a-virtual-machine_overview-img?resMode=sharp2&op_usm=1.5,0.65,15,0&wid=1280&hei=431&qlt=95)

## Como funciona uma máquina virtual?

Virtualização é o processo de criação de uma versão baseada em software ou "virtual" de um computador, com quantidades dedicadas de CPU, memória e armazenamento que são "emprestadas" de um computador host físico, como o seu computador pessoal, e/ou um servidor remoto, como um servidor no datacenter de um provedor de nuvem. Uma máquina virtual é um arquivo de computador (normalmente chamado de imagem) que se comporta como um computador de verdade. Ela pode ser executada em uma janela como um ambiente computacional separado, geralmente para executar um sistema operacional diferente, ou até mesmo para funcionar como a experiência completa do computador do usuário, como é comum nos computadores de trabalho de muitas pessoas. A máquina virtual é particionada do restante do sistema, o que significa que o software dentro de uma VM não pode interferir no sistema operacional primário do computador host.

## Para que são usadas as VMs?

Aqui estão algumas maneiras de usar máquinas virtuais:

- Criar e implantar aplicativos na nuvem.
- Experimentar um novo SO (sistema operacional), incluindo versões beta.
- Criar um novo ambiente para tornar a execução de cenários de desenvolvimento e teste mais simples e rápida para os desenvolvedores.
- Fazer backup de seu sistema operacional existente.
- Acessar dados infectados por vírus ou executar um aplicativo antigo instalando um sistema operacional mais antigo.
- Executar software ou aplicativos em sistemas operacionais para os quais eles não foram originalmente destinados.

## Quais são os benefícios do uso de VMs?

Embora as máquinas virtuais sejam executadas como computadores individuais com sistemas operacionais e aplicativos individuais, elas têm a vantagem de permanecer completamente independentes umas das outras e do computador host físico. Um software chamado hipervisor, ou Virtual Machine Manager, permite que você execute sistemas operacionais diferentes em máquinas virtuais diferentes ao mesmo tempo. Isso torna possível executar VMs do Linux, por exemplo, em um sistema operacional Windows, ou executar uma versão anterior do Windows em um sistema operacional Windows mais atual.

E, como as VMs são independentes umas das outras, elas também são extremamente portáteis. Você pode mover uma VM de um hipervisor para outro hipervisor em um computador completamente diferente quase instantaneamente.

Devido à sua flexibilidade e portabilidade, as máquinas virtuais oferecem muitos benefícios, como:

- **Economia de custos** – a execução de vários ambientes virtuais por meio de uma única infraestrutura significa que você pode reduzir significativamente o volume ocupado pela infraestrutura física. Isso aumenta seus resultados, diminuindo a necessidade de manter tantos servidores e economizando em custos de manutenção e eletricidade.
- **Agilidade e velocidade** – ativar uma VM é relativamente fácil e rápido, e muito mais simples do que provisionar um ambiente totalmente novo para seus desenvolvedores. A virtualização torna o processo de execução de cenários de desenvolvimento e teste muito mais rápido.
- **Tempo de inatividade reduzido** – as VMs são muito portáteis e fáceis de passar de um hipervisor para outro em um computador diferente, o que significa que são uma ótima solução para backup, caso o host fique inativo inesperadamente.
- **Escalabilidade** – as VMs permitem que você escale seus aplicativos mais facilmente, adicionando mais servidores físicos ou virtuais para distribuir a carga de trabalho entre várias VMs. Como resultado, você pode aumentar a disponibilidade e o desempenho de seus aplicativos.
- **Benefícios de segurança** – como as máquinas virtuais são executadas em vários sistemas operacionais, o uso de um sistema operacional convidado em uma VM permite que você execute aplicativos de segurança questionável, protegendo o sistema operacional do host. As VMs também permitem melhor análise forense de segurança e costumam ser usadas para estudar vírus de computador de maneira segura, isolando-os para evitar riscos para o computador host.