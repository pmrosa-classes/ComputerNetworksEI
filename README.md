# Redes e Comunicação de Dados 2021-2022 - Engenharia Informática
*Conteudos da Unidade Curricular de Redes de Computadores em exclusivo no curso de ***Engenharia Informática 1º ano*** do IADE/Universidade Europeia*

O objectivo da cadeira é dotar os alunos de conhecimentos da concepção das componentes protocolares das redes de computadores, bem como de algumas componentes práticas de redes TCP/IP e de equipamentos activos de rede.

Existem vários trabalhos a serem realizados para alunos em **avaliação continua**. Nas aulas teóricas os alunos deverão escolher um paper de investigação cientifica sobre temas da cadeira (Networking/IoT) e apresentar um resumo oralmente para a turma. Nas aulas práticas existem um cojunto de trabalhos práticos, de acordo com as matérias lecionadas nos laboratórios, incluindo um trabalho final de maior envergadura que consiste em implementar uma rede multi-serviço com divisão de tráfego, incluindo equipamentos ativos de rede, terminais e componentes IoT.

***Esforço requerido aos alunos: 6 ECTS, com 42 horas em aula e 126 horas fora do ambiente de aula***

### Horário 
| Dia | Hora | Turma |
| :-----------: | :-----------: | :----------: |
| Quarta-feira | 16:00 - 18:40 | T2 |
| Quinta-feira | 16:00 - 18:40 | T1 |

## Programa
### Aulas Teóricas
-	Introdução a Redes de Computadores & Aplicações 
-	Modelo OSI - tecnologias (ethernet, wifi, 5g)  e layer 2 - VLANs, etc
-	Modelo OSI - layer 3/routing
- Modelo OSI - layer 4/transporte
- Modelo OSI - camadas aplicacionais
- Internet (história/breve)
- TCP/IP arquitetura, Unicast, Multicast
-	TCP/IP pacotes IP / layer IP
-	TCP/IP ICMP, TCP, UDP / layer transporte
-	TCP/IP endereçamento IPv4 (inclui subnetting)
-	Protocolos (DNS, DHCP, HTTP, SNMP, etc)
-	IPv4 vs IPv6 enquadrar IPv6 como “obrigatório” nos dias de hoje
-	IPv6 features e endereçamento (inclui diferentes dimensões de redes e distinções na divisão com IPv4)
-	IPv6 e serviços (DNSv6 e DHCPv6)
-	IoT enquadrar com serviços de Cloud/associar a virtualização; Fog computing; necessidades de networking, armazenamento em IoT; exemplos práticos (smart homes, buildings, cities, veículos autónomos, etc); referencia a big data; referencia a segurança em IOT, nem que seja apenas com exemplos estilo Mirai botnet, etc)

*Slides disponiveis no Canvas.*

