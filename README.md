# Copa 2026

Repositório de dados públicos e estáticos da Copa 2026.

Os dados de interesse, ficam armazenados no diretório `/dados`
(por ora, a tabela da copa e a lista de países).

## Atualização

Para atualizar os dados, basta rodar o `/bin/fetch-worldcup-json`
do diretório base do repo, esperar o processo terminar e fazer o
commit dos dados atualizados.

O script faz um clone e checkout seletivo do repositório com o
conteúdo original e descarta tudo, deixando apenas os dados de
interesse. Como esses dados mudam pouco, minha expectativa é que
isso não mude.
