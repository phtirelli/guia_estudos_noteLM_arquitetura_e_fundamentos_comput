# 💻 Guia de Estudos: Fundamentos e Arquitetura de Computadores

Este repositório contém um guia de estudos estruturado sobre a organização e o funcionamento dos sistemas computacionais. O material foi desenvolvido utilizando o **NotebookLM** como ferramenta auxiliar para sintetizar e organizar informações de diversas fontes acadêmicas.

---

## 📝 Contexto do Projeto

Este caderno foi elaborado com dois objetivos principais:
1.  **Exploração Tecnológica:** Testar as capacidades da ferramenta *NotebookLM* em organizar e enriquecer fluxos de estudo a partir de múltiplas fontes.
2.  **Apoio Acadêmico:** Consolidar conhecimentos da disciplina de **Fundamentos de Arquitetura de Computadores**, integrante da minha graduação atual.

---

## 📚 Fontes Utilizadas

O conhecimento aqui sintetizado provém de uma curadoria de materiais diversificados:
* 3 Apostilas acadêmicas especializadas.
* Artigo técnico da Wikipedia.
* Vídeo educativo do YouTube.

---

## 🧠 Resumo do Conteúdo (Q&A)

Abaixo, apresento 10 questões fundamentais que resumem os pilares da arquitetura de computadores, baseadas nas fontes consultadas.

### 1. Arquitetura de Von Neumann
**O que a caracteriza e quais são seus componentes básicos?**
É um modelo que centraliza o processamento, onde dados e instruções de programas são armazenados na mesma memória. 
* **Componentes:** Unidade de Controle (UC), Unidade Lógica e Aritmética (ULA), Memória e Dispositivos de E/S.




### 2. Sistemas de Numeração
**Por que usamos base binária, octal e hexadecimal?**
* **Binário:** Ajusta-se à lógica dos circuitos (ligado/desligado).
* **Octal/Hexadecimal:** Funcionam como "atalhos" para agrupar bits, facilitando a leitura humana de grandes sequências de dados.

### 3. Álgebra Booleana e Portas Lógicas
**Qual sua função na computação?**
A Álgebra Booleana é a linguagem matemática da lógica (verdadeiro/falso). As portas lógicas (AND, OR, NOT) são os componentes físicos que executam essas operações, formando o "cérebro" dos sistemas digitais.

### 4. Representação de Mídia
**Como imagens e áudios são digitalizados?**
* **Imagens:** Mapeadas em matrizes de pixels (frequentemente no modelo RGB).
* **Áudio:** Passa pelos processos de *amostragem* (captura de vibração em intervalos) e *quantização* (conversão para valores binários).

### 5. Circuitos Combinacionais vs. Sequenciais
**Qual a diferença fundamental?**
* **Combinacionais:** A saída depende apenas das entradas atuais.
* **Sequenciais:** Possuem memória (flip-flops), permitindo que a saída dependa também do histórico de eventos.

### 6. Ciclo de Instrução
**Como o processador executa tarefas?**
Ocorre em três etapas principais:
1.  **Fetch (Busca):** Coleta a instrução na memória.
2.  **Decode (Decodificação):** Traduz o comando para acionar os circuitos.
3.  **Execute (Execução):** Realiza a operação (geralmente via ULA) e armazena o resultado.

### 7. Hierarquia de Memória
**Como ela está organizada?**
Busca o equilíbrio entre velocidade, capacidade e custo, seguindo esta pirâmide:
1.  **Topo:** Registradores e Cache (Rápidos, caros, pequena capacidade).
2.  **Meio:** Memória Principal (RAM).
3.  **Base:** Memória Secundária (HD/SSD - Lentos, baratos, alta capacidade).



[Image of computer memory hierarchy]


### 8. Barramentos e E/S
**Como ocorre a comunicação entre CPU e periféricos?**
Através de **barramentos** (linhas de comunicação de dados, endereços e controle). A interação pode ser por:
* **Interrupção:** O dispositivo avisa a CPU quando precisa dela.
* **Polling:** A CPU verifica periodicamente se o dispositivo tem solicitações.

### 9. Pipelining
**Como ele otimiza o desempenho?**
É uma técnica que divide o ciclo de instrução em estágios sobrepostos. Isso permite que múltiplas instruções sejam processadas simultaneamente em fases diferentes, aumentando o volume de informações processadas por segundo.

### 10. Arquiteturas Avançadas (GPU, FPGA e ASIC)
**Quais suas aplicações práticas?**
* **GPUs:** Alto processamento paralelo (IA e Ciência de Dados).
* **FPGAs:** Chips reconfiguráveis (Automação e Medicina).
* **ASICs:** Circuitos de tarefa fixa (Altíssima eficiência e desempenho superior em funções específicas).

---
*Guia construído para fins didáticos.*
