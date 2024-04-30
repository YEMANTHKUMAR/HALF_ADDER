
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)

 VERILOG CODE:
 ````
module halfadder(a,b,sum,carry);
input a,b;
output sum,carry;
xor x1(sum,a,b);
and x2(carry,a,b);
endmodule
``````
OUTPUT:
![image](https://github.com/YEMANTHKUMAR/HALF_ADDER/assets/160569469/c3791de4-cbdc-43e6-965e-2c865a088ff2)



