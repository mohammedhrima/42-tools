# 42-tools

A couple of small helper tools I used while working on 42 projects.

## `map_generator_so_long`

Generates a random valid `.ber` map for the So_long project (walls, a player, collectibles and an
exit). C, no dependencies.

```sh
cd map_generator_so_long
cc map_generator.c
./a.out <height> <width>   # writes map.ber
```

## `push_swap_tester`

Tests a push_swap binary: generates random numbers, replays the operations push_swap prints, and
checks the result is sorted while counting the moves. C + Python, built with make. Expects your
`push_swap` one directory up.

```sh
cd push_swap_tester
make tests     # fast run
make debug     # slower, animated stack view
```
