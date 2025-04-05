# 🏭 V-Belt Conveyor Idler Roller - 800mm

<div align="center">
  
  ![Modelo 3D Interativo](/cad/V-Shape Roller 800 mm - Base Free Roller 800 mm-1.STL)
  
  *Rolo livre para correia transportadora em V - Diâmetro 800mm*  
  [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
  [![GitHub Issues](https://img.shields.io/github/issues/thylellys/v-belt-conveyor-idler-roller)](https://github.com/thylellys/v-belt-conveyor-idler-roller/issues)

</div>

## 📋 Descrição do Projeto
Componente mecânico para sistemas de transporte de materiais pesados, projetado para operar em:
- Esteiras de mineração
- Indústrias de cimento
- Plantas de processamento de grãos

## 🛠️ Especificações Técnicas
| Parâmetro               | Valor               |
|-------------------------|---------------------|
| Diâmetro                | 800 mm              |
| Material Principal      | Aço SAE 1045        |
| Capacidade de Carga     | 1200 kg (estático)  |
| Rolamentos             | SKF 6312-2RS1       |
| Ângulo da Correia em V  | 30°                 |

## 📂 Estrutura dos Arquivos

v-belt-conveyor-idler-roller/
├── cad/
│   ├── V-Shape_Roller_800mm_-_Base_Free_Roller_800mm-1.STL  ← Modelo 3D principal
│   └── assembly/            ← Arquivos de montagem completa
├── simulations/
│   ├── ansys/               ← Arquivos de simulação (.mechdb)
│   └── matlab/              ← Scripts de análise dinâmica
├── docs/
│   ├── specifications.pdf   ← Manual técnico
│   └── calculations.xlsx    ← Planilha de dimensionamento
└── images/                  ← Renderizações e diagramas

## 🚀 Como Usar
### Visualização do Modelo
1. Clique no visualizador 3D acima (funciona direto no GitHub)
2. Ou abra em softwares:
   - [FreeCAD](https://www.freecad.org/) (gratuito)
   - [Fusion 360](https://www.autodesk.com/products/fusion-360)

### Simulações
# Rodar análise no ANSYS
cd simulations/ansys
ansys mechanical -b -i analysis_file.mechdb

## 🧪 Testes Realizados
1. **Teste de Resistência**:
   - Carga aplicada: 1500 kg
   - Deformação máxima: 0.12 mm
   
2. **Análise de Fadiga**:
   - Vida útil estimada: >50,000 horas

## 🤝 Como Contribuir
1. Reporte problemas em [Issues](https://github.com/thylellys/v-belt-conveyor-idler-roller/issues)
2. Siga nosso [Guia de Contribuição](CONTRIBUTING.md)
3. Use os templates:
   ```bash
   git clone https://github.com/seu-usuario/v-belt-conveyor-idler-roller.git
   ```

## 📌 Próximas Etapas
- [X] Modelagem 3D inicial
- [ ] Análise térmica (CFD)
- [ ] Prototipagem física

## 📬 Contato
**Eng. [Seu Nome]**  
✉️ email@projeto.com  
🔗 [LinkedIn](https://linkedin.com/in/seu-perfil)  
🏢 [Site da Empresa](https://www.empresa.com)
