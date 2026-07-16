## Apresentação

Uma função se estabelece quando se relaciona uma ou mais grandezas. Pensando de modo mais formal, ao considerar dois conjuntos, A e B, não vazios, uma função de A em B é uma relação que associa a cada elemento de x pertencente a A um único elemento de y pertencente a B. Isso significa que, ao fazer uso de diagramas de flechas para representar uma função, todo x do conjunto de partida (A) estará associado a algum y do conjunto de chegada (B), além de nenhum x poder estar associado a mais de um y (Stewart, 2013).

O estudo de funções tem vasta aplicação, tanto na matemática quanto nos fenômenos naturais, econômicos, entre outros campos. Com isso em mente, é possível avançar para o estudo de limite, que busca determinar o comportamento de uma função à medida que ela se aproxima de algum valor de interesse. Esse tópico da matemática é relevante para diversas situações mais avançadas, como análise de pontos de máximo e mínimo, interseção entre funções, continuidade de funções, séries numéricas, etc. (Guidorizzi, 2001).

Nesta Unidade de Aprendizagem, você perceberá a aplicabilidade de funções e limites e será instigado a refletir sobre problemas aplicáveis à educação básica e sobre formas de trabalhar esse campo do conhecimento com exemplos e representações intuitivas, consistentes e eficientes. Espera-se que os elementos sugeridos sejam estimulantes para a busca do aprofundamento dos estudos e para a compreensão ​​​​​​​do conceito de função, de limites e de suas respectivas propriedades.

Bons estudos.

#### Ao final desta Unidade de Aprendizagem, você deve apresentar os seguintes aprendizados:

- Descrever o conceito formal de função.
- Identificar a definição formal de limite.
- Reconhecer as propriedades de limites.


## Desafio

 Prazo para envio: 31/07/26 23:59
 Liberação do feedback: 01/08/26 00:00

A modelagem matemática é uma ferramenta utilizada para prever o comportamento de sistemas reais, desde fenômenos físicos até operações de negócios. Em muitos cenários, os sistemas têm uma capacidade máxima ou um ponto de ruptura. Funções, especialmente as funções racionais, são frequentemente utilizadas para descrever tais situações, pois seu comportamento pode mudar drasticamente quando a variável de entrada se aproxima de um valor crítico – tipicamente um valor que anularia o denominador da função (Boyce; Diprima, 2010).

Graficamente, esse ponto crítico está associado a uma assíntota vertical, uma fronteira de que a função se aproxima, mas nunca atinge, e onde o sistema se torna instável. O conceito de limite é a ferramenta fundamental que nos permite analisar e prever com precisão o que acontece com a função à medida que ela se aproxima desse ponto, descrevendo se ela "explode" em direção ao infinito e, portanto, indicando a iminência de uma falha (Stewart, 2013).

Analise o caso descrito a seguir:

![Descrição da imagem não disponível](https://creator-files.plataforma.grupoa.education/learning-object/154432/46717_EXA_DES_V2-2025-10-15T11:32:44-03:00.png)

Você precisa analisar o desempenho do servidor e fornecer uma recomendação clara para a próxima campanha da Black Friday, que é o evento mais crítico para a empresa.

Assim:

a) Descreva o que a relação expressa pela função T(u) significa em termos práticos. Calcule o tempo de resposta para 5.000 (u=5) e 15.000 (u=15) usuários. O que a diferença entre esses dois resultados indica sobre o comportamento do servidor?

b) O time de engenharia afirma que o sistema se torna instável quando o tempo de resposta ultrapassa 10 segundos. No entanto, sua análise deve focar no limite teórico da infraestrutura. Utilizando o conceito de limite, determine o comportamento do tempo de resposta à medida que o número de usuários se aproxima da capacidade máxima do servidor (20.000 usuários). Expresse sua análise usando a notação formal de limite.

