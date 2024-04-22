# Teste de Infraestrutura
Teste de Infraestrutura QuiteJá

 Configuração de uma Máquina Linux na AWS, Implantação de um Servidor Nginx e Aplicação Web.

**Objetivo:**  
 Este teste tem como objetivo avaliar a capacidade do candidato em configurar uma instância Linux na AWS, implantar um servidor Nginx, e uma aplicação web.

# Tarefas:

 **1. Configuração da Instância EC2:**  
 - Crie uma instância EC2 na AWS com o sistema operacional Linux, utilizando o nome de usuário "devops".  

**2. Criação do Usuário "devops":**  
 - Configure um usuário não privilegiado chamado "devops" na instância EC2 e configure-o para execução de comandos sem a necessidade de sudo.

**3. Instalação do Docker e Docker Compose:**  
 - Instale o Docker e o Docker Compose na instância EC2.  

**4. Implantação do Servidor Nginx (Em docker):**  
- Configure e inicie um servidor Nginx na ultima versão na instância EC2.  
- Verifique se o Nginx está funcionando corretamente.  

**5. Implantação da Aplicação :**  
- Implante uma aplicação na instância EC2.  
- Você deve utilizar arquivo docker-compose.yml fornecido via GitHub. (https://github.com/quiteja/infrastructure-test/blob/develop/docker-compose.yml)  

**6. Configuração do Nginx como Proxy Reverso:**  
- Configure o Nginx como um proxy reverso para encaminhar o tráfego para a aplicação Python.  
- Verifique se o Nginx está roteando corretamente o tráfego para a aplicação.  

**7. Documentação:**  
- Documente cada etapa do processo, incluindo comandos utilizados e observações importantes.
- Adicionar o link (endereço de acesso da aplicaçã0) na documentação.

# Critérios de Avaliação:

Configuração correta da instância EC2 na AWS, utilizando o nome de usuário "devops".    

Criação e configuração adequada do usuário não privilegiado "devops".    

Instalação correta do Docker e Docker Compose na instância EC2.  

Implantação bem-sucedida do servidor Nginx e da aplicação na instância EC2.   

Configuração adequada do Nginx como proxy reverso para a aplicação Python.  

Documentação clara e completa de cada etapa do processo.

# Observações:  

O candidato pode escolher a distribuição Linux de sua preferência.  

É obrigatório que o candidato utilize práticas de segurança ao configurar a instância EC2 e o acesso à aplicação.  

Preste atenção aos grupos de segurança da AWS durante a configuração da instância EC2 e do Nginx.  

Certifique-se de não liberar mais permissões do que o necessário e de restringir o acesso apenas aos recursos essenciais para acessar a aplicação. Isso é fundamental para garantir a segurança da infraestrutura e minimizar o risco de exposição a possíveis vulnerabilidades.  

Todo o processo deve ser realizado na instância Free Tier da AWS. Certifique-se de acompanhar os custos,para evitar cobranças inesperadas.  

Caso tenha algum problema que não consiga resolver na implementação lembre-se de descrever na **documentação**.
