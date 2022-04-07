Crie um site que tenha quatro inputs:

- qtd de números aleatórios
- qtd de colunas
- valorMínimo
- valorMáximo

Quando o usuário clicar no botão de gerar, exiba numa TAG do tipo PRE a tabela com números aleatórios, com números aleatórios ente os valores mínimo e máximo.

DICA1:  Math.trunc(Math.random() * 100) + 1
DICA2: 
if (i % colunas == 0) {
   tabela.innerHTML += "\n";
}