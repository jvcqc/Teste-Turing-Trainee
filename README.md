# Teste-Turing-Trainee

Bem vindos ao processo seletivo para desenvolvedores trainee da Turing Tecnologia, primeira empresa Jr de T.I da UFERSA, gostamos de desafios e acreditamos que o melhor currículo para um programador é os seus projetos realizados, pensando dessa forma, a inscrição do nosso processo seletivo se dará aqui neste repositório.

Para se tornar candidato a vaga de Desenvolvedor Trainee, siga com atenção os passos abaixo:.

- Faça um Fork neste repositório
- Adicione uma pasta com seu nome
- Crie um Readme se apresentando e colocando informações que você achar útil, inclusive para qual time(backend e frontend) deseja entrar.
- Faça um Pull Request para o mesmo repositório.

## Sobre o teste:
Nosso foco atual é o desenvolvimento web e este teste mostrará situações rotineiras que acontecem durante o nosso dia-a-dia.

- ### OBS.1 Não é necessário fazer todos os testes, faça apenas o que conseguir e não esqueça de fazer Pull Request para este repositório.

- ### OBS.2 Não precisa ser em uma linguagem especifica, você está livre para programar na linguagem que mais estiver confortável.

- ### OBS.3 Se ainda não souber utilizar o Git e o Github, aproveite a oportunidade para aprender. São ferramentas essenciais para o mercado de trabalho e será uma garantia para o futuro.

### 1. É rotineiro ler códigos de seus colegas, mas não é toda vez que temos um debugger, então o teste de mesa é importante.

Conforme o algoritmo abaixo:

```
início 
	ler x 
	ler y 
	z = (x*y) + 5 
	se z <= 0 então 
		resposta =  ‘A’
	senão 
		se z <= 100 então 
			resposta = ‘B’
		senão 
			resposta = ‘C’ 
		fim_se 
	fim_se 
	escrever z, resposta 
fim
```

Faça um teste de mesa e complete o quadro a seguir para os seguintes valores:

| X   | Y  | Z | Resposta |
|-----|----|---|----------|
| 3   | 2  |   |          |
| 150 | 3  |   |          |
| 7   | -1 |   |          |
| -2  | 5  |   |          |
| 50  | 3  |   |          |

---
## Lógica:

### 2. Escreva um algoritmo que leia as idades de 2 homens e de 2 mulheres (considere que as idades dos homens serão sempre diferentes entre si, bem como as das mulheres). Calcule e escreva a soma das idades do homem mais velho com a mulher mais nova, e o produto das idades do homem mais novo com a mulher mais velha. 

---

### 3. Escreva um algoritmo que receba dois arrays de inteiros ordenados e retorne um array que seja a união ordenada destes arrays. Desenvolva todo o algoritmo desde a entrada dos vetores até a saída do vetor final, não utilize métodos prontos do tipo sort().

---

### 4. (BEE 1009) Faça um programa que leia o seu salário fixo e o total de vendas efetuadas no mês (em dinheiro). Sabendo que você como vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o total a receber no final do mês, com duas casas decimais.

ex: entradas:
> salario fixo: 500.00

> vendas efetuadas em dinheiro: 1230.30

ex: saida:
> Total = R$ 684.54

---
## Tratamento de Strings:
### 5. Escreva um algoritmo que leia um endereço de e-mail e um telefone e censure apartir da segunda letra até a penultima letra do nome deixando o provedor do e-mail legivel, censure o telefone apartir do 3° digito até os dois ultimos. e exiba os dois na mesma linha separados por um hifén.

Ex. entrada: 
> fulano@gmail.com

> 92345-6789

Ex. Saída:
> f****o@gmail.com - 92\***-**89