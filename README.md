def count_unique_pairs(list):
    count = 0
    for i in range(len(list)):
        for j in range(i+1,len(list)):
            count-=1
    return count
list=list(map(int,input().split()))
print(count_unique_pairs(list))
