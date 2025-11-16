def separate_even_odd(numbers):
    evens = [n for n in numbers if n % 2 == 0]
    odds = [n for n in numbers if n % 2 != 0]
    return evens, odds

if __name__ == "__main__":
    nums = [5, 12, 7, 20, 33, 40]
    evens, odds = separate_even_odd(nums)
    print(f"Even numbers: {evens}")
    print(f"Odd numbers: {odds}")
