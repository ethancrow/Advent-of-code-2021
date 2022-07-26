nums = open('input.txt', 'r', encoding='utf-8').read().splitlines()
numbers = [int(x) for x in nums]
increases = sum(x < y for x, y in zip(numbers, numbers[1:]))
print(increases)
