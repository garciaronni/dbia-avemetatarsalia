# dbia-avemetatarsalia
dBIA - Dataset Integrado dos Avemetatarsalia. Banco de dados e eBook de análise paleontológica/biológica.

# dBIA: Database Integrada dos Avemetatarsalian
[![ODS 4: Educação de Qualidade](https://shields.io)](https://un.org)
[![Open Data](https://shields.io)](#)

Seja bem-vindo(a) ao repositório oficial do **dBIA (Database Integrated of Avemetatarsalian)**. Este projeto nasceu com o propósito de integrar o rigor da pesquisa paleontológica de ponta com o impacto social da extensão universitária, alinhando-se diretamente ao **Objetivo de Desenvolvimento Sustentável 4 (ODS 4) da ONU: Educação de Qualidade e Universal**.

Aqui, a ciência de dados e a paleontologia se unem para criar um ecossistema educacional "fígital" (físico e digital), democratizando o acesso ao conhecimento sobre a evolução dos arcossauros da linhagem das aves (Avemetatarsalian).

---

## Motivação Científico-Pedagógica

A divulgação científica sobre o período Mesozoico frequentemente sofre com dois extremos: ou os dados são apresentados de forma extremamente técnica, restritos a artigos acadêmicos de difícil leitura para o público leigo, ou são reduzidos a conteúdos infantis superficiais que ignoram a complexidade evolutiva e geológica.

O **dBIA** quebra essa barreira. Sua motivação central é dupla:
1. **Científica:** Consolidar em uma única base de dados aberta variáveis complexas de taxonomia, tafonomia, paleogeografia e biologia reprodutiva de espécimes, servindo como ponto de partida confiável para entusiastas e pesquisadores.
2. **Pedagógica:** Transformar dados brutos em ferramentas de encantamento visual. O projeto visa atrair o público jovem para as ciências exatas e biológicas, utilizando o fascínio natural pelos dinossauros como um "gancho" para ensinar geologia, estatística e interpretação de dados.

---

## Inovações da Base de Dados

Diferente de repositórios globais tradicionais como a *Paleobiology Database (PBDB)* — que são excelentes, mas focados puramente em ocorrências de fósseis e catalogação —, o **dBIA** inova ao trazer uma abordagem **multidimensional e integrada**:

* **Casamento Geográfico-Temporal Dinâmico:** A base não fornece apenas as coordenadas atuais de descoberta (`Latitude` e `Longitude`), mas inclui dados de `PaleoLatitude`, `PaleoLongitude` e a respectiva `Placa_Tectônica`. Isso permite reconstruir exatamente onde o animal vivia milhões de anos atrás, e não onde ele foi achado hoje.
* **Métricas de Concretude Biológica:** Introdução de campos que raramente andam juntos em bases públicas, como o `Nível de Conhecimento Público` (audiência), a `Completude do Fóssil` (integridade do achado) e o `Tempo de Maturações em Anos` (ontogenia).
* **Foco em Paleoecologia Comportamental:** Dados tabulados sobre `Grupos de Convívio`, `Predadores/Presas Conhecidos` e `Evidências de Comportamento Social`, permitindo análises ricas sobre a dinâmica dos ecossistemas antigos.
* **Transparência Metodológica:** Integração direta com identificadores digitais de artigos (`DOI_Artigo`) e números de referência da PBDB, garantindo a rastreabilidade científica de cada linha inserida.


## Possibilidades de Aplicação (O que gerar com o dBIA?)

A estrutura do dBIA foi projetada para ser flexível, permitindo que a comunidade científica, desenvolvedores e educadores gerem subprodutos de maior impacto:

### Na Educação (Ensino Fundamental e Médio)
* **Material Impresso e Guias de Campo:** Criação de livretos didáticos focados nas escolas públicas locais para apoiar professores de Biologia e Geografia (Ensino por Investigação).
* **Livros Digitais (E-books Gratuitos):** Distribuição universal de materiais dinâmicos e ricamente ilustrados, acessíveis offline em qualquer dispositivo móvel.

### Na Ciência de Dados e BI
* **Dashboards Interativos Dinâmicos:** Conexão nativa com ferramentas como o **Power BI** para criar experiências visuais fluidas — como mapas interativos de paleolocalização e menus baseados em cliques nas camadas geológicas da Terra.
* **Análises Preditivas em Python/R:** Modelagem estatística para tentar prever o peso ou a velocidade estimada de novas espécies descobertas com base nas proporções ósseas já catalogadas na base.


## Estrutura deste Repositório

* `dBIA_dataset.csv`: Base de dados pura, otimizada para conexões automatizadas com ferramentas de BI e scripts de programação.
* `dBIA_dataset_visual.xlsx`: Versão em Excel tratada visualmente (com filtros e organização intuitiva) para professores de escola e não especialistas consultarem manualmente.
* `Dicionario_Dados_Confiabilidade.md`: O mapa completo de campos detalhando a descrição de cada coluna, fontes utilizadas e o nível de consenso científico do dado.


## Como Colaborar (Deixando um Legado)

Este projeto foi desenhado para ser perpétuo e colaborativo. Se você é paleontólogo, geólogo, educador ou entusiasta e encontrou algum dado que precisa de revisão ou deseja incluir uma nova espécie de *Avemetatarsalian*:
1. Faça um **Fork** deste repositório.
2. Atualize o arquivo com as novas informações acadêmicas e adicione as devidas referências bibliográficas.
3. Abra um **Pull Request** explicando a alteração.

Sua contribuição ajudará a manter viva uma ferramenta gratuita de educação universal!
