# acessibilidadenovimeto-e-visao
# Interface Acessível: Movimentação e Visão

[![Acessibilidade WCAG 2.1](https://shields.io)](https://w3.org)
[![Licença MIT](https://shields.io)](LICENSE)

Este é um projeto base desenvolvido para demonstrar a aplicação prática de diretrizes de acessibilidade web (WCAG 2.1 AA), focando especificamente nas necessidades de usuários com limitações **visuais** e **motoras (movimentação)**.

---

## ♿ Recursos de Acessibilidade Implementados

### 👁️ Para Acessibilidade Visual (Baixa Visão e Cegueira)
* **Textos Alternativos (`alt`):** Todas as imagens funcionais possuem descrições detalhadas para leitura por leitores de tela (como NVDA e JAWS).
* **Semântica HTML5 Pura:** Uso de tags estruturais (`<main>`, `<nav>`, `<header>`) que permitem aos softwares de leitura mapear o site corretamente.
* **Alto Contraste:** Relação de contraste entre texto e fundo testada e validada acima do padrão mínimo de 4.5:1.
* **Hierarquia de Títulos:** Organização rígida de headings (`# H1` a `### H3`) para permitir o salto rápido de seções via teclado.

### 🦽 Para Acessibilidade de Movimentação (Navegação por Teclado)
* **Navegação 100% via Teclado:** Controle total da aplicação usando apenas as teclas `Tab`, `Shift + Tab`, `Enter` e `Espaço`.
* **Link de Salto (Skip Link):** Atalho oculto no topo da página que permite pular o menu principal e ir direto ao conteúdo.
* **Foco Visual Reforçado (`:focus`):** Indicador de foco customizado com alto contraste (borda amarela de 4px) para que usuários que não usam mouse saibam exatamente onde estão navegando.

---

## 🛠️ Tecnologias Utilizadas

* HTML5 Acessível
* CSS3 (Estilização com foco em contraste e visibilidade)

---

## 🧪 Como Testar a Acessibilidade Deste Projeto

Para validar as ferramentas de acessibilidade instaladas:
1. Abra o arquivo `index.html` no seu navegador.
2. **Teste de Movimentação:** Deixe o mouse de lado e use a tecla `Tab` para navegar por todos os elementos clicáveis. Verifique se o indicador visual amarelo aparece.
3. **Teste de Visão:** Instale uma extensão de leitor de tela (ou use o Narrador nativo do Windows/VoiceOver do Mac) e navegue pela página de olhos fechados para validar a experiência sonora.

---

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.
