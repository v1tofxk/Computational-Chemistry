# Introdução ao Formato XYZ em Química Computacional 🧬

O formato XYZ é uma notação comumente utilizada em química computacional para representar as coordenadas tridimensionais de átomos em uma molécula. Essa representação simples fornece informações cruciais sobre a geometria molecular, sendo amplamente empregada em cálculos e simulações químicas.

## Estrutura Básica do Formato XYZ

- Número Total de Átomos: A primeira linha do arquivo XYZ indica o número total de átomos na molécula.

- Comentário (Opcional): A segunda linha pode conter um comentário que fornece informações adicionais sobre a molécula.

- Coordenadas dos Átomos: A partir da terceira linha, cada linha representa um átomo e inclui informações sobre o tipo de átomo e suas coordenadas x, y e z.

 ## Exemplo Prático:

```bash
3
Molécula de Água
O   0.00000   0.00000   0.00000
H   0.75760   0.58640   0.00000
H  -0.75760   0.58640   0.00000
```

Peimeira coluna - Simbolo atômico
Segunda coluna - Quarta coluna -  Cordenadas

## Lembrando que..

- Muitas vezes essas 3 cordenadas são redundantes pq podemos mover a molécula desde onde começamos 
- Podemos somar ou subtrair uma constante pra cada uma dessas colunas e ela vai continuar sendo a mesma molécula
- Você pode ter 3 rotações caso seja uma molécula não linear, caso seja linear você tem 2
- Se a sua molécula for não linear ela tem 3N-6 Cordenadas únicas, já se for linear você tem 3N-5
