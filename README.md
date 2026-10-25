# Publicar a ADA Education no GitHub Pages

## 1. Preparar os ficheiros

Extraia este ZIP. Os ficheiros `index.html`, `style.css` e `script.js`, e a pasta `assets`, devem ficar na raiz do repositório. O logótipo está em `assets/logo-ada.jpeg`. Não é necessário instalar dependências nem executar comandos.

## 2. Criar o repositório

Entre em https://github.com/ e escolha New repository. Dê o nome `ada-education`, escolha Public e crie o repositório. Na página do repositório, use a opção para carregar ficheiros (uploading an existing file / Add file → Upload files). Carregue o conteúdo extraído do ZIP, incluindo a pasta `assets`, e confirme em Commit changes. Verifique que `index.html` aparece logo na raiz, sem uma pasta adicional por cima.

## 3. Activar o site

Abra Settings → Pages. Em Source, escolha Deploy from a branch. Seleccione a branch main e a pasta /(root). Clique em Save. Aguarde a publicação e use o endereço que o GitHub apresentar em Pages.

O formato habitual será `https://SEU-UTILIZADOR.github.io/ada-education/`. SEU-UTILIZADOR representa o seu nome de utilizador no GitHub; isto é apenas um exemplo, não um endereço já publicado.

O site deixará de usar o endereço chatgpt.site quando visitar a versão publicada no GitHub Pages. O endereço gratuito do GitHub inclui github.io. Um domínio próprio é opcional e configura-se separadamente.

Guia oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## 4. Actualizar o site

Edite ou substitua os ficheiros no repositório e confirme as alterações em Commit changes. O GitHub Pages volta a publicar a partir da branch seleccionada.

---

# ADA Connect Education — site em português

Site em HTML, CSS e JavaScript puro, preparado para estudantes moçambicanos. O logótipo oficial enviado está em `assets/logo-ada.jpeg`; a imagem foi mantida intacta.

## Abrir no computador

Extraia o ZIP para uma pasta. Mantenha `index.html`, `style.css`, `script.js` e a pasta `assets` juntos. Abra `index.html` no navegador. Não precisa de instalar programas nem de um servidor. A imagem do campus e o WhatsApp precisam de internet; o catálogo está incluído no próprio projecto.

## Contactos

- Andlyn Dausse: +91 70694 19522 — https://wa.me/917069419522
- Contacto geral de Moçambique, mantido do pedido anterior: +258 85 500 7607 — https://wa.me/258855007607
- Savelyn Dausse: +91 84886 53475 — https://wa.me/918488653475
- Elizabeth Togarepi: +258 84 310 2439 — https://wa.me/258843102439
- E-mail oficial: adaconnecteducation@rightunichoice.com

Os indicativos de Savelyn (+91) e Elizabeth (+258) foram inferidos a partir do formato dos números recebidos. Confirme-os antes da divulgação externa. O contacto de Andlyn usa o primeiro número fornecido no pedido original.

Todos os contactos de WhatsApp aparecem na secção de contacto e no rodapé. O formulário permite escolher o destinatário. O e-mail abre a aplicação de correio do visitante; não é enviado automaticamente.

Para alterar números, edite `CONFIG.whatsapp` em `script.js` e os links `wa.me` em `index.html`. Use apenas algarismos no endereço, incluindo o indicativo do país. Para mudar o e-mail, substitua o endereço em `index.html`.

## Português e pesquisa

Os menus, explicações, perguntas frequentes, formulário, mensagens de WhatsApp, calculador e filtros estão em português. Os nomes oficiais dos cursos continuam em inglês. A pesquisa aceita termos como «enfermagem», «informática», «gestão» e «engenharia», com ou sem acentos.

## Dados dos cursos e propinas

A lista contém 414 links distintos do catálogo oficial consultado em 25 de Outubro de 2026. A duração foi localizada em 395 páginas de cursos. Os restantes casos pedem confirmação. As áreas são associadas pelos links das faculdades; os casos não confirmados estão identificados. Os catálogos de doutoramento e cursos à distância têm links separados; não é alegada uma lista completa e actual de todas as especialidades de investigação ou cursos online.

As propinas internacionais e os preços actuais de alojamento não puderam ser verificados: a pesquisa da página oficial de propinas internacionais não devolveu cursos. Não foram usados preços antigos ou preços nacionais da Índia como substitutos.

O calculador utiliza valores da cotação escrita do estudante, em INR, introduzidos separadamente para cada ano. Campos vazios continuam por confirmar. Os subtotais incompletos estão assinalados. Os valores não são copiados automaticamente de um ano para outro. Despesas pessoais e honorários da ADA não fazem parte do total universitário.

Para actualizar cursos, edite o array `COURSES` no início de `script.js`. Cada registo tem `name`, `faculty`, `level`, `track`, `source`, `duration` e `annualFee`. Mantenha `null` quando um valor não estiver confirmado; não use zero para indicar desconhecido. Os campos originais em inglês são apresentados com etiquetas em português. Actualize a fonte e a data no site. Introduza uma propina numérica apenas depois de confirmar que é anual, em INR, internacional e aplicável ao curso. Não multiplique valores sem confirmar os períodos abrangidos.

Fontes oficiais consultadas em 25 de Outubro de 2026:

- https://www.paruluniversity.ac.in/admission/all-programs/
- https://www.paruluniversity.ac.in/international-students-fees-structure/
- https://www.paruluniversity.ac.in/international-admissions/
- https://www.paruluniversity.ac.in/life-at-pu/hostel-residence/
- https://www.paruluniversity.ac.in/program-type/doctoral-post-doctoral-program/
- https://www.paruluniversity.ac.in/program-type/certificate-programs/
- https://www.paruluniversity.ac.in/gallery/

## Formulário e privacidade

O formulário valida os campos e prepara uma mensagem no WhatsApp para o visitante rever e enviar. O site não guarda os dados, não envia mensagens sozinho e não envia o formulário para o e-mail da empresa. Uma base de dados ou entrega de e-mails precisaria de um serviço externo ou backend.

## Fotografias e condições do serviço

A fotografia externa do campus está identificada como proveniente da galeria oficial da universidade. A licença para reutilização comercial não foi confirmada: obtenha autorização ou substitua `CONFIG.campusImage` por uma imagem com licença adequada antes do lançamento comercial público. O site apresenta um fundo alternativo se a fotografia não carregar.

Confirme o âmbito real dos serviços, os honorários e as condições de tratamento de dados da ADA antes de oferecer serviços pagos. Não são prometidas admissão ou aprovação de visto. Não é alegada parceria oficial com a universidade.

## Publicar no GitHub Pages

Crie um repositório no GitHub e carregue os três ficheiros e a pasta `assets` na raiz. Em Settings → Pages, seleccione Deploy from a branch e escolha a branch e a pasta raiz. Guarde e abra o endereço fornecido pelo GitHub.

Instruções oficiais: https://docs.github.com/en/pages/quickstart

Para um domínio próprio, verifique o domínio e introduza-o em Settings → Pages → Custom domain antes de alterar o DNS. Para `www`, configure um CNAME para `utilizador.github.io`, sem o nome do repositório. Para um domínio raiz, siga os registos A/ALIAS/ANAME indicados pelo GitHub. Active HTTPS quando disponível.

Guia oficial: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Verificação desta actualização

Verificados: sintaxe JavaScript, apresentação no navegador, pesquisa com termos em português, etiquetas traduzidas, contactos e destinatários do formulário, e-mail e menu móvel num ecrã de 390 px sem deslocamento horizontal. Não foi enviada nenhuma mensagem ou consulta real.
