# Recicla‑Tech  

## Introdução  
O **Recicla‑Tech** é o desenvolvimento de um website para uma empresa fictícia, criado no âmbito do curso VaiNaWeb. 
Ele serve como demonstração de aplicação de HTML, CSS/SCSS, e boa organização de projeto, visando apresentar a empresa fictícia de forma moderna, responsiva e atrativa.

## Tópicos  
- [Instalação](#instalação)  
- [Uso](#uso)  
- [Funcionalidades](#funcionalidades)  
- [Arquitetura / estrutura do projeto](#arquitetura--estrutura-do-projeto)  
- [Dependências](#dependências)  
- [Configuração](#configuração)  
- [Contribuidores](#contribuidores)  
- [Licença](#licença)  

## Instalação  
1. Clone o repositório  
   ```bash  
   git clone https://github.com/Leonel‑p‑a/recicla‑tech.git  
   ```  
2. Acesse a pasta do projeto  
   ```bash  
   cd recicla‑tech  
   ```  
3. Abra o arquivo `index.html` no navegador ou execute através de um servidor local (recomendado para ver funcionalidades de CSS/SCSS corretamente compiladas).

## Uso  
- Após abrir o site, você verá a página principal da empresa fictícia.  
- A navegação inclui seções como “Sobre Nós”, “Serviços”, “Contato” ou outras conforme estrutura criada.  
- Para desenvolvimento adicional, modifique os arquivos em `src/assets/css` (SCSS) ou `public/images` para alterar visuais, bem como o HTML principal (`index.html`).  

## Funcionalidades  
- Layout responsivo, adaptando‑se a diferentes tamanhos de tela (desktop, tablet, mobile).  
- Uso de estrutura moderna (HTML5 + CSS3/SCSS) para estilização.  
- Organização clara de pastas: separação entre assets, imagens, estilos, etc.  
- Visual profissional para uma empresa fictícia de tecnologia / reciclagem.

## Arquitetura / estrutura do projeto  
Uma visão geral dos arquivos e pastas:  
```
recicla‑tech/
├── public/
│   └── images/       ← imagens utilizadas no site  
├── src/
│   └── assets/
│       └── css/      ← arquivos SCSS/CSS  
├── index.html        ← página principal  
└── README.md         ← este arquivo (adicionado)  
```  

Essa estrutura permite fácil manutenção e escalabilidade do layout.

## Dependências  
- Navegador moderno (Chrome, Firefox, Edge, Safari) com suporte a CSS3 e flexbox/grid.  
- (Opcional) Se você estiver usando pré‑processamento SCSS: compilador de SCSS para CSS.  
- (Opcional) Um servidor local simples (ex: [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VSCode) para testes.

## Configuração  
Se quiser alterar configurações visuais como cores, tipografia ou layout global:
- Edite os arquivos SCSS em `src/assets/css/`.  
- Recompile (se aplicável) ou atualize o CSS gerado.  
- Substitua as imagens em `public/images/` conforme necessidade.

## Contribuidores  
- **Leonel P-A** – Autor original do projeto.  
- Contribuições são bem‑vindas! Se você quiser colaborar (melhorias visuais, adição de funcionalidades, correção de bugs), por favor abra um *pull request*.

## Licença  
Este projeto está licenciado sob a [MIT License](LICENSE).
