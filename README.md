# Projeto Smart-Home ESP32
Este é um projeto FullStack em que envolve a medição de temperatura, umidade e calculo da amplitude térmica de um comodo de casa, para saber se o como está saudável para se ficar.
## Stacks do Projeto.
### Embarcado (esp32)
 - Compilação em C++ usando Framework Arduino.
 - Requisições HTTP automatizadas.
 - Configuração de wi-fi do ESP32
 - Sensor utilizado: DHT-11
### Back-end (server)
- Utilização do MongoDB.
- Configuração de ORM usando Prisma.
- Configuração de rotas para API Rest.
- Rota para autenticação JWT.
- Middleware para autenticação JWT.
- Configurações de CORS e outros recursos de segurança.
### Front-end (web)
- Aplicação criada com ReactJS
- Proteção de rotas.
- Painel responsivo para diversos dispositivos.
- Framework utilizada: Ant Design.
- Aplicar persistência (Para o usuário não precisar logar sempre que entrará no sistema)
