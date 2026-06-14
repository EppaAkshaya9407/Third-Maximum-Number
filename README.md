# Third-Maximum-Number
nums = list(map(int, input("Enter numbers: ").split()))
nums = set(nums)
n = len(nums)
if n <= 2:
    print(max(nums))
elif n == 3:
    print(min(nums))
else:
    r = sorted(list(nums))
    m = len(r)
    print(r[m - 3])
