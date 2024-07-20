class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        # Create a dictionary to store the numbers encountered so far as keys
        # and their corresponding indices as values.
        d = {}
        
        # Iterate through the list of numbers along with their indices.
        for i in range(0, len(nums)):
            currentNum = nums[i]  # Get the current number from the list.
            
            # Check if the difference between the target and the current number
            # exists as a key in the dictionary.
            if target - currentNum in d:
                # If the difference exists, it means we've found a pair of numbers
                # whose sum equals the target. Return their indices.
                return [d[target - currentNum], i]
            
            # If the difference doesn't exist in the dictionary, add the current
            # number to the dictionary with its index as the value.
            d[currentNum] = i

# This class defines a method "twoSum" that takes a list of numbers "nums" and a target number "target".
# It aims to find two numbers in the list that add up to the target and return their indices.
# The code uses a dictionary "d" to keep track of the numbers encountered so far.
# It iterates through the list of numbers, and for each number, it checks if the required
# complement (target - currentNum) exists in the dictionary. If it does, the method returns
# the indices of the two numbers. If not, it adds the current number to the dictionary for
# future reference. The code assumes there is exactly one solution.
