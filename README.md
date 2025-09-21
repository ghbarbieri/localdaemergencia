# Localização de Emergência

[![Licença: MIT](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Um Progressive Web App (PWA) de código aberto, projetado para fornecer e compartilhar informações de geolocalização de forma rápida e clara durante emergências, especialmente ao volante.

**Este projeto é 100% privado:** nenhum dado de localização ou de uso é armazenado em servidores. Todo o processamento ocorre diretamente no seu navegador.

---

### 🚀 Acesso Rápido (Demo)

**[Acesse a aplicação aqui!](URL_DO_SEU_SITE_AQUI)**

*(Substitua `URL_DO_SEU_SITE_AQUI` pelo link do seu site no Netlify, GitHub Pages, etc.)*

---

### ✨ Funcionalidades Principais

* **Geolocalização Precisa:** Mostra Rua, Bairro e Cidade, com a melhor aproximação de número ou cruzamento disponível.
* **Dados Vitais para Direção:** Informa a **velocidade** atual e o **sentido** (Norte, Sul, etc.) para facilitar a comunicação.
* **Pontos de Referência:** Identifica locais importantes próximos (Hospitais, Delegacias, Supermercados) para dar contexto à sua localização.
* **Compartilhamento Rápido:** Um botão para compartilhar todas as informações via WhatsApp ou pelo menu nativo do celular.
* **Discagem de Emergência:** Botões de acesso rápido para ligar para **190 (Polícia)**, **192 (SAMU)** e **193 (Bombeiros)**.
* **Assistente de RCP:** Um metrônomo sonoro com o ritmo de **110 batidas por minuto** para guiar massagens cardíacas.
* **Design Focado em Emergência:** Interface limpa, com fontes grandes e um tema que se adapta automaticamente (claro/alto contraste de dia, escuro à noite).
* **Resiliência:** Funciona offline (após o primeiro acesso) e detecta quando a conexão de internet é perdida, informando o usuário.

![Screenshot do App](URL_DA_SUA_IMAGEM_AQUI)
*(Dica: tire um print da tela do celular, faça o upload na aba "Issues" do seu repositório no GitHub para gerar um link, e cole o link aqui)*

### O Problema que este Projeto Resolve

Imagine estar em uma situação de perigo — como ser seguido no trânsito ou presenciar um acidente — e precisar informar sua localização em tempo real para os serviços de emergência pelo telefone. Em pânico, é difícil descrever onde você está, especialmente em uma via desconhecida ou em movimento.

Esta ferramenta foi criada para eliminar essa fricção. Com um único olhar, você tem a informação mais crítica formatada de maneira clara para ser lida em voz alta.

### 📲 Como Instalar no Celular

Este site é um PWA e pode ser instalado na tela de início do seu celular para acesso rápido.

#### Android (Chrome)
1.  Acesse o link da aplicação no Google Chrome.
2.  Toque nos **três pontinhos** (menu) no canto superior direito.
3.  Selecione **"Instalar aplicativo"** ou **"Adicionar à tela inicial"**.

#### iPhone (Safari)
1.  Acesse o link da aplicação no Safari.
2.  Toque no ícone de **Compartilhamento** (quadrado com uma seta para cima).
3.  Role para baixo e selecione **"Adicionar à Tela de Início"**.

### 🔧 Tecnologias Utilizadas

A beleza deste projeto está em sua simplicidade e robustez.

* **HTML5**
* **CSS3 (Vanilla):** Uso de variáveis CSS para temas e design responsivo.
* **JavaScript (Vanilla, ES Modules):** Sem frameworks ou dependências externas.
* **APIs do Navegador:**
    * Geolocation API
    * Web Audio API (para o beep da RCP)
    * Web Share API (para compartilhamento nativo)
* **Princípios de PWA:** Service Worker e Web App Manifest para funcionalidade offline e instalação.
* **Fonte de Dados:** [OpenStreetMap](https://www.openstreetmap.org/) através das APIs públicas [Nominatim](https://nominatim.org/) (geocodificação reversa) e [Overpass API](https://overpass-api.de/) (pontos de referência).

### 🤝 Como Contribuir

Contribuições são muito bem-vindas! Se você tem uma ideia para uma nova funcionalidade ou encontrou um bug, sinta-se à vontade para:

1.  Abrir uma **Issue** para discutir a sua ideia.
2.  Fazer um **Fork** do repositório.
3.  Criar uma nova **Branch** (`git checkout -b feature/sua-feature`).
4.  Fazer o **Commit** das suas mudanças (`git commit -m 'Adiciona nova feature'`).
5.  Fazer o **Push** para a sua branch (`git push origin feature/sua-feature`).
6.  Abrir um **Pull Request**.

### 📄 Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo `LICENSE` para mais detalhes.
