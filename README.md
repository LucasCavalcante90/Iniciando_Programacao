*Este projeto é uma demonstração prática desenvolvida durante um curso de Git e GitHub. Trata-se do meu primeiro repositório, criado para aplicar e testar minhas habilidades em Python :snake: e na utilização do GitHub :octocat:. O programa é simples, mas funcional ele realiza sorteios aleatórios de nomes, servindo como um exemplo do meu progresso no aprendizado.*

![image](https://github.com/user-attachments/assets/a117cdf6-d3f1-40f8-9def-7e7b727f88ef)

# Projeto escolha de nomes Aleatorios 
---
## O Professor quer sortear um dos seus quatro alunos para apagar o quadro




```
print(' 😄 \033[1;33;40m Digite o nome dos Alunos  \033[m 😄  ')
import random 
from time import sleep
n1 = str(input('\033[31m Primeiro nome :  '))
n2 = str(input('\033[31m Segundo nome :  '))
n3 = str(input('\033[31m Terceiro nome :  '))
n4 = str(input('\033[31m Quarto nome : '))
lista = [n1 , n2 , n3 , n4]
escolhido = random.choice(lista)
print('\033[0;34;43m O nome escolhido foi? \033[m')
sleep(1)
print(' \033[0;34m 3 ')
sleep(1)
print(' \033[0;33m 2 ')
sleep(1)
print('\033[0;36m  1 ')
sleep(1)
print(' O ESCOLHIDO FOI  .... \033[m ')
sleep(2)
print('\033[31m ----->    {}  <-----\033[m '.format(escolhido.upper()))
print('\033[1;32;40m ====> Você foi escolhido para ajudar o professor apagar o quadro 😄😄')
```
