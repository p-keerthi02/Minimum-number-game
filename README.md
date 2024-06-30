class Solution:
    def numberGame(self, nums: List[int]) -> List[int]:
        nums.sort()
        x=[]
        while nums:
            i=nums.pop(0)
            j=nums.pop(0)
            x.append(j)
            x.append(i)
        return x
