### Python input
def abc(nums, K):
  .........
  
if __name__ == "__main__":
  try:
    n = int(input().strip())
    nums = list(map(int,input().split()))
    K = int(input().strip())
    print(abc(nums, K))
  except EOFError:      
    pass
