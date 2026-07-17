## Apresentação

Os limites de funções consistem em uma das mais importantes ferramentas da Matemática. Devido à sua importância, este é um dos primeiros temas a ser estudado nos diferentes cursos da área de Exatas. No entanto, geralmente, nesse primeiro contato, o tema dos limites é visto para funções definidas no conjunto dos números reais. Posteriormente, avança-se para o contexto das funções de variáveis complexas.

Nesta Unidade de Aprendizagem, você aprenderá a definição formal para o limite de uma função de variável complexa, bem como suas propriedades operatórias. Também verá como calcular limites de funções quando estes tendem ao infinito e compreenderá como a continuidade de uma função de variável complexa está conectada com o cálculo de limites. Ao final, você terá aprendido os conceitos fundamentais que envolvem o cálculo do limite de uma função de variável complexa, bem como a investigação da continuidade desta.

Bons estudos.

#### Ao final desta Unidade de Aprendizagem, você deve apresentar os seguintes aprendizados:

- Definir limites de funções complexas e seus teoremas.
- Calcular limites envolvendo o infinito.
- Identificar funções contínuas.



## Desafio

 Prazo para envio: 31/07/26 23:59
 Liberação do feedback: 01/08/26 00:00

Na área da Matemática, os pesquisadores têm inúmeros desafios a serem superados, pois, para que os resultados de suas pesquisas sejam aceitos pela comunidade científica, eles devem ser demonstrados como verdadeiros.

Neste Desafio, você deverá empregar a definição de continuidade para funções de variáveis complexas, a fim de demonstrar se uma função de variáveis complexas é contínua. Para tanto, considere o cenário proposto a seguir.

