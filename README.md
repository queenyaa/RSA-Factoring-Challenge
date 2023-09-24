Readme of RSA Factoring Challenge

```
# Prime Factors Finder

This is a Python script that reads a file containing natural numbers and factors them into a product of two prime numbers (`p` and `q`).

## Usage

### Requirements

- Python 3.x

### Running the Script

1. Save the script as `prime_factors.py`.
2. Make the script executable: `chmod +x prime_factors.py`.
3. Create a text file (`input.txt`) containing the natural numbers you want to factor, with one number per line.
4. Run the script with the following command:

   ```bash
   ./prime_factors.py input.txt
   ```

   Replace `input.txt` with the name of your input file.

### Output Format

The script will print the factorization in the following format for each number:

```
n = p * q
```

- `n` is the input number.
- `p` and `q` are prime numbers that multiply to give `n`.

If no two prime factors are found for a number, the script will report that no two prime factors were found.

## Example

Input (`input.txt`):

```
15
21
35
```

Output:

```
15 = 3 * 5
21 = 3 * 7
35 = 5 * 7
```

## Note

- The script checks for primality of factors to ensure that both `p` and `q` are prime numbers.
- If a number is prime and cannot be factored into two smaller prime numbers, it will report that no two prime factors were found.
