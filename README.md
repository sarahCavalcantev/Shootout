# COWBOY SHOOTOUT - Duelo em Assembly x86_64 (Linux)

**COWBOY SHOOTOUT** é um minijogo de reação desenvolvido em Assembly NASM para Linux 64 bits. Feito com base no jogo Shootout da revista Computer Battlegames For zx Spectrum na adeira de Oganização de Computadores e Linguagens de Montagem I. O jogador deve reagir rapidamente após o inimigo sacar a arma, mas perde automaticamente se atirar antes da hora.

---

## Requisitos

- Sistema operacional Linux 64 bits
- NASM (Netwide Assembler)
- `ld` (GNU Linker)

---

## Compilação e Exec

```bash
nasm -f elf64 cowboy64.asm -o cowboy64.o
ld cowboy64.o -o cowboy64
./cowboy64

