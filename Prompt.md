Atue como um Engenheiro de Machine Learning e Cientista de Dados Sênior. 

Estou desenvolvendo um projeto prático de Aprendizado de Máquina utilizando o dataset Breast Cancer Wisconsin (Diagnostic) [OpenML ID: 560 | 569 instâncias | 30 atributos numéricos contínuos | Classe Alvo Binária: Maligno vs. Benigno].

Os dados brutos estão localizados no diretório local `database/`. 
Anexei dois arquivos de especificação ao projeto:
1. `enunciado.pdf`: contém a descrição geral do problema, objetivos e regras de negócio.
2. `description.png`: contém os requisitos específicos de implementação, métricas e restrições.

---

### Seu Objetivo:
Analise detalhadamente o conteúdo dos dois arquivos anexados (`enunciado.pdf` e `description.png`) e elabore um plano de ação completo para a solução, estruturado nas seguintes etapas:

1. **Visão Geral e Requisitos:**
   - Resumo claro do que o enunciado e a imagem estão exigindo.
   - Identificação do problema principal, métrica primária de avaliação (ex: Recall/Sensibilidade, F1-Score, AUC-ROC) e justificativa da escolha baseada no contexto médico.

2. **Engenharia de Dados & EDA:**
   - Checklist do pipeline de Pré-processamento de Dados (tratamento de valores ausentes se houver, verificação de desbalanceamento de classes, escalonamento/normalização).
   - Proposta de Análise Exploratória de Dados (EDA) focada em detecção de multicolinearidade (como matriz de correlação) e distribuição das variáveis.

3. **Modelagem e Avaliação:**
   - Sugestão de pelo menos 3 a 4 algoritmos de classificação baseline e avançados (ex: Regressão Logística, Random Forest, XGBoost/LightGBM, SVM).
   - Estratégia rigorosa de validação cruzada (ex: Stratified K-Fold) para evitar vazamento de dados (*data leakage*).

4. **Guia de Código (Python):**
   - Estrutura modular sugerida para o código (orientada a scikit-learn/pipelines).

---

Para começarmos, confirme a leitura dos requisitos dos arquivos `enunciado.pdf` e `description.png`, apresente o resumo dos pontos chave e proponha o plano de execução passo a passo antes de gerarmos o código.
