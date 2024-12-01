#Consumo de API da CoinGecko com Diferentes Abordagens
Este projeto demonstra o consumo de dados da API pública da CoinGecko para obter informações das 10 principais criptomoedas em termos de capitalização de mercado. O objetivo é explorar diferentes abordagens para trabalhar com requisições HTTP e manipulação de dados no JavaScript.

Abordagens Utilizadas
Callback:

Utiliza funções de retorno para processar os dados após a requisição.
Exibe os dados no console.
Promise:

Baseada no método fetch combinado com .then e .catch.
Torna o fluxo mais legível do que os callbacks.
Fetch com Promise:

Similar à abordagem de Promise, mas foca em um fluxo mais direto para a manipulação dos dados.
Async/Await:

Abordagem moderna e mais legível.
Permite tratar erros de maneira clara com try/catch.
Requisitos
Navegador moderno que suporte fetch e async/await.
Execução
Copie o código para um arquivo .js.
Importe o arquivo em um ambiente JavaScript ou insira em um arquivo HTML.
Abra o console do navegador para ver os resultados.
Saída Esperada
O console exibirá informações como o nome e o preço das 10 principais criptomoedas em cada abordagem.

Exemplo:

python
Copiar código
Buscando criptomoedas com Callback...
Dados recebidos com Callback:
Nome: Bitcoin, Preço: $40000
...
