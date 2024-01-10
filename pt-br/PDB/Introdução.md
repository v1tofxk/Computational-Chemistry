# Introdução ao Formato PDB (Protein Data Bank) 🧬

O **formato PDB**, ou Protein Data Bank, é um padrão amplamente utilizado para representar informações estruturais de macromoléculas biológicas, como proteínas e ácidos nucleicos. O Protein Data Bank é um repositório global que armazena e distribui dados sobre a estrutura tridimensional de biomoléculas.

## Uso do Formato PDB

O formato PDB é essencial para a comunicação eficaz de dados estruturais entre pesquisadores e é amplamente utilizado em biologia estrutural, bioinformática e pesquisas relacionadas. Ele permite a visualização tridimensional de estruturas moleculares, a análise de interações atômicas e é crucial para a compreensão das funções biológicas das macromoléculas.

## Ferramentas e Aplicações

Diversas ferramentas e softwares foram desenvolvidos para manipular e visualizar arquivos PDB, facilitando a análise e a interpretação de estruturas moleculares. Além disso, o acesso ao Protein Data Bank (PDB) online permite que pesquisadores compartilhem, busquem e baixem dados estruturais para suas investigações.

Em resumo, o formato PDB desempenha um papel vital na pesquisa biológica, fornecendo uma representação detalhada das estruturas tridimensionais das macromoléculas e promovendo a colaboração e o avanço do conhecimento na área da biologia molecular.

```bash
ATOM  6  CG  PRO  A  1  29.296  37.591  7.162  1.0  38.40  C  
```

## Como funciona
#### Campo 1 (ATOM): Indica o tipo de registro, que neste caso é um átomo.

#### Campos 2-6 (6 CG PRO A 1): Informações sobre o átomo e sua localização:
- 2 (6): Número do átomo no modelo (número sequencial).
- 3 (CG): Nome do átomo.
- 4 (PRO): Nome do resíduo (nesse caso, o resíduo é prolina).
- 5 (A): Identificador da cadeia (neste caso, cadeia A).
 - 6 (1): Número do resíduo na sequência.

#### Campos 7-8 (29.296 37.591): Coordenadas tridimensionais do átomo:
  - 7 (29.296): Coordenada x.
  - 8 (37.591): Coordenada y.

#### Campos 9-10 (7.162 1.0): Mais informações sobre o átomo:
  - 9 (7.162): Coordenada z.
  - 10 (1.0): Ocupância do átomo (neste caso, 1.0 indica totalmente ocupado).

#### Campos 11-12 (38.40 C): Mais informações sobre o átomo:
   - 11 (38.40): Fator de temperatura (ou B-factor), que reflete a vibração térmica do átomo.
   - 12 (C): Elemento químico do átomo.

Em muitas linhas você verá muito sobre "records", que se refere a linhas específicas que contêm informações estruturais sobre a macromoléculas em questão.

Os principais registros em um arquivo PDB:
- HEADER: Fornecendo informações gerais sobre a entrada, como o nome da molécula e sua classe.

- ATOM e HETATM: Descrevendo as coordenadas atômicas da estrutura, indicando o tipo de átomo, sua posição tridimensional, e outros detalhes relacionados.

- CONECT: Especificando as ligações entre átomos.

- REMARK: Contendo comentários e informações adicionais.

- SEQRES: Listando as sequências de aminoácidos ou nucleotídeos.

- TER: Indicando o término de uma cadeia de átomos.
