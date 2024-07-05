# Ajay-markdown
Code_Notes

##Two sum
``` python
def twosum(nums,target):
    dic={}
    for i in range(0,len(nums)):
         val=nums[0]
         diff=target-val
         if val not in dic:
              dic[diff]=i
         else:
              return [i,dic[val]]

```
