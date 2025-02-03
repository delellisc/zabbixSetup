# Configuração de ambiente Zabbix
Repositório dedicado à configuração de um ambiente Zabbix para um projeto de alta disponibilidade da matéria de Sistemas Distribuídos.

## Instalação da máquina virtual

### Download da ISO
Antes de realizar a instalação da máquina virtual, é preciso selecionar e realizar o download do sistema operacional desejado. Para esse projeto, a distribuição Linux Debian 12 foi escolhida. Sua ISO está disponível no site [debian.org](https://www.debian.org/download) e pode ser baixada ao acessar a página e clicar no link abaixo:
![alt text](./imagens/b.png)

### Criação da máquina no VirtualBox
Ao abrir o VirtualBox, a seguinte tela irá ser carregada:
![alt text](./imagens/image.png)

Para criar uma nova máquina virtual, é preciso clicar no botão "New", disposto no menu horizontal com ícones. Após clicar nessa opção, a seguinte tela será exibida:
![alt text](./imagens/image-1.png)

Nessa tela, é preciso inserir informações como o nome da máquina virtual, Debian12Server no meu caso, e o caminho para ISO, que como foi baixada recentemente, se encontra na pasta Downloads:
![alt text](./imagens/a.png)

OBS.: caso a opção "Skip Unattended Installation" não seja selecionada, a instalação será feita de maneira automática, instalando a versão desktop da distribuição com os pacotes padrões e o GNOME como 

Ao clicar em "Next", a próxima tela irá ser disposta, requisitando informações do sistema. Como essa será uma instalação mínima, as opções padrões foram mantidas (2GB RAM e 1 CPU):
![alt text](./imagens/image-2.png)

Por fim são requisitadas as informações de disco do sistema, que também foram mantidas as opções padrão, criando um novo disco virtual de 20GB:
![alt text](./imagens/image-3.png)

Ao informar todas as informações necessárias, uma tela de confirmação é exibida, dando-nos a oportunidade de revisar os parâmetros fornecidos:
![alt text](./imagens/image-4.png)

Ao clicar em "Finish", a máquina virtual será criada, sendo disposta na tela inicial do VirtualBox:
![alt text](./imagens/image-5.png)

### Instalação do Debian 12 Server
Embora a máquina virtual tenha sido criada, sua instalação ainda não foi realizada. Para dar início à instalação, é preciso iniciar a máquina virtual clicando no botão "Start":
![alt text](./imagens/c.png)

Ao clicar no botão "Start", a máquina virtual será inicializada e a tela inicial de instalação do Debian será exibida:
![alt text](./imagens/image-6.png)

![alt text](./imagens/image-7.png)

![alt text](./imagens/image-8.png)

![alt text](./imagens/image-9.png)

![alt text](./imagens/image-10.png)

![alt text](./imagens/image-11.png)

![alt text](./imagens/image-12.png)

![alt text](./imagens/image-13.png)

![alt text](./imagens/image-14.png)

![alt text](./imagens/image-15.png)

![alt text](./imagens/image-16.png)

![alt text](./imagens/image-17.png)

![alt text](./imagens/image-18.png)

![alt text](./imagens/image-19.png)

![alt text](./imagens/image-21.png)

![alt text](./imagens/image-22.png)

![alt text](./imagens/image-23.png)

![alt text](./imagens/image-24.png)

![alt text](./imagens/image-25.png)

![alt text](./imagens/image-26.png)

![alt text](./imagens/image-27.png)

![alt text](./imagens/image-28.png)

![alt text](./imagens/image-29.png)

![alt text](./imagens/image-31.png)

![alt text](./imagens/image-32.png)

![alt text](./imagens/image-33.png)

![alt text](./imagens/image-34.png)

![alt text](./imagens/image-35.png)

![alt text](./imagens/image-36.png)

![alt text](./imagens/image-37.png)

![alt text](./imagens/image-38.png)

![alt text](./imagens/image-39.png)

![alt text](./imagens/image-40.png)

![alt text](./imagens/image-41.png)

![alt text](./imagens/image-42.png)

![alt text](./imagens/image-43.png)

![alt text](./imagens/image-44.png)

![alt text](./imagens/image-45.png)

![alt text](./imagens/image-46.png)

## Configuração do Zabbix

### Instalação de pacotes necessários