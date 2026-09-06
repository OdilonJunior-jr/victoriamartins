VICTORIA MARTINS ATELIÊ — GUIA DO PROJETO

Como abrir
1. Abra o arquivo index.html em um navegador moderno.
2. Para publicar, envie index.html e a pasta assets mantendo essa estrutura.

Antes de entregar à cliente
1. Abra index.html em um editor de texto.
2. Procure por: const WHATSAPP_NUMBER = '';
3. Insira o número com código do país e DDD, somente números.
   Exemplo: const WHATSAPP_NUMBER = '5511999999999';
4. Teste os três contatos: botão da página inicial, consulta do catálogo e envio da encomenda.

Como atualizar o catálogo
- Cada bloco com a classe model-card representa um modelo.
- data-piece guarda o nome do modelo.
- Cada botão model-color guarda a foto em data-src e o nome da cor em data-color.
- Duplique um model-card completo para adicionar outro modelo e troque fotos, nome, cores e textos alternativos.

Estrutura necessária
- index.html: experiência completa.
- assets/hero-desktop.png e hero-mobile.png: fundos responsivos.
- assets/logo-transparent.png: logo principal.
- assets/btn_catalogo.png e btn_encomendar.png: botões da página inicial.
- assets/black.jpg, silver.jpg, gold.jpg e brown.jpg: variações atuais do modelo demonstrativo.
- O pacote de entrega contém somente os arquivos usados atualmente pelo site.

Observação
O projeto não exige banco de dados. As atualizações do catálogo são feitas diretamente no index.html.
