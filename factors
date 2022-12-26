#!/usr/bin/python3

import sys

"""Defining the integer"""

def factorize(n):
    for i in range(2, int(n**0.5)+1):
        if n % i == 0:
            return (i, n//i)
    return (n, 1)

"""Defining the factors"""

def main():
    for line in sys.stdin:
        n = int(line.strip())
        p, q = factorize(n)
        print(f"{n} = {p} * {q}")

if __name__ = ""__main__":
    main()
