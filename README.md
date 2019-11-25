# Análise dados Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP)

Análise de dados de docentes e discentes de ensino superior brasileiro quanto à raça/cor, gênero e nível acadêmico.
Trabalho realizado para a discliplina de Estrutura de Dados da Faculdade de Tecnologia de São José dos Campos, sob supervisão do [Professor Fernando Massanori](https://github.com/fmasanori)

- [Dados acerca dos Docentes](https://github.com/CauaneAndrade/analise-dados-inep/blob/master/Dados_de_docentes.ipynb)
- [Dados acerca dos Discentes](https://github.com/CauaneAndrade/analise-dados-inep/blob/master/Dados_de_discentes.ipynb)

## Dicionário de variáveis utilizadas nos códigos fontes
'''
# Dicionário de dados de docentes
– Categoria Administrativa
A) Pública Federal: DM_DOCENTE.TP_CATEGORIA_ADMINISTRATIVA = 1 <br>
B) Pública Estadual: DM_DOCENTE.TP_CATEGORIA_ADMINISTRATIVA = 2 <br>
C) Pública Municipal: DM_DOCENTE.TP_CATEGORIA_ADMINISTRATIVA = 3 <br>
D) Privadas: DM_DOCENTE.TP_CATEGORIA_ADMINISTRATIVA IN (4,5) <br>
E) Especial: DM_DOCENTE.TP_CATEGORIA_ADMINISTRATIVA = 7 <br>
Para a Sinopse, a Categoria Administrativa Especial foi somada com a Municipal.

## Organização Acadêmica
A) Universidade: DM_DOCENTE.TP_ORGANIZACAO_ACADEMICA = 1 <br>
B) Centro Universitário: DM_DOCENTE.TP_ORGANIZACAO_ACADEMICA = 2 <br>
C) Faculdade: DM_DOCENTE.TP_ORGANIZACAO_ACADEMICA = 3 <br>
D) Instituto Federal: DM_DOCENTE.TP_ORGANIZACAO_ACADEMICA IN (4,5) <br>
Para a Sinopse, as Organizações Acadêmicas Instituto Federal de Educação, Ciência e Tecnologia e Centro Federal de
Educação Tecnológica foram agregadas.

## Grau de Escolaridade do Docente
A) Sem Graduação: DM_DOCENTE.TP_ESCOLARIDADE_DOCENTE = 1 <br>
B) Graduação: DM_DOCENTE.TP_ESCOLARIDADE_DOCENTE = 2 <br>
C) Especialização: DM_DOCENTE.TP_ESCOLARIDADE_DOCENTE = 3 <br>
D) Mestrado: DM_DOCENTE.TP_ESCOLARIDADE_DOCENTE = 4 <br>
E) Doutorado: DM_DOCENTE.TP_ESCOLARIDADE_DOCENTE = 5

## Regime de Trabalho do Docente
A) Tempo Integral com dedicação exclusiva: DM_DOCENTE.TP_REGIME_TRABALHO = 1 <br>
B) Tempo Integral sem dedicação exclusiva: DM_DOCENTE.TP_REGIME_TRABALHO = 2 <br>
C) Tempo Parcial: DM_DOCENTE.TP_REGIME_TRABALHO = 3 <br>
D) Horista: DM_DOCENTE.TP_REGIME_TRABALHO = 4

## Sexo do Docente
A) Feminino: DM_DOCENTE.TP_SEXO= 1 <br>
B) Masculino: DM_DOCENTE.TP_SEXO= 2

## Cor/Raça do Docente
A) Branca: DM_DOCENTE.TP_COR_RACA= 1 <br>
B) Preta: DM_DOCENTE.TP_COR_RACA= 2 <br>
C) Parda: DM_DOCENTE.TP_COR_RACA= 3 <br>
D) Amarela: DM_DOCENTE.TP_COR_RACA= 4 <br>
E) Indígena: DM_DOCENTE.TP_COR_RACA= 5 <br>
F) Não dispõe da informação: DM_DOCENTE.TP_COR_RACA= 9 <br>
G) Docente não quis declarar cor/raça: DM_DOCENTE.TP_COR_RACA= 0
'''
