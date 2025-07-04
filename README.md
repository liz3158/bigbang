# BIG BANG Number Generator 🔢💥

This Node.js script generates an array of numbers from 1 to 100, replacing:
- Numbers divisible by **3** with `"BIG"`
- Numbers divisible by **5** with `"BANG"`
- Numbers divisible by **both 3 and 5** with `"BIGBANG"`

The result is saved to a file called `output.json`.

## Files Included

- `bigbang.js` — The main JavaScript script that generates the output  
- `output.json` — The output JSON file containing the generated array (created after script runs)  
- `README.md` — Instructions for setup and usage  

## How to Run

### 1. Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your computer.

Check your Node.js version by running:

```bash
node -v
````

### 2. Run the Script

Open a terminal in the folder where `bigbang.js` is located, then run:

```bash
node bigbang.js
```

After running the script, a file named `output.json` will be created in the same directory, containing the result array.
