# CS_SpeechADV
The code of the CyberSecurity contest which is ranked number 2. Our method is a modfifed method based on the C&W which is combined some other loss funtions to conduct the higer SNR. The whole method is easy to go and the every adversarial example can be generated in 15min~2h. The results of our generated files can seen in [generated.txt](./generated/generated.txt), the four colums are the generated adversarial example (the failed attacked files are attached with 'failed'), the result of attack (True for success, False for failure), SNR of the generated adversarial example, target command of the method, respectively.
# Usage
Our attack method can be seen in [OPT.py](./OPT.py), 
    python OPT.py --source [] --command [] --save []
# Related file
