# 🤖 RPA - Automação de Consolidação de Relatórios em Excel

## 📌 Visão Geral
Este projeto demonstra uma automação de processos (RPA) desenvolvida com UiPath para consolidar múltiplos arquivos Excel em um único relatório final.

A solução simula um cenário comum em empresas, onde equipes operacionais precisam consolidar manualmente diversos relatórios, consumindo tempo e aumentando o risco de erros.

---

## 🧠 Problema de Negócio
Em ambientes corporativos, é comum o recebimento de vários arquivos Excel com dados operacionais (vendas, pedidos, indicadores, etc.).

O processo manual de:
- abrir arquivos
- copiar dados
- consolidar informações

é repetitivo, demorado e sujeito a falhas.

---

## ⚙️ Solução Desenvolvida
O robô desenvolvido em UiPath realiza automaticamente:

- Leitura de múltiplos arquivos Excel em uma pasta
- Iteração sobre cada arquivo
- Extração dos dados das planilhas
- Consolidação das informações em uma única estrutura
- Preparação de um relatório final unificado

---

## 🛠️ Tecnologias Utilizadas
- UiPath Studio
- Automação de Excel
- DataTables (manipulação de dados)
- Lógica de fluxo (For Each, If, Merge)

---

## 🔄 Fluxo da Automação

1. Identificação dos arquivos na pasta de entrada
2. Loop para leitura de cada arquivo
3. Extração dos dados das planilhas
4. Consolidação dos dados em um DataTable principal
5. Geração de saída com os dados consolidados

---

## 📁 Estrutura do Projeto

RPA_Excel_Report_Automation/
│
├── Main.xaml
├── data/
│ ├── input/
│ └── output/
│
├── docs/
└── README.md

---

## 🎯 Objetivo do Projeto
Demonstrar habilidades práticas em:

- Automação de tarefas repetitivas
- Manipulação e consolidação de dados
- Estruturação de fluxos de RPA
- Aplicação de lógica de negócio em automações

---

## 📎 Observações
Este projeto foi desenvolvido com foco educacional e simula um cenário real de automação empresarial.

A execução completa pode depender de configurações específicas de ambiente (como acesso ao Excel Desktop ou alternativas como leitura via CSV).

---

## 🚀 Próximos Passos
- Implementar tratamento de erros mais robusto
- Adicionar logs de execução
- Automatizar envio de relatórios por e-mail
- Melhorar a escalabilidade da solução

---

## 👨‍💻 Autor
Lucas Vieira