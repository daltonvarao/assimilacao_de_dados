# Sobre
Repositório referente aos códigos do Trabalho de iniciação científica cujo objetivo é aplicar métodos de assimilação de dados ao sistema caótico de lorenz.


# Teoria do caos e Efeito Borboleta (sensibilidade às condições iniciais)
A teoria do caos afirma que, em um determinado Problema de Valor Inicial (PVI), quando se tem uma gama muito grande de variáveis a sua previsibilidade em um intervalo longo de tempo é muito pequena devido às constantes mudanças nesse intervalo. Isso se dá por conta dessa variação, em sua maioria, não se comportar de forma constante ou padronizada, tornando o sistema cótico e não determinístico. Essa imprevisibilidade foi observada por Edward Lorenz em seus estudos acerca da previsão numérica do tempo. Ao observar os dados do seu modelo de estudo, Lorenz concluiu que pequenas mudanças nas condições iniciais do modelo, causadas por aproximação de casas decimais nos cálculos, podem levar os resultados futuros a comportamentos extrema e exponecialmente divergentes do esperado, Lorenz chamou esse evento de Efeito Borboleta. Lorenz desenvolvel um sistema de equações simplificando as equações de Saltzman.

![Fig. 1- Equações de Lorenz](https://raw.githubusercontent.com/daltonfelipe/assimilacao_de_dados/master/figuras/equacoes_lorenz.png).

# Assimilação de dados
É uma técnica numérica utilizada para determinar ótimas condições iniciais, combinando valores de um modelo matemático com valores de observações, tendo assim dados de análise que aproximam-se, dado determinado erro, dos dados do modelo "correto". Admitindo a natureza caótica da maioria dos modelos matemáticos que representam os fenômenos que nos cercam, é imprescindível a sua utilização para a minimização dos erros e uma melhor previsão de futuros comportamentos de tais modelos. Ou seja, a partir da adição de observações em uma determinada frequência a um modelo com valores ligeiramente pertubados (background) em relação ao modelo que se assume como correto (solução real), ocorre a correção do modelo background o aproximando, com o menor erro possivel, da solução real. Correções sucessivas e Interpolação Ótima são exemplos de técnicas de assimilação de dados.

# 

   

