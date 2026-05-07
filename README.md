# Detectar-Mão-Aberta-Python

Código em Python que detecta quando a mão está aberta e retorna o resultado no console.

Fluxo do programa:

Webcam →
Frame →
MediaPipe detecta a mão →
Conta os dedos →
Mostra o resultado →
Executa ações.

Obs: O código precisa ser executado em uma `.venv` por conta das bibliotecas.

Para executar, coloque esse comando no bash da pasta onde está o Script:

vision_env\Scripts\python.exe hand_gesture.py


A camera do programa pode ser fechada com Esc. 

Se precisar mudar para uma segunda camera é so trocar o numero no final de VideoCapture = "self.cap = cv2.VideoCapture(0)"
Camera 1: "self.cap = cv2.VideoCapture(1)"
Camera 2: "self.cap = cv2.VideoCapture(2)"
Etc...


---------------------------------------------------------README-EN--------------------------------------------

#Detect-Open-Hand-Python
Python code that detects when the hand is open and returns the result in the console.

Program flow:

Webcam →
Frame →
MediaPipe detects the hand →
Counts the fingers →
Shows the result →
Executes actions.

Note: The code needs to be executed in a .venv because of the libraries.

To run, use this command in the bash of the folder where the Script is located:

vision_env\Scripts\python.exe hand_gesture.py

The program’s camera can be closed with Esc.

If you need to switch to a second camera, just change the number at the end of VideoCapture = "self.cap = cv2.VideoCapture(0)"
Camera 1: "self.cap = cv2.VideoCapture(1)"
Camera 2: "self.cap = cv2.VideoCapture(2)"
And so on...


