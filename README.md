# DP_DIO_AIAzure01
Repositório para o Desafio de Projeto da aula
"Trabalhando com Machine Learning na Prática no Azure ML"
do bootcamp "Microsoft Azure AI Fundamentals" da DIO.

O resultado do teste esta em resultado.json, a informação de entrada em testInput.json e á informação "Swagger URI" em arquivo.json .

O resultado foi alcançado seguindo tanto os passo da instrutora quanto as instruções da documentação oficial 
*https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html* .

Primeiro passo foi criar um "workspace" com recursos do Azure Machine Learning no portal.azure.com
  - Após efetuar login no portal do Azure, para criar um "workspace", é nessessario presciso criar um
recurso de Azure Machine Learning.
  - Depois de criar o recurso, entre no Azure Machine Learning studio (*https://ml.azure.com*) e selecione o "workspace" que foi criado.
  - No Azure Machine Learning studio selecione a pagina "Automated ML".
  - Em seguida, crie um novo Automated ML Job com suas informações e requisitos ou use o exemplo em *https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html*
  - Envie e espere até terminar.
  - após terminar o envio, em "Overview" selecione a opção abaixo de "Algorithm name" we faça um review dos detalhes do melhor modelo disponivel.
  - Selecione "Metrics' e verifique oas diferenças entre o valor previsto e os resultados reais em "residuals" e em "predicted_true".
  - Em seguida na aba "Model" selecione "Deploy" e use "web servises", configure o modelo e espere até a implentação começar e terminar, pode demorar alguns minutose vai ter finalizdo quando o "Deploy status' mostar como "Succeded".
  - Por ultimo é somente testar o modelo, no Azure Machine Learning Studio, na Aba de "Endpoints" selecione o modelo criado e clique na aba de "Test" onde você vai inserir o input, clicar no botão de "Test" e verificar os resultados.
