# √2 (Square Root of 2) Digit Files

This repository contains plain text files with the value of √2 (the square root of 2) truncated to different numbers of decimal places. Each file starts with `1.` followed by the digits after the decimal point (no extra whitespace or trailing newline).

## Files

| File                   | Decimal digits | File size          |
| ---------------------- | --------------- | ------------------- |
| `sqrt2_10.txt`         | 10               | 12 bytes             |
| `sqrt2_100.txt`        | 100              | 102 bytes            |
| `sqrt2_1000.txt`       | 1,000            | 1,002 bytes          |
| `sqrt2_10000.txt`      | 10,000           | 10,002 bytes         |
| `sqrt2_100000.txt`     | 100,000          | 100,002 bytes        |
| `sqrt2_1000000.txt`    | 1,000,000        | 1,000,002 bytes      |
| `sqrt2_10000000.txt`   | 10,000,000       | 10,000,002 bytes     |
| `sqrt2_50000000.txt`   | 50,000,000       | 50,000,002 bytes     |
| `sqrt2_100000000.7z`   | 100,000,000      | 100,000,002 bytes (uncompressed) |

> The `sqrt2_100000000.7z` archive needs to be decompressed.

## Example

`sqrt2_10.txt`:

```
1.4142135623
```

## Format

Each file follows the pattern:

```
1.<N digits of √2>
```

where `<N digits of √2>` is the first N digits of √2 after the decimal point.

## Source

Digits were truncated from a 160,000,000-decimal-digit reference file of √2 (only the first 100,000,000 digits are provided here).

## About

This project allows you to download a plain text file containing √2 (the square root of 2) to 100 million decimal places.
