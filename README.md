# Projeto-GDG

<p align="center">
  <img src="https://img.shields.io/static/v1?label=LICENSE&message=UniCesumar&color=blue&labelColor=0a2540&style=for-the-badge"/>
  <img src="https://img.shields.io/static/v1?label=STATUS&message=Finalizado&color=blue&labelColor=0a2540&style=for-the-badge"/>
</p>

## ✨ Descrição do Projeto

Este site foi desenvolvido para divulgar e gerenciar um **evento acadêmico de tecnologia** promovido por estudantes da Unicesumar em parceria com o **GDG Londrina (Google Developer Groups de Londrina)**.

O site reúne todas as informações essenciais sobre o evento, incluindo **data, hora, local, programação, palestrantes e formulário de inscrição**. Também oferece recursos visuais atrativos e responsivos, promovendo uma navegação fluida e moderna para os usuários.

O objetivo é **facilitar o acesso às informações**, permitir **inscrições rápidas e validadas**, e proporcionar uma **experiência imersiva** com animações e design responsivo.

## 🔧 Funcionalidades da Página

### Página Inicial

- **Menu hamburguer funcional**, acessível por todas as páginas e otimizado para dispositivos móveis.
- Exibição de um banner com nome, data e descrição do evento.
- Botão de chamada para ação: “Inscreva-se agora”.
- Cards de **eventos anteriores** exibidos em um grid com botão “Ver mais”, mostrando 4 eventos por vez.
- Ícones de redes sociais interativos.
- Rodapé com patrocinadores e apoiadores.
- Animação de fundo com `Vanta.net` em azul.
- Animações `fade-in` ao rolar a página.
- **Botão Bolha**: aparece ao rolar a página, após o botão de inscrição.
  - Ao ser clicado, leva diretamente ao menu hamburguer.
  - O menu realiza uma leve **animação pulse**.
  - Após isso, o botão recebe uma **bolinha vermelha de notificação**, que **só desaparece após o menu ser aberto**.

### Página de Programação

- Cronograma com horários e atividades do evento.
- Animações `fade-in` ao rolar a página.
- Animação de fundo com `Vanta.net` em verde.

### Página de Palestrantes

- Cards com foto, nome, e profissão.
- Janela modal com currículo, cargo, redes sociais e descrição de cada palestrante.
- Animações `fade-in` ao rolar a página.
- Animação de fundo com `Vanta.net` em laranja.

### Página de Localização

- Endereço completo com integração ao Google Maps.
- Indicação do local exato dentro do campus.
- Informações do estacionamento do local.
- Informações sobre transporte público.
- Ícones de redes sociais interativos.
- Animações `fade-in` ao rolar a página.
- Animação de fundo com `Vanta.net` em vermelho.

### Página de Inscrição

- Formulário de inscrição com validação de campos.
- Barra de carregamento até o término do processamento da inscrição.
- Sistema de mensagens que exibe:
  - Confirmação de inscrição bem-sucedida.
  - Alerta de que o participante já está inscrito, impedindo inscrições duplicadas.
  - Notificações de erro em caso de preenchimento incorreto.
- Temporizador de contagem regressiva até o início do evento.
  - Exibição da mensagem "O evento começou" após o fim da contagem.
- Animações `fade-in` ao rolar a página.
- Animação `Matrix 2D` com as cores azul, laranja, verde e vermelho como plano de fundo.

---

## 📱 Responsividade Geral

- Fonte Audiowide para todo o site.
- Layout 100% responsivo para desktop, tablet e mobile.
- Menu hamburguer funcional em todas as resoluções e páginas.
- **Footer unificado** em todas as páginas do site, com exibição dos **apoiadores do evento**.
  - Cada imagem de apoiador é **clicável** e direciona para o **site oficial** correspondente.

## 🔼 Público-Alvo

- `Programadores`
- `Universitários`
- `Interessados`
- `Investidores`

## 💻 Linguagens Utilizadas

- `HTML5`
- `CSS3`
- `JavaScript`

## 🚀 Tecnologias Utilizadas

- `Visual Studio Code`
- `Canva`
- `Figma`
- `Trello`
- `Git/GitHub`

## 🗃 Armazenamento de Dados

- `Google Sheets` – Utilizado como banco de dados para armazenar inscrições, permitindo uma gestão centralizada e fácil de dados.

## 📚 Bibliotecas e Recursos Externos

