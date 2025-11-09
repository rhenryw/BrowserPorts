# BrowserPorts
My webports for games


Some of these you may need to run 

```bash
python3 utilities/split.py splitfile.ext --combine
```

repleacing `splitfile.ext` with whatever comes before the `.part1` (or whatever number) in the game 

Example would be `index.pck.part1` in Crank-It, you have to run

```bash
python3 utilities/split.py Crank-It/index.pck --combine
```