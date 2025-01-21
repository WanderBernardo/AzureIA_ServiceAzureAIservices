# AzureIA_ServiceAzureAIservices
Objetivo desse item é realizar configuração do Serviço: Azure AI services

01 - Após logar no portal Azure. Criar um ``` Create a resource  ```
![image](https://github.com/user-attachments/assets/74e81e19-8c4d-42db-a3c6-9b93d4fe95bb)

02 - Na barra de pesquisa digitar a opção: ``` Azure AI services  ```. Cuidado que no meu caso apresentou duas opções com o mesmo nome, mas vão usar a opção que tem o ícone de nuvem.
![image](https://github.com/user-attachments/assets/8b61c68c-e269-4090-8d8b-b44b5d761077)

Clicar em botão: ``` Create ```
![image](https://github.com/user-attachments/assets/e658a628-f329-412f-a30f-4a9474610872)

03 - Iniciar a configuração criando o repositório onde será salvo nosso projeto, modelo, laboratório. Fique a vontade para chamar do melhor padrão para sua necessidade.
   * Subscription: é a conta que você está logado. É como se você a sua empresa. Repositótorio geral de tudo que é criado, a Pasta principal. Já vem preenchido de padrão, Esse padrão é criado automaticamente quando realiza o cadastro. Mas pode ser criado outras opções.
   * Resource group: é uma sub-repositório do "Subscription".
Imagina uma gaveteiro onde o gaveteiro inteiro é Subscriptiom e uma gaveta desse gaveteiro é o Resource group.
   * Region: basicamente, quer dizer em qual servidor da Microsoft você quer salvar(brasil, USA etc). Acredito que também determina a moeda que será cobrado por utilizar esse serviço.
   * Name: nome do seu projeto, modelo (Deve ser único)
   * Pricing tier: Selecionar a padrão do sistema.
   * Check box: "By checking this box I acknowledge that I have read and understood all the terms below". Deve marcar, pois precisa aceitar os termos e condições.
![image](https://github.com/user-attachments/assets/188b515a-fd4e-4973-9983-d3505ae796ad)

04 - Demais Abas: vamos manter o padrão, pois estamos realizando uma configuração basica e iremos excluir esse modelo no final. Então, click no botão ``` Review + create ``` para validar as configurações e depois click novamente no botão ``` Create ``` 
   * Networking: configuração de privacidade do seu modelo(Publico/Privado)
   * Identity: usar o controle de acesso
   * Tags: muito usado para criar filtros. Por exemplo: Quero fazer rateio para lançamento de custo por Departamento, então, cria as tags por departamento. Conforme sua necessidade.
![image](https://github.com/user-attachments/assets/8c6870b4-9686-4c93-b5c8-a049315f8e6b)
