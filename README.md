# Automação E2E - SauceDemo (UiPath)

Projeto de automação de testes End-to-End (E2E) desenvolvido no UiPath Studio para validação do fluxo principal de compras na plataforma e-commerce [SauceDemo](https://www.saucedemo.com/).

---

## 🎬 Demonstração

![Demonstração do Robô](docs/demo.gif)

*(Caso o seu arquivo de vídeo esteja em outro formato, como .mp4, você também pode arrastar e soltar o vídeo diretamente na edição do README no GitHub)*

---

## 📌 Fluxo da Automação

O robô realiza as seguintes etapas de forma totalmente automatizada:

1. **Acesso à Aplicação:** Abre o navegador Google Chrome no site do SauceDemo.
2. **Autenticação:** Preenche as credenciais do usuário (`standard_user` / `secret_sauce`) e realiza o login.
3. **Seleção de Produto:** Localiza o produto **Sauce Labs Backpack** e o adiciona ao carrinho de compras.
4. **Navegação ao Carrinho:** Acessa a página do carrinho de compras (`/cart.html`).
5. **Geração de Evidência:** Captura uma imagem da tela do carrinho com o item adicionado e salva localmente (`Evidencia_Carrinho.png`).
6. **Finalização:** Encerra a sessão do navegador de forma limpa.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **UiPath Studio** (Atividades Modernas de UI Automation)
* **Linguagem:** VB.NET
* **Navegador:** Google Chrome
* **Plataforma Testada:** SauceDemo Web App

---

## 🚀 Como Executar o Projeto

1. Certifique-se de ter o **UiPath Studio** instalado na sua máquina.
2. Clone este repositório para o seu ambiente local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/SauceDemo_E2E_UiPath.git](https://github.com/SEU_USUARIO/SauceDemo_E2E_UiPath.git)