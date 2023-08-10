# linkedlist
K-th element in linked list
public class Solution {
    public int solve(ListNode A, int B) {
        ListNode h=A;
        for(int i=0; i<B; i++){
        if(h==null){
            break;
        }
            if(i==B){
               return h.val;
            }
            h=h.next;
        }
        return h.val;
    }
}
 
