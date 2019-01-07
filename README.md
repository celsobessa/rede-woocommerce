# Módulo WooCommerce

Esse módulo foi desenvolvido com suporte ao WooCommerce 3+.

## Requisitos

Os requisitos desse módulo são os mesmos requisitos do próprio WooCommerce, ou seja, se o WordPress suportar o WooCommerce 3+, ele suportará o módulo.

# Instalação

Esse módulo utiliza o SDK PHP como dependência. Por isso é importante que, assim que o módulo for clonado, seja feita sua instalação:

```bash
composer install
```

Feito isso, basta enviar tudo para o diretório de plugins do WordPress - via ftp ou ssh - mesclando e/ou sobrescrevendo conforme solicitado.

## Instalação via composer

Também é possível fazer o download direto via composer. Para isso, basta executar:

```
composer require developersrede/woocommerce
```

Isso fará o download do módulo já com todas as dependências. Se feito diretamente no servidor, bastará fazer a configuração do módulo.