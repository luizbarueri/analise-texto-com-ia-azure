# analise-texto-com-ia-azure
Testando o serviço de analise de texto da Azure com IA.

Analisar texto no portal do Azure AI Foundry
Processamento de Linguagem Natural (PLN) é um ramo da IA ​​que lida com linguagem escrita e falada. Você pode usar o PNL para construir soluções que extraem significado semântico de texto ou fala, ou que formulam respostas significativas em linguagem natural.

O serviço Azure AI Language inclui o Text Analytics, com recursos como reconhecimento de entidade, extração de frase-chave, resumo e análise de sentimento. Por exemplo, suponha que a agente de viagens fictícia Margie's Travel incentive os clientes a enviar avaliações para estadias em hotéis. Você pode usar o serviço Language para extrair entidades nomeadas, identificar frases-chave, resumir texto e muito mais.

Neste exercício, você usará o Azure AI Language no portal Azure AI Foundry, a plataforma da Microsoft para criação de aplicativos inteligentes, para analisar avaliações de hotéis.

Crie um projeto no portal do Azure AI Foundry
Em uma guia do navegador, navegue até Azure AI Foundry .

Entre com sua conta.

Na página inicial do portal do Azure AI Foundry, selecione Create a project . No Azure AI Foundry, os projetos são contêineres que ajudam a organizar seu trabalho.

Explore an Azure AI Search index (UI)
Let’s imagine you work for Fourth Coffee, a national coffee chain. You’re asked to help build a knowledge mining solution that makes it easy to search for insights about customer experiences. You decide to build an Azure AI Search index using data extracted from customer reviews.

In this lab you’ll:

Create Azure resources
Extract data from a data source
Enrich data with AI skills
Use Azure’s indexer in the Azure portal
Query your search index
Review results saved to a Knowledge Store
Azure resources needed
The solution you’ll create for Fourth Coffee requires the following resources in your Azure subscription:

An Azure AI Search resource, which will manage indexing and querying.
An Azure AI services resource, which provides AI services for skills that your search solution can use to enrich the data in the data source with AI-generated insights.

Prepare-se para um projeto de desenvolvimento de IA
Neste exercício, você usa o portal do Azure AI Foundry para criar um hub e um projeto, prontos para uma equipe de desenvolvedores criar uma solução de IA.

Este exercício leva aproximadamente 30 minutos.

Abra o portal do Azure AI Foundry
Vamos começar entrando no portal do Azure AI Foundry.

Em um navegador da Web, abra o portal do Azure AI Foundry em https://ai.azure.come faça login usando suas credenciais do Azure. Feche todas as dicas ou painéis de início rápido que forem abertos na primeira vez que você fizer login e, se necessário, use o logotipo do Azure AI Foundry no canto superior esquerdo para navegar até a página inicial, que se parece com a seguinte imagem:


