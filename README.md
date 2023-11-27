# Move-Zeros-using-Java-Leetcode

    class Solution {
        public void moveZeroes(int[] nums) {
            int j= 0;
            for(int i =0; i<nums.length;i++){
                if(nums[i]!=0){
                    nums[j] = nums[i];
                    j++;
                }
            }
            while(j<nums.length){
                nums[j]=0;
                j++;
            }
        }
    }

289 Move Zeros in Leetcode

Idea:
Our task is to move zero value to last in an array. My approach is traversing an array linearly if an array element not equal to zero. I will assign to element first in an array and increase the index to point the next index. Moving to next again and again finally I will get a last non zero value. Now j value is equal to number of non zero value right! In here I will assign a balance elements in an array to zero. That's it I will get an answer.         



