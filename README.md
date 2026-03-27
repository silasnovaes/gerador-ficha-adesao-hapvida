# 📄 Ficha de Adesão Corporate - Processo Digital Integrado

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.com/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/Overview.en.html)
[![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Uma aplicação web (Single Page Application) desenvolvida para digitalizar e simplificar o processo de adesão ao plano de saúde corporativo para os colaboradores da empresa JR Esquadrias. 

O sistema substitui formulários de papel complexos por uma interface amigável, aplicando regras de negócio em tempo real e gerando um documento PDF perfeitamente formatado, pronto para assinatura.

## ✨ Funcionalidades

* **Validação de Regras de Negócio:** Aplicação automática de restrições de dependentes (idade máxima para filhos e obrigatoriedade de data de casamento para cônjuges).
* **Geração de PDF no Frontend:** Utilização da biblioteca `html2pdf.js` para renderizar um layout de impressão pixel-perfect, sem necessidade de processamento no servidor (backend).
* **Memória de Estado (Local Storage):** Salva o progresso do preenchimento automaticamente no navegador do usuário, evitando perda de dados caso a página seja recarregada ou fechada.
* **Campos Condicionais e Dinâmicos:** A interface se adapta à quantidade de dependentes informada, exibindo campos específicos apenas quando necessário (ex: data de casamento).
* **Design Responsivo:** Interface otimizada para uso em smartphones, tablets e desktops (Mobile First).

## 🛠️ Tecnologias Utilizadas

* **HTML5 & CSS3:** Semântica, CSS Variables e Flexbox/Grid para estruturação fluida.
* **Vanilla JavaScript (ES6+):** Lógica de controle, manipulação do DOM e Local Storage.
* **html2pdf.js:** Biblioteca para conversão de elementos HTML estruturados em arquivos PDF para download.

## 🚀 Como Executar

Por ser uma aplicação totalmente *Client-Side* (Frontend puro), não há necessidade de configurar servidores ou bancos de dados.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/adesao-corporate-jr-esquadrias.git](https://github.com/SEU-USUARIO/adesao-corporate-jr-esquadrias.git)

2. Abra a pasta do projeto.
3. Dê um duplo clique no arquivo index.html para abri-lo em seu navegador padrão.

Desenvolvido com foco na experiência do usuário por Silas Novaes.
Especialista em Gestão de Benefícios Corporativos & Desenvolvedor de Software.
