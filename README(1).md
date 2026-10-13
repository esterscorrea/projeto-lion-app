# 🦁 Projeto Lion App — Organização Financeira para o Imposto de Renda

Planilha em Excel que organiza os dados financeiros de uma pessoa física (titular, rendimentos bancários e entradas mensais) e gera automaticamente um resumo com indicadores, pensada para facilitar a preparação da declaração do Imposto de Renda.

> Projeto desenvolvido como entrega de desafio de projeto na [DIO](https://www.dio.me/).

---

## 📌 Objetivo

Reunir em um só lugar as informações necessárias para a declaração do IR e transformar dados dispersos (informes de bancos, holerites, extratos) em uma visão financeira clara, sem cálculos manuais.

## 🗂️ Estrutura da planilha

A planilha [`projeto_lion_app.xlsx`](./projeto_lion_app.xlsx) possui 4 abas, em fluxo de preenchimento:

| Aba | Função |
|---|---|
| **1. TITULAR** | Cadastro dos dados da pessoa física (nome, CPF, endereço, contato) e perguntas de perfil, como alterações desde a entrega anterior, dependente cônjuge e residência no exterior. |
| **2. INFORMES** | Informes de rendimentos bancários: banco, valor atual e arquivo anexo (PDF do informe) de cada instituição, com o total consolidado. |
| **3. NOTAS** | Registro das entradas mês a mês (data, categoria e valor), vindas de holerite, notas bancárias ou extratos. |
| **4. RESUMO** | Visão geral **calculada automaticamente** a partir das abas anteriores, com gráficos. |

### O que a aba RESUMO calcula

- **Patrimônio por banco:** valor atual de cada instituição e o percentual sobre o total.
- **Entradas por categoria:** quantidade de lançamentos, valor total e percentual por categoria (Holerite, CNPJ, Freelance).
- **Indicadores:** patrimônio total em bancos, total de entradas, número de lançamentos, média por lançamento e maior entrada.

Ao alterar os dados em INFORMES ou NOTAS, o resumo e os gráficos se atualizam sozinhos.

## 🛠️ Tecnologias e ferramentas

- Microsoft Excel (fórmulas e gráficos)
- Claude (assistente de IA) como apoio na estruturação do projeto
- GitHub para documentação e versionamento

<!-- Ajuste a lista acima com as ferramentas que você realmente usou -->

## 🚀 Como usar

1. Baixe o arquivo `projeto_lion_app.xlsx`.
2. Na aba **TITULAR**, preencha seus dados.
3. Na aba **INFORMES**, informe o banco, o valor atual e o nome do PDF do informe de cada instituição.
4. Na aba **NOTAS**, registre cada entrada de receita (data, categoria, valor).
5. Abra a aba **RESUMO** para ver os totais, percentuais e gráficos.

## 💡 Aprendizados

- **Layout e organização visual:** nas vídeo-aulas aprendi a montar o layout de uma planilha, deixando tudo organizado e visualmente agradável, com títulos, seções e formatação que facilitam o preenchimento e a leitura.
- **Uso de IA como apoio:** usei o Claude para me ajudar a criar a nova aba **RESUMO**, que reúne automaticamente os dados das outras abas em totais, percentuais, indicadores e gráficos.
- **Resultado:** com o resumo ligado às abas INFORMES e NOTAS, basta atualizar os dados e a visão geral se atualiza sozinha, sem cálculos manuais.

## 🔒 Privacidade

Esta planilha lida com dados sensíveis (CPF, título de eleitor, contatos e valores financeiros). A versão publicada neste repositório contém **apenas dados fictícios** para demonstração. Nunca publique seus dados reais em um repositório público.

## 📁 Estrutura do repositório

```
.
├── README.md
├── projeto_lion_app.xlsx
└── images/
    ├── titular.png
    ├── informes.png
    ├── notas.png
    └── resumo.png
```

## 🖼️ Capturas de tela

<!-- Depois de subir os prints na pasta /images, estas linhas passam a funcionar -->

![Aba Titular](./images/titular.png)
![Aba Informes](./images/informes.png)
![Aba Notas](./images/notas.png)
![Aba Resumo](./images/resumo.png)

## 👩‍💻 Autora

**Mary Lima Nogueira**
