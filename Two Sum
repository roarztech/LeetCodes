nums = []
while True:
    num = input("Enter a value (or press Enter to stop): ")
    if num == "":
        break
    nums.append(int(num))
target = int(input("What's your target: "))
print(nums)

for i in range(len(nums)):
    for j in range(i + 1, len(nums)):
        if nums[i] + nums[j] == target:
            print([i, j])
