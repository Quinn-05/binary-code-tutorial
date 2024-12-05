# Converting Between Binary and Decimal

## Binary to Decimal
To convert a binary number to decimal, you simply sum the values of the bits that are set to `1`. The place values for binary are powers of 2. For example:

### Example 1:
Binary: `1011`

Steps:
- Starting from the right, the place values are: `1, 2, 4, 8`.
- Now, multiply each bit by its corresponding place value:
  - `1 x 8 = 8`
  - `0 x 4 = 0`
  - `1 x 2 = 2`
  - `1 x 1 = 1`

Sum: `8 + 0 + 2 + 1 = 11` (Decimal)

### Example 2:
Binary: `1101`

Steps:
- Place values: `1, 2, 4, 8`
- Multiply each bit:
  - `1 x 8 = 8`
  - `1 x 4 = 4`
  - `0 x 2 = 0`
  - `1 x 1 = 1`

Sum: `8 + 4 + 0 + 1 = 13` (Decimal)

## Decimal to Binary
To convert from decimal to binary, repeatedly divide the decimal number by 2, recording the remainder. For example:

### Example:
Decimal: `13`

Steps:
- `13 ÷ 2 = 6, remainder 1`
- `6 ÷ 2 = 3, remainder 0`
- `3 ÷ 2 = 1, remainder 1`
- `1 ÷ 2 = 0, remainder 1`

Reading the remainders from bottom to top gives the binary number: `1101`
