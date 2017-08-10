# Calculadora de minado de Ethereums
Pueden ver la version en vivo funcionando de la [Calculadora de minado de Ethereums](https://avilaroman.github.io/ethereum-mining-calculator/).

## Cálculos

Prácticos para poder llegar a Calcular el ROI de una inversion en RIGs de minado.

### Network hashrate 

Nosotros estimamos el hashrate en "GH" usando la siguiente ecuación:

```
netHashGH = (difficulty / blockTime) / 1e9;
```

Donde `difficulty` es la actual dificultad para minar un bloque y `blockTime` es el tiempo del bloque actual de la red, están adquiridos en timpo real ambos datos del BlockChain.
