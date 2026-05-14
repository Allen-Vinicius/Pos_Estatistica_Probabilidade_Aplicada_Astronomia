# Pos_Estatistica_Probabilidade_Aplicada_Astronomia
  Aluno: Allen Vinicius Barbosa Ferreira - 2011200788
  * Professores Orientadores: Sérgio Monteiro, D.Sc. e Manuel Martins, D.Sc.

* Enunciado do Problema: Calibração de Brilho em Estrelas Variáveis
Em astronomia, a medição do brilho de astros (magnitude aparente) é frequentemente afetada por ruídos instrumentais e atmosféricos. Imagine que uma equipe de astrofísicos está monitorando uma estrela específica e sabe que, devido às propriedades físicas do astro, as medições de brilho tendem a seguir uma Distribuição Gaussiana (Normal) em torno de um valor central (μ), com uma variabilidade inerente (σ).

* O Problema: O objetivo é simular um conjunto de 1.000 observações de brilho para esta estrela, realizar uma análise de inferência para estimar se a média observada condiz com o valor teórico esperado e identificar possíveis anomalias nos dados captados.

* Conclusão dos resultados obtidos:
  
✓ Telescópio bem calibrado
μ teórico (15,5000) dentro do IC 95% [15,4188; 15,5239]. t-test não rejeita H₀ com p=0,2848 > 0,05. Ambos os testes de normalidade confirmam aderência à distribuição Normal.

↗ Remoção melhora a precisão
Sem os 17 detectados (n=983): σ cai de 0,8468 → 0,7777 (−8,2%) e a largura do IC 95% reduz de 0,1051 → 0,0974 mag (−7,3%). Estimativa mais confiável.

⚠ Ruído levemente acima do esperado
σ amostral (0,8468) supera o teórico (0,8000) em 5,9%. Os limites de Tukey se expandem e 3 dos 20 outliers injetados não foram detectados.

✗ 17 falhas instrumentais identificadas
LI=13,2977 · LS=17,6705 mag (Q1−1,5·IQR / Q3+1,5·IQR). 3 outliers escaparam — magnitudes deslocadas caíram dentro da amplitude natural de σ=0,8.
