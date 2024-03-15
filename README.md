# Curso ITA Orientação a Objetos com Java.

# Conceitos trabalhados

Olá! Bem-vindo à semana 4 do curso Orientação a Objetos com Java! Nesta semana você aprofundará seu contato com Herança e Modificadores de Acesso. Ao final desta semana, você será capaz de 1) projetar e estruturar programas Java com base em boas práticas no uso de herança, 2) além de garantir acoplamento baixo entre classes pelo uso adequado de modificadores de acesso

# Instruções

Crie uma classe chamada Produto que deve possuir um nome, um código e um preço. Sobrescreva os métodos equals() e hashCode() de Object (veja seção sobre esses métodos), de forma a serem considerados iguais instancias de Produto que possuam o mesmo código.

Crie uma classe chamada ProdutoComTamanho que estenda a classe Produto. Essa classe deve possuir uma informação adicional de tamanho. Um exemplo seria o tamanho de uma roupa ou a numeração de um calçado. Método equals() e hashCode() devem ser sobrescritos de forma que um produto com mesmo código e tamanhos diferentes são considerados diferentes.

Crie uma classe CarrinhoDeCompras que armazene em um atributo interno do tipo HashMap cada produto adicionado no carrinho e sua respectiva quantidade. O método adicionaProduto() deve receber a instancia do produto e a quantidade. Caso o produto já exista no HashMap, a quantidade deve ser somada a que já existe no carrinho. Deve haver também um método removeProduto() que também recebe a instancia do produto e a quantidade a ser removida. Observe que produtos de tamanhos diferentes devem ser considerados como produtos diferentes no carrinho. O carrinho deve possuir um método que calcula o valor total da compra.

Crie testes com Unit para a classe Produto, para a classe ProdutoComTamanho e para a classe CarrinhoDeCompras. Os testes de cada classe devem ser colocados em classes separadas e devem estar em um diretório de código diferente das classes de produção.

-	Linguagens utilizadas:
	-	![Java](https://img.shields.io/badge/Java-orange.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAAOxAAADsQBlSsOGwAAAxxJREFUWIXF112IlGUUB/Dfrlumsju2gboRRRsZGJGkJGhYF0VEFBaBIAVFYRdB3ZVIdCOoXUiI6IUIgnhjhVIUEllREEUQUtGHBZLaF+ZX6brmTjtdnDPOu9OOOzPs6B9e3neeeZ/zP895zvmf52XyMLedSd2T6MAzk2irZQzgNLouB3kP3sOJy0E+FW+igu2XmnwOPk3yv3BD4b8S7sL0TpHfiV+SvIxlmIEX8AW+w6JOkT+Ms0n+L57Gffg1x3bo4MqX4p8C+UoswTmM4pVOEVfxfZJX8FKOVfNgR6fJSwXyD3LsCpEDFTzVjtFWlPBv/J7Pu/Jexpl8frQdB6a0+H63SLifsTfHqiV3Mz7E4XYcaRY9+ETUfSnHpqnlxu5OklfRj/14uTD2UDrwWavG2umGJ3AP7sCsHDuY99fbsNcQs/Cc0Ph9WJ2kVad7cFs+v4a1xnbDbqzA1/gWT4xH0qh9zhH7OjN/v4EtYvVnheh0iWbUjxsxlPOuxQg2iAoZwMcYFIeWarQuiquwUyhcpcmrjJ+wUfSFItbnO8uajUAV00WYF6b3R0RoR0QkTuGoaEyHcL6Bnfdxr9jC/RNw/g8rRHi3qSVdEV24Ho+IY1lP3f/3iy37qFXiKtalgUre/8SP+EFEpH6b3hFbCPNF3uzDNeMZb/YMNw8P4Hax2pJY6TkcF8r4jWhMX6UjC0WrfltNNdvGoFDArWqrk04M4jFsEns8KRjA3UJwevGqsdl+XCRg2djwj4hcqEfTp+XZ4oQ7miQbxOpKeFHs5WFR38M4JkRmD1bh1gZ23xWaMSHWqK1mTbNeXwRXiuiVRVQnxC34TS3j9wo5XoSrm5g/VSTscmwW54chPFt4p684Yby9KeWE5aKMig3rjAj7aVEBRCL2poP9aXMEX4oK2I4/0rlVQuIvNK2JkqMkSm8urhO1PFOEdkoSDeOkmiIeEHkxnDZm43E8j7fyfgH1qlWPISE8fbnygyIJTzV4v1d8oDyIBaKSFggVfNI4atjKx+QAFguBuUlEo09EaUZeoyISR0QUPhfHtKONjP4HxJ7K18iRRpEAAAAASUVORK5CYII=)
-	Controle de Versionamento:
	-	![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)	![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

## Desenvolvedor
🙋🏼‍♂️ [Márcio Adriano da Silva](https://www.linkedin.com/in/mads1974/)
