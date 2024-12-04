# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
de

**Program:**
```
module experiment2(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module experiment2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

Developed by:Yasvanth RD
RegisterNumber:24900517

```

**RTL realization**

![WhatsApp Image 2024-12-04 at 13 36 12_c3024417](https://github.com/user-attachments/assets/b97693dc-765a-42d6-98ce-9c97896888c8)
![WhatsApp Image 2024-12-04 at 13 36 11_1d8ed032](https://github.com/user-attachments/assets/a16fe9fe-8008-4254-bdc3-0a966d29c13c)



**Timing Diagram**

![WhatsApp Image 2024-12-04 at 13 36 11_b8c74449](https://github.com/user-attachments/assets/c98052de-b062-4d7d-921c-abcdddb1d736)
![WhatsApp Image 2024-12-04 at 13 36 11_171358e8](https://github.com/user-attachments/assets/38f29ad5-9485-4f7d-b049-6dbf849203bf)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

