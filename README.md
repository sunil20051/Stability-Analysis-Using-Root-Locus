# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software
## Theory:
![WhatsApp Image 2025-11-20 at 18 21 18_256027be](https://github.com/user-attachments/assets/cb482765-a393-4fe0-b8fa-f40d0de665f8)
![WhatsApp Image 2025-11-20 at 18 21 18_e8441476](https://github.com/user-attachments/assets/f563ecc3-b07e-441d-af2d-bc74c2299fe1)
![WhatsApp Image 2025-11-20 at 18 21 19_3986bb2b](https://github.com/user-attachments/assets/4c59c139-6278-4be9-a4dc-b0facd7f13d5)






## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 

num=[1];<br>
den=[1 15 50 0];<br>
sys=tf(num,den);<br>
rlocus(sys);<br>
[k,poles]=rlocfind(sys)<br>

## OUTPUT:
<img width="1913" height="1035" alt="image" src="https://github.com/user-attachments/assets/a0dfdf13-0487-46b9-96a3-ec1f2512fdf5" />

![WhatsApp Image 2025-11-03 at 10 24 46_49311f88](https://github.com/user-attachments/assets/a6f608cf-cb16-41fc-90e8-c598f28650f9)



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 755.9205