- [Google Fonts](https://fonts.google.com/) – Tipografia personalizada para melhorar a legibilidade e estética
- [Font Awesome](https://fontawesome.com/) – Ícones vetoriais usados na interface
- [Vanta.js](https://www.vantajs.com/) – Animação de fundo com efeito de rede (Net)

## ✨ Animações e Efeitos Visuais

Durante o desenvolvimento, foram aplicadas animações específicas para cada página, visando melhorar a experiência do usuário e reforçar a identidade visual do site.

### 🔹 Animação Fade-in

- Aplicada em todas as páginas para uma transição suave dos elementos ao carregar.
- Aumenta a fluidez da navegação e dá um aspecto moderno ao site.

### 🔸 Fundo Animado com Vanta.NET

- Presente em todas as páginas, com **variações de cores específicas por página**.
- Utiliza a biblioteca `Vanta.js`, especificamente o efeito `NET`, que cria uma malha interativa de linhas e pontos em constante movimento.
- Esse efeito responde ao movimento do mouse ou do dedo (celular), proporcionando uma sensação de profundidade e interatividade.
- Reforça a identidade visual do site com um fundo moderno, dinâmico e tecnológico.

## 🎨 Justificativa do Design

As cores foram inspiradas na identidade visual do `GDG Londrina` e da `Unicesumar`, promovendo a união entre os dois.

## 🖋️ Wireframes e Esboços

- Página Inicial: Informativa sobre o evento.
- Página de Programação: Informa sobre os temas, horários, palestrantes, intervalos (se houver) no dia do evento.
- Página de Palestrantes: Currículos e cargos dos palestrantes.
- Página de Inscrição: Para efetuar a inscrição e receber certificado (se houver emissão).
- Página de Localização: Contém informações sobre o local, horário e em qual parte do campus será realizado o evento, além de conter um mapa integrado levando diretamente à localização.

🔗 [Clique aqui para acessar os wireframes e esboços no Figma](https://www.figma.com/design/4hg1Heg24TUCfrjrQD5CZ4/evento-tech?node-id=0-1&t=VGOS6Vt91PE3hOpb-0)

## 🔠 Mapa Mental

O mapa mental foi elaborado na etapa inicial do projeto para organizar ideias, definir as páginas, funcionalidades e a identidade visual. Ele serviu como base para estruturar todo o desenvolvimento.

![Mapa Mental](./Images/Mapa_mental.jpg)

## 📅 Trello

O quadro no Trello foi utilizado para **organizar as tarefas da equipe**, acompanhar o progresso e dividir responsabilidades. As colunas representam as etapas: ideias, a fazer, em andamento e concluído.

![Trello](./Images/trello.webp)

---

# Projeto GDG – Página Inicial

## 📄 Descrição da Página Inicial

A página inicial tem como objetivo principal apresentar as informações essenciais do evento GDG Londrina, com um layout moderno, interações visuais e acessibilidade para diversos dispositivos.

Além disso, a página conta com **animações visuais** que tornam a navegação mais envolvente:

- 💠 **Fundo animado com Vanta.net (Azul)**: Um background interativo que dá movimento à página com uma malha interativa de linhas e pontos em constante movimento.
- ✨ **Animações fade-in**: Aplicadas aos elementos principais para que apareçam suavemente à medida que o usuário rola a página.

Esses efeitos visuais aumentam o dinamismo da interface, tornando a experiência mais fluida e moderna.

A seguir estão as principais seções da página inicial, com suas funcionalidades e espaço para demonstração visual (GIFs/fotos):

---

## 📱 Menu Hamburguer

O menu hamburguer possui fundo **meio transparente** e pode ser fechado ao clicar no “X” ou **clicando fora dele**. Ele mostra as seguintes páginas:

- Página Inicial
- Programação
- Palestrantes
- Inscrição
- Localização
- Site Oficial do GDG Londrina

📌 _Funciona perfeitamente em dispositivos móveis, com boa responsividade._

🎥 **GIF demonstrativo do Menu Hamburguer:**

![GIF do Menu](./Gifs/Gif_menu_hamburguer.gif)

---

## 📅 Seção de Informações do Evento

Logo após o header, é exibida uma **seção com data, horário, nome e localização** do evento GDG. Abaixo dessas informações, há uma **descrição do evento**.

📸 **Imagem dessa seção:**

![GIF Info Evento](./Images/Sobre-o-evento.png)

---

## 🟢 Botão de Inscrição

Um botão grande e chamativo com chamada à ação leva diretamente para a página do **formulário de inscrição**.

🎥 **GIF do botão de inscrição:**

![Gif Botão de Inscrição](./Gifs/Gif-botao-inscreverSe-pagina-inicial.gif)

---

## 🔴 Botão Flutuante com Animação Pulse

Ao rolar a página, surge um **botão pequeno no canto inferior direito** com uma animação “pulse” e uma **bolinha vermelha**, incentivando o usuário a abrir o menu hamburguer.

- A bolinha desaparece após o menu ser clicado pela primeira vez.

🎥 **GIF do botão flutuante com animação:**

![GIF Botão Pulse](./Gifs/Gif-botao-bolha.gif)

---

## 🧾 Cards dos Eventos Anteriores (com botão "Ver mais")

A antiga galeria foi substituída por um **grid de cards responsivos** que exibem eventos anteriores. Cada card apresenta imagem, título e breve descrição do evento.

- Por padrão, **4 cards são exibidos inicialmente**;
- Ao clicar no botão **"Ver mais"**, são carregados mais 4 eventos;
- A funcionalidade evita rolagens longas e mantém a organização visual;
- Totalmente responsivo e com animações suaves para exibição dos novos cards.

🎥 **GIF dos cards com botão "Ver mais":**

![GIF Cards Evento](./Gifs/gifDosCardsEventosAnteriores.gif)

---

## 📞 Seção de Contato

Ícones de redes sociais redondos e interativos:

- Ao passar o mouse ou clicar (em dispositivos móveis), mudam a cor de fundo para a respectiva da rede social.
- Todos os botões estão linkados corretamente:
  - Twitter (X)
  - Instagram
  - LinkedIn
  - YouTube
  - GitHub

🎥 **GIF dos ícones interativos:**

![GIF Contato](./Gifs/Gif-contatos.gif)

---

## 🧩 Footer – Apoio e Patrocínio

No final da página, há uma seção de "Apoio", destacando os **patrocinadores, colaboradores e apoiadores** do evento.

🎥 **GIF do footer:**

![GIF Footer](./Gifs/Gif-footer.gif)

---

## 🗓️ Página de Programação

Apresenta os horários, temas e palestrantes do evento de forma clara e estilizada.

- Mantém o mesmo layout da página inicial (com header, menu e animações);
- Efeito de fundo **Vanta.net em verde**, com transição suave (fade-in);
- Cards com:
  - Foto e nome do palestrante;
  - Tema da palestra;
  - Horário do bloco.

🎥 **GIF da página de programação:**

![Gif Página de Programação](./Gifs/Gif-pagina-programacao.gif)

---

## 👩‍🏫 Página de Palestrantes

Apresenta os palestrantes do evento com destaque visual e informações relevantes.

- Mantém o mesmo layout da página inicial (header, menu hambúrguer e animações);
- Fundo animado com **Vanta.net em laranja**, incluindo transição suave (fade-in);
- Cada palestrante é exibido em um **card estilizado**, contendo:
  - Foto com bordas arredondadas e contorno laranja;
  - Nome e título profissional (ex: “Especialista em IA”);
  - Botão com animação ao clicar, rotulado como **"Ver Perfil"**

## 🧾 Ao clicar em “Ver Perfil”:

- É exibido um **modal** chamado **Perfil Completo**:
  - Mostra a foto do palestrante (sem bordas);
  - Exibe todas as informações relevantes sobre ele (mini currículo);
  - Inclui **ícones interativos com links para redes sociais** (LinkedIn, GitHub, Instagram, Twitter (X), etc).

🎥 **GIF da página de palestrantes:**

![Gif Página de Palestrantes](./Gifs/Gif_pagina_de_palestrantes.gif)

---

## 📝 Página de Inscrição

Página acessada ao clicar no botão **“Inscreva-se agora!”** na página inicial ou no **menu hambúrguer**.

- Mantém o mesmo layout das outras páginas (header, menu hambúrguer, footer e animações com fade-in);
- **Fundo animado estilo “Matrix”** com `canvas` simulando chuva de "0" e "1" em **cores alternadas** (azul, verde, laranja e vermelho), refletindo a identidade visual do evento.

🎥 **GIF da animação de fundo:**

![Gif Animação de Fundo](./Gifs/Fundo-matrix2D.gif)

---

### 🧾 Formulário de Inscrição

Exibido centralizado e em destaque com `box-shadow`, dando aparência de estar acima do fundo.

- Título: **“Inscreva-se”**;
- Campos obrigatórios:

  - Nome;
  - Sobrenome;
  - Endereço de e-mail;
  - Número de celular.

- Botão de envio com **animação ao clicar**;
- Ao clicado pelo usuário após todos os dados serem preenchidos corretamente:
  - Uma **barra de carregamento** aparece abaixo do botão;
  - Os dados são verificados e enviados para uma **planilha no Google Sheets**, criada exclusivamente para armazenar as inscrições com segurança (ex: para emissão de certificados de participação).

🎥 **GIF do formulário e da barra de carregamento:**

![Formulário de Inscrição](./Gifs/Gif-formulario-inscricao.gif)

---

### ✉️ Mensagens de Retorno

Após o envio dos dados, o sistema responde com mensagens claras dentro da mesma seção:

- ✅**Inscrição realizada com sucesso!** (mensagem azul);
- 🟢**Você já está inscrito!** (mensagem verde – caso o usuário tente se inscrever novamente com os mesmos dados);
- ❌**Erro ao enviar inscrição. Tente novamente.** (mensagem vermelha – possíveis causas):
  - Falha na conexão com a internet;
  - API do Google Sheets fora do ar;
  - Campos obrigatórios não preenchidos corretamente;
  - Formato de e-mail ou número inválidos.

📸 **Imagens das mensagens de retorno:**

### ✅ Inscrição realizada com sucesso!

![Inscrição realizada com sucesso](./Images/Mensagem-de-inscricao-realizada.png)

---

### 🟢 Você já está inscrito!

![Já inscrito](./Images/Mensagem-voce-ja-esta-inscrito.png)

---

### ❌ Erro ao enviar inscrição. Tente novamente.

![Erro ao enviar](./Images/Mensagem-erro.png)

---

### ⏳ Temporizador do Evento

Logo abaixo do formulário, é exibido um **contador regressivo em tempo real**:

- Texto: **“Faltam apenas:”**
- Seguido de: dias, horas, minutos e segundos, **atualizando a cada segundo** sem atrasos ou recarregamento da página.

## Temporizador para o Início do Evento

![Temporizador para o Início do Evento](./Gifs/Gif-temporizador-para-inicio-do-evento.gif)

---

🎉 Quando o contador chega a zero (horário de início do evento), ele é **automaticamente substituído** por uma mensagem:

> **"O evento começou!"**

## Mensagem após o Temporizador Zerar

![Mensagem após o Temporizador Zerar](./Gifs/Gif-mensagem-apos-zerar-o-temporizador.gif)

---

## 📍 Página de Localização

Página acessada ao clicar no botão **“Localização”** no menu hambúrguer da página principal ou em qualqer uma das outras.

- Mantém o mesmo layout das outras páginas (header, menu hambúrguer, footer e animações com fade-in).
- Fundo com **efeito visual Vanta.NET vermelho**;
- Apresenta as **informações do local do evento** com clareza:

  - 🏛️ Local: Auditório da Unicesumar (2º andar);
  - 📍 Endereço: Av. Santa Mônica, 450 – Franca, Londrina – PR, 86027-610;
  - 🛍️ Ponto de referência: Próximo ao Shopping Boulevard;
  - 🚗 Estacionamento interno liberado para todos do evento (**conforme disponibilidade de vagas**) – incentivamos **caronas colaborativas!**;
  - 🚌 Linhas de transporte público: **102 e 103**.

- Mapa do Google Maps embutido, com bordas arredondadas e `box-shadow`, direcionando o usuário diretamente para o site ou aplicativo, para ter acesso a localização exata e rotas até o local do evento;
- Responsivo e adaptável para celulares.

🎥 **GIF do mapa e visual da página:**

![GIF Página de Localização](./Gifs/Gif-pagina-localizacao.gif)

---

## 👨‍💻 Desenvolvedores

Este projeto foi desenvolvido por estudantes de Engenharia de Software da Unicesumar:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/Paulovcarraro">
        <img src="https://github.com/Paulovcarraro.png" width="100px;" alt="Foto do Paulo Vinicius"/><br />
        <sub><b>Paulo Vinícius Carraro</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Matheuspenas">
        <img src="https://github.com/Matheuspenas.png" width="100px;" alt="Foto do Matheus Pena"/><br />
        <sub><b>Matheus Pena</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/DanielBiLL13">
        <img src="https://github.com/DanielBiLL13.png" width="100px;" alt="Foto do Daniel Bill"/><br />
        <sub><b>Daniel Bill</b></sub>
      </a>
    </td>
  </tr>
</table>

---

## 🌐 Acesse o Projeto

Você pode visualizar o site no GitHub Pages pelo link abaixo:

🔗 [Acessar Site GDG - GitHub Pages](https://matheuspenas.github.io/projeto-gdg/)
