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
ORG 00H
MOV RO,#50H
MOV A,@RO
MOV B,@RO
MUL AB
INC RØ
MOV @RO,A

END
```

## OUTPUT
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/da07dceb-6b32-4b6e-8fa0-a77a1db057bb" />
<img width="912" height="293" alt="Screenshot 2026-02-25 111306" src="https://github.com/user-attachments/assets/66a71e4f-7d24-4d1c-8e8d-54d494e3d357" />



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
MOV A, PO
MOV B, A
MUL AB
MOV RØ, A
MOV A, R0
MOV B, PO
MUL AB
MOV P2, A
END

```


## OUTPUT
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/0a325828-cfce-4982-99d7-aca67eb021d2" />

<img width="547" height="399" alt="Screenshot 2026-02-25 111355" src="https://github.com/user-attachments/assets/b6ebf9e0-d3d9-49f4-8676-2b34b7c869b9" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


