# dio-cognitive-search

## Azure AI Search
É preciso criar um serviço de pesquisa IA e consigurar alguns detalhes dele, bem como:
  * Assinatura: Além da assinatura é necessário informar um grupo de recursos existente nesta assinatura.
  * Detalhes da Instância: Nele precisa ser criado um nome para este serviço, preferenciamente um nome ue seja bem sujestivo sendo de facil entendimento qual seu proposito, escolher uma localização e o preço. O preço vai interferir diretamente com varias coisas como armazenamento, unidades disponíveis para pesquisa, replicas entre outros e conseguentemente quanto mais recursos disponiveis mais caro será.

## Azure AI Service
Além de criar um serviço de pesquisa de IA é necessário criar um serviço de IA. Assim como o **Serviço de Pesquisa** é necessário informar as mesma coisas como *assinatura* e *detalhes da instância*. Porém, além destas informações, é necessário preencher uma check box informando que você leu e entendeu todos os termos.

## Conta de Armazenamento

Para criar a conta de armazenamento é necessário informar alguns detalhes do projeto, sendo eles:
  * Assinatura: Além da assinatura é necessário informar um grupo de recursos existente nesta assinatura.
  * Detalhes da Instância: Nele precisa ser criado um nome para a Conta de Armazenamento, a região, o serviço primário, o desempenho e a redundância.

Os dados utilizados neste serviço serão utilizados pelo serviço de IA para a busca das informações. Essas buscas podem ser de "n" variaveis como Regão, produto, serviço, atendimento, marca e etc. O tipo de busca será determinada somentem, e exclusivamente, com base no dados providos.

Com estes recursos é possivél saber quanto foi vendido e/ou produzido nas unidades que a empresa possuí, quais foram as avaliações recebidas de uma determinada localidade, 
