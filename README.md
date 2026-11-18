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
MOV B,A
MUL AB
INC R0
MOV @R0,A
END

```

<img width="577" height="551" alt="image" src="https://github.com/user-attachments/assets/db11da43-c2f3-4df8-8c5b-0de942703dfe" />

## OUTPUT

<img width="1047" height="630" alt="image" src="https://github.com/user-attachments/assets/ab288754-0971-4b72-a510-6aa95cf1c2ac" />

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
MOV R0,#50H
MOV A,@R0
MOV B,A
MUL AB
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
INC R0
MOV @R0,A
END


```
<img width="577" height="687" alt="image" src="https://github.com/user-attachments/assets/334a5484-a94d-4d17-8b1f-d193806e3892" />


## OUTPUT
<img width="1048" height="752" alt="image" src="https://github.com/user-attachments/assets/8e64581f-97fe-4dbf-991f-7634afff1e7c" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


