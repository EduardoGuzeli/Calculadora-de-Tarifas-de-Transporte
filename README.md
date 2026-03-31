# 🚍 Calculadora de Tarifas de Transporte

Este projeto foi desenvolvido com o objetivo de praticar lógica de programação utilizando **Python**, focando em estruturas condicionais e interação com o usuário via terminal.

A aplicação simula um sistema simples de cálculo de tarifas de transporte, levando em consideração o tipo de usuário e a distância percorrida, aplicando descontos específicos para cada categoria.

---

## 🚀 Sobre o projeto

O programa apresenta um menu interativo onde o usuário pode escolher entre diferentes perfis:

- Estudante  
- Trabalhador  
- Idoso  
- Comum  

Com base na escolha, o sistema calcula automaticamente o valor da tarifa:

- 🎓 Estudantes recebem 50% de desconto  
- 👷 Trabalhadores recebem 20% de desconto  
- 👴 Idosos não pagam (gratuito)  
- 👤 Usuários comuns pagam o valor integral  

Tudo isso de forma simples, rápida e direta no terminal.

---

## 🧠 Lógica aplicada

O cálculo da tarifa é baseado na seguinte regra:

```bash
Valor = Distância × Tarifa base (R$ 2.50)
