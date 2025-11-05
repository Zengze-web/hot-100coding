package com.zoke.leetcode;

import org.testng.annotations.Test;

import java.util.Arrays;

public class MoveZero {

    @Test
    public void movingZero(int[]num){
        int n = num.length;
        int left = 0;
        int right = 0;
        while (right<n){
            if (num[right] !=0){
                swap(left,right,num);
                left++;
            }right++;

        }

    }
    public void swap(int left,int right,int []num){
        int temp  = num[left];
        num[left] = num[right];
        num[right] = temp;

    }
}
