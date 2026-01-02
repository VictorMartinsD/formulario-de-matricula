## ⚙️ 1. Ambiente e Ferramentas (Node/NPM)

- **Gerenciamento de Dependências**: Aprendizado sobre a sincronização entre `package.json` e `package-lock.json`. O comando `npm install` é o responsável por atualizar o lockfile após mudanças manuais no nome ou versão do projeto.
- **Padronização**: Nomes de projetos devem seguir o padrão _kebab-case_ (minúsculas e hífens).

## 🔍 2. SEO e Performance Visual

- **Head Strategy**: Implementação de tags Open Graph (`og:image`, `og:description`) para garantir que o compartilhamento do link em redes sociais seja profissional.
- **Preview Progressivo**: Técnica de deixar o caminho da imagem de preview pronto no código antes mesmo de tirar o print final do projeto.

## 🎨 3. CSS Avançado e Arquitetura

- **Unidades Relativas (REM)**: Conversão de pixels para rem (divisão por 16) para garantir que o layout respeite as configurações de acessibilidade do usuário.
- **Layout Grid**: Divisão do layout em duas colunas principais (`aside` e `main`) utilizando porcentagens precisas baseadas no Figma (51.25% e 48.75%).
- **Prevenção de Layout Shift**:
  - Uso de bordas transparentes fixas para evitar que o elemento "balance" ao receber foco.
  - Diferença entre `outline` e `border`: O `outline` não ocupa espaço no modelo de caixa (_box model_), sendo ideal para realces de foco sem mover elementos vizinhos.

## 📝 4. HTML Semântico e Acessibilidade

- **Agrupamento de Dados**: Uso de `<fieldset>` e `<legend>` para separar logicamente as informações da criança, do responsável e as opções de matrícula.
- **Customização de Inputs**:
  - Estrutura de `input-wrapper` para controle total sobre label e campo.
  - Técnicas para esconder o input original (como `file` ou `radio`) e estilizar o elemento visual por cima, mantendo a funcionalidade nativa através do atributo `id` e `for`.

## 🚀 5. Boas Práticas de Código

- **Escalabilidade**: Organização do CSS em múltiplos arquivos (vincular arquivos específicos para componentes como `dropzone.css`) para facilitar a manutenção.
- **Namespacing**: Uso de classes específicas para evitar conflitos de estilo entre diferentes partes do formulário.

---

> [!NOTE]
> Estas notas são um resumo técnico. O processo detalhado de 80 páginas com todos os desafios resolvidos está documentado nos meus arquivos pessoais de estudo.
> [Veja as anotações de estudo deste projeto aqui](https://docs.google.com/document/d/1sMT9Y_XwljgE6UKzWjEWGXqDqah3FR7pkPFs3cMEmfE/edit?usp=sharing)
