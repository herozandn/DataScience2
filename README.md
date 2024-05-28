# Objetivos do projeto

* Prever a posição final das equipes do Campeonato Brasileiro com base em algumas variáveis
* Estimar a chance de vitória, derrota e empate de dois times em uma partida
* *Bônus:* Prever o resultado de partidas de futebol

# Estrutura do Trabalho

1. Coleta dos dados (via Kaggle e Github);
   * Possíveis datasets:
       [Medium](https://raw.githubusercontent.com/viniciusfjacinto/medium/main/futpred_medium.csv), [Semestre passado](https://www.kaggle.com/datasets/adaoduque/campeonato-brasileiro-de-futebol), [Kaggle](https://www.kaggle.com/datasets/andreifnmg/campeonato-braileiro-20092018?select=Legenda_Tabela_Clubes), [Kaggle principal](https://www.kaggle.com/datasets/josevitormichelin/brazilian-football-championship-brasileiro)
3. Pré-Processamento (limpeza dos dados, imputação de informações faltantes, criação de novas variáveis, padronização);
4. Seleção das variáveis mais importantes (fazer teste de correlação);
5. Divisão da base de dados em treino e teste;
6. Aplicação dos Modelos;
7. Avaliação (a partir daí, realiza-se a implementação do modelo ou retorna-se ao ponto 2 ou 3 se os resultados não forem satisfatórios)
