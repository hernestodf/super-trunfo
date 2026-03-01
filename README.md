# Super Trunfo - Jogo de Cartas em C

Trabalho acadêmico de Programação em C - Implementação do jogo Super Trunfo

## 📋 Sobre

Este projeto contém dois programas:
- **gerador_cartas.c**: Gera 16 cartas com atributos aleatórios
- **super_trunfo.c**: Jogo principal para 2 jogadores

## 🎮 Regras
- 2 jogadores, 4 cartas cada
- 4 rodadas
- Vitória = 2 pontos, Empate = 1 ponto
- Jogadores alternam na escolha dos atributos

## 🚀 Como executar

```bash
# Compilar gerador
gcc -o bin/gerador src/gerador_cartas.c
./bin/gerador

# Compilar jogo
gcc -o bin/super_trunfo src/super_trunfo.c
./bin/super_trunfo
