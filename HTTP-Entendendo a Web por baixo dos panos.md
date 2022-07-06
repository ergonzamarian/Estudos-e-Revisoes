# HTTP-Entendendo a Web por Baixo dos Panos

Uma comunicação tem duas partes bem conhecidas que chamamos de Cliente e Servidor. Este é um modelo arquitetural, ou seja, a internet inteira é baseada nesta arquitetura onde há um cliente que solicita e um servidor que responde.

Em qualquer comunicação é preciso existir algumas regras para que as duas partes consigam se entender com sucesso, esse conjunto de regras é basicamente um protocolo e neste caso chegamos a definição do HTTP (um protocolo que define as regras de comunicação entre cliente e servidor).

![image](https://user-images.githubusercontent.com/50181268/177465714-133156e9-5fe7-4e7a-926d-88d09d9d3921.png)

## HTTPS

O HTTPS é basicamente o HTTP comum, porém com uma camada adicional de segurança/criptografia que antes era SSL, mas posteriormente passou a ser também TLS. É muito comum que estas duas siglas sejam encontradas juntas como SSL/TLS por se tratarem da mesma questão de segurança. Sendo assim, temos dois termos:

HTTP: HyperText Transfer Protocol
SSL/TLS: Secure Sockets Layer / Transport Layer Security

*Ainda falta adicionar informações sobre endereços, domínio, DNS, portas e recursos - nos próximos dias irei adicionar*
## Rest
- Rest é um padrão arquitetural para comunicaçôes entre aplicações
- Ele Aproveita a estrutura do HTTP
- Recursos são definidos via URI
- Operações com métodos HTTP(GET/POST/PUT/DELETE)
- Cabeçalhos(Accept/Content-Type) são usados para especificar as representações(JSON, XML,...)
