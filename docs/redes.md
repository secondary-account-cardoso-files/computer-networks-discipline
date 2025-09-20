# 📘 Redes de Computadores - Material de Estudos

Este material reúne o conteúdo das **Aulas 1, 2 e 3** sobre Redes de Computadores, organizado em formato de estudo.

---

## 🔹 Aula 1 - Introdução às Redes

### O que são Redes de Computadores?
- Conjunto de dispositivos interligados para **compartilhamento de recursos** e **troca de informações**.
- Podem compartilhar: arquivos, impressoras, acesso à internet e programas.

### Concepção das Redes
- Problema inicial: incompatibilidade entre fabricantes.
- Solução: **Modelos de referência**.
  - **Modelo OSI (7 camadas)** – ISO, 1970.
  - **Modelo TCP/IP (4 camadas)** – Departamento de Defesa dos EUA.

### História da Internet
- **1969** – ARPANET criada pela ARPA/DARPA.
- **Década de 1980** – protocolos TCP/IP adotados como padrão.
- ARPANET tornou-se a espinha dorsal da **Internet moderna**.

### TCP/IP
- **TCP**: garante a entrega correta e ordenada dos dados.
- **IP**: responsável pelo endereçamento e roteamento.

### Internet, Intranet e Extranet
- **Internet**: rede pública mundial.
- **Intranet**: rede privada de uma organização, baseada em TCP/IP.
- **Extranet**: interligação de redes privadas (geralmente WAN).

### WWW (World Wide Web)
- Serviço principal da internet.
- Baseado em **hipertextos (HTML)** e acessado via **protocolos HTTP/HTTPS**.

### Vantagens e Desvantagens das Redes
- **Vantagens**: compartilhamento de recursos, cloud computing, acesso remoto.
- **Desvantagens**: vulnerabilidade a vírus, falhas em servidores, invasões.

---

## 🔹 Aula 2 - Componentes e Camada Física

### Componentes de uma Rede
- **Hosts**: dispositivos finais (PCs, servidores, celulares).
- **Dispositivos intermediários**: switches, roteadores, pontos de acesso.
- **Meios de transmissão**: cabos (UTP, coaxial, fibra) ou sinais sem fio.

### Software de Comunicação
- **Sistema Operacional de Rede (SOR)** – ex.: Unix, Linux, Windows Server.
- **Cliente de acesso**: software que conecta usuários à rede.

### Estações de Trabalho e Servidores
- **Servidor**: computador dedicado a fornecer recursos.
- **Estação de Trabalho**: dispositivo do usuário final.

### Camada 1: Física (Modelo OSI)
- Responsável por transmitir bits como sinais elétricos, ópticos ou de rádio.
- Exemplos: cabos UTP, coaxial, fibra óptica.

### Equipamentos de Rede
- **Passivos**: cabos, conectores.
- **Ativos**:
  - Hub (Camada 1)
  - Switch (Camada 2)
  - Roteador (Camada 3)

### Tipos de Redes
- **LAN** – rede local (Ethernet).
- **WAN** – rede geograficamente distribuída (Internet).

### Padronização
- **ISO, IEEE, ITU-T**: padrões globais.
- **IETF, ICANN, W3C**: internet.
- **ABNT**: adapta padrões internacionais ao Brasil.

---

## 🔹 Aula 3 - Camada de Enlace e Ethernet

### Camada 2: Enlace (Modelo OSI)
- Garante a **transmissão confiável entre dispositivos na mesma rede local**.
- Trabalha com **quadros (frames)** e **endereços MAC**.
- Responsável por: enquadramento, detecção de erros, controle de fluxo e acesso ao meio.

### Endereços MAC
- Identificador físico único da placa de rede (NIC).
- Gravado em **ROM**, com 48 bits (12 caracteres hexadecimais).

### Protocolos e Tecnologias da Camada 2
- **Ethernet (IEEE 802.3)**
- **Wi-Fi (IEEE 802.11)**
- **PPP** (conexões ponto a ponto)
- **HDLC** (WAN)
- **ARP** (resolução de IP para MAC)

### Protocolo Ethernet
- Padrão de redes locais.
- Utiliza CSMA/CD para evitar colisões.
- Evolução histórica:
  - 10BASE-T (10 Mbps)
  - 100BASE-T (Fast Ethernet)
  - 1000BASE-T (Gigabit Ethernet)
  - 10GBASE-T (10 Gbps)
  - 40/100/400 Gbps (backbones e datacenters).

### Switches
- **Switch L2**: trabalha com endereços MAC.
- **Switch L3**: inclui roteamento (endereços IP).
- **Gerenciáveis**: permitem VLANs, QoS, SNMP.

### VLANs (Virtual LANs)
- Criam **redes virtuais lógicas** dentro de um mesmo switch físico.
- Vantagens:
  - Segurança (isola departamentos)
  - Eficiência (reduz broadcast)
  - Flexibilidade e organização

### Topologias de Rede
- **Estrela** – dispositivos conectados a um ponto central.
- **Linear (barramento)** – todos no mesmo cabo.
- **Anel** – dados circulam entre os dispositivos.

---

## 📌 Conclusão
Compreender as **camadas do modelo OSI**, os **protocolos TCP/IP**, os **componentes de rede** e os **padrões Ethernet** é essencial para o estudo de redes.  
O próximo passo é praticar no **Cisco Packet Tracer**, simulando topologias com switches, roteadores e VLANs.
