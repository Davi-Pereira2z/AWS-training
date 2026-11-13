# Criação e Gerenciamento de uma Instância EC2

Nesta atividade, foi criada uma instância Amazon EC2 utilizando o sistema operacional Amazon Linux. Durante o processo, foram realizadas configurações de rede e segurança, instalação automática de um servidor web, consulta do endereço IP público, paralisação da instância, alteração de sua capacidade computacional e do armazenamento, reinicialização e, por fim, a exclusão da instância.

## Etapas realizadas

### 1. Acessando o Amazon EC2

Acessei o serviço Amazon EC2 e iniciei o processo de criação de uma nova instância.

![Acessando o EC2](./imagens/1.png)

---

### 2. Configurando o nome e o sistema operacional

Defini o nome da instância como **Web Server** e selecionei a imagem do sistema operacional **Amazon Linux**.

![Configurando a instância](./imagens/2.png)

---

### 3. Configurando o tipo da instância e a rede

Configurei o tipo da instância como **t3.micro**, além das configurações de acesso, rede e grupo de segurança.

![Configurações da instância](./imagens/3.png)

---

### 4. Ajustando configurações adicionais

Configurei opções adicionais da instância, como o comportamento de desligamento e a proteção contra encerramento.

![Configurações adicionais](./imagens/4.png)

---

### 5. Configurando o servidor web

Adicionei um script de **User Data** para instalar e iniciar automaticamente um servidor web HTTP e criar uma página HTML.

![Script de User Data](./imagens/5.png)

---

### 6. Criando a instância

A criação da instância EC2 foi concluída com sucesso.

![Instância criada](./imagens/6.png)

---

### 7. Verificando a instância em execução

Verifiquei que a instância **Web Server** estava em execução, com o status **Running**.

![Instância em execução](./imagens/7.png)

---

### 8. Consultando o endereço IPv4 público

Acessei os detalhes da instância para identificar o **endereço IPv4 público**, utilizado para acessar o servidor pela internet.

![Detalhes da instância](./imagens/8.png)

---

### 9. Paralisando a instância

Paralisei a instância, alterando seu estado de **Running** para **Stopping**.

![Paralisando a instância](./imagens/9.png)

---

### 10. Alterando a capacidade computacional

Após paralisar a instância, iniciei o processo de alteração do seu tipo, modificando de **t3.micro** para **t3.small**.

![Alterando o tipo da instância](./imagens/10.png)

---

### 11. Modificando o armazenamento

Também modifiquei as configurações do volume de armazenamento **EBS**, alterando sua capacidade.

![Modificando o volume](./imagens/11.png)

---

### 12. Confirmando a modificação do volume

A solicitação de modificação do volume foi realizada e o processo de alteração foi iniciado.

![Modificação do volume](./imagens/12.png)

---

### 13. Reiniciando a instância

Após realizar as modificações, iniciei novamente a instância e verifiquei que ela estava em execução com o novo tipo **t3.small**.

![Instância reiniciada](./imagens/13.png)

---

### 14. Excluindo a instância

Por fim, encerrei a instância EC2, finalizando a atividade e excluindo os recursos utilizados.

![Instância encerrada](./imagens/14.png)

---

### 15. Inicialização do Amazon Linux

Esta imagem mostra a tela de inicialização do sistema operacional **Amazon Linux** utilizado na instância EC2.

![Inicialização do Amazon Linux](./imagens/i-0534b8144bf80d79e.jpg)
