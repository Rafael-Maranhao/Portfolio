## 📊 Estudo de Correlação: Fatores que Impactam Salários em Dados

<br>

Este projeto investiga como variáveis como cargo, tamanho da empresa e trabalho remoto se relacionam com os salários em USD na área de dados. Utilizando técnicas de regressão linear e análise estatística, o estudo busca identificar padrões e limitações dessas correlações, destacando insights valiosos e desafios comuns em análises de remuneração.

<br>

### 🎯 Objetivo do Estudo
Analisar a influência de três fatores no salário em USD:

- Cargo (codificado por nível)
- Tamanho da empresa (pequena, média, grande)
- Trabalho remoto (binário: remoto vs. híbrido/presencial)

<br>

### 📉 Principais Resultados

<br>

- R² = 5,23%: As variáveis analisadas explicam apenas 5,23% da variação salarial, indicando que fatores não incluídos (ex.: experiência, educação, localização) dominam a determinação dos salários;
- Cargo: Explica 5,07% da variação (+USD 439/ano por nível superior, p < 0,001);
- Tamanho da empresa: Empresas maiores pagam USD 7.634 menos/ano (p = 0,001);
- Trabalho remoto: Vagas remotas têm salários USD 3.588 menores/ano (p = 0,001).

<br>

##### 🔗 Explore o código completo no notebook para detalhes técnicos, visualizações e conclusões aprofundadas!
Dica: Os dados processados estão disponíveis em salarios_processados.csv.
