# Descrição
Neste desafio, você criará uma solução para um sistema bancário utilizando conceitos de orientação a objetos. A implementação solicitada pela equipe de desenvolvimento da empresa bancária, gostaria de fosse realizado uma melhoria no sistema de registros, onde é recebido os dados brutos dos registros bancários. O objetivo é obter as informações de uma forma mais amigavel para o cliente e não oferecer informações brutas.

Considere que cada transação é representada por apenas uma string contendo as seguintes informações:
## Como Funciona

Cada transação é representada por uma string contendo os seguintes campos:

```
data,hora,descricao,valor
```

A classe `Transacoes` recebe essa string de entrada e extrai os seguintes atributos:

- Data
- Hora
- Descrição
- Valor

A saída é formatada de forma amigável, apresentando a transação efetuada com os detalhes a seguir:

```
Descrição: [Descrição]
Data: [Data]
Hora: [Hora]
Valor: [Valor]
```

## Exemplos

Aqui estão alguns exemplos de entrada e as respectivas saídas esperadas:

### Exemplo 1:

Entrada:

```
01/02/2023,09:00:00,Deposito,100.00
```

Saída:

```
Descrição: Deposito
Data: 01/02/2023
Hora: 09:00:00
Valor: 100.00
```

### Exemplo 2:

Entrada:

```
11/05/2023,11:15:00,Transferencia,25.00
```

Saída:

```
Descrição: Transferencia
Data: 11/05/2023
Hora: 11:15:00
Valor: 25.00
```

### Exemplo 3:

Entrada:

```
21/09/2023,10:30:00,Saque,30.00
```

Saída:

```
Descrição: Saque
Data: 21/09/2023
Hora: 10:30:00
Valor: 30.00
```
