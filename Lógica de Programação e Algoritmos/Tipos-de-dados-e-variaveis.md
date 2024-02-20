# Tipos de dados e variáveis
### O Problema:

![Legenda](https://helpful-jump-17b.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fbc4126a3-040b-4b12-8072-e6a9f8ba75ab%2FUntitled.png?table=block&id=73d55bf4-d301-4f2d-8450-fac0d05bfe4f&spaceId=88e4dc6b-f3c4-4b5b-bb05-18f02b6815fb&width=2000&userId=&cache=v2)

![Legenda](https://helpful-jump-17b.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Ff8eba906-1d45-4ca9-b490-c751e8c5882c%2FUntitled.png?table=block&id=9ca51193-bfd3-4722-9375-69c94d903848&spaceId=88e4dc6b-f3c4-4b5b-bb05-18f02b6815fb&width=2000&userId=&cache=v2)

![Legenda](https://helpful-jump-17b.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F25bc0bb0-2b61-44a6-bd47-54c5f7c272a1%2FUntitled.png?table=block&id=3bff7237-142c-4439-a416-5234cadb5837&spaceId=88e4dc6b-f3c4-4b5b-bb05-18f02b6815fb&width=2000&userId=&cache=v2)

### **Declarando Variáveis**


```
console.log("Digita o nome do seu jogador")

//declara uma variável
let nickname = "Maria mestra do Pikachu"

//concantenando uma mensagem fixa + uma variável
console.log("Bem vinda " + nickname)
console.log(nickname + " entrou no servidor")
```

### **Declarando Constantes**

```
const notificacao = "Pokemon Go diz: "

//saida
console.log(notificacao + "tem um novo pokemon na região")
console.log(notificacao + "você foi derrotado por um líder")
```

![Legenda](https://helpful-jump-17b.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F2124c293-bb8e-4ab3-b541-6aa5346d4c1a%2FUntitled.png?table=block&id=0761ab3b-fd56-45f7-bb02-5c4e3d1e8562&spaceId=88e4dc6b-f3c4-4b5b-bb05-18f02b6815fb&width=1600&userId=&cache=v2)

### **Ajudando a Vovó**

```
let poteCafe = "café pilão"
let poteAcucar = "Açucar cristal"
let poteBiscoito = "Biscoito Maizena"
const messagemDaVovo = "Na cozinha da vovó hoje tem: "

console.log(messagemDaVovo + 
poteCafe + " - " +
poteAcucar + " - " +
poteBiscoito
)

poteCafe = "Café 3 corações"

console.log(messagemDaVovo + 
poteCafe + " - " +
poteAcucar + " - " +
poteBiscoito
)
```
### **Tipos Variáveis**

`string` - são variaveis que armazenam texto

`number` - são variaveis que armazenam números

`boolean` - são variaveis lógicas, que armazenam o valor de ligado ou desligado (true/false)

```
//pokemon
let nomePokemon = "pikachu"
let pokemonSexo = "M"

let nivelPokemon = 20
let pontosDeVidaPokemon = 45

let selecionavel = false
```
### **Outros tipos de variáveis**

Tipo de Variável        | Descrição
---------               | --------- 
Variáveis numéricas     |  São usadas para armazenar valores numéricos.
Inteiro                 | Armazena números inteiros, como 1, 10, -5.
Ponto flutuante ou decimal | Armazena números com casas decimais, como 3.14, -0.5.
Números complexos | 	Armazena números complexos, como 2+3j.
Variáveis de texto | Usadas para armazenar sequências de caracteres.
String | Armazena uma sequência de caracteres, como "Olá, mundo!"
Caractere | Armazena um único caractere, como 'a', 'X', '@'.
Variáveis lógicas | 	Usadas para armazenar valores de verdadeiro ou falso.
Booleano | Armazena os valores True ou False.
Variáveis de data e hora | Utilizadas para representar datas e horários.
Data | Armazena datas, no formato AAAA-MM-DD.
Hora | 	Armazena horários, no formato HH:MM:SS.
