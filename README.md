# Write-a-program-to-find-all-numbers-that-are-divisible-by-7-but-not-multiples-of-5-within-10-and-20
Write a program to find all numbers that are divisible by 7 but not multiples of 5, within 10 and 200 (including 10 and 200). The resulting numbers will be printed as a string on one line, separated by commas.
arr = []
for i in range(10, 201):
    if (i % 7 == 0) and (i % 5 != 0):
        arr.append(str(i))
print (', '.join(arr))
