# Case de Precificação de Imóvel em Nova York
 
Este projeto teve como objetivo precificar um imóvel disponível para aluguel na cidade de Nova York, utilizando análise exploratória de dados, estatísticas descritivas e modelos de machine learning.

Além da precificação, algumas perguntas foram respondidas:</br>
</br>
🔹Qual o melhor bairro para investir? </br>
🔹O número mínimo de noites e a disponibilidade afetam o preço? </br>
🔹Existem padrões nos anúncios de imóveis mais caros? </br>

</br></br>
Etapas:

1. Análise exploratória dos dados (EDA)


**Tratamento de dados:** remoção de valores nulos, duplicatas e outliers.</br>
**Análise estatística:** identificação de padrões, correlações e tendências.</br>
**Engenharia de variáveis:** criação de novas métricas para melhor entendimento do faturamento.</br>


2. Modelo de precificação

Foram testados três modelos de machine learning:</br>
**Regressão Linear** → Simples, mas com baixa capacidade de captura de padrões complexos.</br>
**Random Forest** → Melhorou os resultados, mas ainda apresentava alto erro médio.</br>
**Random Forest 2** → Remoção de outliers para melhora de resultados.</br>
**XGBoost** → Melhor desempenho entre os modelos testados.</br>

        Previsão do modelo:
        📌 Melhor modelo: XGBoost </br>
        📌 Preço previsto para o imóvel: US$ 188,81 </br>
        📌 Erro médio do modelo (MAE): ± US$ 28,95 </br>
        📌 Faixa de preço estimada: US$ 159,86 - US$ 217,76 </br>

3. Estimativa de faturamento

![Estimativa de faturamento de acordo com as possíveis taxas de ocupação do imóvel](/case-precificacao-imovel/imagens/faturamento_final.png)

4. Resumo final


O projeto demonstrou que o **XGBoost é o modelo mais eficiente** para precificação de imóveis, prevendo **um preço médio de US$ 188,81**, com um erro de aproximadamente US$ 29 para mais ou para menos.

**Manhattan continua sendo a melhor região para investimento**, e estratégias como descrições estratégicas e diferenciação por comodidades podem otimizar os ganhos do cliente. Mínimo de noites e disponibilidade não impactam o preço final. 

Agora, o cliente pode tomar decisões baseadas em dados para otimizar sua precificação e maximizar sua receita no mercado de aluguel de Nova York!




