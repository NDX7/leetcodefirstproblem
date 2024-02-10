class Solution(object):
  def twoSum(self, nums, target):
    # Iterate over the numbers in the array.
    for i in range(len(nums)):
        # For each number, iterate over the rest of the numbers in the array.
        for j in range(i+1, len(nums)):
            #  Check if the current two numbers add up to the target.
            if nums[i] + nums[j] == target:
                return [i, j]
    #  If no such pair is found, return an empty list.
    return []

