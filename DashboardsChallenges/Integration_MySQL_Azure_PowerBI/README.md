# 📊 Processamento de Dados Simplificado com Power BI

> **Desafio de Projeto:** Integração do MySQL e Azure com Power BI para análise e visualização de dados.

## 🚀 Etapas do Projeto

1. **Criação de Instância MySQL no Azure** 🌐
   - Configure uma nova instância do MySQL no Azure.

2. **Criação do Banco de Dados** 🗃️
   - Importe a base de dados disponível no [GitHub](https://github.com/julianazanelatto/power_bi_analyst/tree/main/M%C3%B3dulo%203/Desafio%20de%20Projeto).

3. **Integração do Power BI com MySQL** 🔗
   - Conecte o Power BI à instância MySQL criada no Azure.

4. **Verificação e Transformação dos Dados** 🔍
   - **Cabeçalhos e Tipos de Dados:** Verifique se estão corretos e consistentes.
   - **Valores Monetários:** Converta para o tipo `double` para precisão.
   - **Valores Nulos:** Identifique e analise se é necessário remover ou tratar os valores nulos.
   - **Colaboradores Sem Gerente:** Verifique se há colaboradores sem gerente e investigue a causa. 🤔
   - **Departamentos Sem Gerente:** Identifique se há departamentos sem gerente e preencha as lacunas conforme necessário. 📊
   - **Horas dos Projetos:** Verifique e valide o número de horas registradas para os projetos.
   - **Separação de Colunas Complexas:** Separe colunas que contêm múltiplos dados para simplificar a análise.
   - **Mesclagem de Consultas:**
     - Mescle as tabelas `employee` e `department` para criar uma tabela `employee` com os nomes dos departamentos associados. 🏢
     - Elimine colunas desnecessárias durante esse processo.
   - **Junção de Colaboradores e Gerentes:**
     - Realize a junção entre a tabela de colaboradores e a tabela de gerentes. Você pode usar SQL ou Power BI para isso. 🛠️
     - **Se usar SQL**, inclua a query utilizada no README.
   - **Mesclagem de Nomes:**
     - Combine as colunas de Nome e Sobrenome em uma única coluna para simplificar a visualização. 📝
   - **Mesclagem de Departamentos e Localizações:**
     - Crie uma coluna única que combine os nomes dos departamentos e suas localizações. 🌍

5. **Agrupamento dos Dados** 📊
   - Agrupe os dados para determinar o número de colaboradores por gerente.

6. **Eliminação de Colunas Desnecessárias** 🚮
   - Remova colunas que não serão utilizadas nos relatórios finais.

## 📌 Explicação dos Conceitos

- **Mesclar vs. Atribuir:** 
  - A mesclagem é usada para criar um campo único combinando dados relacionados, como nomes de departamentos e localizações. Isso é essencial para criar um modelo estrela eficiente em módulos futuros. Atribuir, por outro lado, seria inadequado neste contexto, pois não permite a combinação direta de dados e não contribui para a criação de um modelo de dados consolidado. 🌟
