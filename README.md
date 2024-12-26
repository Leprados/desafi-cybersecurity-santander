# desafio-cybersecurity-santander

Este leia-me se refere ao resultado do desafio de cybersecurity santader.
No desafio foi usado o kallil linux e programa setoolkit
Duarante o processo tive problemas com a porta:80
Então usei o comando sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill, para resolver o problema de porta.
RESULTADO:

![image](https://github.com/user-attachments/assets/fcf5aa92-8aea-432f-beff-4608ad79484a)
