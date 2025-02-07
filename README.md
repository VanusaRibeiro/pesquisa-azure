<h1>Como criar um serviço de Pesquisa de IA no portal do Azure</h1>
<p align="height">A Pesquisa de IA do Azure é uma plataforma de recuperação de informações para a empresa que dá suporte à pesquisa tradicional e à pesquisa orientada por IA para experiências de "chat com seus dados" sobre seu conteúdo proprietário.
A maneira mais fácil de criar um serviço é usando o portal do Azure.
Para experimentar a Pesquisa de IA do Azure gratuitamente, abra uma assinatura de avaliação e crie seu serviço de pesquisa escolhendo o nível Gratuito. Você pode ter um serviço de pesquisa gratuito por assinatura do Azure. 
Para localizar ofertas da IA do Azure Search, você precisa:
1- Entrar no portal do Azure:

No canto superior esquerdo, selecione Criar um recurso”.

2- Use a barra de pesquisa para localizar "Pesquisa de IA do Azure":
Se você tiver mais de uma assinatura, escolha uma para o serviço de pesquisa. Caso estiver implementando a criptografia gerenciada pelo cliente ou se usar outros recursos que dependam das identidades de serviço gerenciadas para acesso a dados externos, escolha a mesma assinatura usada para o Azure Key Vault ou outros serviços nos quais as identidades gerenciadas são usadas.<br>
3- Deverá definir um grupo de recursos:</br>
Um grupo de recursos é um contêiner que mantém os recursos relacionados da sua solução do Azure.<br>
4- Precisa dá um nome ao serviço:
Em Detalhes da Instância, dê um nome ao serviço no campo URL. O nome faz parte do ponto de extremidade na qual as chamadas à API são emitidas: https://your-service-name.search.windows.net.
O nome de serviço possui os seguintes requisitos:
Exclusivo dentro do namespace search.windows.net
Entre 2 e 60 caracteres de comprimento
Consiste em letras minúsculas, dígitos ou traços (-)
Não use traços nos dois primeiros caracteres ou como o último caractere único
Não use traços consecutivos em nenhum lugar
Se você estiver usando vários serviços do Azure, coloque todos eles na mesma região, minimizará ou anulará os encargos de largura de banda. Não há encargos para saída de dados entre serviços de mesma região.<br>
5- Precisa escolher uma região próxima a você, a menos que as seguintes considerações se apliquem:
Sua região mais próxima está no limite de capacidade. Uma vantagem de usar o portal do Azure para configuração de recursos é que ele fornece apenas as regiões e camadas disponíveis.
Você deseja usar o agrupamento e a vetorização de dados integrados ou habilidades internas para enriquecimento de IA. As operações integradas têm requisitos de região.
Você deseja usar o Armazenamento do Microsoft Azure para indexação baseada em indexador ou precisa armazenar dados de aplicativo que não estão em um índice. O estado da sessão de depuração, os caches de enriquecimento e os repositórios de conhecimento são recursos da Pesquisa de IA do Azure que têm uma dependência no Armazenamento do Microsoft Azure. <br>
6- Liste a verificação para escolher uma região
A Pesquisa de IA do Azure está disponível em alguma região próxima? Verifique a lista de regiões com suporte.<br>
7- Escolha uma faixa:
A Pesquisa de IA do Azure é oferecida em vários tipos de preços: Gratuito, Básico, Standard ou Otimizado para armazenamento.<br>
8- Depois de fornecer as entradas necessárias, crie o serviço.
O serviço é implantado em minutos. Monitore o progresso por meio de notificações do Azure. Considere a possibilidade de fixar o serviço no painel para facilitar o acesso no futuro.</p>
