

# Typical Device Breakpoints
    Pequenas Telas: até 600px

        Celular: 320px até 390px
        Tablet: 600px até 992px
        Desktop: 992px até 1440px

    Grandes telas: acima de 1440px 


1. Desenhe para o celular primeiro: É mais fácil empilhar blocos um em cima do outro.

2. Use ```min-width:``` Comece com o estilo simples e vá "adicionando complexidade" à medida que a tela cresce.

3. Use Unidades Relativas: Tente usar ```%```, ```vw``` ou ```rem``` em vez de valores fixos em ```px``` para o layout. Isso torna o design mais fluido entre os *breakpoints*.

## Cuidados ao usar 320px como base
1. **Toque (Touch targets)**: Botões devem ter pelo menos *44x44px*, independentemente da largura da tela.
 
2. **Imagens**: Use unidades relativas (como *%* ou *vw*) ou Imagens Responsivas (MDN) para evitar que elementos ultrapassem a largura da **viewport**.
   
3. **Escalabilidade**: Verifique se textos longos ou tabelas não quebram o layout em *320px*