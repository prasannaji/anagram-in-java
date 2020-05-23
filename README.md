# anagram-in-java
 to check whether two given strings are anagram of each other or not. An anagram of a string is another string that contains same characters, only the order of characters can be different. For example, “prasanna” and “annapras” are anagram of each other.

import java.util.*;
class Main
{
  public static void main(Sting[] args)
  {
    Scanner obj = new Scanner(System.in);
    String s1 = obj.nextLine();
    String s2 = obj.nextLine();
    String[] str1 = s1.split("");
    String[] str1 = s1.split("");
    Arrays.sort(str1);
    Arrays.sort(str2);
    if(Arrays.deepEquals(str1,str2))
    {
       System.out.println("the given word is annnagram");
    }
    else
    {
       System.out.println("the given word is annnagram");
    }
  }
}   