![Descrição da imagem não disponível](https://statics-marketplace.plataforma.grupoa.education/sagah/63f83ca0-f7e9-41d4-95bb-98ef53ad477e/b424c88e-39ea-43b4-864c-357b448e80bb.jpg)

Diante do exposto, apresente o resultado para o limite dado e, a partir desse resultado, defina se a função f(z) é contínua.

#### ✅ Resposta ao Desafio

Função dada

$$
f(z) =
\begin{cases}
\frac{z^2}{|z|}, & \text{se } z \neq 0 \\
0, & \text{se } z = 0
\end{cases}
$$

Definição de continuidade

$$
\lim_{z \to z_0} f(z) = f(z_0)
$$

Proposição (em termos das partes reais e imaginárias)

$$
\lim_{z \to z_0} f(z) = \lim_{(x,y) \to (x_0,y_0)} u(x,y) + i \cdot \lim_{(x,y) \to (x_0,y_0)} v(x,y)
$$


Cálculo do limite em z0=0
Para z=x+iy:

$$
z^2 = (x + iy)^2 = x^2 - y^2 + 2xyi
$$

$$
|z| = \sqrt{x^2 + y^2}
$$

$$
f(z) = \frac{x^2 - y^2}{\sqrt{x^2 + y^2}} + i \cdot \frac{2xy}{\sqrt{x^2 + y^2}}
$$

Testando aproximações:
Se y=0:

$$
u(x,0) = |x| \to 0, \quad v(x,0) = 0
$$

Se x=0:

$$
u(0,y) = -|y| \to 0, \quad v(0,y) = 0
$$


Se y=x:

$$
u(x,x) = 0, \quad v(x,x) = \sqrt{2}|x| \to 0
$$

Em todos os casos, o limite tende a 0.

Comparação com f(0)

$$
f(0) = 0
$$

$$
\lim_{z \to 0} f(z) = 0
$$
Conclusão
A função f(z) é contínua em todo C, pois o limite coincide com o valor da função no ponto z0=0.


Enviado em: 17/07/2026 20:18



## Infográfico

A Matemática se caracteriza por ser uma ciência formal. Seus avanços devem ser inicialmente demonstrados algebricamente para que, em um segundo momento, os pesquisadores possam validá-los. Nesse sentido, muito do conhecimento matemático é construído por meio do estudo de limites e continuidade de funções.

Neste Infográfico, veja como demonstrar a continuidade de uma função de variáveis complexas por meio de sua definição.

![Descrição da imagem não disponível](https://statics-marketplace.plataforma.grupoa.education/sagah/ae5d4196-b61e-476f-b4a7-35d92b0c7bdb/fffbecc6-364b-4573-821a-293d6c275479.jpg)

​​​​​​​​​​​​​​
## Conteúdo do Livro

O estudo de funções e limites é fundamental para a Matemática, pois permite inúmeras aplicações nos mais diversos campos do conhecimento, seja modelando fenômenos de mecânica dos fluidos, seja na dinâmica populacional em Biologia.

No capítulo Limite e continuidade de funções complexas, da obra Variáveis complexas, base teórica desta Unidade de Aprendizagem, você vai estudar o tema dos limites. Em um primeiro momento, será apresentada a definição formal de limite para uma função de variáveis complexas, bem como suas principais operações. Em seguida, você aprenderá a calcular limites de funções quando estes tendem ao infinito, podendo o resultado ser finito ou infinito. O capítulo se encerra com a definição de continuidade para funções de variáveis complexas, para que você compreenda como a continuidade de uma função de variáveis complexas está conectada com o cálculo de limites.

Boa leitura.

![Descrição da imagem não disponível](https://statics-marketplace.plataforma.grupoa.education/sagah/0de5d406-dda8-4673-9f93-6faf9444170e/1559678c-0cd3-44b1-9e00-802de4cc2572.jpg)


## Dica do Professor

Muitas vezes, o cálculo do limite para funções de variáveis complexas gera dúvidas entre os alunos, pois envolve saber manipular uma função que apresenta duas entradas reais, nem sempre compreendida.

Por isso, esta Dica do Professor apresentará formas de resolver o limite de funções de variáveis complexas, passo a passo, a fim de contribuir para o seu efetivo aprendizado. Acompanhe.


## Exercícios

 Prazo para envio: 31/07/26 23:59
 Liberação do feedback: 01/08/26 00:00

#### Questão 1
Sejam A um subconjunto aberto de C e f: A⟶C uma função de variáveis complexas. Dado z0 ∈ A, diz-se que w ∈ A é `________________` de f quando z ∈ A tende a z0, se para todo ϵ > 0 existe um δ > 0, tal que, se 0 < | z − z0 | < δ, então | f(z) − w0 | < ε.

Assinale a alternativa que preenche corretamente a lacuna:

A. a perturbação.
B. o limite.
C. o ponto fixo.
D. a derivada.
E. o coeficiente angular.

✅ Resposta: Alternativa B.


#### Questão 2
O cálculo dos limites envolvendo funções complexas se assemelha ao cálculo dos limites de funções reais. No entanto, no primeiro caso, está-se trabalhando no corpo dos números complexos, e, no segundo, com o corpo dos números reais.

Considerando a propriedade operatória:

$$
\lim_{z \to z_0} \frac{f_2(z)}{f_1(z)} = \frac{w_2}{w_1}
$$

Sendo $f_1, f_2: A \to \mathbb{C}$ e $A \subset \mathbb{C}$, calcule:

$$
\lim_{z \to 1 + i} \frac{4z^2 - 8i}{z^2 - 2z + 2}
$$

​​​​​​​​​​​​​​Após o cálculo, assinale a alternativa correta.

A. 2 + 2i.
B. 2 − 2i.
C. 4 − 4i.
D. 4 + 4i.
E. 1 − 4i.

✅ Resposta: Alternativa C.


#### Questão 3
Muitas estratégias empregadas para o cálculo dos limites de funções reais também podem ser empregadas para o caso das funções complexas.​​​​​​​

Julgue as afirmações que seguem, classificando-as em verdadeiras (V) ou falsas (F):

( ) O limite $\lim_{z \to i} \frac{z^2 + 3}{5z^3}$ é igual a $-\frac{2}{5i}$.

( ) O limite $\lim_{z \to i} \frac{1}{z^2 + 1}$ é igual a 1.

( ) O limite $\lim_{z \to \infty} \frac{z^3 + z^2}{3z^2 + z}$ é igual a $\infty$.

( ) O limite $\lim_{z \to \infty} \frac{5z^2 + z}{3z^2 + z}$ é igual a $\frac{5}{3}$.

Feito isso, assinale a alternativa que preenche corretamente as lacunas, de cima para baixo:

A. V – V – F – F.
B. V – F – V – F.
C. V – V – F – V.
D. V – F – V – V.
E. F – F – V – V.

✅ Resposta: Alternativa D.

#### Questão 4
O limite de f(z) tende a L quando z tende ao infinito, z→∞, se, para todo ϵ > 0, existir R > 0, tal que | f(z) − L | < ϵ sempre que z ∈ A e | z | > R. Assim, ∀ϵ > 0, ∃R > 0, z ∈ A e | z | > R ⇒ | f (z) − L | < ϵ.

Julgue as asserções que seguem e a relação proposta entre elas:

I. O $$\lim_{z \to \infty} \frac{5z^3 + 4}{2z^3 + 1}$ existe, é finito e igual a $\frac{5}{2}$$

Porque

II. $$\lim_{z \to \infty} \frac{5z^3 + 4}{2z^3 + 1} 
= \lim_{z \to \infty} \frac{z^3(5 + 4/z)}{z^3(2 + 1/z)} 
= \lim_{z \to \infty} \frac{5 + 4/z}{2 + 1/z} 
= \frac{5}{2}$$

A respeito das asserções I e II, assinale a alternativa correta:

A. As asserções I e II são proposições verdadeiras, e a II é uma justificativa correta da I.
B. As asserções I e II são proposições verdadeiras, mas a II não é uma justificativa correta da I.
C. A asserção I é uma proposição verdadeira, e a II é uma proposição falsa.
D. A asserção I é uma proposição falsa, e a II é uma proposição verdadeira.
E. As asserções I e II são proposições falsas.

✅ Resposta: Alternativa A.

#### Questão 5
Sejam A, B ⊂ C abertos, considere as funções de variáveis complexas f1: A→C, f2: A→C e g: B→C, sendo que f1: A ⊂ B. Suponha que as funções f1 e f2 são ambas contínuas em z0 ∈ A, e a função g é contínua em f1(z0).

Nesse contexto, julgue as afirmações que seguem:

I. Sejam f1(z), f2(z) como apresentados, então f1(z) + f2(z) = (f1 + f2)(z) é contínua.
II. Seja f1 como apresentado, sendo f1(z) ≠ 0, então 1/f1(z) é contínua.
​​​​​​​III. Sejam f1(z), g(z) como apresentados, então g ∘ f1: A→C é contínua em z0.

Está correto o que se afirma em:

A. I, apenas.
B. I e II, apenas.
C. II e III, apenas.
D. I e III, apenas.
E. I, II e III.

✅ Resposta: Alternativa E.


Respostas enviadas em: 17/07/2026 20:07


## Na prática

O cálculo dos limites é fundamental para as funções de variáveis complexas, permitindo que se estude o comportamento de uma função na vizinhança de um ponto. Além disso, esse cálculo também possibilita compreender o comportamento da função quando sua variável independente tende ao infinito.

O estudo das funções de variáveis complexas é importante a diversas áreas do conhecimento, incluindo fenômenos relacionados à transferência de calor, à mecânica dos fluidos, à eletricidade, entre outros fenômenos em meios contínuos.

Neste Na Prática, a partir de três exemplos, aprenda a realizar o cálculo do limite de uma função, passo a passo, empregando algumas das principais estratégias algébricas necessárias ao seu desenvolvimento.

![Descrição da imagem não disponível](https://statics-marketplace.plataforma.grupoa.education/sagah/04a80fcf-235b-4bd0-a739-3cf38b548f37/8054e05d-7a4c-4f7c-aa82-9374f5110d86.jpg)


## Saiba mais

Para ampliar o seu conhecimento a respeito desse assunto, veja abaixo as sugestões do professor:

Variáveis complexas: limite e continuidade
Nesta videoaula, é introduzida a noção de limite e continuidade para funções de uma variável complexa. Além disso, são resolvidos alguns exercícios por meio da definição de limite.
[Mais](https://www.youtube.com/embed/-K8-DD6Po1o)

Limites de funções complexas
Assista a este vídeo para rever os principais conceitos de limites para funções de variáveis complexas e também estudar a continuidade dessas funções.
[Mais](https://www.youtube.com/embed/CnFcvl2gV58)

Cálculo de limites de funções complexas: exercícios resolvidos
Neste vídeo, acompanhe um passo a passo de exercícios resolvidos sobre limites de funções complexas.
[Mais](https://www.youtube.com/embed/zfwBUF2NXp0)


## REFERÊNCIAS BIBLIOGRÁFICAS E CRÉDITOS DE IMAGENS

BROWN, J. W.; CHURCHILL, R. V. Funções analíticas. In: BROWN, J. W.; CHURCHILL, R. V.
Variáveis complexas e aplicações. 9. ed. Porto Alegre: McGraw Hill, 2015, p. 37-82.

COELHO, L. Funções complexas. 2000. 69 f. Trabalho de Conclusão de Curso (Licenciatura em Matemática) – Universidade Federal de Santa Catarina, Florianópolis, 2000.

VIEIRA, E. Funções holomorfas de uma variável. 2011. Disponível em:
http://emis.impa.br/EMIS/journals/em/docs/coloquios/NE-1.09.pdf. Acesso em: 20 nov. 2020.

ZANI, S. L. Algumas funções elementares. In: ZANI, S. L. Funções de uma variável complexa.
2020.Disponível em: https://sites.icmc.usp.br/szani/complexa.pdf. Acesso em: 12 nov. 2020

Bancos de imagens Pexels, Pixabay e Shutterstock.
SAGAH, 2020.

