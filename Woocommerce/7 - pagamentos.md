- Descobrir qual o meio de pagamento do cliente (mas tentar colocar o plugin que exista já)
    
    > Fazer a configuração do pagseguro

       - woocommerce / config / pagamentos

       - ativar pagseguro

       - Nome / Descrição (que aparece no site)

       - Métodos [redirecionamento (para o site do pagseguro) | LightBox(abre na tela um box pequeno) | Checkout Transparente fica só na página do cliente]

       - Manda o Tutorial para o cliente poder enviar o token pra mim https://www.hostnet.com.br/info/modulos-de-pagamento-obtendo-credenciais/

       - Fazer no sandbox pra testar (https://sandbox.pagseguro.uol.com.br/)

       - abri vendedor e copiar email e token no sandbox

       - ativar os meios de de checkout (boleto, cartão, etc)

       - prefixo pedido (caracteres que coloca no pedido) para ver no painel do pagseguro

    > Transferências Bancárias

      - Ativar

      - mudar título

      - Descrição (na hora de comprar)

      - Instrução (depois que eu der o checkout, colocar aqui o CPF ou CNPF, e falar que só vai confirmar quando verificar o depósito)

      - Colocar a conta no Detalhes 

    > Pagamento na Entrega

      - Colocar as descrições que eu achar necessário

    > MERCADO PAGO

      - Instalar o plugin 

      - Teste primeiro ao invés de já ir jogando para produção

      - Buscar as credenciais (Copiar a Public Key e o Access token - de teste ou de produção) e copiar elas no sistema

      - Demora para homologar a conta

      - Configurar como vai sair na fatura do cliente

      - Ativar o checkout da loja (não converter moeda)

      - Não ativar o desconto (pq o desconto será do woocommerce)