# Binary-quivalent-in-c-

    #include<iostream>
    using namespace std;

    void binary_equivalent(int n){
      if (n==0)
        return;

      binary_equivalent(n/2);
      cout<< n%2 <<endl; 
    }

    void main(){
      int x;
      scanf("%d", &x);
      binary_equivalent(x);
    }
