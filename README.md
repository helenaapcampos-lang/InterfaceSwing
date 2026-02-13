## 📖 Explicação do código

O arquivo `ExemploSwing.java` cria uma aplicação gráfica simples usando **Java Swing**.  
Aqui estão os principais pontos:

1. **Janela principal (`JFrame`)**
   - É criada uma janela chamada "Minha Interface Swing".
   - Define tamanho fixo (400x200) e comportamento de fechar ao clicar no "X".

2. **Painel (`JPanel`)**
   - Serve como contêiner para organizar os componentes da interface.

3. **Componentes**
   - `JLabel`: mostra o texto "Digite seu nome:".
   - `JTextField`: campo de texto para o usuário digitar o nome.
   - `JButton`: botão "Enviar".
   - Outro `JLabel`: mostra o resultado da interação.

4. **Ação do botão (`ActionListener`)**
   - Quando o usuário clica em "Enviar":
     - O programa pega o texto digitado no campo.
     - Atualiza o `JLabel` de resultado com a mensagem:  
       ```
       Olá, [nome digitado]!
       ```

5. **Exibição**
   - Todos os componentes são adicionados ao painel.
   - O painel é colocado dentro da janela.
   - A janela é exibida na tela com `frame.setVisible(true)`.

---

### Resultado esperado
Ao executar o programa:
- Uma janela aparece com campo de texto e botão.
- O usuário digita o nome e clica em "Enviar".
- A interface responde mostrando uma saudação personalizada.
