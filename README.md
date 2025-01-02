class Solution{ public boolean isPalindrome(int x) { if (x<0) { return false; }

    int num x;
    int rem 0;

   while(num!=0)
   {
     rem = rem * 10 + num % 10;
     num = num/10;
   }
   return rem == x;
} }
