# Meta Careers Coding Puzzles: My Solutions

My solutions to the practice puzzles on the Meta Careers coding-puzzle page, written while preparing for interviews. Each file is named after a puzzle and has no file extension. Most are **Python 3**, a few are **C++**. Each file defines only the function the puzzle asks for (for example `getMaxAdditionalDinersCount` in `Cafeteria`), so you need a small driver to run it.

Puzzles: ABCs, All Wrong, Battleship, Cafeteria, Director of Photography (Ch. 1 and 2), Hops, Kaitenzushi, Missing Mail, Portals, Rabbit Hole (Ch. 1), Rotary Lock (Ch. 1 and 2), Scoreboard Inference (Ch. 1 and 2), Stack Stabilization (Ch. 1), Tunnel Time, Uniform Integers.

## Run

```bash
# Python solutions
python3 -c "exec(open('ABCs').read()); print(getSum(1, 2, 3))"

# C++ solutions (for example Hops, Kaitenzushi): write a wrapper with main() that includes the file
g++ -std=c++11 -o sol wrapper.cpp && ./sol
```

## License

MIT, see `LICENSE`.
