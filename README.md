# SQUARE AND CUBE OF A NUMBER
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
MOV B,A
MUL AB
INC R0
MOV @R0,A
END
```

## OUTPUT
![WhatsApp Image 2025-10-07 at 22 50 46_f6ee2649](https://github.com/user-attachments/assets/bb254ae4-c3fa-43fa-90ad-7ee4462494b8)

![WhatsApp Image 2025-10-07 at 22 51 02_3f007542](https://github.com/user-attachments/assets/8d792c9d-0cb3-4f5e-9a71-d6328e1bcfbb)



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
ORG 00H
MOV R0,#10H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,B
END
```


## OUTPUT
![WhatsApp Image 2025-10-07 at 22 35 26_0ae31e38](https://github.com/user-attachments/assets/c8c4c453-a3db-434c-8c86-6b565743c4a3)
![WhatsApp Image 2025-10-07 at 22 35 46_4d4f2464](https://github.com/user-attachments/assets/2ebb03fd-7d00-4959-9454-b5dede25cadf)

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
