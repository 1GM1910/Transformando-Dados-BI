# Transformação de Dados

Este projeto tem como objetivo realizar a transformação de dados brutos , integrando-os ao Azure MySQL e, em seguida, utilizando o Power BI para análise e visualização. Durante o processo, são identificados problemas na base de dados que exigem transformações específicas para garantir a integridade e a utilidade dos dados.



 **Criação de uma Instância na Azure para MySQL**
   - Uma instância MySQL foi provisionada na plataforma Azure para armazenamento seguro e escalável dos dados.O banco de dados foi criado utilizando os dados disponíveis no repositório do GitHub.

 **Integração do Power BI com MySQL no Azure**
   - O Power BI foi configurado para se integrar com o banco de dados MySQL hospedado na plataforma Azure, permitindo a visualização dos dados de forma dinâmica e interativa.

 **Verificação de Problemas na Base de Dados e Transformações Necessárias**
   - **Verificação de Cabeçalhos e Tipos de Dados:** Os cabeçalhos e tipos de dados foram verificados para garantir consistência e integridade.
   - **Modificação de Valores Monetários para o Tipo Double Preciso:** Os valores monetários foram convertidos para o tipo de dados double preciso para melhor precisão e manipulação.
   - **Verificação de Nulos e Remoção:** Os registros nulos foram identificados e tratados conforme apropriado, incluindo a remoção ou preenchimento dos valores ausentes.
   - **Separação de Colunas Complexas:** Colunas complexas foram identificadas e divididas em componentes mais simples para facilitar a análise e a manipulação.
   - **Mesclagem de Consultas Employee e Department:** As tabelas de funcionários e departamentos foram mescladas para criar uma nova tabela que associa os nomes dos departamentos aos colaboradores.
   - **Eliminação de Colunas Desnecessárias:** Colunas desnecessárias foram removidas para simplificar a estrutura da tabela e reduzir o volume de dados.
   - **Mesclagem de Colunas de Nome e Sobrenome:** As colunas de nome e sobrenome foram combinadas em uma única coluna para melhorar a legibilidade e a usabilidade dos dados.

## Ferramentas Utilizadas
- **Azure**: Para hospedagem da instância MySQL.
- **Power BI**: Para análise e visualização de dados.
- **MySQL Workbench**: Para administração e gerenciamento do banco de dados MySQL.

