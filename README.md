# Checkpoint 4 ECCS
**Nome dos integrantes do grupo:** </br>
*Julia Azevedo Lins RM98690* </br>
*Luis Gustavo Barreto Garrido RM99210* </br>
*Luan Silveira Macéa RM98290* </br>
*Felipe Cortez dos Santos RM99750* </br>
*Victor Hugo Aranda Forte RM99667* </br>

**Turma: (ESPW)**

**Ano: 2023**

## Objetivo
Vocês foram contratados pela Vinheria Agnello para desenvolver um sistema de monitoramento a ser instalado no ambiente em que os vinhos são armazenados. O dono a Vinheria informou que a qualidade do vinho é influenciada diretamente pelas condições de temperatura, umidade e luminosidade do ambiente.
Dado que já auxiliamos anteriormente com a questão da luminosidade agora iremos fazer o pacote completo e seguir com a montagem de um sistema arduino que capture todas essas informções.

## Descrição do desafio
- Precisam medir a temperatura e umidade do ambiente, utilizando um sensor integrado DHT11, precisamos aprender a instalar e utilizar esse sensor no IDE do Arduino para ler a temperatura e umidade do ambiente.

## Integração com o Tago

Durante a execução deste projeto, realizamos a integração dos dados coletados pelo Arduino com a plataforma Tago. Essa integração foi essencial para armazenar e visualizar as informações de temperatura, umidade e luminosidade de forma organizada e acessível.
Configuramos um novo dispositivo para representar o Arduino. Nesse dispositivo, definimos três variáveis fundamentais para os nossos dados: temperatura, umidade e luminosidade. Essas variáveis representam os valores que o Arduino envia para o Tago.

Para estabelecer a comunicação entre o Arduino e o Tago, adaptamos o código do Arduino para enviar os dados simulados através da comunicação serial. Assim, os dados são "enviados" para o Tago, representando o processo real de transmissão das informações.

## Visualização no Dashboard
Com os dados chegando ao Tago, criamos um dashboard na plataforma para visualizar e acompanhar em tempo real as condições do ambiente de armazenamento dos vinhos. No dashboard, adicionamos widgets para representar as variáveis temperatura, umidade e luminosidade.

Personalizamos o layout do dashboard de acordo com as necessidades e preferências, utilizando gráficos e indicadores para fornecer uma representação visual clara e intuitiva das informações coletadas. Isso nos permitiu monitorar o ambiente de armazenamento de forma eficaz, garantindo que as condições ideais para a preservação dos vinhos estivessem sempre sob controle.

Essa integração com o Tago foi crucial para transformar os dados brutos coletados pelo Arduino em informações úteis e acessíveis, possibilitando uma gestão eficiente das condições ambientais da Vinheria Agnello.

![image](https://github.com/Grupo-Arthemis/Checkpoint_4_ECCS/assets/126623977/19d262e6-432d-4672-8711-7d1116ff201c)

![1000067985](https://github.com/Grupo-Arthemis/Checkpoint_4_ECCS/assets/126623977/13506b86-0e5b-4d4e-8375-c4e820db20c2)
