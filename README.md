# 💊 Modernização e Redução de Custos em Farmácia com AWS

## 📌 Descrição
Este projeto apresenta uma proposta de modernização da infraestrutura de TI de uma farmácia fictícia, utilizando serviços da AWS para reduzir custos operacionais, aumentar a escalabilidade e melhorar a eficiência dos sistemas.

## 🏢 Cenário Atual
A farmácia opera com um sistema local (on-premise), apresentando os seguintes problemas:

- Alto custo com servidores físicos
- Falta de escalabilidade
- Risco de perda de dados
- Baixa performance em horários de pico

## 🎯 Objetivo
Reduzir custos e melhorar a eficiência do sistema através da migração para a nuvem AWS.

---

## ☁️ Solução Proposta

### 🔹 Etapa 1 – Armazenamento com Amazon S3
- Migração de dados para o Amazon S3
- Uso de **S3 Intelligent-Tiering** para reduzir custos automaticamente
- Configuração de políticas de lifecycle

### 🔹 Etapa 2 – Processamento com AWS Lambda
- Substituição de servidores por funções serverless
- Execução sob demanda (paga apenas pelo uso)
- Redução de recursos ociosos

### 🔹 Etapa 3 – Monitoramento e Controle
- AWS CloudWatch para monitoramento
- AWS Cost Explorer para análise de custos
- Alertas de gastos para evitar surpresas

---

## 🧱 Arquitetura da Solução

Sistema baseado em arquitetura serverless:

- Amazon S3 → armazenamento de dados
- AWS Lambda → processamento
- API Gateway → comunicação com sistema
- DynamoDB → banco de dados
- CloudWatch → monitoramento

---

## 💰 Benefícios Esperados

- Redução significativa de custos operacionais
- Eliminação de servidores físicos
- Escalabilidade automática
- Maior segurança e disponibilidade

Segundo a própria AWS, empresas que modernizam seus sistemas podem reduzir custos em até 40% :contentReference[oaicite:0]{index=0}

---

## 🔄 Comparação: Antes vs Depois

| Antes (On-Premise) | Depois (AWS) |
|------------------|-------------|
| Servidores físicos | Serverless |
| Alto custo fixo | Custo sob demanda |
| Escalabilidade limitada | Escala automática |
| Risco de perda de dados | Backup em nuvem |

---

## 🚀 Resultados Esperados

- Sistema mais rápido e confiável
- Redução de falhas
- Melhor experiência do usuário
- Facilidade de expansão

---

## 📚 Referências

- AWS Documentation
- Desafio DIO
- Artigos sobre redução de custos na AWS
