# gs-securing-web
Requisitos:

Java 8+;
Maven 3.5+;
Docker;
JMeter.

Segue abaixo as instruções para rodar o trabalho de Avaliação de Desempenho:

- Clonar o repositório do projeto;
>>SUGESTÃO: Como teste, rodem o projeto sem utilizar o docker antes;

- Instalar o Docker;
- Criar a imagem do Docker;
- Executar o comando:
	- docker run -p (Número da porta: Numero da porta) Codigo da imagem docker 

Após esses passos sua aplicação já estará rodando no docker;

Instale o JMeter;

Executando o JMeter:
- Ir até a pasta onde está instalado o JMeter (no meu caso está em cd /opt/jmeter/bin) e execute o comando no terminal:
- ./jmeter.sh

Ou execute o .jar do JMeter:

- Com o JMeter aberto, crie um Plano de Teste e dentro do Plano de Teste, crie um Grupo de Usuários;
- Adicione uma requisição HTTP ao plano de teste;
- A requisição HTTP deve conter o local onde está rodando seu projeto, no meu caso:
	- Protocolo HTTP: HTTP
	- Nome do Servidor ou IP: localhost
	- Número da Porta: 8080
- Adicionar um ouvinte do tipo Ver resultados em tabela ao plano de teste para ele pegar as estatísticas
Adicionar um outro ouvinte do tipo 
