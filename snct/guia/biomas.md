<!---
Open Source program Pynoplia - Copyright © 2024  Carlo Oliveira** <carlo@nce.ufrj.br>,
PDX-License-Identifier:** `GNU General Public License v3.0 or later <http://is.gd/3Udt>`_.
-->
# Guia do Agente da SNCT - Conhecendo os Biomas
> E agora para algo totalmente diferente! <br>
> Aprenda conceitos básicos de Python resolvendo, modificando, criando jogos e desafios. <br>

## A floresta Amazônica

Vamos fazer um jogo com animais da amazônia

```python
bichos = "escolha um bicho da amazônia: a-anta, b-lobo guará, c-capivara, d-tatu."
bicho = input(bichos)
while bicho not in "acd":
    bicho = input(bichos)
input("você acertou")
```
Vamos fazer um jogo com o bioma da amazônia
```python
print("Diga qual o rio com maior comprimento da Amazônia")
rio = input("a- Rio Solimões, b- Rio Madeira, c- Rio Amazonas, d- Rio Tapajós ")

if rio == "c":
  print("Resposta correta! O Rio Amazonas é o de maior comprimento da Amazônia.")
else:
  print("Resposta correta é a letra 'a', Rio Amazonas.")

```


## A mata atlântica

Vamos fazer um jogo com animais da mata atlântica

```python
bichos = "escolha um bicho da mata atlântica: a-quati, b-mico leão-dourado, c-coruja."
bicho = input(bichos)
while bicho not in "ab":
    bicho = input(bichos)
input("você acertou")
```

vamos fazer um jogo com a localidade da mata atlântica

```python
print("A Mata Atlântica é um bioma incrível!")
print("Você tem 3 chances para descobrir onde ela está localizada.")

localizacoes_corretas = "litoral"
tentativas = 0
acertou = False

while tentativas < 3:
    comando = input("Em qual região do Brasil a Mata Atlântica está PREDOMINANTEMENTE localizada? ")
    if comando.lower() == localizacoes_corretas:
        print("Parabéns! Você acertou!")
        acertou = True
        break
    else:
        print("Resposta incorreta. Tente novamente.")
        tentativas += 1

if acertou:
    print("Você acertou pelo menos uma vez! A Mata Atlântica é um bioma riquíssimo em biodiversidade.")
else:
    print("Você não acertou nenhuma vez. A Mata Atlântica está localizada principalmente no litoral do Brasil.")
```



## A caatinga

Vamos fazer um jogo com animais da caatinga

```python
bichos = "escolha um bicho da caatinga: a-onça-parda, b-tatu-bola, c-gambá, d-mocó."
bicho = input(bichos)
while bicho not in "c":
    bicho = input(bichos)
input("você acertou")
```
Vamos fazer um jogo com o clima da caatinga
```python
print("Responda com o clima correto da caatinga")
clima = input("a- semiárido, b- equatorial, c- úmido, d- tropical ")

if clima == "a":
  print("Resposta correta")
else:
  print("Resposta correta é a letra 'a' semiárido")
```

## O pantanal

Vamos fazer um jogo com animais do pantanal

```python
bichos = "escolha um bicho do pantanal: a-onça pintada, b-ariranha, c-arara azul."
bicho = input(bichos)
while bicho not in "c":
    bicho = input(bichos)
input("você acertou")
```
Vamos fazer um jogo com animais do pantanal

```python
print("Você precisa atravessar uma trilha e evitar jacarés.")
print("Dê 5 passos e atravesse em segurança!Comando: 'passo seguro'")

passos = 0
while passos < 5:
  comando = input("Digite o comando para dar o passo:")
  if comando == "passo seguro":
    print("Passo dado!")
    passos +=1
  else:
    print("Comando incorreto! Tente novamente.")
print("Parabéns! Você deu 5 passos e cruzou a trilha com segurança!")
```


## O cerrado

Vamos fazer um jogo com animais do cerrado

```python
bichos = "escolha um bicho do cerrado: a-lontra, b-tatu-canastra, c-tamanduà, d-catitu, e-macaco-prego"
bicho = input(bichos)
while bicho not in "a":
    bicho = input(bichos)
input("você acertou")
```

Vamos fazer um jogo com o bioma do cerrado

```python
print("Jatobá é uma árvore comum no cerrado. Ajude-nos a plantar mais!")
print("para plantar, escreva o comando 'plantar' quando solicitado")
arvores_plantadas = 0

while arvores_plantadas < 3:
    comando = input("Escreva o comando:")
    if comando == "plantar":
       arvores_plantadas += 1
    else:
        print("Comando incorreto! Tente novamente.")
print("Parabéns! Você plantou 3 árvores e ajudou a preservar o Cerrado!")

```


## O pampa

Vamos fazer um jogo com animais do pampa

```python
bichos = "escolha um bicho do pampa: a-tachã, b-tuco-tuco, c-sapinho de barriga vermelha, d-beija flor da barba azul."
bicho = input(bichos)
while bicho not in "d":
    bicho = input(bichos)
input("você acertou")

```
Vamos fazer um jogo com animais do pampa
```python
conhecer = input("Deseja sconhecer os 5 animais mais comuns da Pampa? (sim/não): ").lower()

animaisPampa = ["Jaguar", "Veado-campeiro", "Capivara", "Cervo", "Tatu-bola"]

if conhecer == "sim":
    
        print(" Aqui estão os 5 animais mais comuns da Pampa:")
        print (animaisPampa)
    
else if conhecer == "não":
    print("Claro que quer!! Aqui estão os 5 animais mais comuns da Pampa:")
    print(animaisPampa)
else:
    print("Resposta incorreta. Tente novamente.")

```
## A fauna

- PANTANAL- ONÇA PINTADA, ARIRANHA, ARARA AZUL GRANDE.
- AMAZÔNIA- ANTA, LOBO GUARÀ, CAPIVARA, TATU.
- MATA ATLÂNTICA- QUATI, MICO-LEÃO-DOURADO, CORUJA.
- CAATINGA- ONÇA-PARDA, TATU-BOLA, GAMBÀ, MOCÒ.
- PAMPA- TACHÃ, TUCO-TUCO, SAPINHO DE BARRIGA VERMELHA, BEIJA FLOR DA BARBA AZUL.
- CERRADO- LONTRA, TATU-CANASTRA, TAMANDUÀ, CATITU, MACACO-PREGO.

#### LABASE
[footer](footer.md ':include')