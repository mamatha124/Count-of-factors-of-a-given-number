# Count-of-factors-of-a-given-number in python
# Approach-1
n = int(input())
c = 0
for i in range(1,n+1):
  if n%i == 0:
    c = c + 1
print(c)

# Approach-2
n = int(input())
c = 0
i = 1
while i <= n:
  if n%i == 0:
    c = c + 1
  i = i + 1
print(c)
