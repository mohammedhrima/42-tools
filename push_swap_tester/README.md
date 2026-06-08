# push_swap tester

Tests a push_swap project: it generates random integers, runs your `push_swap` with them, replays the
operations it prints, and checks the stack ends up sorted (and counts the moves). It expects your
`push_swap` binary one directory up (`../push_swap`).

## Use

```bash
make tests     # fast run
make debug     # slower, animated stack view
```

You'll be prompted for the number of tests, how many numbers to generate per test, and whether to
include negatives:

```
how many tests you want:
how many generated numbers you need: 100
with negative numbers ? [y/n]:
Press Enter to start the test...
```

https://user-images.githubusercontent.com/71414472/220415001-1220c158-240b-4e61-84ad-b28af49ef487.mov
