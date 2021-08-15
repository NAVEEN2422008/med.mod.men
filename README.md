# med.mod.men

Three short Python scripts that compute the mean (men), median (med), and mode (mod) of a height/weight dataset.

## Features
- Reads `SOCR-HeightWeight.csv` using the `csv` module
- Computes the arithmetic mean of the second numeric column
- Computes the median with correct even/odd-length handling
- Computes the mode into specified ranges via `Counter`

## Tech Stack
- Python 3, standard library (`csv`, `collections.Counter`)

## Project Structure
```
m,m,m/
  med.py       # median calculator
  men.py       # mean/average calculator
  mod.py       # mode-by-range calculator
  SOCR-HeightWeight.csv   # input data
```

## Installation
No dependencies — Python 3 only.

## Usage
```
python m,m,m/med.py
python m,m,m/men.py
python m,m,m/mod.py
```
Run each from the project root so the CSV is found; results print to stdout.