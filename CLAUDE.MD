# Projeto: Clone de Slither.io para PlayStation 3

## Objetivo
Criar um jogo homebrew 2D para PlayStation 3 (compilável para .pkg e testável no RPCS3) fiel às mecânicas clássicas do Slither.io.

## Mecânicas Principais Necessárias
1. **Movimentação e Câmera:** Cobra controlada pelo analógico esquerdo (L3) com rotação suave de 360 graus e câmera seguindo a cabeça no centro da tela.
2. **Boost (Aceleração):** Segurar X ou R2 aumenta a velocidade da cobra e consome seu comprimento aos poucos, soltando orbes de energia atrás dela.
3. **Crescimento e Orbes:** Orbes brilhantes espalhados pelo mapa. Comer orbes aumenta o tamanho e a espessura da cobra.
4. **Colisão e Morte:** Se a cabeça da cobra bater no corpo de outra cobra, ela explode em vários orbes grandes e o jogo reinicia. Bater no próprio corpo não mata.
5. **Bots com IA:** Pelo menos 15 a 20 cobras controladas por IA vagando pelo mapa, desviando de outras cobras e buscando orbes.
6. **Arena Circular:** Mapa grande com borda vermelha brilhante (encostar na borda mata a cobra) e um minimapa no canto da tela.
7. **HUD:** Pontuação atual (tamanho) e ranking Top 5 no canto superior direito.

## Regras para o Claude (Modo Gratuito)
- Nunca gere o jogo inteiro de uma vez para não cortar o código no meio.
- Trabalhe por etapas (Etapa 1: Janela + Cobra + Movimento; Etapa 2: Orbes + Crescimento; Etapa 3: Bots + Colisão; Etapa 4: Bordas + Minimapa + HUD).
- Entregue sempre os arquivos completos e prontos para copiar e colar, junto com o Makefile para gerar o .pkg.
