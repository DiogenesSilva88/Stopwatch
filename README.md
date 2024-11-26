# Contador de Tempo (Timer)

Este é um programa simples em C# que simula um contador de tempo, onde você pode definir um intervalo de tempo em segundos ou minutos para o temporizador.

## Funcionalidade

O programa possui um menu interativo onde você pode inserir o tempo desejado e escolher se ele será em segundos ou minutos. O temporizador contará o tempo até zerar e, em seguida, retornará ao menu.

### Como funciona:
1. O programa exibe as opções para o usuário:
   - `S = Segundo` (Exemplo: 10s = 10 segundos)
   - `M = Minuto` (Exemplo: 1m = 1 minuto)
   - `0 = Sair`
2. O usuário insere o tempo desejado, e o contador começa.
3. O temporizador conta o tempo e exibe o tempo restante até chegar a zero.
4. Após o tempo acabar, ele exibe "Stopwatch finalizado!" e retorna ao menu inicial.

## Como usar

1. Clone o repositório ou copie o código para o seu ambiente de desenvolvimento.
2. Compile e execute o programa.
3. O programa irá pedir para você inserir um valor de tempo no formato `10s` ou `1m`:
   - Exemplo de entrada: `10s` para 10 segundos.
   - Exemplo de entrada: `2m` para 2 minutos.
4. Após inserir o valor, o contador começará a contagem regressiva.
5. O temporizador terminará quando o tempo chegar a zero, e o programa retornará ao menu.

## Exemplo de uso

```bash
S = Segundo => 10s = 10 segundos
M = Minuto => 1m = 1 minuto
0 = Sair
Quanto tempo deseja contar?
