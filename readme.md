# Diagrama de Blocos em Scilab/Xcos

## 📌 Descrição  
Este projeto tem como objetivo a implementação de um diagrama de blocos no Scilab/Xcos baseado no esquema fornecido. O modelo simula o controle de uma máquina de indução, realizando transformações abc → dq, cálculos em eixos Q e D, e reconversão dq → abc.

![diagrama a ser realizado](/Assets/diagrama.png)

## 🛠️ Estrutura do Projeto  
- **main.zcos** → Arquivo principal do diagrama de blocos no Xcos.  
- **script.sce** → Código Scilab correspondente ao diagrama.  

## 📥 Requisitos  
- [Scilab](https://www.scilab.org/) (versão 6.1 ou superior)  
- Xcos instalado (vem junto com o Scilab)  

## 🚀 Como Executar  
1. Abra o Scilab.  
2. Carregue o arquivo `.xcos` no Xcos para visualizar e modificar o diagrama.  
3. Ou execute o script `.sce` no console do Scilab:  
   ```scilab
   exec('script.sce', -1);
