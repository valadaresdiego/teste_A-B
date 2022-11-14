# Teste A/B
Projeto realizado na formação cientista de dados da data science academy

Um Teste A/B consiste em testar duas diferentes estratégias em umgrupo específico. Para ilustrar, digamos que você tenha uma página de venda de livros online com um botão para o usuário se cadastrar e receber seus e-mails – esse elemento é chamadodecontrole (o elemento existente). Você quer saber se algo pode ser melhorado na página, para atrair mais inscritos. Detodas as estratégias de Marketing, a comunicação via e-mail ainda é a mais eficiente. Então, você cria outra página com um botão de inscrição diferente – você pode mudar olugar do botão, a cor, o texto call-to-action, o formato, etc. Este novo elemento é chamadovariável.Agora, você exibe as duas versões da página para divisão 50/50 de toda sua audiência. Ou seja, todos os seus usuários visualizarão o botão de cadastro, mas alguns visualizarãoapágina onde o botão é azul e outros visualizarão a página onde o botão é verde, por exemplo. Desta forma, você reunirá os dados analíticos das duas versões, a controle e a variável, epoderá usar como fator decisivo. Qual deles pode trazer mais inscritos?

O que obteve mais resultados deve ser o escolhido.

Nosso objetivo aqui é analisar o resultadodeum Teste A/B.

Os dados são fictícios, mas representam valores válidos para esse tipo de trabalho.


## Como Analisar Testes A/B?

Em geral, realizamos esses 5 passos para analisar um Teste A/B:

1. Configuramos o experimento.

2. Executamos o teste de hipóteses e registramos a taxa de sucesso de cada grupo.

3. Criamos o Plot da distribuição da diferença entre as duas amostras.

4. Calculamos o poder estatístico.

5. Avaliamos como o tamanho das amostras afeta os Testes A/B.

## Conclusão
O poder calculado para este tamanho de amostra foi de aproximadamente 0,80. Portanto, para afirmar que a mudança na página removendo as avaliações de usuários realmente aumentou a taxa de conversão precisamos de pelos menos 1249 amostras.
O segredo do Teste A/B não está na execução do teste de hipótese em si, mas em conseguir obter o poder estatístico necessário para afirmar que as mudanças tiveram ou não efeito na taxa de conversão.

Para o nosso exemplo, com 1249 amostras podemos afirmar que sim, remover as avaliações de usuários da página aumenta a taxa de conversão.
