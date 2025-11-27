# resumo-lab-dio.me
Breve resumo sobre o aprendido na aula: Computação em nuvem - Laboratorio 


## O que eu aprendi?

### 1. Azure
É a plataforma de nuvem da Microsoft. Basicamente, é onde gerenciamos toda a infraestrutura (servidores, redes, bancos de dados) através de um portal web super completo.

### 2. Jump Server
É uma máquina intermediária usada para acessar servidores que estão em uma rede privada.
* **O problema:** Você precisa cuidar da segurança e manutenção dessa máquina extra, o que dá trabalho.

### 3. Azure Bastion
Aqui o jogo muda! O Bastion é um serviço gerenciado que substitui o Jump Server "manual".
* **A mágica:** Você acessa suas máquinas virtuais (RDP ou SSH) direto pelo navegador, usando HTTPS.
* **Vantagem:** Não precisa expor o IP da sua máquina para a internet pública. Muito mais seguro e prático.

### 4. Firewall na Nuvem
É o "porteiro" da sua rede. Ele filtra todo o tráfego de entrada e saída, garantindo que só passe o que for autorizado, protegendo seus recursos contra acessos indesejados.

---
## 🚀 Conclusão
Entendi que usar soluções nativas como o **Bastion** e **Firewall** simplifica a arquitetura e aumenta drasticamente a segurança, sem a dor de cabeça de gerenciar servidores de acesso manualmente.
