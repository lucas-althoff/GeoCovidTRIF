# GeoCovidTRIF
Repositório para controle de versão do Sistema de Geoprocessamento de Informações de COVID-19 da Tríplice Fronteira- BR - CO - PE. Este sistema é mantido com o apoio do IRD.

### Requisitos
- [QGIS 3.16](https://www.qgis.org/pt_BR/site/forusers/download.html)
- [Lizmap plugin](https://github.com/3liz/lizmap-plugin)

### Link para acesso:
- [Plataforma QGIS - Uso Padrão](https://cartogy.cayenne.ird.fr/index.php/view/map/?repository=trifrontiere&project=trif)
- Página da Plataforma (em desenvolvimento)

### Princípios para a construção da ferramenta: 
- Leve para acesso remoto com baixa disponibilidade de internet
- Informações estatísticas
- Dados Harmonizados
- Bases Oficiais
- Oferecer informação sobre critérios de harmonização dos indicadores e dados

<br />

### Controle de Versão do Sistema:

<img align="center" alt="System Version Control" width="1800px" src="https://github.com/lucas-althoff/GeoCovidTRIF/blob/main/ADM_GeoCovidTRIF.PNG" />

<br />

### Bases de dados

**Peru**
> [Base de Dados Governamental Covid](https://www.diresaloreto.gob.pe/covid)

**Brasil**
> [FVS e - Brasil](http://www.fvs.am.gov.br/transparenciacovid19_dadosepidemiologicos)

> [Gov Amazônia](http://www.saude.am.gov.br/painel/corona/)

**Colômbia** 
> [Panél de Covid](https://app.powerbi.com/view?r=eyJrIjoiMjBjZWNlOGUtNzc1Yi00NjVkLTkyMjktOTJmMGU3YTU2Nzk4IiwidCI6ImE2MmQ2YzdiLTlmNTktNDQ2OS05MzU5LTM1MzcxNDc1OTRiYiIsImMiOjR9&pageName=ReportSection0c50ea3406afe4407370)
 
Tabela de Qualidade de Dados Por Indicador
|   | Casos Nac.  | Casos p/ Loc.  | Óbitos Nac.  | Óbitos p/ Loc. |Vacina Nac| Vacina Loc.|
|---|---|---|---|---|---|---|
| Brasil  |  :heavy_check_mark: | :heavy_check_mark:  | :heavy_check_mark:  |  :heavy_check_mark: |:clock9:|:clock9:|
| Peru  |  :heavy_check_mark: | :x:  | :heavy_check_mark:  | :x: | :clock9:|:clock9:|
| Colômbia  |  :heavy_check_mark: | :heavy_check_mark:  |  :heavy_check_mark: |  :heavy_check_mark: |:clock9:|:clock9:|
