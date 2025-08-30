
# 📊 Relatório de Implementação de Serviços AWS

**Data:** 30/08/2025  
**Empresa:** PharmaTech Solutions  
**Responsável:** Gustavo Balbino de Sousa

---

## 📝 Introdução
Este relatório apresenta o processo de implementação de serviços **AWS** na empresa **PharmaTech Solutions**, conduzido por *Gustavo Balbino de Sousa*.  
O objetivo do projeto foi selecionar **três serviços AWS estratégicos**, visando:

- Reduzir custos operacionais;  
- Melhorar a escalabilidade;  
- Otimizar processos internos da empresa farmacêutica, especialmente em áreas de **pesquisa, gestão de dados e análise de desempenho**.  

---

## 🚀 Descrição do Projeto
O projeto foi dividido em três etapas, cada uma com a escolha de um serviço AWS, seu foco principal e um caso de uso aplicado à empresa.

---

### 🔹 Etapa 1
**Serviço:** `Amazon S3`  
**Foco da ferramenta:** Armazenamento de dados escalável e seguro  

**Caso de uso:**  
Todos os registros de pesquisa, relatórios laboratoriais, dados de ensaios clínicos e planilhas de controle de estoque são armazenados no Amazon S3.  
Isso permite:  
- Redução de custos com servidores físicos;  
- Compartilhamento simples entre departamentos;  
- Integração com ferramentas de análise, como **AWS Athena**, para relatórios automatizados.  

**Exemplo de aplicação:**  
Uma planilha de controle de estoque criada no Excel pode ser carregada automaticamente no **S3**, permitindo que **dashboards no Tableau ou Power BI** se atualizem em tempo real.  

---

### 🔹 Etapa 2
**Serviço:** `Amazon RDS (Relational Database Service)`  
**Foco da ferramenta:** Banco de dados relacional gerenciado para armazenamento e consulta eficiente de informações críticas  

**Caso de uso:**  
Dados de pacientes, históricos de vendas e relatórios de produção farmacêutica são centralizados em um **RDS PostgreSQL**, garantindo:  
- Alta disponibilidade;  
- Backup automático;  
- Eliminação da manutenção manual de servidores.  

**Exemplo de aplicação:**  
Criação de dashboards de produção e vendas, mostrando tendências de medicamentos por região.  
Os dados do **RDS** podem ser visualizados em **Google Sheets** ou **Power BI**.  

---

### 🔹 Etapa 3
**Serviço:** `AWS Lambda`  
**Foco da ferramenta:** Processamento serverless e automatização de tarefas  

**Caso de uso:**  
Processos repetitivos, como conversão de dados laboratoriais em relatórios, notificações de estoque baixo ou cálculos de demanda de medicamentos, são automatizados com funções Lambda.  
Isso garante:  
- Redução de custos com servidores dedicados;  
- Maior produtividade;  
- Escalabilidade imediata.  

**Exemplo de aplicação:**  
Ao subir novas planilhas no **S3**, uma **função Lambda** é acionada para:  
- Processar os dados;  
- Gerar gráficos de desempenho em dashboards (ex.: Figma);  
- Enviar relatórios por e-mail aos gestores.  

---

## ✅ Conclusão
A implementação dos serviços **Amazon S3, Amazon RDS e AWS Lambda** na PharmaTech Solutions proporcionará:  

- 💰 Redução de custos com infraestrutura física;  
- 📈 Escalabilidade de armazenamento e processamento conforme a demanda;  
- ⚡ Automatização de processos críticos, aumentando a produtividade;  
- 📊 Integração com dashboards, planilhas e ferramentas como Power BI e Figma.  

Recomenda-se também avaliar o uso de **Amazon Redshift** e **DynamoDB** para otimizar ainda mais a análise e o armazenamento de grandes volumes de dados laboratoriais.  

---

✍️ **Assinatura do Responsável pelo Projeto:**  
**Gustavo Balbino**  
