# Tempo

## Classe para representar o tempo

![relogio](https://i.pinimg.com/originals/99/bd/a6/99bda67dc6f2481597d4050a0f4bbacc.gif)

- Possui 4 construtores
- Há uso de modificadores de acesso
- Método toString() para retorno de tempo no formato 00:00:00
- Métodos para alterar hora, minuto ou segundo
- Método para retorno do tempo em segundos
- Método para retornar diferença entre dois tempos

## Como usar a classe Tempo():

- Objetos do tipo Tempo podem ser construidos com valores nulos, somente hora, hora e minuto ou hora minuto e segundo definidor pelo usuário.
Para isso deve-se enviar os parâmetros desejáveis, lembrando que os atributos que não receberam nenhum parâmetro no construtor 
será iniciado com zero (a ordem é: (hora, minuto, segundo)).

- Método toString() retorna o tempo no formato 00:00:00, e para isso deve-se utilizar o método Sistem.out.print();

- Métodos para modificar hora (setHora()), minuto (setMin()) e segundo (setSeg()), retornando true (mudança feita) ou false (quando há erro).

- Método que retorna um long com o valor total do tempo em segundos.

- Método que retorna um long com a diferença de dois tempos em segundos.


![relogio](https://www.altoastral.com.br/wp-content/uploads/2016/08/relogio-velho.gif)