c) A equipe de marketing planeja uma campanha extremamente agressiva para a Black Friday, com uma meta de atrair 22.000 usuários simultâneos. Com base na sua análise completa da função e do seu limite, qual seria sua recomendação final (em uma frase) para a head de tecnologia? Justifique sua resposta de forma técnica, explicando os riscos operacionais envolvidos.


#### ✅ Resposta ao Desafio

a) Cálculo para valores específicos

Para u=5 (5.000 usuários) 

$$ T(5) = \frac{2 \cdot 5}{20 - 5} = \frac{10}{15} \approx 0,67 \text{ segundos} $$


Para u=15 (15.000 usuários) 

$$ T(15) = \frac{2 \cdot 15}{20 - 15} = \frac{30}{5} = 6 \text{ segundos} $$

O tempo cresce de forma não linear, mostrando que perto da capacidade máxima o servidor degrada rapidamente.

---
b) Análise do limite
Limite quando u→20− 

$$ \lim_{u \to 20^-} \frac{2u}{20 - u} $$



Como o denominador tende a zero positivo: 

$$ \lim_{u \to 20^-} T(u) = +\infty $$


O tempo de resposta explode, confirmando a instabilidade do sistema e a assíntota vertical em u=20.

---
c) Recomendação final

Para u=22 (22.000 usuários), a função não é definida. Isso representa falha total da infraestrutura.

Conclusão:
 A campanha da Black Friday não deve ser realizada sem expansão da infraestrutura, pois o sistema entrará em colapso ao ultrapassar 20.000 usuários simultâneos, tornando o site indisponível e gerando riscos críticos de operação.


Enviado em: 16/07/2026 20:03


## Infográfico

Ao estudar cálculo, logo há o primeiro contato com limites. A essência do limite consiste em analisar e descrever o comportamento de funções, para o cálculo de área, em diversas aplicações práticas, além de ser fundamental para a definição de derivadas (conceito que o sucede) (Stewart, 2013).

A definição formal de limite pode parecer um pouco complexa, mas é muito importante para a compreensão dos limites estudados na sequência. Existem métodos e propriedades que viabilizam o seu cálculo de maneira muito eficiente e menos trabalhosa (Guidorizzi, 2001).

Neste Infográfico, você verá a definição formal de limite por meio de representações gráficas, passo a passo, para que consiga perceber todo o raciocínio envolvido por trás de sua definição. ​​​​​​​

