# 📦 Gestão de Stock de Materiais Escolares

Este projeto consiste no desenvolvimento de um programa em Python para gerir o stock de materiais escolares de uma escola.

O sistema permite registar, consultar e atualizar materiais de forma simples e eficiente através de um menu interativo no terminal.

---

## 🎯 Objetivo

Criar um programa que utilize **funções em Python** para:

- Registar novos materiais
- Consultar o stock existente
- Atualizar quantidades (entrada e saída)
- Visualizar o estado geral do stock
- Simular exportação de dados para ficheiro

---

## 🧠 Funcionalidades

### ➕ Adicionar Material
Permite inserir um novo material no stock com uma quantidade inicial.

### 🔍 Consultar Stock
Consulta a quantidade disponível de um material específico.

### 🔄 Atualizar Stock
Permite:
- Adicionar unidades ao stock
- Remover unidades do stock (com validação)

### 📋 Exibir Stock Geral
Mostra todos os materiais e respetivas quantidades.

### 💾 Exportar (Simulado)
Permite indicar um nome de ficheiro para guardar os dados (funcionalidade simulada).

---

## 🏗️ Estrutura do Código

O programa está organizado nas seguintes funções:

- `adicionar_material(stock)`
- `consultar_stock(stock)`
- `atualizar_stock(stock)`
- `exibir_stock(stock)`
- `Exportar_para_ficheiro(stock)`
- `main()`

O stock é armazenado num **dicionário Python**, onde:
- chave = nome do material
- valor = quantidade

---

## ▶️ Como Executar

1. Certifica-te de que tens o Python instalado
2. Guarda o ficheiro com extensão `.py`
3. Executa no terminal:

```bash
python 1I-PSI-M3-14818-EXPA04.py
