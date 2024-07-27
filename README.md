# Anagram-or-not-in-Java
import java.util.*;
public class Main{
    public static void main(String[] args){
        String s1="top";
        String s2="pot";
        char[] c1=s1.toCharArray();
        char[] c2=s2.toCharArray();
        Arrays.sort(c1);
        Arrays.sort(c2);
        if(Arrays.equals(c1,c2)){
            System.out.println("Both are Anagram");
        }else{
            System.out.println("Not anagram");
        }
    }
}