![Descrição da imagem não disponível](https://creator-files.plataforma.grupoa.education/learning-object/154433/46717_EXA_INF_V2-2025-10-15T11:41:15-03:00.png)



## Conteúdo do Livro

O número surgiu na Antiguidade como uma necessidade humana de quantificar os objetos, resolver as questões de troca de mercadorias e serviços, além de cuidar dos animais, dos quais vinha o sustento das famílias. Já o cálculo foi desenvolvido para compreender fenômenos físicos, como as marés, ou, ainda, fenômenos da natureza, como as fases da lua, a contagem do tempo, a luz, a gravidade, etc. Todas essas relações envolvem o conceito de função, que foi e ainda é essencial para a humanidade (Boyer; Merzbach, 2012).

Outro conceito fundamental é o de limite. Newton e Leibniz, de forma independente, estudaram o significado de taxa de variação instantânea, que tem como princípio o conceito de limite. Essas descobertas, que formam a base do cálculo diferencial, permitiram o surgimento de métodos eficientes e promissores para a ciência (Struik, 2009).

No capítulo Funções e limites, base teórica desta Unidade de Aprendizagem, você vai estudar esses importantes conceitos da matemática, percebendo sua aplicabilidade e a noção intuitiva de limite, até chegar à sua formalização rigorosa. À medida que você for conhecendo os conceitos, as definições e as propriedades, percebendo-os como parte de seu cotidiano, poderá buscar soluções para problemas reais e identificar a grande relevância do tema.

Boa leitura. ​​​​​​​

![Descrição da imagem não disponível](https://statics-marketplace.plataforma.grupoa.education/sagah/934b29d3-5e80-4665-ab1d-4c988e14456b/0dd941ed-598b-444a-a509-c1d9c3cd1f63.jpg)



## Dica do Professor

Para compreender a definição formal de limites, é importante ter uma noção intuitiva, o que pode ser obtido, por exemplo, por meio de análises gráficas e da construção de tabelas. Lançar mão desses métodos é interessante para que o estudante faça uma conexão entre o que é dado em determinado teorema ou definição e o que isso representa na prática. Outro ponto relevante é ter claro que o limite permite analisar o comportamento de uma função e tirar conclusões a seu respeito (Stewart, 2013).

Essa abordagem intuitiva é fundamental para a construção do conhecimento, mas pode se mostrar imprecisa ou trabalhosa dependendo da complexidade da função. Por sua vez, a definição formal de limite, embora seja o alicerce rigoroso do cálculo, frequentemente representa um alto nível de abstração para o primeiro contato com o tema. Diante desse cenário, surge uma pergunta natural: como calcular limites de forma precisa sem ter que recorrer sempre à análise gráfica ou à complexa definição formal? (Munem; Foulis, 1982)

Nesta Dica do Professor, você vai aprender uma das maneiras de trabalhar com limites a partir de suas propriedades, que, por sua vez, foram deduzidas no intuito de tornar o uso de limite mais eficiente e prático, sem a necessidade de resolvê-lo a partir de sua definição formal, tarefa que pode ser bastante trabalhosa. 

​​​​​​​​​​​​​​
## Exercícios

 Prazo para envio: 31/07/26 23:59
 Liberação do feedback: 01/08/26 00:00


#### Questão 1
Em matemática, uma função é uma regra que estabelece uma correspondência unívoca entre dois conjuntos. Formalmente, dados dois conjuntos não vazios, A e B, uma função de A em B, denotada por f: A → B, é uma relação que associa a cada elemento x ∈ A um único elemento y ∈ B (Stewart, 2013).

Com base nessa definição rigorosa, assinale a alternativa que descreve corretamente e de forma completa as condições para que uma relação f seja uma função de A em B.

A. Cada elemento de A deve estar associado a pelo menos um elemento de B, e cada elemento de B deve estar associado a exatamente um elemento de A.

B. Todos os elementos do conjunto A devem estar associados a um único elemento do conjunto B, e é possível que diferentes elementos de A estejam associados ao mesmo elemento de B.

C. Deve haver uma associação onde alguns elementos de A podem se conectar a mais de um elemento em B, desde que todos os elementos de B sejam utilizados na relação.

D. Para cada elemento x de A existe um elemento y de B tal que (x,y) pertence à relação, e se (x,y) e (x,z) pertencem à relação, então y pode ser diferente de z.

E. ​​​​​​​A relação deve garantir que nenhum elemento de B esteja associado a mais de um elemento de A, e que sobrem elementos em A não associados.

✅ Resposta: Alternativa B.


#### Questão 2
A definição formal de limite, conhecida como definição épsilon-delta (ε-δ), estabelece com rigor a ideia de que f(x) se aproxima de L quando x se aproxima de c. Ela afirma que para todo número ε > 0, existe um número δ > 0 tal que, se 0 < |x - c| < δ, então |f(x) - L| < ε (Guidorizzi, 2001).

Nessa definição, a escolha de um valor para δ está intrinsecamente ligada a qual outro elemento?

A. A escolha de δ depende apenas do valor de c, o ponto para o qual x tende, pois determina o centro do intervalo de análise.

B. A escolha de δ é arbitrária e pode ser qualquer número positivo, independentemente dos outros parâmetros da função ou do limite.

C. A escolha de δ depende fundamentalmente do valor de ε, que representa a tolerância de erro em torno do limite L.

D. A escolha de δ depende exclusivamente da função f(x), sendo uma constante característica para cada tipo de função (linear, quadrática, etc.).

E. A escolha de δ depende apenas do valor do limite L, pois δ define um intervalo simétrico em torno de L no eixo y.

✅ Resposta: Alternativa C.


#### Questão 3
As propriedades dos limites são ferramentas que permitem calcular limites de funções complexas a partir de limites de funções mais simples. Por exemplo, o limite da soma é a soma dos limites, e o limite do produto é o produto dos limites, desde que esses limites existam (Stewart, 2013).

Suponha que você saiba que limx→2​f(x)=5 e limx→2​g(x)=−3. Utilizando as propriedades dos limites, calcule o valor de limx→2​[x⋅f(x)−f(x)g(x)].

A. O limite é igual a 16.
B. O limite é igual a 25.
C. O limite é igual a -5.
D. O limite é igual a 10.
E. O limite não pode ser determinado com as informações dadas.

✅ Resposta: Alternativa B.

#### Questão 4
O teorema do confronto (ou teorema do sanduíche) é uma ferramenta poderosa para determinar o limite de uma função que pode ser difícil de calcular diretamente. Ele afirma que, se uma função f(x) está "espremida" entre outras duas funções, g(x) e h(x), numa vizinhança de um ponto c, e se g(x) e h(x) tendem para o mesmo limite L quando x tende a c, então f(x) também deve tender para L (Guidorizzi, 2001).

Considere uma função f(x) que satisfaz a desigualdade 1−4x2​≤f(x)≤1+2x2​ para todo x ≠ 0.

Qual é o valor de limx→0​f(x)?

A. O limite é igual a 0.
B. O limite é igual a 1/2.
C. O limite é igual a 1.
D. O limite não existe, pois f(x) oscila entre as duas funções.
E. O limite não pode ser determinado sem a expressão explícita de f(x).

✅ Resposta: Alternativa C.


#### Questão 5
O conceito de limite no infinito é utilizado para descrever o comportamento de uma função à medida que a variável de entrada cresce ou decresce sem limites. Se o limite de f(x) quando x tende a infinito (ou menos infinito) é um número finito L, dizemos que a reta y = L é uma assíntota horizontal do gráfico da função (Stewart, 2013).

Dada a função racional f(x)=2x3+x−810x3−2x2+5​, a existência e o valor do limite limx→∞​f(x) implicam qual característica gráfica para f(x)?

A. A existência de uma assíntota vertical na reta x = 5, pois é o resultado da divisão dos coeficientes dominantes.

B. A existência de uma raiz da função em y = 5, indicando que o gráfico cruza o eixo y nesse ponto.

C. A existência de uma assíntota oblíqua, pois o grau do numerador é igual ao grau do denominador.

D. A existência de uma assíntota horizontal na reta y = 5, pois o limite da função no infinito é 5.

E. A inexistência de assíntotas, pois a função cresce indefinidamente conforme x aumenta.​​​​​​​

✅ Resposta: Alternativa D.


Respostas enviadas em: 16/07/2026 20:12


## Na Prática

Por vezes, o ensino de funções se desconecta da prática, ainda que exista uma variedade de problemas cotidianos que podem ser resolvidos por meio desses conceitos. Para superar essa lacuna, destaca-se a importância de o professor aprofundar o conceito de funções, para que se tenha uma formação sólida e consiga visualizar aplicações que podem ser utilizadas de forma criativa em sua sala de aula na educação básica (Dante, 2010).

O estudo das funções é fundamental como base para compreender tópicos mais complexos da matemática, como limites, continuidade e derivadas. Além disso, apresentar os conceitos e exemplos de forma mais visual e intuitiva é uma estratégia que facilita significativamente o processo de ensino e aprendizagem, tornando o conteúdo mais acessível e interessante para os estudantes (Caraça, 1998).

Neste Na Prática, você vai ver algumas sugestões de atividades pensadas para alunos da educação básica envolvendo o conceito de função e sua representação.

![Descrição da imagem não disponível](https://creator-files.plataforma.grupoa.education/learning-object/154437/CAPA-2025-10-16T09:17:05-03:00.png)


## Saiba Mais

Para ampliar o seu conhecimento a respeito desse assunto, veja abaixo as sugestões do professor:

Uma proposta de ensino de limites e derivadas no ensino médio
Esta dissertação discute a viabilidade e os benefícios pedagógicos da introdução de noções de cálculo diferencial no currículo do ensino médio, apresentando um arcabouço metodológico com sequências didáticas, exemplos de aplicação e resultados preliminares de sua implementação.
[Mais](https://repositorio.unb.br/handle/10482/46727)


Cálculo
O Capítulo 2 desta obra traz uma abordagem numérica e gráfica bastante ampla de limites, contextualizando suas definições, características e aplicações, além de apresentar exercícios.
[Mais](https://bibliotecaa.grupoa.com.br/lti/launch.php?gl=MzPEqArem1S5Exyfy1WzmyyE5yRre3xUwBwOPkVqXwp8a9h0zTy5S3%2BdUiTo%2Bxm9u%2FurTK%2Bdd6bGEr9NSY1XB3zZXQmc9mxYxCSXgfy6pex6j3wbBf%2FIO2bSelaFTqr9JvieZdKr6P2Ed3XKSY9R1qaIXmr9Xyk00IXQo95QM3CMF7OIAPS8qPCQC3ubQd12HKglHyuIr7eO9dg00QNRfk9SuOCzfKSUK6xenaOqH6M%3D)

Funções afim e quadrática: uma análise de avaliações externas para uma abordagem didática no ensino dessas funções
Este estudo foi elaborado com o objetivo de desconstruir a percepção de que o estudo das derivadas é inacessível ou excessivamente complexo, por meio de exemplos contextualizados e aplicáveis, a partir de conceitos fundamentais como taxas de variação e otimização.
[Mais](https://repositorio.ufc.br/bitstream/riufc/72463/5/2023_dis_leptavoraneto.pdf)


## REFERÊNCIAS BIBLIOGRÁFICAS E CRÉDITOS DE IMAGENS


ANTON, H.; BIVENS, I.; DAVIS, S. Cálculo. 10. ed. Porto Alegre: Bookman, 2014. v. 1. 

BOYCE, W. E.; DIPRIMA, R. C. Equações diferenciais elementares e problemas de valores de contorno. 9. ed. Rio de Janeiro: LTC, 2010. 

BOYER, C. B.; MERZBACH, U. C. História da matemática. 3. ed. São Paulo: Blucher, 2012. 

CARAÇA, B. J. Conceitos fundamentais da matemática. Lisboa: Gradiva, 1998. 

DANTE, L. R. Didática da resolução de problemas de matemática. 24. ed. São Paulo: Ática, 2010.

FRIEDRICH, M. A.; MANZINI, N. Matemática aplicada: administração e ciências contábeis. 2. ed. São Leopoldo: Unisinos, 2015. 

GOMES, F. M. Pré-cálculo: operações, equações, funções e sequências. São Paulo: Cengage Learning, 2018. 

GUIDORIZZI, H. L. Um curso de cálculo. 5. ed. Rio de Janeiro: LTC, 2001. 

GUIDORIZZI, H. L. Matemática para administração. Rio de Janeiro: LTC, 2010. 

MUNEM, M. A.; FOULIS, D. J. Cálculo: volume 1. 2. ed. Rio de Janeiro: Guanabara Dois, 1982. 

NERI, C.; CABRAL, M. Curso de análise real. 2. ed. Rio de Janeiro: Instituto de Matemática, Universidade Federal do Rio de Janeiro, 2011. Disponível em: https://www.labma.ufrj.br/~mcabral/livros/livro-analise/curso-analise-real-a4.pdf. Acesso em: 23 mar. 2021.

STEWART, J. Cálculo: volume 1. São Paulo: Cengage Learning, 2016. 

STEWART, J. Cálculo: volume 1. 7. ed. São Paulo: Cengage Learning, 2013. 

STRUIK, D. J. História concisa das matemáticas. 3. ed. Lisboa: Gradiva, 2009. 

Bancos gratuitos de imagens e Shutterstock. 
SAGAH, 2025.

