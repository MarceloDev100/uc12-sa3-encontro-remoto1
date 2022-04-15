## SENAI-SP

### UC12 - SA3 - Encontro remoto 1

#### Modos de proteção de senha usando _funções de hash criptográficas_, por meio do Microsoft SQL Server Management Studio (SSMS) e SQL Server Express.

-----------

Foi criada uma base de dados chamada "TesteSeguranca", onde foi construída uma tabela Usuários com os seguintes campos:

- [x] Id, do tipo inteiro , sendo uma chave primária e auto-incrementável.

- [x] Email, do tipo varchar com limite de até 100 caracteres , sendo um campo único e não nulo.

- [x] Senha, do tipo varchar com limite de até 50 caracteres e não nula.

Após a criação da tabela, foram feitas 2(duas) inserções de dados na referida tabela, nos seus respectivos campos e-mail e senha. O comando SELECT foi usado para que os dados pudessem ser exibidos.

Para finalizar, conforme objetivo proposto da atividade, foram feitos vários comandos SELECT consecutivos na tabela, para o campo email e para senha passada como argumento na função HASHBYTES, devendo exibir como retorno a senha já criptografada, de acordo com o algoritmo da função Hash (MD2, MD4, MD5, SHA, SHA1, SHA2_256 ou SHA2_512).

No final da sentença SQL, uma restrição foi acrescentada para mostrar somente os dados do usuário com Id = 1.  E como resultado, foi exibido na tela além do e-mail cadastrado , os diversos tipos de hash da mesma senha, de forma a poder comparar os resultados e o tamanho de cada hash.


_Vide abaixo_ (Clique em cada figura para exibir em tamanho maior).

-----------
**Sentenças SQL**:

![tela1](https://user-images.githubusercontent.com/88597534/163498101-47d08b9e-5ea0-4117-afbd-396563d9a2c9.jpg)

**Resultado**:

![tela2](https://user-images.githubusercontent.com/88597534/163498118-91aaf243-a493-45bb-bec3-cb343067b724.jpg)

