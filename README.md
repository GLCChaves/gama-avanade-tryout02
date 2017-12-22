# Avanade Angular Academy by Gama - Simulado #2

Segundo simulado para testar suas habilidades de HTML, CSS e TypeScript do programa Avanade Angular Academy (AAA) By Gama. Neste simulado o objetivo é testar sua habilidade para desenvolver usando [Angular](https://angular.io).

Finalmente vamos começar a brincar de verdade né?! Bateu um frio na barriga só de ver o nome Angular? Fica sossegado que é bem tranquilo e hoje o angular-cli, typescript e o plugin momentjs vão ser seus melhores amigos.

Agora chega de conversa e vamos codar!

## Configurando ambiente no Windows, Mac e Ubuntu

Visto que você já tem o node instalado e ja fez o primeiro simulado vamos apenas instalar as dependencias do projeto:
```
npm install
```
Dependências instaladas, vamos entender a estrutura inicial. Você vai encontrar alguns arquivos já criados e trabalhar a partir daí. A ideia aqui é exercitar um pouco de TDD (Test Driven Development). A primeira coisa que você precisa fazer é rodar na sua linha de comando o seguinte:
```
npm test
```
Para saber mais sobre testes de aceitação, leia sobre o framework Mocha. O primeiro teste irá passar e os demais irão falhar. Para terminar este simulado o seu objetivo é fazer todos os testes passarem.

## O que vamos desenvolver?

Neste simulado iremos desenvolver um calendário de eventos utilizando Angular e [Moment.js](https://momentjs.com/) - para uma manipulação mais facil de datas. O nosso calendário já possui um arquivo de seed e para utilizá-lo precisaremos consultar nossa API local para manipular os dados utilizando o plugin [In-memory Web API](https://github.com/angular/in-memory-web-api).

Ta achando que é muita informação?? Fica calmo! Dê uma olhadinha nesses dois tutoriais oficiais da pagina do Angular que eles abordam o minimo necessario para você finalizar esse simulado com maestria:

- [QuickStart](https://angular.io/guide/quickstart)
- [Tutorial: Tour of Heroes](https://angular.io/tutorial)

## Mas e o layout? Como fica?

Ficar abrindo photoshop para pegar medidas de layout, hexadecimal de cores e tipo das fontes é chato né? Nosso super Designer preparou um style-guide para facilitar a vida de vocês!

![style-guide](https://raw.githubusercontent.com/gamaacademy/gama-avanade-tryout02/master/images/readme-image-0.png)

![style-guide-2](https://raw.githubusercontent.com/gamaacademy/gama-avanade-tryout02/master/images/readme-image-1.jpg)

## Algumas pequenas regras!

**ATENÇÃO:** O seu calendário após carregado deve sempre ser exibido com o dia `18-12-2017` selecionado e com os respectivos eventos deste.

Para passar por todos os testes alguns elementos do seu código devem ter algumas classes e ids específicos, abaixo temos a listagem:

- Campo de input de eventos deve ter o id `appointment-input`
- Botão de adicionar o evento naquela data deve ter o id `appointment-submit`
- Dias do calendário devem ter a classe `calendar__day`
- Dias do calendário que possuem eventos devem possuir duas classes: `calendar__day` e `has-event`, sendo esta última a responsável por adicionar o indicador de evento naquela data

Para rodar os testes execute:

```
npm test
```

## Dúvidas?

Ta confuso com alguma coisa? Achou as instruções muito superficiais? Abre um issue pra gente que respondemos rapidinho!

[Abrir um issue](https://github.com/gamaacademy/gama-avanade-tryout02/issues)

Prefere falar no privado? Só enviar um email para `matheus+avanade@gama.academy`