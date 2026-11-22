# 🎁 Amigo Oculto

Sorteio de amigo oculto em um único `index.html`, sem servidor.

1. Coloque o nome de todo mundo e clique em **Sortear**.
2. O resultado não aparece: cada pessoa ganha um link próprio (copiar ou mandar no WhatsApp).
3. A pessoa abre o link dela e vê quem tirou.

O par fica codificado no próprio link (não é segurança, só evita spoiler).
O sorteio usa `crypto.getRandomValues` e é uniforme entre todas as combinações onde ninguém tira a si mesmo.

Para os links funcionarem, a página precisa estar publicada (ex.: GitHub Pages).
