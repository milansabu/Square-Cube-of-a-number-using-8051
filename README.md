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
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC RO
MOV @R0,A
END







```

## OUTPUT
<img width="912" height="293" alt="image" src="https://github.com/user-attachments/assets/e5a17829-8cd0-4f8e-ba53-c7a9b46f1917" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/e94df3c5-1621-48b9-ae80-31aa72e27720" />




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
<img width="547" height="399" alt="image" src="https://github.com/user-attachments/assets/5f5ccdca-e58d-4b66-a8c7-1b369af951e1" />
<img width="899" height="1599" alt="image" src="https://github.com/user-attachments/assets/023d830f-7dbf-42c1-a3ac-470e125bab88" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


