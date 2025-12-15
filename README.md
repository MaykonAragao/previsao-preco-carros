# ✅ Conclusão Final do Projeto

Este projeto demonstrou a eficácia de um modelo **Random Forest Regressor** para prever os preços de carros usados. O processo envolveu análise exploratória, engenharia de features e treinamento de um modelo robusto, resultando em um alto poder preditivo.

### Resumo do Processo

1.  **Análise Exploratória (EDA):** A análise inicial revelou fortes correlações entre o preço de venda e características como o ano de fabricação, a quilometragem e o preço original do veículo.

2.  **Engenharia de Features:** Uma nova feature, `Car_Age` (idade do carro), foi criada a partir do ano de fabricação para fornecer uma variável mais intuitiva e poderosa para o modelo.

3.  **Pré-processamento:** As variáveis categóricas (`Fuel_Type`, `Seller_Type`, `Transmission`) foram transformadas em formato numérico através de One-Hot Encoding.

### Resultados e Performance do Modelo

O modelo `RandomForestRegressor` treinado apresentou uma performance excelente no conjunto de teste:

*   **Coeficiente de Determinação (R²):** O modelo alcançou um **R² de aproximadamente 0.96**, indicando que consegue explicar 96% da variabilidade nos preços de venda dos carros. Este é um resultado excepcional.
*   **Erro (RMSE):** O erro médio de previsão, medido pelo RMSE, foi baixo, confirmando a alta precisão do modelo.

### Análise de Importância das Features

Uma das principais vantagens do Random Forest é a capacidade de extrair a importância de cada feature. A análise revelou que os fatores mais decisivos para determinar o preço de um carro usado são:

1.  **`Present_Price`:** O preço de um carro novo do mesmo modelo. Este foi, de longe, o preditor mais forte.
2.  **`Car_Age`:** A idade do carro. Quanto mais velho, menor o preço.
3.  **`Kms_Driven`:** A quilometragem.



**Conclusão Final:** O modelo não apenas prevê os preços com alta precisão, mas também confirma a intuição de mercado de que o preço original e a idade do veículo são os principais fatores que ditam seu valor de revenda.
