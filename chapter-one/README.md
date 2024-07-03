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

O custo de um código ruim pode ser resumido em uma história que o livro nos conta:

""