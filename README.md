# Basic-of-Stack
package Stacks;
import java.util.*;
public class basicsOfStacks {
    public static void main(String[] args) {
        Stack<Integer> st=new Stack<>();
        st.push(1);  //add=push
        st.push(23);
        st.push(90);
        st.push(5);
        // topmost isme 5 h
        // agar ab value return krwani ho toh
        System.out.println((st.peek()));
        System.out.println(st); // to print whole stack
        st.pop();
        System.out.println(st);// toh isme se topmost wala hat jyega
        System.out.println(st.size()); // to print the size

    }
}
