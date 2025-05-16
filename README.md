# Vinheria Agnello - Projeto Web

## 🍷 Sobre o Projeto
Desenvolvimento de um portal de e-commerce para a Vinheria Agnello, tradicional loja de vinhos que busca expandir suas vendas para o ambiente digital sem perder a essência do atendimento personalizado que a tornou referência.<br>
O projeto apresenta:
- História da vinheria
- Catálogo de produtos
- Galeria de imagens
- Equipe especializada
- Página de contato funcional

## 🖥️ Estrutura do Projeto
```css
vinheria-agnello/
│
├── index.html # Página Inicial
├── README.md
├── src/
│ ├── assets/ # Imagens e ícones
│ ├── css/ # Estilos globais e por página
│ ├── js/ 
│ └── pages/ # Páginas secundárias
│ ├── sobre.html # História da vinheria
│ ├── produtos.html # Catálogo de vinhos
│ ├── galeria.html # Fotos da loja e eventos
│ ├── equipe.html # Conheça nossos especialistas
│ └── contato.html # Formulário de contato
```
## 💫 Efeitos Visuais
### 🎯 Pseudo-classes
- `:hover` – Usado em links, imagens, botões, itens de tabela e membros da equipe.
- `:focus` – Usado em campos de formulário para realçar o foco.
- `:nth-child()` – Aplicado para estilizar colunas específicas e alternar cores de linhas da tabela.
- `:invalid` - Usado em inputs de e-mail, fica vermelho em e-mails inválidos.

### 🎯 Pseudo-elementos
- `::after` – Adiciona o emoji 📬 no título da seção de newsletter.
- `::placeholder` – Estiliza os placeholders dos formulários.


### 💫 Animações
Foi criada uma animação com `@keyframes` chamada `fadeIn`, aplicada em títulos das páginas:
- `.sobre h1`, `.produtos h1`, `.galeria h1`, `.equipe h1`


### 🔄 Transições
Foram aplicadas transições suaves nos seguintes elementos:
- Cor de links e botões ao passar o mouse.
- Inputs e textarea ao receber foco.
- Imagens e membros da equipe com efeito de transformação suave.

### 🎢 Transformações 
Transformações foram usadas para criar efeitos de movimento e escala:
- `scale()` – Em imagens para dar zoom no hover.
- `translateY()` – Em membros da equipe, simulando elevação ao passar o mouse.


## 👥 Equipe
Ana Clara Rocha de Oliveira

## 🌐 Acesso
Disponível em: [\Vinheria-Agnello\]](https://olivanaa.github.io/vinheria-agnello/)