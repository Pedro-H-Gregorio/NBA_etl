# MINI MUNDO

O banco de dados da NBA é estruturado para armazenar e gerenciar informações abrangentes sobre a liga de basquete. Ele organiza dados relacionados às temporadas, equipes, jogos, jogadores e suas estatísticas, oferecendo mecanismos para análises e consultas. Cada **temporada** é identificada por um código único e inclui o ano correspondente, a partir de 1946, que marca o início da liga, esta tabela permite associar todas as informações subsequentes a períodos específicos da competição. A tabela de **equipes** contém detalhes sobre cada equipe da NBA, como a cidade, nome abreviado, nome curto, nome completo e o número de aparições no All-Star, cada equipe é identificada por um código único, facilitando a gestão e identificação das diferentes equipes. Para associar as equipes a temporadas específicas, utilizamos a tabela **equipe na temporada**, que relaciona cada equipe com a temporada em que participou, por meio de chaves estrangeiras que conectam a tabela de equipes e a tabela de temporadas. A tabela de **jogos** registra todos os detalhes das partidas realizadas, incluindo data, horários de início e término, nome da arena, cidade e país onde o jogo ocorreu, fase da temporada e status do jogo. Ela também conecta o jogo às equipes envolvidas e à temporada em que o jogo ocorreu, permitindo rastrear e analisar as partidas. Os **jogadores** são registrados em uma tabela específica que inclui informações como nome, país de origem, número da camisa, altura, peso e a equipe à qual pertencem.  Cada jogador tem um código único, o que facilita a identificação e gestão de dados individuais. Para analisar o desempenho dos jogadores ao longo das temporadas, a tabela **jogador na temporada** relaciona os jogadores com as temporadas específicas em que jogaram. Essa tabela permite acompanhar o desempenho dos jogadores em diferentes períodos da competição. Finalmente, a tabela de **estatísticas dos jogadores** captura o desempenho detalhado dos jogadores em cada jogo, ela inclui dados como pontos, rebotes, bloqueios, assistências, roubos de bola, arremessos de três pontos e cestas do perímetro. Cada conjunto de estatísticas está associado a um jogador e a um jogo específico, possibilitando análises detalhadas do desempenho dos jogadores em partidas individuais. No conjunto, o banco de dados da NBA fornece uma estrutura organizada para o gerenciamento e análise de dados, facilitando a consulta e a visualização de informações essenciais sobre a liga, equipes, jogadores e suas estatísticas.