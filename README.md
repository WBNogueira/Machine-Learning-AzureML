# Trabalhando com Machine Learning na Prática no Azure ML

Este repositório contém instruções passo a passo para realizar aprendizado de máquina automatizado no Azure Machine Learning para treinar, avaliar, implantar e testar um modelo de previsão de aluguel de bicicletas.

## Configuração do Espaço de Trabalho

1. Acesse o [portal do Azure](https://portal.azure.com) usando suas credenciais da Microsoft.
2. Selecione "+ Criar um recurso" e pesquise por "Machine Learning".
3. Crie um novo recurso do Azure Machine Learning com as configurações necessárias, incluindo assinatura, grupo de recursos, nome, região, conta de armazenamento, cofre de chaves, entre outros.
4. Após a criação do espaço de trabalho, acesse o Azure Machine Learning Studio.

## Treinamento do Modelo

1. No Azure Machine Learning Studio, navegue até a página Automated ML em Authoring.
2. Crie um novo trabalho de ML automatizado com as configurações específicas fornecidas, incluindo nome do trabalho, tipo de tarefa, conjunto de dados, métrica primária, modelos permitidos, limites, entre outros.
3. Envie o trabalho de treinamento e aguarde a conclusão.

## Avaliação do Modelo

1. Na guia Visão geral do trabalho automatizado de aprendizado de máquina, revise o melhor resumo do modelo.
2. Selecione o nome do algoritmo do melhor modelo para visualizar seus detalhes.
3. Analise as métricas e gráficos residuais para avaliar o desempenho do modelo.

## Implantação e Teste do Modelo

1. Na guia Modelo do melhor modelo treinado, selecione Implantar e escolha a opção de serviço Web.
2. Configure a implantação com nome, descrição, tipo de computação e habilitação de autenticação.
3. Aguarde até que a implantação seja concluída.
4. Teste o serviço implantado fornecendo dados de entrada e verificando os resultados retornados.

## Teste do Serviço Implantado

1. No Azure Machine Learning Studio, acesse a seção Endpoints e abra o endpoint em tempo real de previsão de aluguel.
2. Na página de teste do endpoint, insira os dados de entrada para testar o serviço.
3. Revise os resultados do teste para verificar o número previsto de aluguéis com base nos recursos de entrada.

---

**Observação:** Este README fornece instruções básicas para realizar aprendizado de máquina automatizado no Azure Machine Learning. Certifique-se de seguir os passos detalhados no exercício original para obter resultados precisos.

**Autor: Wagner Nogueira**