# FIAP Ride

## Classe Passageiro

A classe Passageiro representa uma pessoa que utiliza o sistema de transporte FIAP Ride.

O passageiro possui nome, CPF e saldo.

### Métodos

O método `adicionarSaldo()` adiciona dinheiro ao saldo do passageiro. O valor precisa ser maior que zero.

O método `pagarViagem()` desconta o valor da viagem do saldo. O valor precisa ser maior que zero e o passageiro precisa ter saldo suficiente.

### Exemplo

```java
Passageiro passageiro = new Passageiro("Ana Silva", "222");

passageiro.adicionarSaldo(50.0);
passageiro.pagarViagem(20.0);
