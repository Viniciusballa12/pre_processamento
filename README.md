# pre_processamento

Descrição

Este repositório contém um notebook Jupyter (Profissao Cientista de Dados M14 Pratique (1).ipynb) que aborda a etapa de pré-processamento de dados no contexto de um projeto de análise de churn em uma empresa de telecomunicações. O objetivo é realizar a limpeza e o tratamento de uma base de dados relacionada a serviços de internet, telefone e TV, preparando-a para modelagem futura.

Estrutura do Projeto





Profissao_Cientista_de_Dados_M14_Pratique: Notebook principal com o código e explicações passo a passo do pré-processamento.



CHURN_TELECON_MOD08_TAREFA.csv: Arquivo CSV contendo os dados brutos de churn utilizados no exercício (deve ser colocado no diretório especificado no código).

Conteúdo do Notebook

O notebook está dividido em várias seções que cobrem as etapas de pré-processamento de dados:





Carregamento e Verificação dos Tipos de Dados





Carrega o dataset e ajusta os tipos de dados para corresponder às colunas (ex.: categórico, numérico).



Tratamento de Dados Faltantes





A) Identifica e calcula a porcentagem de dados faltantes por coluna.



B) Exclui linhas com valores ausentes em Pagamento_Mensal e Churn, justificando a escolha com base na baixa proporção de perda e na importância das variáveis.



C) Substitui valores ausentes em PhoneService pela moda e em Pagamento_Mensal e Total_Pago pela mediana, com justificativas baseadas na distribuição dos dados.



Correção de Valores Inconsistentes





Padroniza valores categóricos (ex.: minúsculas, correção de variações como "Yes" e "yes") e ajusta PhoneService para valores numéricos (0.0 e 0.1).



[EXTRA] Renomeação de Colunas





Renomeia colunas (ex.: PaymentMethod para Metodo_de_Pagamento) e remove colunas desnecessárias (ex.: customerID) para manter um padrão consistente.

Pré-requisitos





Python 3.x



Bibliotecas:





pandas



seaborn



matplotlib



Arquivo CSV CHURN_TELECON_MOD08_TAREFA.csv no diretório especificado ou ajustado no código.

Como Usar





Clone ou baixe este repositório.



Certifique-se de que o arquivo CHURN_TELECON_MOD08_TAREFA.csv está no caminho correto (ex.: C:/Users/vinicius/Downloads/ ou ajuste no código).



Abra o notebook Profissao_Cientista_de_Dados_M14_Pratique em um ambiente Jupyter (ex.: Jupyter Notebook, JupyterLab ou Google Colab).



Execute as células na ordem para replicar o pré-processamento.

Contribuições

Sinta-se à vontade para sugerir melhorias ou correções. Abra uma issue ou envie um pull request com suas alterações.

Licença

Este projeto não possui uma licença específica definida. Use-o para aprendizado e prática, respeitando os direitos dos dados originais, se aplicável.

Autor
Vinicius Martins Guimarães





Desenvolvido como parte do módulo 14 do curso de Profissão Cientista de Dados.



Contato: [viniciusmartinsguimaraes6@gmail.com].
