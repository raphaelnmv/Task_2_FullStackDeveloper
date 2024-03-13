Tarefa 2 (Diferencial - Conhecimento em Magento 2)
Crie, conforme seus conhecimentos, um módulo no Magento para criação de um
método de entrega customizado da loja. O método deve ter o título de “Retirado na
Loja” e não deve realizar cotação de frete. Esta opção de entrega deve aparecer na
loja para ser selecionada pelo cliente, no pedido salvo no Administrativo e no grid de
pedidos, com opção de filtro.
- Utilize a versão do Magento de sua preferência.
- Enviar somente o módulo para ser instalado em qualquer loja.
- Especificar a versão utilizada e o processo para instalação do módulo.
-
-
- Versão: Magento 2.2.2
- Processo de instalação:
Execute os seguintes comandos no terminal, na raiz da instalação Magento:

php bin/magento module:enable Vendor_CustomShipping

php bin/magento setup:upgrade

php bin/magento cache:flush

//Após isso, use isso para o magento identificar o módulo
php bin/magento setup:upgrade

//Compila o modulo
php bin/magento setup:di:compile

