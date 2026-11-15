# Portfólio Pessoal - Desenvolvimento Web

**Aluno:** Victor Jose Dos Santos Oliveira

## Descrição do Portfólio
Este projeto consiste em um site de portfólio pessoal responsivo desenvolvido para apresentar meu perfil, minhas habilidades técnicas e os projetos criados ao longo da disciplina.

## Tecnologias Utilizadas
* **HTML5:** Estruturação semântica das seções da página.
* **CSS3:** Estilização personalizada, gradientes, rolagem suave e animações.
* **Bootstrap 5:** Sistema de grid responsivo, barra de navegação, cards e formulário.
* **Bootstrap Icons:** Ícones para links de redes sociais.

## Link do Site Publicado
Acesse o site online através do GitHub Pages: [https://seu-usuario.github.io/nome-do-repositorio/](https://seu-usuario.github.io/nome-do-repositorio/)

## Explicação do Funcionamento do Projeto
O site é estruturado em uma única página (*One Page*) dividida em seções conectadas por um menu de navegação fixo no topo (`navbar`). Ao clicar nos links do menu, a página desliza suavemente até a seção correspondente. O layout adapta-se automaticamente a computadores, tablets e celulares graças às classes responsivas do Bootstrap.

## Descrição do Recurso Novo Adicionado
Foram adicionados dois recursos além do modelo básico visto em aula:
1. **Animações de Hover e Transição nos Cards:** Ao passar o cursor sobre os cards na seção de Projetos, eles se elevam suavemente e ganham uma sombra mais destacada.
2. **Nova Seção de Habilidades:** Inclusão de uma seção dedicada às competências técnicas utilizando barras de progresso (`progress-bar`) do Bootstrap.

## Explicação de Como o Recurso Foi Implementado
* **Animações CSS:** Foi criada a classe `.card-projeto` no bloco `<style>` utilizando a propriedade `transition: transform 0.3s ease, box-shadow 0.3s ease;`. No estado `:hover`, aplicou-se `transform: translateY(-8px)` para mover o card para cima e `box-shadow` para criar profundidade.
* **Seção de Habilidades:** Foi estruturada uma `<section id="habilidades">` vinculada ao menu principal, utilizando os componentes `.progress` e `.progress-bar` do Bootstrap 5 com larguras definidas em porcentagem via CSS inline.
