# Curso Python Exercícios
## Aqui são guardados os exercícios em Python que estou fazendo, com detalhes escritos e com imagens.

### Exercicio 001
#### Apenas escrever "hello World!" na tela.
<blockquote>
Use uma função chamada <strong>Print</strong>. Um delimitador especial para mensagens. <br>
Todos os comandos são funçao, então toda função tem que ter <strong>()</strong>
</blockquote>
<img width="323" height="70" alt="Captura de tela 2026-01-16 210129" src="https://github.com/user-attachments/assets/7e9ac521-a36c-44bc-8946-b2fe5bf7d168" /> <br>
<code>print("Hello World!")</code>

---

### Exercicio 002
#### Pergunte qual o nome do usuario e mande uma mensagem de bem vindo com o nome do usuario.
<blockquote>
Primeiro Precisamos de uma <strong>variavel</strong> que ira receber o valor do <strong>input (input: Pegunta e recebe o valor respondido)</strong> <br>
depois fazemos o print, mas inves de colocar a variavel depois da string coloque <strong>{}</strong> como uma String e depois coloque <strong>.format()</strong> no final, <br>
esse .format vai pegar uma variavel em específico e colocar no lugar da {}.
</blockquote>
<img width="459" height="69" alt="Captura de tela 2026-01-16 210936" src="https://github.com/user-attachments/assets/fcdb70e7-fd42-49a8-bebf-2ab37e3cccba" /> <br>
<code>name = input('Escreva seu nome: ') <br>
 print('Prazer em te conhecer, {}!'.format(name))</code>

---

### Exercicio 003
#### Coloque dois numeros e some os dois, apos isso mande uma mensagem mostrando os numeros colocados e a soma dos dois.
<blockquote>
Crie Variaveis para receberem os numeros que seram somados e uma variavel que vai mostra a resposta, agora mudando apenas o .format() <br>
ele ira colocar por ordem e para isso voce precisa colocar as variaveis na ordem em que cada {} esta.
</blockquote>
<img width="535" height="106" alt="image" src="https://github.com/user-attachments/assets/b836fac4-6244-45d2-be1f-4eff202a087a" /> <br>
<code>n1 = int(input('escolha um numero: '))
n2 = int(input('escolha outro numero: '))
s = n1 + n2
print('A soma de {} com {} é {}'.format(n1,n2,s))</code>

---

### Exercicio 004
#### Faça um programa que mostre na tela seu tipo primitivo e todas as informaçoes possiveis sobre ele.
<blockquote>
Primeiro precisa de uma variavel para receber a palavra/numero, depois preciso que me diga qual o <strong>Tipo Primitivo</strong> dela, <br>
para isso usamos a Função <strong>type()</strong> essa função pega a variavel e indentifica seu tipo primitivo. Agora para as outras informaçoes <br>
usamos algumas funções que começam com <strong>is</strong>, para usar apenas coloque a variavel depois <strong>.is</strong> e aparece varias opçoes <br>
cada uma delas mostra se essa variavel pode mudar seu tipo primitivo para outros tipos.
</blockquote>
<img width="457" height="225" alt="image" src="https://github.com/user-attachments/assets/4345f0b6-57a2-4c0c-acd4-e108a0f64430" /> <br>
<code>a = input('Digite algo: ')
print('A classe do digito é ', type(a))
print('O digíto tem só espaços?', a.isspace())
print('É alfabetico?', a.isalpha())
print('É um numero?', a.isnumeric())
print('É alfanumerico?', a.isalnum())
print('Esta em maiuscula?', a.isupper())
print('esta em minusculo?', a.islower())
print('Esta capitalizada?', a.istitle())</code>

### - EXTRA
####  quais são os tipos primitivos e como mudar?
<blockquote>
Int: Transforma Strings em numeros inteiros <br>
Float: Transforma em numero reais (ex: 4.5, 0.076) <br>
bool: Só aceita valores "True" ou "False" <br>
str: Transforma numeros em strings
</blockquote>
para mudar o tipo coloque: <br>
<code>n = int(input(Escreva algo: ))</code>
<p>Apenas coloque o tipo primitivo antes do <strong>input()</strong>.</p>

---

### Exercicio 005
