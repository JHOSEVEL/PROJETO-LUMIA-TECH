# Portfólio QA Senior: Projeto Lumina Tech E-commerce

## 🚀 Visão Geral

Este repositório apresenta um projeto de Quality Assurance (QA) de nível junior, demonstrando uma abordagem completa para a garantia de qualidade em um e-commerce fictício de gadgets premium, a **Lumina Tech**. O foco principal é assegurar a **fidelidade do design (Pixel Perfect)**, a **consistência da marca** e a **usabilidade técnica**, elementos cruciais para a experiência do usuário em plataformas digitais.

O projeto destaca a capacidade de um QA não apenas identificar defeitos, mas também em fornecer um contexto rico e acionável para a equipe de desenvolvimento, otimizando o ciclo de correção e elevando o padrão de qualidade do produto.

## 💡 Lumina Tech: O E-commerce Fictício

A **Lumina Tech** é uma plataforma de e-commerce de ponta, especializada em gadgets e eletrônicos premium. Seu design minimalista, navegação intuitiva e foco em produtos de alta qualidade exigem uma estratégia de QA rigorosa para manter a excelência. Os testes abordam desde a responsividade em diversos dispositivos até a acessibilidade e a performance visual, garantindo uma experiência de compra impecável.

## 🎯 Metodologia de QA e Entregáveis

Nossa metodologia de QA é abrangente, cobrindo **Testes de Layout, Responsividade, Acessibilidade, Usabilidade e Funcionais**. Utilizamos ferramentas de inspeção de navegador e uma variedade de dispositivos para simular cenários reais de uso.

**Principais Entregáveis deste Portfólio:**

1.  **Planilha de Execução de Testes de Layout (`Planilha_QA_LuminaTech_Portfolio.xlsx`):** Uma ferramenta estruturada para documentar e acompanhar casos de teste, status, gravidade e observações, garantindo rastreabilidade e clareza.
2.  **Protocolo de Report de Bugs:** Um modelo detalhado para reportar defeitos, assegurando que cada bug seja documentado com clareza, contexto e evidências visuais, minimizando a comunicação adicional e acelerando a resolução.
3.  **Exemplos de Bug Reports:** Três exemplos práticos de relatórios de bugs (Crítico, Alto, Médio) seguindo o protocolo, incluindo "Sugestões Técnicas" que demonstram uma visão aprofundada do problema e possíveis soluções.
4.  **Conceito do E-commerce (`lumina_tech_concept.md`):** Detalhes sobre a marca Lumina Tech, seu público-alvo e os desafios de QA específicos que ela apresenta.

## 🐞 Protocolo de Report de Bugs (Exemplo)

Para ilustrar a profundidade do nosso protocolo de reporte, segue um exemplo:

```markdown
🐞 [UI/UX] Bug Report: Botão de Checkout sobreposto no carrinho (mobile)
ID: #001
Severidade: Alta
Prioridade: P2 - Alta

🖥️ Ambiente de Teste
Dispositivo: iPhone 13
SO: iOS 17.4
Navegador: Safari Mobile
Resolução: 390x844px

📝 Descrição do Problema
O botão "Finalizar Compra" na página de carrinho está sobrepondo o texto do subtotal e o valor do frete quando visualizado em resoluções de tela menores que 400px de largura, especificamente no iPhone 13.

🛠️ Passos para Reproduzir
1. Acessar a URL: `https://www.luminat.tech/carrinho` (URL fictícia)
2. Adicionar qualquer produto ao carrinho (ex: "Smartphone Lumina X Pro").
3. Abrir o Inspetor de Elementos (F12) no navegador desktop e alternar para a visualização mobile (iPhone SE ou iPhone 13).
4. Observar a seção de fechamento do pedido no rodapé da página.

🎯 Resultado Esperado (Conforme Figma/Protótipo)
O botão "Finalizar Compra" deve manter um `margin-top: 24px` em relação ao subtotal e ocupar 100% da largura da tela (Mobile), sem sobrepor nenhum outro elemento da interface. O protótipo do Figma para a página de carrinho mobile mostra o botão claramente abaixo do subtotal e frete.

❌ Resultado Atual (O que ocorre no site)
O botão "Finalizar Compra" está com `position: absolute` fixo, causando sobreposição no texto do subtotal e impedindo a leitura clara do valor total do frete. Isso impacta negativamente a usabilidade e a finalização da compra.

🖼️ Evidências (Obrigatório)
Print de Tela: [Anexe aqui a imagem com uma seta vermelha apontando o erro, ex: `bug_001_checkout_iphone13.png`]
Link do Figma: [Cole aqui o link da seção específica do design para comparação, ex: `https://www.figma.com/file/LuminaTech_Design/carrinho#checkout-mobile`]
Log do Console (Opcional): N/A

💡 Sugestão Técnica:
Dica: Verifique se a classe `.btn-checkout` não está herdando um `padding` fixo do container pai que está forçando a quebra de linha prematura no container de texto, ou se o `position: absolute` não está sendo aplicado de forma inadequada para este breakpoint. Considere usar `flexbox` ou `grid` para um layout mais responsivo e robusto na seção do rodapé do carrinho.

```

## 🤝 Por Que Este Portfólio?

Este projeto demonstra minha proficiência em:

*   **Pensamento Crítico e Analítico:** Identificação de problemas complexos de UI/UX e funcionalidade.
*   **Comunicação Eficaz:** Elaboração de documentação clara e reportes de bugs detalhados e acionáveis.
*   **Visão Estratégica de Qualidade:** Foco em Pixel Perfect, consistência de marca e usabilidade técnica.
*   **Colaboração com Desenvolvimento e Design:** Fornecimento de sugestões técnicas que agilizam a correção.

## ✍️ Autor

    * JOSEVEL ALVES SILVA
