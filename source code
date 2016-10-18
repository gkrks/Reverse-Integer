
public class Solution {
    public int reverse(int x) {
        int sum = 0, p;
        int n = Math.abs(x);
        while(n!=0){
            int r = n%10;
            sum = (sum * 10) + r;
            n = n / 10;
        }
        if(x > 0 && x <= 2147447412){
            p = sum;
        }
        else{
            if(x < 0 && x >= -2147447412 ){
                p = sum * -1;
                
            }
            else{
                p = 0;
            }
            
        }
        return p;
        
        
    }
}
