# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 23 32 34_7f482b36](https://github.com/user-attachments/assets/9594dc8c-0f56-435e-8ca4-06b6d0cbbce6)
![WhatsApp Image 2025-11-27 at 23 33 32_d4d10015](https://github.com/user-attachments/assets/3d191b0c-6baa-4e43-a969-50c4000ac6f5)
![WhatsApp Image 2025-11-27 at 23 34 22_37dbb442](https://github.com/user-attachments/assets/4d023324-b761-4fa6-9b57-20a6b5f81223)
![WhatsApp Image 2025-11-27 at 23 34 56_0787f030](https://github.com/user-attachments/assets/13a1b4ee-6e24-4848-9075-9288edbbf618)



## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 

```
num=[1]
den=[1 15 50 0]
sys=tf(num,den)
rlocus(sys)
[k poles]=rlocfind(sys)
```

## Output:

<img width="699" height="626" alt="image" src="https://github.com/user-attachments/assets/efb210b9-801d-4a1a-b603-66c56093cb8b" />

## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 744.551 .
