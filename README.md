# Coletando daos IBGE, Armazenando no BigQuery e Preenchendo PPT 
Este código coletar dados do IBGE utilizando o SIDRA (Sistema IBGE de Recuperação Automática), que é uma plataforma do IBGE criada com o objetivo de consultar as pesquisas criados e disponibilizadas pelo Instituto, e armazena os dados Gerados no BigQuery e preenche um PPT

O objetivo será mostrar como é possível acessar dados dados do SIDRA utilizando o Python, para exemplificar estarei utilizando a tabela de estimativa populacional por Municipio, preencher um PPT.

Existe um módulo python chamado sidrapy que permite baixar facilmente estes dados e realizar a importação direta para um dataframe Pandas.

Referências que utilizei para construir o código:
- https://pypi.org/project/sidrapy/ => Documentação oficial módulo sidrapy no pipy
- https://sidrapy.readthedocs.io/pt_BR/latest/modules/table.html => documentação do sidrapy (achei esta mais detalhada)
- https://sidra.ibge.gov.br/acervo => Pagina para consultar tableas disponiveis
- https://apisidra.ibge.gov.br/ => Documentação da API

> Para utilizar os códigos será necessário instalar os módulos contidos no arquivo requirements.txt atrvés do comando abaixo. 
> 
> ``` pip install -r requirements.txt ```
> 
