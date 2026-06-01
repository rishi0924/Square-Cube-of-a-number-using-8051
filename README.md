# Square-Cube-of-a-number-using-8051
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 0000H
MOV R0, #30H     
MOV A, @R0      
MOV R1, A         
MOV A, #01H     
FACT:
MOV B, R1        
MUL AB           
DJNZ R1, FACT    
MOV 31H, A       
END
```

## OUTPUT
<img width="814" height="191" alt="Screenshot 2026-02-18 112452" src="https://github.com/user-attachments/assets/ec5c6b75-5452-41c6-b85d-60ae7b3b1393" />

![WhatsApp Image 2026-02-18 at 11 22 24 AM](https://github.com/user-attachments/assets/f517851f-00ad-4e20-8abe-ce424d7f59d1)

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END
```

## OUTPUT
<img width="1459" height="531" alt="551359121-8847f667-4318-428b-bf4d-0271c8dfb85a" src="https://github.com/user-attachments/assets/3ead0920-fe0b-448d-b342-dacf5c68ce02" />

![WhatsApp Image 2026-02-18 at 11 22 46 AM](https://github.com/user-attachments/assets/93c6eae6-3015-46c0-9d9a-40a0dce9bdcc)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
