# java2
program to create mirror image in java
package com.company;

public class mirror {
    public static int[] mirror(int[] nums)
    {
        int[] result = new int[nums.length];
        for(int p=0;p<nums.length;p++)
        {
            int c = nums[p];
            result[c] = p;
        }
    }
}
