# Capítulo 1: Código Limpo

Antes de estudarmos como fazer código limpo precisamos entender algumas questões:
**o que é código? porque fazer código limpo? o que seria um código limpo?**

_"... especificar requisitos detalhadamente de modo que uma máquina possa executá-los é programar - e tal especificação é o código"_

Os clientes tem objetivos, esses objetivos viram projetos e consequentemente software, 
só que há algo aí entre o pensamento do cliente e software, é necessário análise do que se quer, 
detalhamento e formalização de cada funcionalidade desejada e tradução disso para algo que a máquina possa executar.
O código é o resultado de se programar, é essa especificação minuciosa.
Somos os engenheiros e arquitetos, montamos plantas detalhadas que representam o que nosso cliente quer, a máquina é o operário.

Então... se o código é uma especificação, um código ruim é uma especificação ruim?

Isso é complicado, há diversas maneiras de se errar - A porta do erro sempre é mais larga - mas em resumo, sim! 

Nesse livro não iremos tratar de falha no levantamento de requisitos, mas sim falha na programação desse requisito.
É possivel entregar os requisitos solicitados, mesmo tendo programado código ruim - aliás, isso é o que ocorre o tempo inteiro -

**Mas se é possivel entregar escrevendo código ruim, porque fazer código limpo?**

Assistindo as provas em grupo do Masterchef eu percebi que muitas vezes o resultado isolado de um trabalho não demonstra o que foi feito nele. 
Por exemplo, na prova XXX, a equipe que fez uma comida mais gostosa não foi a mais organizada.

Porém cabe dizer que isso vale para algo isolado, na prova em si isso não foi perceptivel, mas projetos são como maratonas, 
são longos e extenuantes, e tem uma tendência a crescer em escopo.
Um restaurante pode fazer uma comida boa sem organização, mas não consegue manter essa qualidade sem organização.

O custo de um código ruim pode ser resumido em um cenário que o livro retrata:
1. Existe uma equipe trabalhando em um projeto, no início desse projeto a equipe acelera sem ligar para a qualidade do código
2. Conforme o tempo passa mais confuso o código fica, o que causa um atraso na entrega das tarefas
3. Vendo a queda na produtividade, o gestor decide contratar mais desenvolvedores, porém isso gera o oposto do esperado. 
Agora temos mais gente que não teve contato com o código envolvido com aquele código extremamente confuso, 
além de que há uma pressão pra se entregar mais do que antes (afinal, foi contratado mais gente)
4. Tudo isso acaba gerando mais código confuso, o que gera a longo prazo uma queda ainda maior na produtividade

E o que é feito então? Mais merda

1. A equipe consegue convencer a gestão que o projeto está insustentavel
2. É criada uma iniciativa para refazer o projeto do zero - agora vai! -
3. É criado um time para cuidar do novo projeto, enquanto o novo projeto é criado o antigo continuará a ser mantido
4. Acontece então uma pressão nesse novo time para que ele termine todas as funcionalidades que existem no projeto antigo
5. O novo time acelera e acaba criando novos códigos ruins
6. Conforme o tempo passa mais confuso o código fica, o que causa um atraso na entrega das tarefas

E aí um novo ciclo desastroso se inicia

Se você passou por isso, minhas condolencias. Não cabe a mim dizer de quem foi a culpa, mas saiba que a culpa foi sua!

Não se assuste, eu sei que quem colocou pressão e deu um prazo extremamente curto não foi você, mas foi você quem criou o código.
Um médico pode justificar que foi por conta da pressão ou do tempo muito curto, mas ele é o culpado quando ocorre displicencia na cirugia.

Mas se acalme, tu não é o único culpado - é sempre melhor tá na desgraça com outra pessoa - 
A gestão é culpada por impor suas decisões, principalmente quando passa por cima do clamor da área técnica.
**Perceba que o código limpo é algo que se inicia no individuo mas que também depende da cultura da empresa**

Tá! Eu entedi o ponto, mas o que seria um código limpo?

É sobre esse ponto que esse livro vai tratar, cabe dizer que a definição de limpo/sujo depende da escola de pensamento do programador
Esse livro não representa uma verdade inquestionável, mas sim lança como alcançar um código limpo na definição do autor.

