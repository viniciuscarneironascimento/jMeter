# jMeter

🔗 [Acesse o repositório no GitHub](https://github.com/viniciuscarneironascimento/jMeter)

---

## 📝 Descrição

Repositório do portfólio dedicado a um estudo prático de **testes de performance** utilizando o **Apache JMeter**.  
O projeto explora a criação de planos de teste, a simulação de múltiplos usuários simultâneos e a análise de tempo de resposta, servindo como uma **prova de conceito para testes de carga em aplicações web**.

---

## 🚀 Resultados Alcançados

- Aprofundei meus conhecimentos em **testes de performance** utilizando o **Apache JMeter** após concluir o **curso *“JMeter – Testes de Performance” (Udemy)***. No treinamento, aprendi os fundamentos da ferramenta, incluindo conceitos básicos, arquitetura, criação de scripts, estrutura de planos de teste, identificação de gargalos e análise de indicadores.

- Realizei testes de performance no site [ge.globo.com](https://ge.globo.com), criando um plano de teste em XML no JMeter para simular carga com **2.000 requisições GET simultâneas**. O objetivo foi **observar o comportamento do site sob alta demanda**, utilizando tabelas e gráficos para coletar métricas de desempenho.

- Desenvolvi também um plano de teste direcionado ao endpoint dos **Correios (busca CEP)**, simulando **100 requisições GET simultâneas**. Esse teste mais leve teve como foco avaliar o tempo de resposta e o índice de sucesso das requisições, servindo como base para análise inicial de performance.

- Criei uma **prova de conceito (POC)** mais robusta aplicada ao domínio [nextme.predigital.com.br](https://nextme.predigital.com.br), com foco em testes de carga pesada.  O plano simula **4.500 requisições quase instantâneas**, exigindo alto desempenho tanto do servidor quanto da máquina que executa o JMeter. Essa configuração é ideal para testes de **estresse** ou **volume**, podendo provocar:
  - Queda da aplicação  
  - Erros por limitação de rede  
  - Travamentos no JMeter por uso excessivo de memória ou CPU  

> ⚠️ **Atenção:** esse tipo de teste não deve ser executado em ambientes de produção sem o devido controle, pois pode comprometer a disponibilidade da aplicação.
