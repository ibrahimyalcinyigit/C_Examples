# C_Examples

=====Reverse an integer number=====

int reverse(int x){
    
    int sum = 0;
    
    while(x){
        sum = sum * 10 + x % 10;
        x /= 10;
    }

    return sum;
}


