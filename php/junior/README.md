# Meus Pedidos
---

## Visão geral do projeto:

No projeto "Meus Pedidos", você criará uma aplicação de gestão de pedidos de venda que permite criar, editar, excluir, ver e buscar os seus pedidos. O projeto enfatiza o uso de PHP e MySQL para criar a aplicação.

## Funcionalidade da aplicação

Nesta aplicação a página principal exibe uma lista com todos os pedidos e as seguintes funcionalidades:
* Criar novo pedido
* Pesquisar pedido

Cada pedido tem um controle que permite:
* Excluir
* Editar

A página principal também tem um link para `/criar`, uma página de criação que permite que você cadastre novos pedidos. Essa página deve conter inputs para cadastrar os seguintes valores:
* Id
* Produto
* Valor
* Imagem

**Atenção:** Os valores acima servem como referência para a criação do banco de dados.

A página principal possui uma entrada de texto que pode ser usada para encontrar pedidos. À medida que o valor da entrada de texto muda, os pedidos que correspondem a essa consulta são exibidos na página, juntamente a um controle que permite editar ou excluir esse pedido. Para manter a interface consistente, você pode considerar a reutilização de algum código que usou para exibir todos os pedidos na página principal.

## Requisitos de envio
Seu projeto deve incluir todos os arquivos necessários para instalar e iniciar sua aplicação em um servidor web local. Você pode supor que seu revisor terá o composer instalado na máquina dele.

## Considerações
O foco deste projeto é escrever um código PHP funcional, e não deixar a página bonita. Caso queira, fique à vontade para passar algum tempo trabalhando no layout, porém, lembre-se de que o objetivo principal é ter os recursos funcionando corretamente.

## Diferencial¹
Certifique-se de que seu código segue as PSRs 1 e 2 e nossos guias de estilo de HTML, CSS, JavaScript e Git.
* [PHP Standards Recommendations 1 e 2](http://www.php-fig.org/psr/)
* [Guia de estilo de HTML](https://tecnologiafox.github.io/frontend-styleguide/index.html)
* [Guia de estilo de CSS](https://tecnologiafox.github.io/frontend-styleguide/css.html)
* [Guia de estilo de JavaScript](https://tecnologiafox.github.io/frontend-styleguide/javascript.html)
* [Guia de estilo de Git](https://tecnologiafox.github.io/git-styleguide/)

Recomendamos usar o Git desde o início. Certifique-se de fazer commits com frequência e usar commits bem formatados.

## Como este projeto será avaliado?
Seu projeto será avaliado por um ou mais revisor de projetos da Tecnologia Fox, considerando as especificações do projeto. Certifique-se de revisá-las antes do envio. Todos os critérios devem "atender às especificações" para que o projeto seja aprovado.

As especificações do projeto são sua fonte de consulta ao desenvolvê-lo. Salve-as nos favoritos de seu navegador para poder acessá-las facilmente!

## Diferencial²
Lembre que seu projeto poderá ser nomeado por excelência pelo nossos revisores! Por isso, fique à vontade para adicionar novos recursos, tecnologias, etc. Aproveite para aplicar no projeto tudo aquilo que você sabe. Desafie-se, pois você aprende muito mais quando tenta algo novo. Apenas lembre que os recursos adicionados não podem interferir nas especificações.

Para entender melhor como seu projeto pode ser diferenciado, confira o último item das especificações do projeto.

## Instruções de envio
Envie seu projeto no GitHub, certificando-se de fazer o push no branch master. E envie para o e-mail de contato do seu recrutador o link do seu projeto.

## Está travado no projeto? Tem perguntas?
abcde...

# ESPECIFICAÇÕES DO PROJETO

**Configuração da aplicação**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| É fácil instalar e iniciar a aplicação? | A aplicação foi criada com o composer e exige apenas o composer install para ser instalada e iniciada. |
| A aplicação inclui o README, com instruções claras de instalação e inicialização? | Um README está incluído no projeto. O README inclui instruções para instalação e inicialização do projeto. |

<br>

**Página principal**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| A página principal exibe uma lista com todos os pedidos criados? | A página principal exibe todos os pedidos criados. |
| A página principal tem um input de busca, que permite que os usuários procurem por pedidos? | A página principal possui um campo de busca. Quando o usuário digita algo no campo de busca, os pedidos relacionados à sua busca são corretamente exibidos na página. |
| A página principal permite que o usuário exclua um pedido? | A página principal possui um botão para excluir pedidos. Quando o usuário clica neste botão, o pedido é excluído da lista. |
| As informações são mantidas quando ocorrem refreshes de página? | Quando é feito refresh no navegador, a página continua exibindo as mesmas informações. |
| Os resultados de busca permitem que um usuário continue excluindo os pedidos? | Os resultados da busca permitem que os usuários excluam mais pedidos normalmente. |

<br>

**Página de criação**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| ... | ... |

<br>

**Página de edição**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| ... | ... |

<br>

**Funcionalidade do código**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| ... | ... |

<br>

**Funcionalidade do código**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| ... | ... |

<br>

**Diferencial, não obrigatório**

| CRITÉRIO        | ATENDEU ÀS ESPECIFICAÇÕES |
| -------------   |-------------------------|
| O projeto desenvolvido se destacou por adicionar recursos extras além do que foi pedido nas especificações do projeto?<br>
`Atenção:` este item será sempre aprovado pelos revisores, portanto, não é um critério obrigatório a se cumprir para ser aprovado no projeto. | O projeto desenvolvido possui pelo menos três dos seguintes itens: <br><br>**Item 1 - A arquitetura de código do projeto está muito bem projetada e enxuta** <br> <ul><li>A composição das classes e métodos está bem definida e coesa</li></ul><br><br>**Item 2 - Há uso de bibliotecas/pacotes externos relevantes não pedidos no projeto**<br><ul><li>Fez uso de pacotes externos para aprimoramento da UI/UX, como loadings, debounce, forms, material design, bootstrap, etc.</li><li>OU utilizou outras tecnologias adicionais ao PHP</li></ul><br><br>**Item 3 - Foram adicionados novos recursos relevantes na aplicação**<ul><li>Implementou recursos além do que foi pedido. Tais features aumentaram a relevância de uso da aplicação, seja enriquecendo a experiência do usuário ou suprindo novas necessidades de uso</li></ul><br><br>**Item 4 - Há uso de testes na aplicação**<ul><li>Aplicou testes na aplicação, seja com PHPUnit ou qualquer outra ferramenta de testes unitários ou de integração. Os testes apresentaram uma cobertura mínima de 80%</li></ul>|