### Aulas Práticas:
- [Laboratórios práticos](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md) de TCP/IP (endereçamento IP, routing em máquinas virtuais e Cisco Packet Tracer)
- Inclui a utilização de máquinas virtuais e do simulador de rede Cisco Packet Tracer (ver [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#0-preparação-dos-laboratórios--pré-requisitos) quais os passos preparatórios para a realização dos laboratórios). Existe um [roteiro](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/roteiro-packet-tracer.md) para as aulas Packet Tracer;
- Apoio a realização do trabalho prático sobre Networking/IoT em Cisco Packet Tracer.

### Planeamento previsto (pode sofrer alterações!)[#planeamento]
| Aula | Data | Aula |
| :-----------: | :-----------: | :---------- |
| 01 | 14/17 fev | Apresentação; Introdução a Redes de Computadores & Aplicações; Introdução ao Modelo OSI  |
| 02 | 23/24 fev | Modelo OSI - tecnologias (ethernet, wifi, 5g)  e layer 2 - VLANs, etc;	Modelo OSI - layer 3/routing; Modelo OSI - layer 4/transporte; ***Laboratório 1 ([pré-requisito 0.1](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#01-instalação-do-cisco-packet-tracer-labs-13-e-6) para elaborar o laboratório)***  |
| 03 | 2/3 mar | Modelo OSI - camadas aplicacionais; Internet (história/breve); TCP/IP arquitetura, Unicast, Multicast; ***Laboratório 2 ([pré-requisito 0.1](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#01-instalação-do-cisco-packet-tracer-labs-13-e-6) para elaborar o laboratório)***|
| 04 | 9/10 mar | TCP/IP pacotes IP / layer IP; TCP/IP ICMP, TCP, UDP / layer transporte; TCP/IP endereçamento IPv4 |
| 05 | 16/17 mar | TCP/IP endereçamento IPv4 ; ***Laboratório 3 ([pré-requisito 0.2](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#02-instalação-de-máquinas-virtuais-em-equipamentos-dos-alunos-labs-24-e-5) para elaborar o laboratório)***|
| 06 | 23/24 mar | TCP/IP endereçamento IPv4 (inclui subnetting)|
| 07 | 30/31 mar | TCP/IP endereçamento IPv4 (inclui subnetting); Inicio do estudo de alguns Protocolos TCP/IP |
| 08 | 6/7 abr | ***Laboratório 4 ([pré-requisito 0.2](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#02-instalação-de-máquinas-virtuais-em-equipamentos-dos-alunos-labs-24-e-5) para elaborar o laboratório)*** |
|   | 13/14 abr | *Páscoa*|
| 09 | 20/21 abr | Protocolos (DNS, DHCP, HTTP, SNMP, etc) – essencial: saber exatemente como se resolvem os nomes; saber exatamente como se distribui endereçamento IP dinamicamente; IPv4 vs IPv6 enquadrar IPv6 como “obrigatório” nos dias de hoje|
| 10 | 27/28 abr | ***Laboratório 5 ([pré-requisito 0.2](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#02-instalação-de-máquinas-virtuais-em-equipamentos-dos-alunos-labs-24-e-5) para elaborar o laboratório)***|
| 11 | 4/5 mai | IPv6 features e endereçamento (inclui diferentes dimensões de redes e distinções na divisão com IPv4); IPv6 e serviços (DNSv6 e DHCPv6); Laboratório 5|
| 12 | 11/12 mai | IoT enquadrar com serviços de Cloud/associar a virtualização; Fog computing; necessidades de networking, armazenamento em IoT; exemplos práticos (smart homes, buildings, cities, veículos autónomos, etc); referencia a big data; referencia a segurança em IOT, nem que seja apenas com exemplos estilo Mirai botnet, etc); ***Laboratório 6 ([pré-requisito 0.1](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/AulasLabsPraticos.md#01-instalação-do-cisco-packet-tracer-labs-13-e-6) para elaborar o laboratório)***|
| 13 | 18/19 mai | Apoio ao trabalho prático Networking/IoT; (possível salvaguarda para a realização de laboratórios atrasados, caso seja possível)|
| 14 | 25/26 mai | Apresentações dos trabalhos práticos Networking/IoT|

### Sumários
Os sumários das aulas podem ser consultados [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/sumarios.md)

## Avaliação 

**NOTAS AVALIAÇÃO CONTINUA** [**AQUI**](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1200574372&single=true)

**NOTAS DOS EXAMES** [**AQUI**](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1428842774&single=true)

*Nota: Este cálculo é automático e será revisto antes do lançamento das classificações finais.*

### 1. Trabalho Teórico (15%)
O trabalho teórico baseia-se na apresentação de um paper. Valerá 15% para a classificação final da Unidade Curricular.Este trabalho é individual.
Consulte o [Enunciado](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/TrabT/TrabT.md) para efetuar a escolha do tema. 

Importante escolher até **18 de fevereiro**.

Depois de distribuídos os temas (até 20 de fevereiro) as datas de apresentação estarão disponiveis [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=467007833&single=true).

### 2. Trabalhos Práticos (45%)
Enunciados dos [Trabalhos Práticos](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/TrabsP/TrabsPraticos.md) da unidade curricular. Este trabalho é em grupo (3 alunos no máximo, 2 alunos no minimo).

Importante respeitar as datas de entrega. Não serão aceites adiamentos.

### 3. Teste Escrito (40%)
Teste Escrito unico a realizar na data marcada pela Secretaria Escolar.

### 4. Regras de Avaliacao Continua / Avaliação Final

De acordo com o **Regulamento Geral de Avaliação de Conhecimentos e Competências da Universidade Europeia.** publicado em DR a 30 de setembro de 2021, os alunos poderão fazer **avaliação continua** sendo que essa avaliação *inclui dois momentos de avaliação:*
- *A realização de vários instrumentos de avaliação durante o período letivo, os quais devem, obrigatoriamente, representar um mínimo de 30 % e um máximo de 70 %, na ponderação para o cálculo da classificação final da unidade curricular;*
- *A realização de uma prova final — teste escrito, coincidente em calendário letivo com a época normal da avaliação final.*
*Sendo a avaliação contínua aquela que, com caráter regular e constante, decorre durante todo o período letivo e reflete uma permanente interação entre o docente e o estudante.*

Nesta UC são instrumentos da avaliação contínua, o Trabalho Teórico (15%) individual que inclui apresentação à turma, os Trabalhos Práticos (45%) em grupo que no trabalho final inclui apresentação e o teste escritos final. 

**Nota Relevante:** Não são admitidos à realização da prova final de avaliação continua, os estudantes que obtiverem uma classificação inferior a 8 (oito) valores na média dos elementos de avaliação previstos, neste caso o Trabalho Teórico (15%) individual e os os Trabalhos Práticos (45%) em grupo. Poderá, no entanto, não realizar alguns trabalhos. 

Os alunos deverão ter uma taxa de presenças de 70% nas aulas. Excecionalmente 50% nos casos excecionados no regulamento.

Ainda de acordo com o mesmo regulamento, os estudantes têm o direito a optar pelo regime de **avaliação final** (avaliação por exame) que integra uma prova escrita, ou outros elementos, sobre a matéria toda lecionada. Esta avaliação final ainda não está completamente definida mas, ou terá também elementos distintos da prova escrita, ou terá 60% do valor teórico/prático escrito (portanto relacionado com os laboratórios e trabalhos práticos).

## Presenças

Os alunos podem acompanhar a percentagem de aulas a que assistem através da disponibilização pública, em Google Sheets, referente à sua turmas:
- Presenças da [T01](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1412701734&single=true)
- Presenças da [T02](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=933545162&single=true)

## Método Pedagógico
Aos alunos é fornecida toda a documentação utilizada durante as aulas, nomeadamente:
- Ficheiros pdf com os slides das aulas teóricas (Plataforma Canvas)
- Laboratórios Práticos com exercícios práticos para configuração dos equipamentos em simulador Cisco Packet Tracer e exercicios práticos com máquinas virtuais (neste repositório)

## Discord
Poderá ser util juntarem-se ao Discord da cadeira: https://discord.gg/HYQnMcuz (invite criado em 16.02.2022).

Para terem acesso aos canais do Discord devem alterar o vosso *nick* para PrimeiroUltimo nome no servidor e colocar uma mensagem em **#general** com "Numero - Primeiro&UltimoNome - Turma" para serem atribuídos os roles adequados.

## Grupos
Os trabalhos práticos são em grupo (3 alunos no máximo, 2 alunos no minimo) e deve ser preenchida a tarefa respetiva no Canvas até dia 25 de fevereiro: https://mycampus.pt/courses/7345/assignments/8738.

**ATUALIZAÇÃO (20220304): A contituição dos grupos já está disponível** [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=592821258&single=true) 

## Resumo do Calendário da UC
*(em atualização)*
- até 18 de fevereiro - Escolha dos temas para os trabalhos teóricos
- 20 de fevereiro - Publicação [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=467007833&single=true) da distribuição dos temas e datas de apresentação
- até 25 de fevereiro - Constituição dos grupos
- a partir de 2 de março iniciam-se as apresentações dos trabalhos teóricos 
- até 25 de março - Trabalho de Routing I - Ponderação: 7,5%
- até 22 de abril - Trabalho de Routing II - Ponderação: 7,5%
- até 6 de maio - Análise de ficheiro pcap - captura de pacotes com Wireshark/tcpdump - Ponderação: 5%
- até 20 de maio - Trabalho Cisco Packet Tracer / IoT - Ponderação: 25%
- 25 e 26 de maio - Apresentações dos Trabalhos Cisco Packet Tracer / IoT 

## Bibliografia
- Computer Networks, Tanenbaum, Andrew S., Prentice Hall http://books.google.pt/books?id=Pd-z64SJRBAC
- Engenharia de Redes Informáticas, Edmundo Monteiro, Fernando Boavida, Editora FCA

## Log
- 2022.07.01: Veja [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1200574372&single=true) as notas finais de Avaliação Continua.
- 2022.07.01: Veja [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1428842774&single=true) as notas dos Exames
- 2022.05.20: Veja [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1889860247&single=true) as classificações do Trabalho Prático de Captura de Tráfego
- 2022.04.06: Veja [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=1944461714&single=true) as classificações do Trabalho Prático Routing II
- 2022.05.05: Trabalho Prático de Captura de Tráfego já disponível [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/TrabsP/TrabP-CapturaPacotes.md)
- 2022.05.01: Laboratório de Captura de Tráfego já disponível [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/CapturaTrafegoRede.md)
- 2022.04.18: Trabalho Prático Routing II já disponível [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/TrabsP/TrabP-RoutingII.md)
- 2022.04.06: Veja [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=271380393&single=true) as classificações do Trabalho Prático Routing I
- 2022.03.22: Trabalho Prático Routing I já disponível [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/RoutingI-Exercicio.md)
- 2022.03.16: Laboratório de Routing II/Firewall já disponível [aqui](https://github.com/pmrosa-classes/ComputerNetworksEI/blob/main/AulasLabsPraticos/RoutingII.md)
- 2022.03.04: A contituição dos grupos já está disponível [aqui](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ7W8DWN7nqIehNu8iVlAwD82BJiTac2m0v2sZ4d56q-nybbrWNlSQ63RirHW5_wt4MFKfJLlfR3HNC/pubhtml?gid=592821258&single=true) 
