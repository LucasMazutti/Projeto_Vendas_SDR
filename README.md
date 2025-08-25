# 📊 Projeto_Vendas_SDR  

🎯 **Análise do setor de pré-vendas** utilizando um dataset do Kaggle que simula um cenário real do dia a dia comercial.  

---

## 🖋️ Resumo do projeto
O dataset foi propositalmente criado para estar **sujo e desorganizado**, exigindo um forte trabalho de limpeza e tratamento.  
Principais problemas encontrados:  
- Mais de **60% dos valores numéricos faltantes/nulos**.  
- Colunas de texto despadronizadas (maiúsculas, minúsculas misturadas).  
- Datas em formatos diferentes (`DD/MM/AAAA`, `AAAA/MM/DD`) e não convertidas para datetime.  
- Valores matemáticos inconsistentes, exigindo recálculo.  

### 🔍 Tratamento aplicado
- **Valores nulos em colunas de texto:** preenchidos com `"No Name"`, `"No Order ID"`, `"No Channel"`.  
- **Valores nulos em colunas numéricas:** preenchidos com a **mediana**, usando hierarquia **fallback**.  
- **Datas:** padronizadas para o formato `YYYY-MM-DD`.  
- **Valores inconsistentes:** recalculados conforme regras de negócio.
Todos os **insights** e a visualização do relatório você encontra no arquivp .pbix aqui mesmo no repositório.

---

## 🛠️ Ferramentas utilizadas
- 🐍 Python (Pandas)  
- 📓 Jupyter Notebook  
- 📊 Excel  
- 📈 Power BI (DAX)  

---

## 🚀 Aprendizados
- Manipulação de **datasets com muitos valores nulos**.  
- Aplicação prática de **estatística básica** (uso de medianas).  
- Integração entre **Python e Power BI**.  
- Estruturação de um fluxo de limpeza de dados próximo ao mundo real.  

---

## 😊 Onde me encontrar
- 🔗 [LinkedIn](https://www.linkedin.com/in/lucas-m-grabarski-3472521b8/)  
- 📧 Email: lucasmazutti10@gmail.com  

