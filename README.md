# Assignment_BTech2026_-2201920130161-.-
IT-C (02/02/2025)

class MyCalculator implements AdvancedArithmetic{
    
      public int divisor_sum(int n){
        int sum=0;
        for(int i=1;i<=n;i++){
            if(n%i==0){
                sum=sum+i;
            }
        }
        return sum;
    }
}
