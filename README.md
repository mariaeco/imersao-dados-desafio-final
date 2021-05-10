
# Desafio Final Imersão Dados

Título: Efeito do composto '87d714366' (um inibidor NFKB) sobre a expressão gênica de n genes
Autor: Maria Marcolina Lima Cardoso

_____________________________________________________________________________________________________________________________________
Um pouco sobre o autor:
Sou Doutora em Ecologia e atualmente cursando Ciência de Dados e Inteligência Artificial pela UFPB, tenho conhecimento de análise de dados no R, e estou começando a aprender Python, pretendo atuar na área de ciência de dados, se possível em empresas que trabalhem com dados biológicos.
_____________________________________________________________________________________________________________________________________


Aqui você irá encontrar:
A) Dois arquivos do google colab: 
      Um arquivo de explorações iniciais: Investigações.ipynb
      Um arquivo do projeto: ProjetoFinal_MariaMarcolina.ipynb
      
B) Uma seleção prévia de varáveis e compostos a serem utilizados: Selecionamos alguns compostos com efeito inibidor mais frequente para modelarmos

C) Aprendizado de maquina para reconhecimento do composto inibidor escolhido



OBS: Toda a análise foi realizada em cima do composto mais replicado, mas como seria com o composto que gera mais expressão e tem pelo menos uma quantidade relativa de replicação? Entranto, acho que não seria viável, pois os compostos que levam a forte expressão gênica só tem 1 réplica (Explicado mais abaixo com base na avaliação do banco de dados) e não tem como inferir nem modelar bem algo que não tempos replicações suficientes.
Perguntas Iniciais:

1) Quais compostos tiveram algum efeito na ativação dos genes? Se o composto não teve efeito, não continuar a análise com ele. (Não significa que não ter efeito não é importante, se um composto for ruim, então é bom que ele não tenha efeito) Exemplo: compostos classificados como nfkb_inhibitor mas que não causaram nenhum efeito sobre a expressão ou viabilidade, não atrapalhariam o Machine Learning?

2) Se apresentaram efeito, quais apresentaram efeito positivo sobre a ativação do gene e quais apresentaram efeito negativo?

3) Qual o mecanismo de ação (banco de dados 2) principal para o efeito sobre o gene?

Importante A quantidade de genes e compostos é enorme. Como trabalhar com isso? Selecionar o que vamos trabalhar? Então saber se o composto não teve efeito já é uma eliminação de variáveis. Mas às vezes um composto tem efeito sobre um gene ou grupo de genes e sobre outros não. Como tratar isso? Mas, pelo que aprendi trabalhando com os dados, isso não é um problema. Serve para o computador identificar no final qual composto será.
