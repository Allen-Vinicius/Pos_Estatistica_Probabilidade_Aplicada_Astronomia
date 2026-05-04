# Pos_Estatistica_Probabilidade_Aplicada_Astronomia
o	Alunos: Allen Vinicius Barbosa Ferreira - 2011200788
o	Professores Orientadores: Sérgio Monteiro, D.Sc. e Manuel Martins, D.Sc.


Enunciado do Problema: Calibração de Brilho em Estrelas Variáveis
Em astronomia, a medição do brilho de astros (magnitude aparente) é frequentemente afetada por ruídos instrumentais e atmosféricos. Imagine que uma equipe de astrofísicos está monitorando uma estrela específica e sabe que, devido às propriedades físicas do astro, as medições de brilho tendem a seguir uma Distribuição Gaussiana (Normal) em torno de um valor central (μ), com uma variabilidade inerente (σ).

O Problema: O objetivo é simular um conjunto de 1.000 observações de brilho para esta estrela, realizar uma análise de inferência para estimar se a média observada condiz com o valor teórico esperado e identificar possíveis anomalias nos dados captados.

##Conclusão dos resultados obtidos## 
======================================================
 SIMULAÇÃO DE BRILHO — ESTRELA VARIÁVEL
======================================================
   μ teórico  : 15.5000 mag
   σ ruído    : 0.8000 mag
   N observ.  : 1000
   Outliers   : 20 injetados (2.0%)
======================================================
 ESTATÍSTICAS DESCRITIVAS
======================================================
   Média amostral  : 15.4713 mag
   Mediana         : 15.4823 mag
   Desvio padrão   : 0.8468 mag
   Coef. de Var.   : 5.47 %%
   Assimetria      : 0.0154
   Curtose (excess): 0.7616
======================================================
 INTERVALO DE CONFIANÇA — 95% (t de Student)
======================================================
   Erro padrão (SE)  : 0.02678 mag
   t crítico (α/2)   : 1.9623
   IC 95%%            : [15.4188 ; 15.5239] mag
   μ teórico está DENTRO do IC
======================================================
 TESTE DE HIPÓTESE — t-test bilateral
======================================================
   H0: μ = 15.50  |  H1: μ ≠ 15.50
   Estatística t     : -1.0702
   p-valor           : 0.284771
   Decisão (α=0.05)  : NÃO REJEITAR H0
======================================================
 DIAGNÓSTICO DE OUTLIERS (Regra de Tukey: 1.5×IQR)
======================================================
   Outliers detectados : 17 (1.7%% das obs.)
   Limite inferior     : 13.2977 mag
   Limite superior     : 17.6705 mag
   Comparativo COM vs SEM outliers:
   Métrica                            COM       SEM
   Média (mag)                    15.4713   15.4631
   Desvio padrão (mag)             0.8468    0.7777
   Viés (x̄ - μ)                -0.0287   -0.0369
   IC 95%% COM : [15.4188 ; 15.5239]
   IC 95%% SEM : [15.4144 ; 15.5118]
======================================================
 TESTES DE NORMALIDADE
======================================================
   Lilliefors  D = 0.0211 | p = 0.34769 | Não rejeita Normal (α=0.05)
   And.-Darling A = 0.6913 | p = 0.07085 | Não rejeita Normal (α=0.05)
   Nota: a rejeição é esperada com outliers injetados;
   confirma a sensibilidade dos testes à contaminação.
======================================================
 ANÁLISE CONCLUÍDA COM SUCESSO
======================================================
