# Página Pessoal

Projeto introdutório de desenvolvimento web criado para praticar a estruturação de uma página pessoal com **HTML5**, com foco em semântica, hierarquia de conteúdo e uso de elementos apropriados.

O site apresenta seções de apresentação, informações pessoais, interesses, objetivos e formas de contato. O conteúdo textual e os dados de contato presentes no HTML são exemplos fictícios/de preenchimento e devem ser substituídos antes de utilizar o projeto como uma página pessoal real.

## Objetivos de aprendizagem

- Construir a estrutura básica de um documento HTML.
- Utilizar elementos semânticos para organizar o conteúdo.
- Aplicar hierarquia de títulos (`h1` e `h2`) e listas.
- Inserir uma imagem com texto alternativo (`alt`).
- Criar links de contato usando os esquemas `tel:` e `mailto:`.
- Organizar os arquivos do projeto e documentar sua execução.

## Demonstração

- **Versão publicada:** https://pratesddev.github.io/fe_pagina_pessoal/
- **Imagem de referência/wireframe:** `assets/image.png`
- **Avatar utilizado na página:** `assets/avatar-1.png`

> O README original apontava para `assets/preview.png`, mas esse arquivo não existe com esse nome no pacote recebido. Há arquivos chamados `assets/old.preview.png` e `assets/previer.png`; eles foram mantidos sem alteração.

## Funcionalidades e conteúdo

| Seção | Descrição |
| --- | --- |
| Cabeçalho | Exibe o título/nome apresentado na página. |
| Apresentação | Mostra um avatar e um texto introdutório. |
| Sobre | Área para informações adicionais sobre a pessoa. |
| Interesses | Lista temas de interesse. |
| Objetivos | Lista metas de estudo e desenvolvimento. |
| Contato | Apresenta links para telefone, e-mail e LinkedIn. |
| Rodapé | Exibe o aviso de direitos autorais. |

## Tecnologias utilizadas

| Tecnologia/recurso | Uso |
| --- | --- |
| **HTML5** | Estrutura, conteúdo e semântica da página. |
| **Git** | Controle de versão do projeto. |
| **GitHub / GitHub Pages** | Hospedagem do repositório e publicação da demonstração. |
| **VS Code** | Editor de código sugerido para desenvolvimento. |

**Não há CSS ou JavaScript no pacote analisado.** Portanto, a apresentação visual depende do estilo padrão aplicado pelo navegador; a página ainda não possui uma camada própria de estilos nem interações implementadas em JavaScript.

## Estrutura do projeto

```text
fe_pagina_pessoal/
├── assets/
│   ├── avatar-1.png
│   ├── image.png
│   ├── old.preview.png
│   └── previer.png
├── index.html
└── README.md
```

- `index.html`: página principal e conteúdo HTML.
- `assets/avatar-1.png`: imagem de avatar utilizada na apresentação.
- `assets/image.png`: referência visual/wireframe documentada no README original.
- `assets/old.preview.png` e `assets/previer.png`: imagens auxiliares mantidas no projeto.

## Como executar localmente

### Pré-requisitos

- Um navegador moderno.
- Um editor de código, como o [Visual Studio Code](https://code.visualstudio.com/).
- Git é opcional caso você vá clonar o repositório.

### Opção 1 — Abrir diretamente

1. Baixe ou extraia os arquivos do projeto.
2. Abra a pasta `fe_pagina_pessoal`.
3. Abra `index.html` no navegador.

### Opção 2 — Clonar o repositório

```bash
git clone https://github.com/pratesddev/fe_pagina_pessoal.git
cd fe_pagina_pessoal
```

Depois, abra `index.html` no navegador ou abra a pasta no VS Code. Como se trata de HTML estático, não é necessário instalar dependências nem iniciar um servidor de aplicação.

## Validação manual

- [ ] O arquivo `index.html` abre sem erros.
- [ ] O avatar é exibido corretamente.
- [ ] As seções aparecem na ordem esperada.
- [ ] Os links de telefone, e-mail e LinkedIn apontam para destinos válidos após a substituição dos exemplos.
- [ ] O texto alternativo da imagem descreve adequadamente o conteúdo.
- [ ] A página permanece legível em larguras de tela diferentes.

## Limitações conhecidas

- O nome “Fulano de Tal”, os textos de apresentação e os dados de contato são conteúdo de exemplo.
- O telefone, e-mail e perfil de LinkedIn usam dados fictícios/de preenchimento; os links precisam ser atualizados antes de publicar uma versão pessoal.
- Não existe arquivo CSS no projeto, então não há layout ou identidade visual personalizada implementados.
- O HTML contém um único `h1` e títulos `h2` para as seções, mas a semântica e o conteúdo devem ser revisados ao personalizar a página.
- O README anterior mencionava uma licença MIT e um arquivo `LICENSE`, mas esse arquivo não está presente no pacote recebido. Não considere a licença formalmente documentada até incluir o arquivo correspondente.
- O README anterior apontava para `assets/preview.png`, nome que não corresponde a nenhum arquivo incluído no pacote.

## Melhorias futuras sugeridas

1. Substituir os textos e dados fictícios por informações reais, removendo qualquer contato que não se deseje publicar.
2. Criar `css/style.css` e vincular a folha de estilos ao HTML.
3. Desenvolver um layout responsivo com Flexbox ou CSS Grid.
4. Melhorar a apresentação visual de links, listas, avatar e rodapé, mantendo contraste e foco visível para navegação por teclado.
5. Conferir se todos os links externos estão corretos e definir `target`/`rel` conscientemente caso novas abas sejam utilizadas.
6. Revisar o conteúdo alternativo das imagens e validar a página com ferramentas de acessibilidade.
7. Adicionar um arquivo `LICENSE` caso o projeto vá ser distribuído sob uma licença específica.

## 👤 Autor

**Diego Prates**

- GitHub: [@pratesddev](https://github.com/pratesddev)
- LinkedIn: [Diego Prates](https://linkedin.com/in/prates-diego)
- E-mail: [dmoprates1@gmail.com](mailto:dmoprates1@gmail.com)
- Site: [ation.dev.br](https://ation.dev.br)

---
