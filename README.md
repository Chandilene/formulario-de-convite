# 🎊 Festivite - Gerador de Convites Digitais

![Desafio Rocketseat](https://img.shields.io/badge/Desafio-Rocketseat-8257e5?style=for-the-badge&logo=rocketseat)

O **Festivite** é uma landing page interativa desenvolvida para facilitar a criação de convites personalizados para eventos. Através de um formulário inteligente e semântico, o usuário pode definir todos os detalhes do seu evento, desde a temática visual até as informações de contato.

💡 *Este projeto foi desenvolvido como um desafio prático da plataforma **Rocketseat**, focado em consolidar fundamentos de HTML semântico e arquitetura de CSS modular.*



---

## ✨ Funcionalidades

* **Customização Temática:** Seleção entre 12 temas visuais (Aniversário, Casamento, Halloween, etc.) usando botões de rádio estilizados como cards.
* **Paleta de Cores Dinâmica:** Escolha da cor principal do convite através de uma interface visual.
* **Upload de Mídia:** Componente customizado para upload de foto de capa.
* **Gestão de Evento:** Campos para definição de título, datas (início/fim), descrição e tipo de evento (Presencial ou Online).
* **Validação Visual:** Tratamento de erros e feedback visual para campos obrigatórios.
* **Termos e Privacidade:** Seção dedicada à aceitação de termos e preferências de marketing.

---

## 🛠 Tecnologias

* **HTML5:** Uso de tags semânticas como `aside`, `main`, `fieldset` e `legend` para acessibilidade.
* **CSS3:** Estilização modularizada utilizando variáveis e layouts modernos (Flexbox e Grid).
* **Google Fonts:** Utilização das fontes *Baloo 2*, *Leckerli One* e *Open Sans*.

---

## 📂 Organização do Projeto

O projeto segue uma estrutura organizada de estilos para facilitar a manutenção:

```text
FORMULÁRIO/
├── assets/             # Ícones (.svg), logos e imagens dos temas
├── styles/             # CSS Modularizado
│   ├── global.css      # Reset e variáveis de cores/fontes
│   ├── layout.css      # Estrutura principal (aside e main)
│   ├── form.css        # Estilos gerais de inputs e labels
│   ├── grid-theme.css  # Estilização da grade de cards de temas
│   ├── style-option.css# Componentes de switch e upload
│   ├── terms.css       # Estilos da seção de termos e checkboxes
│   └── index.css       # Arquivo central que importa todos os estilos
└── index.html          # Estrutura da página



## 🚀 Como Executar
Por ser uma aplicação front-end estática, o processo é simples:

Clone o repositório:

Bash
git clone [https://github.com/seu-usuario/festivite.git](https://github.com/seu-usuario/festivite.git)
Abra o projeto:

Navegue até a pasta e abra o arquivo index.html no seu navegador.

Recomendação: No VS Code, utilize a extensão Live Server para visualizar as alterações em tempo real.

## ✒️ Autor
Desenvolvido por Chandilene Borges durante os estudos na Rocketseat.
