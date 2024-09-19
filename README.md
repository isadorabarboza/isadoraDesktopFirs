PROVA PROGRAMAÇÃO 
Isadora 0079778

O site faz a mudança do computador para o celular (desktopfirst), sendo assim, a visualização fica certa  em  computadores e celulares.

- O projeto é basicamente uma página no feed, mas quando a página é feita no computador ela fica com alguns erros quando abrimos no celular, como os tamanhos, e alinhamentos. E nisso, com o projeto separando o css, usando @media e etc, conseguimos adaptar o projeto para ficar corretamente visível no celular.

- O trabalho consiste na maior parte da nota do bimestre, 6 pontos. Por isso a dedicação e mostrar o que foi aprendido ao longo do ano é muito importante para conseguir realizar o trabalho, ou seja, conseguir atingir uma nota alta é a principal dedicação. 


- Tecnologias usadas (HTML, CSS.). Dentro do CSS aprendemos usar o @media, que muda as dimensões da página do celular, 
 EX: 
@media (max-width: 375px) {
 #BottomBox { 
        display: flex;
        justify-content: center;
        width: 375px;
        height: 667px;
    }  
Separei a página do CSS da do HTML, e em baixo das class, coloquei o @media com as informações que eu queria mudar para a página do celular dar certo.
EX: o ".texto" são as classes e em baixo o @media para o celular.
```
.texto3 {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: -40px;
}

@media (max-width: 375px) {}
```
- **Funcionalidade 1*:* No HTML fiz a página base, mas ao invés dde colocar direto o CSS, comecei com o body, e na outra página do css usei no style,  essa parte foi tranquila de fazer, usei as bases de trabalhos anteriores na estrutura.
-  EX: HTML 
```
    <div class="caixa1">
    <img class="menor" src="https://i.pinimg.com/564x/24/af/e9/24afe96d251d2b58ec71bf4e8a5cc8f4.jpg">
    <div class="texto">Amsterdan</div>
```
Como eu ja havia feitos trabalhos assim, só copiei, mudei e adicionei as informações para o site  novo que estava fazendo .

- **Funcionalidade 2:** Basicamente, usei a base das revisões (CSS, HTML, TRABALHOS ANTIGOS), e mudei os tamanhos , não foi muito fácil kkkkkk, demorei muito pra conseguir arrumar os detalhes, principalmente o css (mobile). 
 Ou seja, o meu método usado foram as bases de trabalhos e revisões. 

- **Funcionalidade 3:** No desenvolvimento da página, eu demorei bastante pra conseguir terminar, tava me perdendo muito em alguns erros até fáceis de arrumar,  
 O CSS foi o mais trabalhoso e complicado para terminar, eu demorei muito pra conseguir colocar o "nome e a profissão" em coluna.
No html, demorei para conseguir colocar a iamgem menor dentro da maior. 
Não consegui fazer a separação de cores na imagem maior, 
