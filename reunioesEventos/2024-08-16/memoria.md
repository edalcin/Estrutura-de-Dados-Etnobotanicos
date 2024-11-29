# Memória Reunião 16/08/2024

<img src="https://raw.githubusercontent.com/edalcin/Estrutura-de-Dados-Etnobotanicos/main/reunioesEventos/2024-08-16/20240816_142302%7E2.jpg" width="800">


## Participantes
* [Viviane Kruel](http://lattes.cnpq.br/0560294487722709)
* [Eduardo Dalcin](http://lattes.cnpq.br/8334174268306003)
* Carlos Coimbra
* [Luisa Ridolph](http://lattes.cnpq.br/5593552951372724)
* [Camila Dantas](http://lattes.cnpq.br/4396367747910248)
* [Nicky van Luijk](http://lattes.cnpq.br/3013537979299517)
* [Giovana de Macedo](http://lattes.cnpq.br/0170596104655416)
* [Mateus Salim](http://lattes.cnpq.br/0248529376853174)
* [Maria Paula Vasconcelos](http://lattes.cnpq.br/0275179451482030)
* [Alysson Barbosa](http://lattes.cnpq.br/4849931630110151) 

## Encaminhamentos

* Propor uma carta de princípios para a atuação do grupo
* Criação de uma __lista de discussão__ sobre estruturas e padrões de dados para a etnobotânica, como uma proposta de canal de comunicação
* Convidar profissionais e representantes de comunidades tradicionais para contribuições e análises criticas das propostas de padronização e estruturas de dados: 
  * [UseParts](https://github.com/edalcin/Estrutura-de-Dados-Etnobotanicos/blob/main/dicionarios/useParts.md)
  * [UseTo](https://github.com/edalcin/Estrutura-de-Dados-Etnobotanicos/blob/main/dicionarios/useTo.md)
  * [UseForm](https://github.com/edalcin/Estrutura-de-Dados-Etnobotanicos/blob/main/dicionarios/useForm.md)
* Alunos de graduação e pós-graduação tenham conhecimento sobre os padrões e estruturas de dados aqui sugeridos e participem da discussão
* Considerar e priorizar a adoção de padrões, dicionários e estruturas de dados já existentes ou propostas e adotadas globalmente (ex: DarwinCore, IBGE...)
* O grupo propõe se reunir a cada 30 dias, de forma presencial, híbrida ou remota, para avaliar o andamento dos encaminhamentos

## Tópicos

### Apresentação Eduardo Dalcin - Estrutura e Padrões de Dados Etnobotânicos

- Banco de dados são representações da vida real
- Os detentores devem ser visibilizados *"Nada sobre nós sem nós"*
- Exemplos de padrões para a categorização de doenças (DATASUS, CID 10, EBDCS,...)
- "Que história você quer contar com os dados?"
- Formato JSON permite a organização dos dados em formato de documento/objeto
- O nome vernacular é mais acessível a todos, sendo este o foco na organização
- Outros tipos de estruturação é o *grafo*, como o MongoDB que são banco de dados multimodais e o Datalake, que consegue armazenar diferentes tipos de dados.

### Apresentação Nicky van Luijk - Trasmissão Cultural e Conservação do Conhecimento Popular sobre Espécies Vegetais

- Perguntas norteadores em pesquisas de tramissão cultural:
   - O que se aprende?
   - Como se aprende?
   - Em que contexto?
   - Com que se aprende?
- Pergunta norteado da pesquisa: "Como as pessoas aprenderam sobre as plantas medicinais e alimentícias?"
- Principal objetivo da pesquisa: **Registrar**, **sistematizar** e **estruturar** o conhecimento e **compreender** como ocorre a transmissão cultural em Arraial do Cabo, Armação dos Búzios e Cabo Frio.
- Como organizar dados complexos relacionados ao processamento e a forma de uso?
- Pensar a utilização do termo *in natura* nas pesquisas
- Como tratar e organizar os dados em formato de áudio/vídeo (exemplo de tratamento com dados nesse formato é o Museu da Pessoa)

### Apresentação Luisa Ridolph - Documentação Científica e Análises Filogenéticas de Plantas Medicinais: um estudo de caso na Coleção Temática de Plnats Medicinais do Instituto de Pesquisas do Jardim Botânico do Rio de Janeiro

- Principal objetivo da pesquisa: documentar cientificamente, elaborar, sistematizar e gerenciar uma base de dados com **evidências científicas** das espécies medicinais cultivadas na coleção e seus usos, e analisar filogeneticamente as espécies e os usos.
- Foi realizada através de uma revisão bibliográfica em bases científicas (Scopus, PubMed, Periódicos Capes e Googlê Acadêmico)
- Todas as evidências foram organizadas em 17 categorias de uso adaptado do Economic Botany Data Collection Standart (Cook, 1995)
- A base antiga e estruturada no Excel, foi reorganizada no GRIST pensando nos [principais contextos](https://eduardo.dalc.in/os-contextos-da-informao-sobre-biodiversidade/#more-84) relacionados a biodiversidade proposto por Dalcin (taxonômico, temporal, temático e espacial).
- Importância de utilizar termos harmônicos/padrões
- Importância de registrar os termos diretamente e de forma fiel a fonte consultada
<img src ="https://raw.githubusercontent.com/edalcin/Estrutura-de-Dados-Etnobotanicos/main/reunioesEventos/2024-08-16/imagem.jpg" width="600">


### Apresentação Camila Dantas - Registros Etnobotânicos de Naturalistas dos Séculos XVII e XIX

- Estuda duas principais obras, o Historia naturalis Brasiliae de Piso e Marcgraf (1648) e base sistematiza HNB de Alcântara-Rodriguez (2019 e 2021). E a outra de Martius (1843) e a versão traduzida por Graças-Brandão (2023)
- Importância de consultar as obras originais
- Os dados relacionados a língua são complexos e existem materias para utilizar como base (IBGE)

### Apresentação Mateus Salim - Uso e manejo de plantas medicinais por agricultores familiares do município de Petrópolis.

- Estuda sobre as plantas medicinais utilizadas no Brejal e no Bonfim localizadas na região de Petrópolis
- Os dados foram coletados através de entrevistas e questionários semi-estruturados
- Sistematizou os usos de acordo com Economic Botany Data Collection Standart (Cook, 1995)
- Importância da harmonização dos termos
- Pensar em como harmonizar os termos relacionados a saúde de forma inclusiva e ética
- Estudar trabalhos de sociologia rural
- *"Primazia de quem fala"* (Carlos Coimbra)

### Alysson Barbosa - breve apresentação

- Irá investigar as samambaias e os possível usos de quatro comunidades que falam 9 línguas diferente nas regiões do Morro de Seis Lagos e São Gabriel da Cachoeira
- A região do  Rio Negro há um grande potencial de diversidade de espécies devido a heterogamia de relações pessoais entre as comunidades

### Discussão final

Pensar nos sistemas de organização em coleções biológicas, priorizando a forma de organização e os principais dados em coleções etnobotânicas.
