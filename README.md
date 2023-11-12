WEEK 1 - SAUTER CHALLENGE 

Tratamento de Dados de Avaliações de Aplicativo

A equipe de Engenharia de Dados da Sauter desenvolveu um case sob medida para atender às necessidades de um cliente do setor de moda. O objetivo principal era conduzir uma análise abrangente do aplicativo da empresa e compará-lo com os aplicativos de seus concorrentes.

Objetivo: Avaliar a capacidade do aluno em lidar com dados provenientes de avaliações de aplicativos da App Store e/ou Google Play Store. O foco está na habilidade de manipulação e transformação de dados.

Instruções:
Escolha do Aplicativo:
Escolha um aplicativo de sua preferência na App Store e/ou Google Play Store.
Leitura e Coleta de Dados:
Utilize bibliotecas adequadas para coletar as avaliações do aplicativo escolhido.
Verifique se o número total de avaliações foi corretamente recuperado e apresentado.
Transformação e Limpeza de Dados:
Transforme os dados brutos obtidos em um DataFrame estruturado.
Normalize os dados da coluna que contém as respostas dos desenvolvedores (caso exista essa informação) e insira as informações resultantes em colunas separadas.
Crie uma nova coluna 'etl_timestamp' com a data e hora atuais no formato 'YYYY-MM-DD HH:MM:SS'.
Converta a coluna 'etl_timestamp' para o formato datetime64[ns].


Desafio Especial:
Considere a possibilidade de que a saída de streaming possa ser truncada nas últimas linhas. Proponha uma solução para recuperar e incluir essas linhas no DataFrame.

A expressão "saída truncada" refere-se ao caso em que uma quantidade significativa de dados é cortada ou encurtada durante a exibição ou captura de resultados, especialmente em ambientes de programação ou sistemas que geram grandes volumes de dados. Isso pode acontecer por uma variedade de razões, incluindo restrições de exibição em consoles, interfaces gráficas ou problemas de comunicação em sistemas distribuídos.


Exibição dos Dados:
Apresente os primeiros registros do DataFrame após as transformações realizadas.


Conclusão:
Documente as principais etapas de tratamento de dados realizadas, mencionando eventuais desafios enfrentados e soluções aplicadas.

Observações Importantes: O foco principal é a manipulação dos dados, não é necessário realizar análises aprofundadas.




# Aplicativo Escolhido: Instagram
# Aluno: Romário Abílio de França
