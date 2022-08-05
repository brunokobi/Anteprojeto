# Comparação de técnicas de redução de dimensionalidade aplicada na detecção de anomalias em poços de petróleo 
Anteprojeto -  Mestrado de Computação Aplicada em Inteligência Artificial</br> 
`Acadêmico: Bruno Kobi Valadares de Amorim`</br>
<br>
`Orientadora: Profª.Dra. Kelly Assis de Souza Gazolli`<br>
`Orientador: Prof. Dr. Hilário Seibel Júnior`<br><br>

# A PROPOSTA
A hipótese deste trabalho é que aplicando técnicas de redução de dimensionalidade,podemos obter uma melhor acurácia do classificador do que a solução sem as técnicas de
redução de dimensionalidade.<br>

A proposta deste trabalho é utilizar três técnicas de redução de dimensionalidade: KPCA (Análise de componentes principais do kernel, em inglês Kernel Principal Component Analysis) (NANGA et al., 2021), ISOMAP (Mapeamento isométrico, em inglês Isometric Mapping) (JIA et al., 2022), e DMT (Transformação múltipla profunda , em inglês Deep Manifold Transformation) (LI; ZANG; WU, 2020).<br>

A base de dados a ser usada nos experimentos é a 3W dataset (VARGAS, 2019). Seguindo o trabalho de Fernandes-Júnior (2022) e Fernandes-Júnior et al. (2020), serão usados os algoritmos de detecção de anomalias de classe única: Floresta de Isolamento (em inglês Isolation Forest), Máquina de Vetor de Suporte de Classe Única (OCSVM do inglês, Oneclass Support Vector Machine), Fator de Anomalia Local (LOF do inglês Local Outlier Factor), Envelope Elíptico (MCD, do inglês Minimum Covariance Determinant) e redes neurais do tipo Autoencoder com camadas feedforward e recorrentes do tipo LSTM (Long Short-Term Memory).<br>

A métrica de comparação utilizada será O F1-score é uma técnica simples que mede a discriminação de dois conjuntos de números reais(AKAY, 2009), variando entre 0 e 1, Os
resultados do uso de técnicas de redução de dimensionalidade serão comparados contra os resultados obtidos por Fernandes-Júnior (2022) e Fernandes-Júnior et al. (2020), que não usam esta etapa em sua solução.
