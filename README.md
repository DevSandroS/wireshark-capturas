# Capturas Wireshark
#  Análises de Tráfego - Wireshark

Este diretório contém capturas de tráfego de rede realizadas como parte de projetos acadêmicos do curso de **Defesa Cibernética** na Universidade Estácio de Sá.  
Os arquivos podem ser abertos no **Wireshark** (versão 4.x ou superior).

---

##  Arquivos de Captura

### 1. Análise de Resolução DNS
**Arquivo:** `analise_resolucao_dns.pcapng`  
- Objetivo: observar e interpretar o funcionamento do protocolo DNS.  
- Pontos analisados:
  - Consultas (`Query`) e respostas (`Response`).
  - Resolução de nomes para endereços IPv4 e IPv6.
  - Tempo de resposta e análise de possíveis falhas de resolução.

---

### 2. Captura de Login Inseguro
**Arquivo:** `captura_login_inseguro.pcapng`  
- Objetivo: identificar credenciais transmitidas sem criptografia.  
- Pontos analisados:
  - Uso de protocolos sem TLS (ex.: HTTP, FTP, Telnet).
  - Visualização de credenciais em texto puro.
  - Riscos associados à transmissão insegura.

---

### 3. Captura de Tráfego - Computador Pessoal
**Arquivo:** `captura_trafego_pc_pessoal.pcapng`  
- Objetivo: analisar o tráfego real gerado por um computador pessoal em uso cotidiano.  
- Pontos analisados:
  - Protocolos comuns (HTTP, HTTPS, DNS, TCP, UDP).
  - Volume de tráfego por protocolo.
  - Identificação de padrões de acesso e possíveis comunicações suspeitas.

---

### 4. Seguindo uma Conversa TCP
**Arquivo:** `seguindo_conversa_tcp.pcapng`  
- Objetivo: acompanhar o fluxo de dados entre cliente e servidor utilizando o recurso "Follow TCP Stream".  
- Pontos analisados:
  - Sequência de pacotes e confirmação de entrega (ACK).
  - Estrutura da comunicação em nível de aplicação.
  - Identificação de padrões e possíveis problemas de retransmissão.

---

##  Ferramentas Utilizadas
- **Wireshark 4.x**
- Windows 11
- Linux Ubuntu/Debian (para simulação de tráfego e captura)

---

##  Como Abrir as Capturas
1. Instale o [Wireshark](https://www.wireshark.org/download.html).
2. Baixe os arquivos `.pcapng` desejados.
3. Abra no Wireshark e utilize filtros como:
   - `dns`
   - `http`
   - `tcp`
   - `ip.addr == <endereço>`

---

##  Licença
Este conteúdo está sob a licença MIT.  
Sinta-se livre para estudar, modificar e compartilhar.
