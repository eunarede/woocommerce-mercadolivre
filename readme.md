# WooCommerce MercadoLivre

* Contributors: agenciamagma, Carlos Cardoso Dias, Andre Bellafronte
* Tags: mercadolivre, mercadopago, woocommerce, integration, mercado livre, woocommerce mercadolivre, woocommerce mercado livre, integração, mercado, livre, mercadoenvios, mercado envios, feedback, comentários, ml
* Requires at least: 4.2.0
* Tested up to: 4.2.2
* Stable tag: 0.1.1
* License: GPLv2 or later
* License URI: http://www.gnu.org/licenses/gpl-2.0.html

Integrates MercadoLivre with the WooCommerce plugin

## Descrição

**Integre sua loja com o MercadoLivre**

WooCommerce MercadoLivre permite a publicação dos produtos, simultaneamente, na sua loja virtual com WooCommerce e também, na sua conta como vendedor do MercadoLivre.  Além disso, permite que os  produtos publicados, através de sua loja virtual, possuam um gerenciamento integrado de estoque, uma atualização automática do produto no MercadoLivre e muitas outras possibilidades.

Este plugin ainda possibilita a visualização, edição e resposta dos últimos comentários feitos no MercadoLivre através de painel administrativo de sua loja.

Deixe que a sua loja virtual e conta de vendedor no MercadoLivre sejam um só agora mesmo!

## Compatibilidade

Compatível com as versões 2.3.x do WooCommerce.

## Instalação

Veja como instalar e configurar este plugin na aba [Installation](http://wordpress.org/extend/plugins/woocommerce-mercadolivre/installation/).

## Dúvidas?

Confira se sua dúvida já foi respondida na seção [FAQ](http://wordpress.org/extend/plugins/woocommerce-mercadolivre/faq/). Caso não encontre uma resposta por lá [crie um tópico](http://wordpress.org/support/plugin/woocommerce-mercadolivre) (apenas em inglês) solicitando ajuda.

## Instalação

* Envie os arquivos do plugin para a pasta `wp-content/plugins` ou usando o instalador de plugins do WordPress.
* Ative o plugin.
* Acesse WooCommerce -> Configurações -> Integração -> MercadoLivre, preencha com seus dados de APP ID e Secret Key, salve as alterações e clique em login.

## Requerimentos

É necessário [criar um aplicativo](https://applications.mercadolivre.com.br) com sua conta no [MercadoLivre](https://www.mercadolivre.com/) e instalar a última versão do [WooCommerce](http://wordpress.org/extend/plugins/woocommerce/).

## FAQ

### Preciso instalar o WooCommerce para usar este plugin?

SIM! Este plugin foi testado utilizando o WooCommerce 2.3.10.

### Como adquiro meu APP ID e Secret Key? =

Para adquirir o seu APP ID e Secret Key você deve estar logado na sua conta do MercadoLivre e acessar a página [https://applications.mercadolivre.com.br](https://applications.mercadolivre.com.br) para criar um novo aplicativo. Após fornecer os dados necessários para a criação do aplicativo, serão fornecidos pelo MercadoLivre seu APP ID e Secret Key prontos para uso.

### Como crio meu aplicativo no MercadoLivre?

* Com sua conta no MercadoLivre logada, acesse a página [https://applications.mercadolivre.com.br](https://applications.mercadolivre.com.br) e clique em 'Create new application'.
* Preencha os itens da seção 'Basic Information' conforme solicitado pelo MercadoLivre.
* Na seção 'Authentication and Security', para o campo 'Redirect URI' digite a URL do seu navegador quando está na página de configurações do plugin `WooCommerce MercadoLivre`, excluindo deste endereço tudo que aparece depois de '?'. No campo 'Scopes' selecione 'read', 'write' e 'offline_access'.
* Para a seção 'Notifications Settings', digite 'http://meudominio.com/ml-notifications' no campo 'Notifications Callback URL', substituindo "meudominio.com" pelo seu domínio e marque 'items' para o campo 'Topics'.
* Aceite os termos de uso e clique em 'Create application'.

### Como publico um item no MercadoLivre utilizando o plugin `WooCommerce MercadoLivre`?

Para publicar um item no MercadoLivre utilizando o plugin `WooCommerce MercadoLivre` você deverá criar um aplicativo no MercadoLivre e fornecer os dados do aplicativo criado no painel administrativo do MercadoLivre na sua loja virtual com o WooCommerce (WooCommerce -> Configurações -> Integração -> MercadoLivre). Após preencher corretamente os dados e efetuar o login, você estará pronto para criar um novo produto na sua loja.

Siga as etapas normais para a criação de um produto no WooCommerce. Após todos os dados terem sido preenchidos, acesse a aba 'MercadoLivre' do painel do produto. Selecione a categoria do seu produto no MercadoLivre e preencha os demais dados conforme a necessidade.

IMPORTANTE 1: Deve ser habilitado o 'gerenciamento de estoque a nível de produto' e uma quantidade finita para o produto deve ser fornecida, esta será a quantidade disponível deste produto no MercadoLivre.

IMPORTANTE 2: A categoria do produto no MercadoLivre deverá ser final. Categorias finais são aquelas onde não haverá o símbolo de 'loading' e nenhuma outra selectbox para seleção de subcategorias será fornecido.

## Telas
1. This screenshot shows the administrative panel.

## Changelog

acesse o [Changelog](changelog.md)
