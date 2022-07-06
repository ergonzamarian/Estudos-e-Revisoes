# HTTP-Entendendo a Web por Baixo dos Panos

Uma comunicação tem duas partes bem conhecidas que chamamos de Cliente e Servidor. Este é um modelo arquitetural, ou seja, a internet inteira é baseada nesta arquitetura onde há um cliente que solicita e um servidor que responde.

Em qualquer comunicação é preciso existir algumas regras para que as duas partes consigam se entender com sucesso, esse conjunto de regras é basicamente um protocolo e neste caso chegamos a definição do HTTP (um protocolo que define as regras de comunicação entre cliente e servidor).

## Rest
- Rest é um padrão arquitetural para comunicaçôes entre aplicações
- Ele Aproveita a estrutura do HTTP
- Recursos são definidos via URI
- Operações com métodos HTTP(GET/POST/PUT/DELETE)
- Cabeçalhos(Accept/Content-Type) são usados para especificar as representações(JSON, XML,...)
