# ETHTestToken
Código em Solidity para criação de Token Padrão em rede de tests da Ethereum desenvolvido durante formação de WEB3 Fundamentals da DIO

## Tecnologias Utilizadas

- Remix: Ethereum IDE
- Sepolia TestNet: Ethereum Test Net
- MetaMask: Carteira Crypto para navegadores Web

## Como Usar

1. Logar ou Criar Carteira Crypto

    https://metamask.io/

2. Configurar Meta Mask para acessar a Test Net:
- Sepolia TestNet:
-   Token: ETH
-   Chain ID: 11155111
-   Block Explorer: https://sepolia.etherscan.io
-   RPC URL: https://endpoints.omniatech.io/v1/eth/sepolia/public

3. Acessar Remix Ethereum IDE:
- Acessar https://remix.ethereum.org/
- Criar arquivo '.sol' e nomear 
- Copiar código do arquivo 'token_padrao.sol'
- Editar com dados do Token Test a ser gerado no intervalo entre a linha 61 e linha 67 e substituir o endereço em 'emit Transfer(address(0),0x88C02Dcc8133ee687e84e32B0FBC2bBf16B1B7CA, _totalSupply);' pelo endereço da sua carteira conectada a testnet
- Salvar

4. Solicitar recebimento de bitcoin na testnet
- Acessar https://cloud.google.com/application/web3/faucet/ethereum/sepolia
- Inserir endereço da carteira e clicar em 'Receber Sepolia ETH'

5. Compilar arquivo .sol
- Dentro da Remix IDE com o arquivo selecionado
- Clicar em 'Solidity Compiler'
- Clicar 'Compile (Nome do Arquivo)'

6. Pagar taxa de criação de crypto
- Dentro da carteira MetaMask surgira uma notificação de taxa de transação
- Aceitar

## Resultado

![Carteira](https://github.com/6uilhermeTeixeira/ETHTestToken/assets/58309213/5ce5c774-8dce-44c9-abc6-15805760677c)
