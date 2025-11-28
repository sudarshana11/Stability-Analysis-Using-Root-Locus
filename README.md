# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
<img width="554" height="1280" alt="image" src="https://github.com/user-attachments/assets/070dd1ee-b9b5-46cf-bea1-aed33bf000f4" />
<img width="695" height="1280" alt="image" src="https://github.com/user-attachments/assets/3190bd96-7478-4809-9459-553b29874ae9" />

<img width="676" height="889" alt="image" src="https://github.com/user-attachments/assets/1f8a6fd3-4f38-4c6d-beaa-db70bafc9e7e" />





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
<img width="702" height="629" alt="image" src="https://github.com/user-attachments/assets/55096823-c15c-4b5a-be8f-cc2d7afc9e88" />


## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 460.6838
