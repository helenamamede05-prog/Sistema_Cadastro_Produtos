# Sistema de Cadastro de Produtos

Abra esta pasta no IntelliJ IDEA e execute a configuração **Executar** ou o método main de `test.ProdutoTest01`. Selecione um JDK 17 ou superior se o IntelliJ solicitar um SDK.

O exemplo cadastra Teclado e Mouse, exibe estoques de R$ 750,00 e R$ 800,00, testa entradas inválidas e adiciona três teclados ao estoque.

O acesso a `preco` de fora da classe gera erro de compilação porque o atributo é privado. Os métodos públicos permitem consultar e alterar o valor com validação. O teste demonstra esse acesso direto em uma linha comentada para manter o projeto compilável.
