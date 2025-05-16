# ponderada-UX

# Autores

Lucas Cozzolino Tort & Vinicius Maciel Flor

# App de Receitas - Tela de Bolo de Cenoura

Este projeto implementa uma interface de aplicativo móvel para exibir uma receita de bolo de cenoura. O design é responsivo e otimizado para dispositivos móveis.

## Estrutura do Projeto

O projeto consiste em três arquivos principais:

- `index.html` - Estrutura da página da receita
- `styles.css` - Estilos CSS para formatação visual
- `img/bolo cenoura.jpg` - Imagem da receita

## Como Executar

1. Clone este repositório ou baixe os arquivos
2. Certifique-se de que a estrutura de pastas está correta, com a imagem na pasta `img`
3. Abra o arquivo `index.html` em qualquer navegador moderno

## Recursos e Funcionalidades

- Layout responsivo otimizado para dispositivos móveis (largura máxima de 414px)
- Design de card com sombras e cantos arredondados
- Exibição de informações da receita com ícones (tempo de preparo e porções)
- Lista de ingredientes formatada
- Botão de chamada para ação para ver a receita completa

## Personalização

### Modificando a Imagem
Para trocar a imagem do bolo, substitua o arquivo na pasta `img` ou atualize o caminho no HTML:

```html

```

### Alterando as Cores
Para modificar as cores principais do aplicativo, edite as seguintes propriedades no arquivo CSS:

- Cor de fundo do card: `.recipe-card { background-color: white; }`
- Cor da pílula de informações: `.info-pill { background-color: #0077FF; }`
- Cor do botão de ação: `.action-button { background-color: #2aad6f; }`

### Adicionando Novos Ingredientes
Para adicionar ou remover ingredientes, edite a lista no HTML:

```html

    Seu novo ingrediente
    

```

## Compatibilidade

Esta interface foi testada e é compatível com:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Navegadores móveis modernos (Chrome para Android, Safari iOS)

## Tecnologias Utilizadas

- HTML5
- CSS3
- Fontes do sistema (Segoe UI, Roboto, etc.)
- Emojis Unicode para ícones

## Próximos Passos

Possíveis melhorias futuras:
- Adicionar modo escuro
- Implementar a página de receita completa
- Adicionar funcionalidade de favoritos
- Incluir sistema de avaliação da receita
- Integrar com backend para salvar receitas

---

Desenvolvido como parte do projeto de interfaces para aplicativos móveis.