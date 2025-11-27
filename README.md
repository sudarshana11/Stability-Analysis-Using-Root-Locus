# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 21 20 33_e1f306aa](https://github.com/user-attachments/assets/54db554a-1d50-44e1-93d1-d9b54882f86b)
![WhatsApp Image 2025-11-27 at 21 21 00_856feffc](https://github.com/user-attachments/assets/acedcfa1-390a-40b3-b002-49d408c66d63)
![IMG-20251115-WA0067](https://github.com/user-attachments/assets/820fb044-7e9c-4f94-99cb-7b9b1bec573e)


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
