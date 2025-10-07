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
<img width="248" height="219" alt="Screenshot 2025-09-23 203950" src="https://github.com/user-attachments/assets/a9f63ad4-39c6-479f-909c-f53cc87cf6dc" />
<img width="1439" height="704" alt="image" src="https://github.com/user-attachments/assets/0c1899ce-26c3-47b5-b610-6de984b395cc" />


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
<img width="315" height="300" alt="Screenshot 2025-09-23 232516" src="https://github.com/user-attachments/assets/a0b4ba6c-0cf1-4651-8f8b-68cd66e26310" />
<img width="1920" height="1080" alt="Screenshot 2025-09-23 232505" src="https://github.com/user-attachments/assets/473c1556-0c86-4c71-9c61-66f3b76e966a" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
