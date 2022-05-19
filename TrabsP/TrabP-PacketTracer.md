# Trabalho Prático - Packet Tracert Networking/IoT (20%)

*Este trabalho prático deve ser realizado no simulador Cisco Packet Tracer utilizado nas aulas práticas*

**Enunciado temporário. Pode sofrer alterações**

# A Smart Campus: Smart Factory & Smart Buildings

## Implementação de todas as componentes de uma rede de suporte a uma Empresa, incluindo equipamentos IoT associados aos edificios inteligentes da empresa.

**Descrição genérica do trabalho:**
1.	O objetivo principal é concretizar uma rede de uma empresa que interliga vários equipamentos de rede e equipamentos IoT (Internet of Things).
2.	A empresa está sediada num *Campus* de dimensão significativa no Oeste de Portugal.
3. Atualmente é composta por quatro contruções (edifício A, edifício B e fábrica C e Datacenter D) mas o *Campus* tem capacidade para um crescimento significativo em número de edificios;
4.  A utilização de equipamentos IoT para gerir os espaços é fundamental para a empresa, com vista a contribuir positivamente para o meio ambiente e ao mesmo tempo reduzir os custos e aumentar a qualidade de vida no *Campus*. Esse foi também o motivo de ter feito um quarto pequeno edificio exclusivamente para Datacenter.
5.	Os dois primeiros edifícios (A e B) têm 3 andares que alojam um total de ~200 funcionários, estando previsto a duplicação do número de funcionários nos próximos 5 anos, caso a evolução da empresa se mantenha nos atuais níveis. 
6.	Tendo os edifícios uma largura de cerca de 100m, o backbone dos edifícios é duplo, ou seja, dois bastidores por piso (devidamente espaçados), interligados a um lugar central no piso 1 do mesmo edifício. 
7.	O Datacenter fica localizado num quarto pequeno edificio, construído para o efeito, onde estão também centralizadas as comunicações.
8.	A infraestrutura central de rede e o acesso à Internet estão dentro do Datacenter.
9.	Os edifícios têm ainda a infraestrutura necessária para interligar diversas componentes de IoT para suporte à gestão inteligente do campus e dos edifícios.
10. Todos os pisos têm disponíveis 4 pontos de acesso sem fios por piso.
11. A empresa têm ainda atualmente muitos funcionários a trabalhar remotamente devido à pandemia.

