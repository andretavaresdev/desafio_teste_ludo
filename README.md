# Ludo

## Especificação do desafio

Partida de Ludo com dois jogadores e quatro peões para cada um. O jogo utiliza dado de seis faces. A saída da base, a movimentação, as capturas, as casas seguras, a reta final e a vitória seguem as regras implementadas no código.

## Funcionamento dos casos de teste

Os testes são escritos em JavaScript e executados com Jest. Cada teste verifica o resultado esperado de uma operação. Os casos também cobrem erros de entrada e situações nos limites das regras.

| Arquivo | Verificação |
|---|---|
| `tests/dado.test.js` | Valores possíveis, sequência de rolagens e validações do dado. |
| `tests/ludo.test.js` | Estado inicial, saída, movimentação, turnos, capturas, casas seguras e vitória. |
| `tests/personalizacao.test.js` | Verificações adicionais de limites e consistência. |

## Como executar

```bash
npm ci
npm test
```

## Colaborador

- André Tavares (RA: 24066498-2)
