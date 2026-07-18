# MottaNetFix

O **MottaNetFix** é um utilitário de manutenção técnica desenvolvido para automatizar o diagnóstico e o reparo de problemas de conectividade de rede no Windows. O projeto consolida em um único executável os procedimentos mais eficazes para restaurar a integridade da sua conexão.

## Funcionalidades Detalhadas
* **1 - Reset Completo de Pilha TCP/IP e Cache:** Executa o reset dos protocolos de rede (Winsock e TCP/IP) para corrigir erros profundos de conexão e "fiação" digital corrompida.
* **2 - Limpeza de Cache DNS (FlushDNS):** Remove o histórico de resolução de endereços, resolvendo falhas onde sites não carregam ou redirecionam incorretamente.
* **3 - Renovação de IP:** Força o adaptador de rede a solicitar um novo endereço IP junto ao roteador (DHCP).
* **4 - Configuração de DNS Google:** Altera os servidores DNS para 8.8.8.8 e 8.8.4.4, visando maior estabilidade e velocidade na navegação.
* **5 - Diagnóstico de Conexão:** Realiza testes de ping sequenciais para o seu roteador local e para o servidor do Google, identificando instabilidades na rota.
* **6 - Testar Velocidade (Relatório Detalhado):** Mede a banda real de **Download**, **Upload** e a **Latência (Ping)** utilizando servidores profissionais, apresentando um relatório completo.

## Como usar
1. Baixe o executável `MottaNetFix.exe` na seção de [Releases](https://github.com/SEU_USUARIO/MottaNetFix/releases).
2. Clique com o botão direito sobre o arquivo e selecione **"Executar como Administrador"**.
3. Escolha a opção desejada no menu interativo. 
   * *Nota: A opção 1 (Reset Completo) requer que o computador seja reiniciado após a conclusão.*

## Requisitos Técnicos
* Windows 10 ou superior.
* Acesso à internet para testes de velocidade e atualizações de DNS.

## Licença
Este projeto é distribuído sob a licença **MIT**.

<img width="987" height="522" alt="image" src="https://github.com/user-attachments/assets/3840db3c-9a2d-4f50-90b1-cc8e9229d5ea" />