**Objetivos a concretizar:**
1.	Elaborar um relatório com a descrição da empresa e tecnologias utilizadas, incluindo diagramas de rede.
2.	Para tal deve escolher um negócio imaginário e caracterizar a empresa de forma adequada e justificada (máximo de duas páginas A4).
3.	O objetivo principal do trabalho é planear, instalar e configurar a rede necessária para servidores, postos de trabalho, portáteis/telemoveis, equipamentos IoT (que suportem a gestão inteligente do Campus e dos Edificios) e capacidade de acesso remoto para tele-trabalho.
4.	Os mapas de rede deverão ser claros e organizados, eventualmente utilizando anotações necessárias para explicações necessárias.
5.	Deverão quantificar o número de switchs a colocar nos pisos dos edifícios, tendo em conta o número de funcionários da empresa e uma margem que considerem interessante para crescimento imediato. Os funcionários estão espalhados de forma muito semelhante pelos pisos 2 e 3. Os pisos 1 dos edifícios têm cerca de 50% dos funcionários dos restantes pisos em ambos os edifícios uma vez que há espaços ludicos e de refeição em ambos os locais.
6.	Deverão escolher os equipamentos mais adequados a colocar nos pontos centrais dos edifícios e no Datacenter, sabendo que apenas existe routing no Datacenter.
7.	Os equipamentos devem ter as portas necessárias configuradas e com respetivas descrições.
8.	A escolha dos modelos dos equipamentos e sua respetiva configuração a nível de hardware é da responsabilidade dos grupos, que devem ser capazes de justificar as suas escolhas (*conselho: não inventar muitoo em relação ao utilizado nos laboratórios práticos*).
9.	Devem ser usadas, pelo menos, as seguintes VLANs, dependendo muito do negócio escolhido a necessidade de existirem mais:
```
VLAN 10 – 192.168.10.0/24 – 2001:1:1:10::/64 – servidores (DHCP, DNS)
VLAN 11 – 192.168.11.0/24 – 2001:1:1:11::/64 – servidores (Web, Mail, IoT)
VLAN 20 – 192.168.20.0/22 – 2001:1:1:20::/64 – IoT
VLAN 30 – 192.168.30.0/24 – 2001:1:1:30::/64 – Apoio Administrativo/Financeiro
VLAN 31 – 192.168.31.0/24 – 2001:1:1:31::/64 – Recursos Humanos
VLAN 32 – 192.168.32.0/24 – 2001:1:1:32::/64 – Marketing/Comunicação
VLAN 33 – 192.168.33.0/24 – 2001:1:1:33::/64 – Direção
VLAN 35 – 192.168.35.0/24 – 2001:1:1.35::/64 – Equipamentos portáteis / rede sem fios
VLAN 40 – 192.168.40.0/24 – 2001:1:1:40::/64 – Laboratórios (ou algo adequado ao negócio)
VLAN 41 – 192.168.41.0/24 – 2001:1:1:41::/64 – Investigação (ou algo adequado ao negócio)
VLAN 50 - 192.168.50.0/22 - 2001:1:1:50::/64 - Fábrica
VLAN 60 – 192.168.60.0/22 – 2001:1:1:60::/64 – Acesso Remoto
```
10.	Devem ser utilizados vários servidores no Datacenter:
```
VLAN 100 - srv01 – 10.10.10.11 - DHCP  – com configuração de todas as pools necessárias para postos de trabalho e equipamentos IoT.   
VLAN 100 - srv02 - 10.10.10.12 - Servidor Primário DNS - Deverão ser colocados os registos dos nomes de todos os servidores no DNS.
VLAN 100 - srv03 - 10.10.10.13 - Servidor VPN
VLAN 100 - srv04 – 10.10.11.11 - Servidor de HTTP - com página levemente customizada da Instituição
VLAN 100 - srv05 – 10.10.11.12 - Servidor de Mail – exemplificar com 10 contas de mail
VLAN 100 - srv06 – 10.10.11.13 - Servidor de Registo de IoT - para todos os equipamentos IoT da empresa.
```
*Nota: VLAN100 modificado no final do prazo do trabalho, não é relevante ser esta VLAN mesmo.*

11.	Sendo edifícios inteligentes, devem ser implementadas as seguintes funcionalidades:
-	Gerir a **temperatura** interna em cada edifício através de um display adequado.
-	Os edifícios têm **sistema de deteção de incêndios** em todos os pisos. Caso seja detetado um incendio deve tocar uma **sirene** e **ligado o sistema de extinção de incêndios**.
-	Os edifícios têm **sensores de CO2**. Uma vez detetado um valor superior a 75% as **janelas devem ser abertas** e a **extração de ar deve ser ligada**. Todo o sistema deve ser desligado quando voltarem a valores inferior a 60%.
-	As portas de entrada dos edifícios têm **controlo por RFID**. Só os utilizadores com cartões válidos devem poder entrar (exemplificar com alguns casos). Sempre que algum cartão inválido seja lido, deve ser ligada uma sirene.
12.	Criar uma rede externa, que simula o acesso à Internet, interligando com o router da empresa. Devem ser criados dois websites: portal.pt e google.pt (que deverão existir nos servidores de DNS). Deve ser configurada a interligação dessa rede com o router da empresa através de uma rede de 30 bits.

**Notas:**
- Colocar alguns computadores pessoais a título de exemplo em cada piso. Não é, obviamente, necessário todos os computadores pessoais.
- Quaisquer informações ausentes podem ser resolvidas pelos alunos, justificando as suas escolhas na apresentação a realizar.
- Todos os equipamentos devem fazer ping a todos os outros (não são implementados mecanismos de segurança que, em produção, deveriam ser considerados).
- A configuração de todos os equipamentos deve ser efetuada em dual stack (Ipv4 e IPv6).

**Datas:**
- Verificar data de entrega/apresentação no calendário da cadeira.

**Entregáveis:**
- Apresentação em PowerPoint/GoogleSlides/etc
- Descrição da empresa;
- Ficheiro(s) packet tracer;
- Notas adicionais para a correta avaliação por parte dos Docentes.

**Deve entregar um unico ficheiro ZIP com a identificação do grupo e do trabalhoo: Gxx-TrabPacketTracerI.zip**
