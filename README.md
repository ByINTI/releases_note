#INTI - Release Notes

# Sprint 101
Essa sprint recebeu o nome de [101](https://en.wikipedia.org/wiki/101_(topic)) pois serve de aprendizado para equipe de desenvolvimento de como não fazer uma sprint. Assim como no primeiro semestre da faculdade, todos chegamos achando que sabíamos o que estávamos fazendo, e acabamos aprendendo que subestimamos muito os desafios. Isso acabou gerando atrasos pois as estimativas de tempo acabaram saindo bem menor do que esperado.


Para equipe de DEV:
 1. Precisamos separar melhor cada pedaço do problema dentro das Sprints para ser mais acertivo nas estimativas de tempo.

#Backend
## Avulsos
* Pesquisa de eventos por nome
* Api aberta
> A api tem o principal objetivo a comunicação entre o back-end (servidor) e o front-end, contudo construída de forma universal possibilitando que outros sistemas se integrem.
* Vendas por transação (Fiado) em admin e bilheteria
> Esse tipo de venda especifico permite que nossos cliente continuem trabalhando de forma tradicional com seu publico alvo, podem fazer uma venda que será registrado no sistema com ingressos válidos, contudo que não teve sua venda liquidada ainda.
* Métodos de pagamento personalizado para cada cliente em Bilheteria
> Em configurações gerais é possível personalizar quais serão os métodos de pagamento aceitos em sua bilheteria.
* Adiciona Promotores (líder) ao sistema
> Várias entidades utilizam promotores para alavancar suas vendas. E muitas dessas entidades mantem o registro de vendas associadas a cada um desses promotores/líder. Além disso, foi implementado os promotores em multinível, possibilitando a distribuição porcentagem de lucros. Quando configurada, essa opção fica habilitada para vendas administrativas, fisicas (bilheteria) e online.
* Relatórios financeiros
> Novos relatórios financeiros foram construídos para atender nossos clientes no seu balanço e fechamentos.

## Sistema
* Nova infraestrutura de acesso ao disco
> O sistema que antes utilizava um HD magnético foi migrado para um SDD. Isso permite que o sistema tenha acesso as informações de banco de dados com performance bem maior.
* Monitoramento de performance
> O monitoramento das máquinas está sendo realizado via New Relic que disponibiliza varias informações de desempenho do sistema. A partir dessa ferramenta conseguimos identificar quais os principais pontos que devemos trabalhar para melhorar o desempenho desde máquinas com excesso de carga até funções problemáticas.
* Transmissão de nota fiscal automatizada
> Integramos o sistema INTI a plataforma Bling para emissão de nota fiscal de forma automática para cada compra realizada.

#Frontend

## Novo Front End
* Novo front-end, vendas online, para eventos sem mapa
> O novo front-office é capaz de trazer uma nova experiencia para os usuários que irão comprar em uma plataforma white-label utilizando imagens, textos, tipos de preços, menu de aplicativo personalizáveis para cada cliente e para cada evento.
