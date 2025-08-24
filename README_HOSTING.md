
PORTFÓLIO - instruções detalhadas de hospedagem rápida e gratuita (GitHub Pages e Netlify)

Resumo das opções (gratuitas):
- GitHub Pages: permite publicar um site estático gratuitamente. Se você nomear o repositório como SEUNOME.github.io o site ficará em https://SEUNOME.github.io — assim seu **nome** aparece no domínio.
- Netlify / Vercel: permitem publicar sites estáticos com deploys automáticos. Você pode escolher um subdomínio gratuito (ex: samuel-portfolio.netlify.app). Também aceitam domínios personalizados se você comprar um.

A) Publicar no GitHub Pages (recomendado — permite domínio com seu nome)
1) Criar conta no GitHub:
   - Acesse https://github.com e registre-se (nome, email, senha).
2) Criar repositório:
   - Clique em "+" → "New repository".
   - Para ter o site em https://SEUNOME.github.io (ex: samuelgarabini.github.io), **nomeie o repositório exatamente** como:
     SEUNOME.github.io
     (substitua SEUNOME pelo seu usuário GitHub desejado — por exemplo: samuelgarabini.github.io)
   - Deixe como "Public" e clique em "Create repository".
3) Fazer upload dos arquivos (sem usar terminal):
   - No repositório recém-criado, clique em "Add file" → "Upload files".
   - Arraste o conteúdo do ZIP que te enviei (mantenha as pastas css/, portfolio_sample/, assets/, etc).
   - Após carregar, clique em "Commit changes".
4) Publicação:
   - Se o repositório estiver nomeado como SEUNOME.github.io, o site será publicado automaticamente em:
     https://SEUNOME.github.io
     - Aguarde alguns minutos se não aparecer imediatamente.
   - Se você usou outro nome para o repositório, então o endereço será:
     https://SEU_USUARIO.github.io/NOME-DO-REPO
5) Atualizações:
   - Para atualizar o site, faça upload novamente dos arquivos alterados ou use Git no terminal (push).

B) Publicar no Netlify (opção alternativa — deploy automático e seleção de subdomínio)
1) Criar conta no https://app.netlify.com (você pode usar GitHub para conectar).
2) No painel, clique em "Sites" → "New site from Git" se você subir o código para um repositório Git (recomendado), ou clique em "Deploy site" → "Drag & drop" para arrastar a pasta com os arquivos (deploy manual).
3) Ao usar drag & drop, escolha a pasta com os arquivos do site (index.html e pastas).
4) O Netlify publicará o site e gerará um subdomínio do tipo random-name.netlify.app. Você pode editar esse nome no painel para algo como samuel-portfolio.netlify.app (se disponível).

C) Domínio com seu nome (opções)
- GitHub Pages com repositório SEUNOME.github.io já mostra seu usuário no domínio.
- Se desejar comprar um domínio (ex: samuelgarabini.com), você pode registrar em registradores (e.g., Registro.br, Namecheap) e configurar um "Custom domain" no GitHub Pages ou Netlify. Posso detalhar esse passo se quiser.

D) Observações técnicas e dicas
- Mantenha o arquivo index.html na raiz do repositório.
- Certifique-se de que o caminho para css/styles.css esteja correto (nos arquivos que enviei está como css/styles.css).
- O formulário de contato é apenas visual. Para receber mensagens:
  - Use serviços como Formspree, Netlify Forms ou configure um backend (Node/Express, servidor simples) e aponte o form action para o endpoint.
- Para fazer pequenas edições locais e enviar para o GitHub com Git:
  - Instale Git, faça `git init`, `git add .`, `git commit -m "site"`, `git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git`, `git push -u origin main`.

Se quiser, eu posso:
- Gerar um tutorial com prints (passo-a-passo com imagens) para cada etapa do GitHub.
- Explicar como ativar HTTPS/custom domain.
- Ajudar a configurar o formulário para enviar emails (Formspree / Netlify Forms).

---
Arquivos já atualizados:
- contato.html (email: samuelgarabini2.0@gmail.com)
- portfolio_sample/sample.html (email: samuelgarabini2.0@gmail.com)
- portfolio.html (frase removida)

