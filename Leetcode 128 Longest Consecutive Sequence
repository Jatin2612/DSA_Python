class Solution:
    def longestConsecutive(self, nums: list[int]) -> int:
        my_set = set(nums)
        
        longest = 0 
        for nums in my_set:
            if nums - 1 not in my_set:
                x = nums
                count = 1
                while x + 1 in my_set:
                    count += 1
                    x += 1
                longest = max(longest, count)
        return longest 
        
