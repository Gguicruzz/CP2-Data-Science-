Análise Exploratória e Descritiva: Evolução dos Processadores AMD
Este projeto realiza uma análise estatística e descritiva detalhada de mais de 30 anos de evolução de hardware da AMD (desde os modelos clássicos de 1994 até as arquiteturas modernas Zen 5 de 2024), utilizando ciência de dados para extrair insights estratégicos sobre performance, precificação e eficiência energética.

° Principais Insights Obtidos:
Lei de Moore na Prática: Forte correlação positiva de 0.89 entre o total de núcleos físicos (cores_total) e o desempenho geral (PassMark), comprovando que o paralelismo ditou o salto de performance.
Desempenho vs. Preço: O preço de lançamento sozinho não garante performance proporcional (correlação moderada de 0.38), revelando que fatores geracionais e de arquitetura pesam mais no custo-benefício.
Eficiência Energética: Segmentação por arquitetura identificou saltos expressivos na relação Performance por Watt, destacando a evolução recente em processos de fabricação menores (nanômetros).
° Stack Tecnológica:
Linguagem: Python
Manipulação de Dados: Pandas, NumPy
Visualização de Dados: Matplotlib
Estatística Descritiva: SciPy (Assimetria, Curtose, IQR e Z-score para detecção de outliers)
° Diferenciais do Projeto:
Pipeline completo desde a extração automatizada via API Kaggle até engenharia de atributos.
Abordagem analítica rigorosa com tratamento de dispersão, distribuição e relações multivariadas.
Visualizações claras (Boxplots, Scatter Plots e Heatmaps de correlação) voltadas para Storytelling de dados.
