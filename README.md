# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Site Cloner ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- URL para clone: http://www.facebook.com

### Resutados

Após iniciado o setoolkit, a nevegação foi realizada como descrito acima:
 1) Social-Engineering Attacks
   2) Website Attack Vectors
     3) Credential Harvester Attack Method
       2) Site Cloner
          http://facebook.com

![set1](https://github.com/user-attachments/assets/b3a679af-ca58-487e-af58-fd9d7fa17e8d)
Na imagem, o ip da máquina atacante está em evidência como uma página web aberta na porta 80.

![phishing1](https://github.com/user-attachments/assets/f1feb4af-c558-43a4-914b-258baec64a28)
A vítima acessa inadvertidamente a página maliciosa.

![phishing2](https://github.com/user-attachments/assets/c054cab7-45dd-43b7-8e47-161fc525b20e)
Após inserir seu login e senha, a vítima é redirecionada para a página original para evitar suspeitas.

![set2](https://github.com/user-attachments/assets/434a0f5a-bee5-477a-9573-e004ce5b1f38)
Por fim, o setoolkit captura os dados inseridos na página maliciosa.


Você encontrará no repositório o arquivo desafio_phishing.txt, que conta com o registro do terminal da execução da ferramenta.
