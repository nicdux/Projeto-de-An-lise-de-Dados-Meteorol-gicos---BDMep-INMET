# Projeto de Análise de Dados Meteorológicos - BDMep/INMET

Este projeto faz parte das atividades acadêmicas da disciplina de **Lógica e Programação de Computadores**, da **PUC-Rio Grande do Sul**. O objetivo é analisar dados meteorológicos históricos obtidos através do Banco de Dados Meteorológicos para Ensino e Pesquisa (BDMep), do Instituto Nacional de Meteorologia (INMET).

![image](https://github.com/user-attachments/assets/42b45db1-028a-4b36-a9bc-c76349fe8c51)

---

## Objetivo do Projeto

Realizar uma análise exploratória dos dados meteorológicos, identificando informações relevantes como:
- Mês e ano mais chuvoso.
- Média histórica da temperatura mínima para meses específicos.
- Gráfico com a evolução da temperatura mínima.

---

## Ferramentas e Bibliotecas

- Python
- CSV
- Matplotlib

---

## Estrutura dos Dados

Os dados utilizados estão armazenados no arquivo CSV obtido do INMET, contendo informações como:
- Data
- Precipitação (mm)
- Temperatura máxima (°C)
- Temperatura mínima (°C)
- Umidade (%)
- Vento (m/s)

---

## Funcionalidades do Código

O código desenvolvido realiza as seguintes funções:

1. **Leitura e tratamento dos dados:**
   - Converte dados para tipos apropriados (inteiros e floats).

2. **Identificação do mês mais chuvoso:**
   - Calcula o mês e ano com a maior soma acumulada de precipitação.

3. **Cálculo da média histórica das temperaturas mínimas:**
   - Média das temperaturas mínimas para um mês escolhido pelo usuário, de 2006 a 2016.

4. **Visualização gráfica:**
   - Exibe gráfico de barras das médias anuais da temperatura mínima para facilitar a análise visual.



## Como Executar o Projeto

1. **Clone este repositório:**

git clone <url-do-seu-repositório>


2. **Instale as dependências necessárias:**

pip install matplotlib


3. **Execute o script Python:**
```bash
python seu_script.py
```

4. **Informe o mês desejado quando solicitado para obter a análise específica.**

---

## Resultados Obtidos

O projeto gera:
- Identificação precisa do mês mais chuvoso no período.
- Médias anuais das temperaturas mínimas.
- Visualização gráfica clara para identificar tendências nas temperaturas mínimas ao longo dos anos.

---

## Exemplos de Saída

- **Mês mais chuvoso:**
```
Mês mais chuvoso: 6/1998 com 291.10 mm
```

- **Média das temperaturas mínimas:**
```
Média de temperatura mínima 6/2006: 15.55ºC
Média geral da temperatura mínima no mês selecionado entre 2006-2016: 16.03ºC
```



---

## Conclusão

Este projeto demonstrou a aplicação prática de Python na análise de dados meteorológicos reais, facilitando insights sobre comportamento climático através da programação.

---




