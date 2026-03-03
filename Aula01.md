# 📚 Notas de Aula: Eletrônica Analógica e Prototipagem
**Repositório de acompanhamento das aulas práticas e teóricas - 2026**

---

## 📅 Cronograma Semestral

### 🟢 Primeiro Bimestre
* **Fundamentos de Bancada:** Introdução teórica dos equipamentos.
* **Semicondutores:** Revisão de diodos retificadores e roteiro prático.
* **Design Eletrônico:** Teoria e Prática de introdução à ferramenta **KiCad**.
* **Circuitos com Diodos:** Ceifadores, limitadores e grampeadores (Teoria e Prática).

### 🔵 Segundo Bimestre
* **Transistores BJT:** Projeto de transistor como chave e roteiro prático.
* **Fontes de Corrente:** Projeto de transistor como fonte de corrente e prática.
* **Amplificadores Operacionais:** Teoria e introdução aos AmpOps com roteiro prático.

---

## 🔬 Aula 01 - Instrumentação e Prototipagem
*Data: 02 de Março de 2026*

### 1. Equipamentos de Bancada
#### **Fonte CA & Gerador de Sinais**
* **Função:** Geração de ondas Senoidal, Triangular e Quadrada.
* **Medições:** Foco em tensão e corrente **RMS** (Alternada e Contínua).



#### **Multímetro**
* **Tensão:** Medida de um ponto com relação ao terra (paralelo).
* **Corrente:** Necessidade de **abrir o circuito** para medição em série.
* **Outros:** Medição de Resistência e teste de continuidade.

#### **Osciloscópio**
* Instrumento fundamental para visualizar sinais em tempo real.
* **Eixo Vertical (Y):** Tensão (Volts).
* **Eixo Horizontal (X):** Tempo (Segundos).



---

### 2. Métodos de Prototipagem

#### **Protoboard (Matriz de Contatos)**
* **Objetivo:** Montar e testar circuitos temporários sem solda.
* **Vantagem:** Facilita a correção rápida de erros e o aprendizado prático.
* **Conexão:** Trilhas internas que permitem interconectar resistores, capacitores e CI's.

#### **PCB (Placa de Circuito Impresso)**
* **Objetivo:** Versão inicial e profissional para validar o design antes da produção.
* **Importância:** Identificar erros de layout precocemente, garantir integridade de sinal e reduzir custos de desenvolvimento em massa.

---

## 🛠️ Prática do Dia: Retificador de Meia Onda
*Referente ao diagrama analisado em aula.*

| Parâmetro | Detalhes |
| :--- | :--- |
| **Entrada** | 10 Vrms / 60 Hz |
| **Diodo** | 1N4001 (Silício) |
| **Carga ($R_L$)** | $1 k\Omega$ |

**Observação Prática:** Ao utilizar o osciloscópio no resistor de carga, nota-se a supressão do semiciclo negativo, caracterizando a retificação de meia onda.

---
*Notas organizadas para fins acadêmicos.*