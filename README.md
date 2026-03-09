![GitHub License](https://img.shields.io/github/license/AndyJosmar/lab-redes01)


# laboratório de redes 01 - lab-redes01
Projeto desenvolvido na disciplina de redes de computadores no Curso Tecnico de Informática do SENAC

ALUNO: Andy josmar

PROFESSOR: jose de assis 

DATA: 09/03/2026

---

## 1.Objetivo :
Implementar uma rede local simples connectado 3 notebooks a um roteador wireless com switch intregado e uma impressora de rede.

o projeto sera realizada em duas etapas: 

1. Simulação de rede no Ciso Packet Tracer
2. Implementação de r5ede no laboratorio real

---

## 2. Equipamento utilizada neste laboratorio 

  - 3 notebooks
  - 1 roteador wireless com 1 wan e 4 portas LAN
  - 1 Impressora 
  - Cabo de rede

---

## 3. Tropologia da rede 
Diagrama lógica da rede utilizada neste laboratório:

```mermaid
graph TD

WAN[INTERNET / WAN do provador]

Router[roteador wireless<bar> 1 Porta WAN<br> 4 Portas LAN]

PC1[notebook 1]
PC2[notebook 2]
PC3[notebook 3]

Printer[impressora da rede]

WAN --> |Porta WAN| Router

Router --> |LAN 1| PC1
Router --> |LAN 2| PC2
Router --> |LAN 3| PC3




```
Imagen da topologia utilizada  no laboratorio





<img width="588" height="540" alt="topologia" src="https://github.com/user-attachments/assets/2ae25e30-4df5-4e13-96a7-d881f7939584" />






