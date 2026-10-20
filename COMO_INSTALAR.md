# Como instalar o Mouse Mapper (sem instalar nada no computador)

O GitHub monta o aplicativo (APK) para você, de graça, na nuvem.

## Parte 1 – Gerar o APK
1. Crie uma conta grátis em github.com (se ainda não tiver).
2. Clique no "+" no canto de cima > "New repository". Nome: mouse-mapper.
   Deixe "Public" marcado e clique em "Create repository".
3. Extraia (descompacte) o arquivo .zip no seu computador.
4. Na página do repositório, clique em "uploading an existing file".
5. Abra a pasta extraída, selecione TUDO que está dentro dela (arquivos e pastas,
   inclusive a pasta ".github") e arraste para a página do GitHub.
6. Role até o fim e clique em "Commit changes".
7. Clique na aba "Actions". Vai aparecer "Build APK" rodando (bolinha amarela).
   Espere uns 5 minutos até ficar com ✓ verde.
8. Clique nesse build. Lá embaixo, em "Artifacts", clique em "MouseMapper-apk".
   Vai baixar um .zip. Extraia: dentro está o app-debug.apk.

## Parte 2 – Instalar no celular
1. Passe o app-debug.apk para o celular (cabo USB, WhatsApp para você mesmo, Drive...).
2. Toque no arquivo. Se pedir, permita "instalar apps desconhecidos" para o app que você usou.
3. Abra o "Mouse Mapper" > botão "1. Abrir Acessibilidade" > Mouse Mapper > Ativar.
   (Android 13 ou mais novo: se o item estiver cinza, vá em Configurações > Apps >
   Mouse Mapper > menu ⋮ > "Permitir configurações restritas" e tente de novo.)
4. Conecte teclado e mouse (cabo OTG ou Bluetooth), abra o jogo em paisagem
   e aperte F1 no teclado para ligar o mapeamento.

## Se algo der errado
- Aba Actions vazia: no repositório clique em "Add file" > "Create new file", escreva o nome
  .github/workflows/build.yml e cole o conteúdo do arquivo build.yml que está no zip.
- Build com ✗ vermelho: abra o build, copie a mensagem de erro e mande para mim.
- Os botões do jogo não são tocados no lugar certo: ajuste os números x e y no perfil
  (dentro do app). 0.5 é o meio da tela, 1.0 é a borda direita/de baixo.

Aviso: jogos online competitivos podem banir quem usa mapeadores.
