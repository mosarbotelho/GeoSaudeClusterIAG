# GeoSaúde Brasil

![Captura de tela do mapa](https://i.imgur.com/your-image.png)

## Sobre o Projeto
O **GeoSaúde Brasil** é uma ferramenta interativa de visualização de dados georreferenciados para o Brasil. Utilizando um mapa dinâmico, o projeto permite explorar e analisar diferentes indicadores socioeconômicos e de saúde por estado, incluindo renda, população, casos de doenças e análises de clusters geradas por Inteligência Artificial.

O objetivo é tornar a visualização de dados complexos mais acessível, permitindo que pesquisadores, estudantes e o público em geral identifiquem padrões, tendências e correlações entre diferentes variáveis em todo o território nacional.

## Funcionalidades
* **Visualização por Categorias:** Troque facilmente entre diferentes mapas temáticos usando uma caixa de seleção, como Renda Média, População, e dados de saúde como Tuberculose, HIV/AIDS e Arboviroses.
* **Mapas de Clusters:** Análises de dados mais avançadas, como clusters socioeconômicos ou correlações entre variáveis (ex: Renda x HIV), são apresentadas de forma intuitiva, gerando insights automáticos.
* **Interatividade:** Ao passar o mouse sobre cada estado, um pop-up exibe informações detalhadas sobre o indicador selecionado.
* **Controle de Interação:** Um controle permite desativar a movimentação e o zoom do mapa, ideal para apresentação ou para evitar movimentos indesejados.
* **Legenda Dinâmica:** A legenda do mapa se atualiza automaticamente de acordo com o indicador selecionado.

## Tecnologias Utilizadas
* **HTML5/CSS3:** Estrutura e estilização da página.
* **JavaScript:** Lógica principal da aplicação.
* **Leaflet.js:** Biblioteca de código aberto para mapas interativos e responsivos.
* **TopoJSON:** Formato de arquivo otimizado para topologia de mapas, garantindo o carregamento rápido dos dados dos estados brasileiros.

## Como Rodar o Projeto Localmente
Para visualizar o projeto em sua máquina:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/geo-saude-brasil.git](https://github.com/seu-usuario/geo-saude-brasil.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd geo-saude-brasil
    ```
3.  **Abra o arquivo `index.html` em seu navegador:**
    Simplesmente clique duas vezes no arquivo ou arraste-o para a janela do seu navegador preferido.

O mapa e todos os seus recursos funcionarão diretamente, sem a necessidade de um servidor web, pois os dados já estão incluídos no código e acessíveis por URLs públicas.
