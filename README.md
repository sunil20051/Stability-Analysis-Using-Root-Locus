# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-03 at 09 52 45_2f8a2c27](https://github.com/user-attachments/assets/ac8fdbc0-ffc0-4c3c-aca9-1de2e87f1b27)

![WhatsApp Image 2025-11-03 at 09 52 44_3ceac7bb](https://github.com/user-attachments/assets/729448b2-9b70-42b9-b473-c88f929240aa)

![WhatsApp Image 2025-11-03 at 09 52 44_2acf4f55](https://github.com/user-attachments/assets/15a045d9-747a-484a-b78e-feb7039a63be)




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
