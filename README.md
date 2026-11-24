<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:3b0764,50:7e22ce,100:c084fc&height=170&section=header&text=SAT%20Solver%20(Horn)&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Valida%C3%A7%C3%A3o%20FNC%2C%20Cl%C3%A1usulas%20de%20Horn%20e%20Satisfatibilidade%20em%20Python&descAlignY=65&descSize=15" width="100%" alt="Banner" />
</div>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
  <img src="https://img.shields.io/badge/L%C3%B3gica-SAT%20%2F%20Horn-7E22CE?style=for-the-badge" alt="SAT Solver" />
</p>

---

## 📖 Sobre o Projeto

Implementação de um **SAT Solver para Cláusulas de Horn** em **Python**, desenvolvido para a disciplina de **Lógica para Computação (CIn - UFPE)**.

A partir de um arquivo de entrada (`Entrada.in`) com múltiplas fórmulas proposicionais, o solver classifica e decide cada problema em 3 etapas:

1. **Validação de FNC:** verifica se a fórmula está na **Forma Normal Conjuntiva**.
2. **Validação de Horn:** verifica se todas as cláusulas possuem no máximo um literal positivo (`hornVal`).
3. **Decisão de Satisfatibilidade:** aplica o algoritmo de propagação unitária para determinar se a fórmula é **satisfatível** ou **insatisfatível**.

---

## 📂 Estrutura

```text
Sat_Solver-Projeto-de-l-gica-/
├── ProjetoLógica.ipynb   # Notebook com a implementação do SAT Solver
└── Projeto-de-Logica.zip # Arquivos auxiliares e casos de entrada
```

---

## 🚀 Como Executar

```bash
git clone https://github.com/charles-gabriel-cc/Sat_Solver-Projeto-de-l-gica-.git
cd Sat_Solver-Projeto-de-l-gica-
jupyter notebook ProjetoLógica.ipynb
```

Coloque o arquivo `Entrada.in` no mesmo diretório do notebook e execute as células para gerar o resultado de cada problema (`Sim, é satisfatível.`, `Não, não é satisfatível.`, `Não está na FNC.` ou `Nem todas as cláusulas são de Horn.`).
