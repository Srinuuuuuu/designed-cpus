# 8-bit CPU (Logisim Evolution)

An 8-bit CPU designed in Logisim Evolution, capable of executing simple programs compiled from C.

## Files

| File | Description |
|------|-------------|
| `CPU.circ` | Main circuit file — open in Logisim Evolution |
| `program.hex` | ROM program in Logisim hex format (v2.0 raw) |
| `ram_contents.txt` | Initial RAM data loaded at startup |

## How to Run

1. Install [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution)
2. Open `CPU.circ`
3. Load `program.hex` into the ROM component
4. Load `ram_contents.txt` into the RAM component
5. Click the clock or enable auto-tick to run the program

## Program

The included `program.hex` contains:

```
1850 0810 2851 1130 0811 3019 4012 10B0 5010
```

These are encoded instructions stored in ROM that the CPU fetches, decodes, and executes each clock cycle.
